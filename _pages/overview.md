---
permalink: /overview/
title: "Overview"
toc: true
toc_label: "FlowEHR Design"
toc_icon: "pencil-ruler"
toc_sticky: true
---

# High Level Design

Our tech stack is opinionated but modular and flexible enough to accommodate multiple use cases and adapt to local needs.  
We are open-source first & foremost.

<a href="/assets/images/FlowEHR-diagram.png">
 <img id="diagram" src="/assets/images/FlowEHR-diagram.png" alt="FlowEHR"  />
</a>

Technical implementation details are available in the public [FlowEHR GitHub repository](https://github.com/UCLH-Foundry/FlowEHR).

Our experience shows that successfully utilising healthcare data demands more than a technical solution and
FlowEHR is composed of _people_, _processes_ and _technology_.

----

# Non-Functional Requirements

Our priorities are:

## 1. Safety
We have aligned with the [_5 Safes Framework_](https://en.wikipedia.org/wiki/Five_safes){:target='_blank'}
- Safe setting
- Safe people
- Safe data
- Safe projects
- Safe outputs

This means privacy, auditability, governance & regulation and data & system integrity & security are baked into the very fabric of the platform.

## 2. Observability
We prioritise maximal transparency of the system, processes, policies, data, models, model performance and user activity.  
Observability is not just good engineering practice but a core requirement for regulatory compliance.

## 3. Usability
It is likely that delivering effective algorithmic solutions will require many iterations and experiments akin to the drug discovery process.   
The success of FlowEHR depends on the ability to onboard many users and very quickly get them to the point where they can trial solutions with as little effort as possible while providing the guardrails that keep everyone safe.  
The platform must have a wide and clearly sign-posted _happy path_.

## 4. Maintainability
FlowEHR is an evolving system which requires effort more similar to tending a garden than constructing and maintaining a bridge.    
However, most NHS organisations have limited DevOps & DataOps resources and so we have doubled down on modern software & infrastructure engineering best practices  
like Infrastructure-as-Code and continuous delivery.


----

# Functional Requirements 

We have identified 6 user personas to help define the requirements.

These have been informed by our direct experience over the past several years, as well as in-depth discussions, seminars & workshops with several regulatory bodies and the wider healthcare, research & technology community.

## 1. The Innovators
As a _cross-functional development team working inside an NHS organisation_,  
we want _low-friction access to a range of live internal & external data sources and a modern deployment 
environment_,  
so that _we can rapidly create apps which generate clinical and operational value_.

## 2. The Imaging Researchers
As a _medical imaging research team at an NHS academic medical centre_,  
we want _a safe, user-friendly environment with industry standard tools & applications and access to pseudonymised, 
linked DICOM and routinely collected electronic healthcare data_,   
so that _we can iteratively develop and evaluate cutting-edge multi-modal computer vision models for improving health outcomes_.

## 3. The Informatics Researchers
As a _health informatics research team at an NHS academic medical centre_,  
we want _a safe, user-friendly environment with industry standard tooling and access to retrospective, de-identified, 
routinely collected healthcare data_,  
so that _we can tackle questions of regional population health, epidemiology, long-term health outcome comparisons or health inequality_.

## 4. The Analysts
As a _dynamic team of data literate clinicians, data fellows, clinical auditors and analysts working inside an NHS organisation_,  
we want _a safe, user-friendly environment with guidance & guardrails, industry standard tools agnostic of the patient record system and access to retrospective data_,  
so that _we can analyse clinical and operational data with Reproducible Analytical Pipelines to improve care and help continue our digital transformation journey_.

## 5. The Pilgrims
As a _multidisciplinary translational machine learning research team working at an academic medical centre_,  
we want _a safe, user-friendly & robust environment for data science with industry-standard tooling, access to live & retrospective data and support for the modern machine learning development lifecycle_,  
so that _we can iteratively develop, deploy and evaluate algorithms in a real-world setting that will improve care and operational efficiency_.

## 6. The Stewards
As a _team of regulatory, governance, clinical, technology & methodology experts working at an NHS organisation_,   
we want _an accredited environment on professionally managed infrastructure with comprehensive monitoring and fail-safes implemented in compliance with regulation and industry standards_,   
so that _we can deploy and manage approved algorithms inside our organisation which improve patient care and operational efficiency_.


----



