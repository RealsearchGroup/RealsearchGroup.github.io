---
title: Surfacing Security Metrics from throughout a Package's Dependency Tree
subtitle: Aid practitioners in making informed decisions about which third-party packages to use or replace
status: active

description: The goal of this research is to aid developers and software architects in making good component choices through an analysis of the relevance and utility of security measures from the entire dependency tree associated with a package.



people:
    - profx
    - grad-b
    - grad-e

layout: project
last-updated: 2024-06-28

notitle: false
nolink: false 

image: /pictures/dependency_tree_colorful.jpg
link: false
---
The goal of this research is to aid developers and software architects in making good component choices through an analysis of the relevance and utility of security measures from the entire dependency tree associated with a package.

## Survey Information

We are currently performing a survey to try to better understand how different approaches for surfacing security information from a project's dependency tree may (or may not) help developers when determining whether to and how to use third-party libraries.

We are looking for participants with experience in using third-party libraries, over 18 years of age, and in the U.S. or Australia. Full informed consent information can be found here: 

If you are interested in participating, please contact Sarah Elder (seelder at ncsu.edu)


## Motivation
Practitioners rely on high-level measures that are readily accessible to evaluate the risk of incorporating an open-source software component. However, incorporating a software component does not always involve just one component. Each component may depend on other components, which in turn depend on other components, creating a network of dependencies often referred to as a dependency tree. Given the rarity of software vulnerabilities and the reactive (not proactive) nature of vulnerability-based security assessments, our work endeavors to understand how other security metrics should incorporate information from throughout a package's dependency tree.



## Research Questions
 - What approaches do practitioners recommend for aggregating measures across a component's dependency tree?
 - How would including aggregate security information from a package's dependencies alter its security score, relative to other packages?

 ## Metrics
 As part of this study, we are using metrics from the [OpenSSF Scorecard](https://securityscorecards.dev) tool. While we are in contact with the OpenSSF Scorecard community, this research is being performed independently and all thoughts and opinions expressed are those of the researchers.

These metrics include a measure of how actively a project is *Maintained*, whether the project uses *Branch Protection* such as preventing force-push actions in Github, whether the project has a *Security Policy* such as documentation of processes for vulnerabilityr reporting, whether the project uses *Code Review*, whether a project has *Pinned Dependencies* and whether the project contains *Binary Artifacts*.














