---
permalink: /status/
title: "Status"

---

We have several years worth of hard-won experience building technology infrastructure for research & innovation and 
integrating with a variety of operational systems inside a busy multi-site London NHS trust.

Starting in 2018, we built a real-time HL7 processing pipeline which surfaces the electronic patient record alongside data from
diagnostic systems in a relational database at a latency of less than ~20sec.  
This datastore allowed us to rapidly build & deploy several real-time applications and dashboards in response to the pandemic to assist
in quality improvement, workforce communication, live resource monitoring, ICU clinical management and NHS data submissions.

In 2021 we started training predictive algorithms & ML models on structured electronic patient record data and 
integrating inference capabilities into some of our applications.  
In doing so we noticed several common technology and governance patterns and extracted these into a proof-of-concept FlowEHR platform running 
in our on-premises virtualised environment.  
We currently have models predicting ICU resource demand, in-patient admission from the emergency department, general ward patient deterioration
and post-anesthesia care requirements as well as prioritising antimicrobial resistance reviews, all running against live data on our proof-of-concept platform.

Towards the end of 2022 we expanded into supporting DICOM imaging data and free-text radiology reports to support a project which aims to
help clinicians identify misplaced nasogastric tubes.  

In early 2023 we started the process of productionising our proof-of-concept platform and replanting FlowEHR in the public cloud.  
We are currently in the process of migrating our ICU demand prediction application and models to our cloud-native implementation which
we aim to complete in Q2 of 2023.

We are also developing a synthetic healthcare dataset with the help of [The Alan Turing Institute](https://www.turing.ac.uk/) which 
would grow the pool from which we source ideas. We aim to provide limited access to this dataset to external users by Q3 2023.

Our plan is to have migrated all existing applications and models by Q4 2023 and to have governance, compliance & risk
templates in place which will accelerate our ability to trial new solutions.
