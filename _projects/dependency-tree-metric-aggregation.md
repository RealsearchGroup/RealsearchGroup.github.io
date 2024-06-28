---
title: Surfacing Security Metrics from throughout a Package's Dependency Tree
subtitle: Aid practitioners in making informed decisions about which third-party packages to use or replace
status: active

description: The goal of this research is to aid developers and software architects in making good component choices through an analysis of the relevance and utility of security measures from the entire dependency tree associated with a package.



people:
    - profx
    - grad-b

layout: project
last-updated: 2024-06-28

notitle: false
nolink: false 

image: /pictures/dependency_tree_colorful.jpg
link: false
---
The goal of this research is to aid developers and software architects in making good component choices through an analysis of the relevance and utility of security measures from the entire dependency tree associated with a package.

# Survey Overview

We are currently performing a survey to try to better understand how different approaches for surfacing security information from a project's dependency tree may (or may not) help developers when determining whether to and how to use third-party libraries.

We are looking for participants with experience in using third-party libraries, over 18 years of age, and in the U.S. or Australia. Full informed consent information can be found here: 

Participants will be asked to fill out a 15-minute survey, in which they will be asked whether different methods for surfacing information from throughout a project's dependency tree would be helpful.

If you are interested in participating, please contact Sarah Elder (seelder at ncsu.edu)

<!-- Survey Link to go Here -->

# About This Study

## Motivation
Practitioners rely on high-level measures that are readily accessible to evaluate the risk of incorporating an open-source software component. However, incorporating a software component does not always involve just one component. Each component may depend on other components, which in turn depend on other components, creating a network of dependencies often referred to as a dependency tree. Given the rarity of software vulnerabilities and the reactive (not proactive) nature of vulnerability-based security assessments, our work endeavors to understand how other security metrics should incorporate information from throughout a package's dependency tree.



## Research Questions
 - What approaches do practitioners recommend for aggregating measures across a component's dependency tree?
 - How would including aggregate security information from a package's dependencies alter its security score, relative to other packages?

 ## Metrics
 As part of this study, we are using metrics from the [OpenSSF Scorecard](https://securityscorecards.dev) tool. While we are in contact with the OpenSSF Scorecard community, this research is being performed independently and all thoughts and opinions expressed are those of the researchers.

These metrics include a measure of how actively a project is *Maintained*, whether the project uses *Branch Protection* such as preventing force-push actions in Github, whether the project has a *Security Policy* such as documentation of processes for vulnerabilityr reporting, whether the project uses *Code Review*, whether a project has *Pinned Dependencies* and whether the project contains *Binary Artifacts*.

Currently these metrics, similar to many other metrics automatically collected, focus on the activity and policies within a particular package (i.e. the "root" package of a dependency tree). These metrics do *not* currently provide information on the additional packages.

Is that a problem? Well, it may depend on the metric. That is where we need help ...

## Survey Details
We are looking for survey participants, as mentioned previously, to provide feedback on our initial prototype methods for aggregating metrics using information throughout a package's dependency tree. If we are completely wrong - that is good to know too!

Participation includes filling out a questionaire about the metrics and aggregation methods, followed by 3 questions to help us understand the background and experience of our participants that may influence their responses. Overall, the survey should take less than 15 minutes to complete.

 We value our participants privacy. Multiple-choice and numeric information will be reported in aggregate, such that an individual response cannot be traced back to an individual. Quotes used from free-response questions will be short, and we will avoid using quotes with information such as the name of an organization the individual is affiliated with, which could be used to identify the participant. 

 We appreciate particpants taking the time to fill out our survey. All participants will be entered into a drawing for one of three $20 Amazon gift cards. Email addresses will be used for this drawing, if the participant chooses to enter, then removed from our records to ensure privacy.



<!-- Survey Link to go Here -->








