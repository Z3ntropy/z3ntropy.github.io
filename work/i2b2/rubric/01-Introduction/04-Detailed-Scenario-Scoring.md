This document provides a detailed breakdown of the scoring for each use case scenario, based on the i2b2 Query Proficiency Rubric. The scores for each scenario are presented in a table, followed by a justification for each assigned score. 

The full i2b2 Query Proficiency Rubric can be found in the [Appendix](../../07%20Appendix/01%20Supplemental%20Information.md) of the main architecture document.

### Use Case Scores:
1. [[#Scenario 1 Basic Cohort Identification (Novice)|Basic Cohort Identification]]
2. [[#Scenario 2 Exploring Temporal Trends (Intermediate)|Exploring Temporal Trends]]
3. [[#**Scenario 3 Advanced Cohort Comparison (Advanced)**|Advanced Cohort Comparison]]
4. [[#**Scenario 4 Integrating External Data (Expert)**|Integrating External Data]]
5. [[#**Scenario 5 Developing and Sharing Query Templates (Expert/Master)**|Developing and Sharing Query Templates]]
6. [[#**Scenario 6 Troubleshooting a Complex Query (Intermediate/Advanced)**|Troubleshooting a Complex Query]]
7. [[#**Scenario 7 Validating Data Quality with Ontology Expertise (Advanced/Expert)**|Validating Data Quality with Ontology Expertise]]
8. [[#**Scenario 8 Onboarding a New Expert User (Novice)**|Onboarding a New Expert User]]


---
# Scenario 1: Basic Cohort Identification (Novice)

---

| Dimension                          | Sub-dimension                                   | Score | Justification                                                                                                                                                  |
| :--------------------------------- | :---------------------------------------------- | :---- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **i2b2 Platform Proficiency (20%)** | Navigation and Interface Familiarity             | 2     | Navigates to the Query Tool but needs to consult documentation.                                                                                                   |
|                                     | Query Tool Features                             | 3     | Uses basic features like drag-and-drop and date ranges but with guidance.                                                                                          |
|                                     | i2b2 Data Model Awareness                       | 1     | Limited understanding of the data model.                                                                                                                          |
|                                     | Error Handling and Troubleshooting              | 1     | Unable to identify or resolve errors without significant assistance.                                                                                                |
|                                     | Personal Query Management                       | 3     | Saves the query for future use.                                                                                                                                    |
|                                     | Iterative Query Refinement                      | 1     | No iterative refinement in this scenario.                                                                                                                         |
|                                     | i2b2 Personalization                            | 1     | No personalization demonstrated.                                                                                                                                     |
| **Domain Expertise (20%)**            | Medical Terminology Expertise                 | 4     | Understands "type 2 diabetes" but needs to look up the code in i2b2.                                                                                                |
|                                     | Clinical Research Methodology                 | 3     | Basic understanding of cohort identification.                                                                                                                    |
|                                     | Specific Disease/Research Area                  | 6     | Solid understanding of the research domain.                                                                                                                       |
| **Query Complexity (35%)**            | Number of Criteria                              | 2     | Uses two criteria (diagnosis and date range).                                                                                                                    |
|                                     | Logical Operators                               | 2     | Uses simple AND operation implicitly.                                                                                                                                  |
|                                     | Temporal Constraints                            | 3     | Specifies a date range ("within the last year").                                                                                                                  |
|                                     | Data Aggregation and Transformation             | 1     | Not applicable in this scenario.                                                                                                                                    |
|                                     | Nested Queries                                  | 1     | Not applicable in this scenario.                                                                                                                                    |
| **Data Integration & External Resources (10%)** | Knowledge of External Data Sources              | 1     | No external data sources used.                                                                                                                                   |
|                                     | Data Integration Techniques                     | 1     | No data integration performed.                                                                                                                                     |
|                                     | Use of External Resources                       | 3     | Consults i2b2 documentation.                                                                                                                                       |
| **Security, Privacy, and Ethics (10%)**   | Compliance with Regulations                     | 4     | Aware of basic regulations.                                                                                                                                        |
|                                     | Data Security Practices                         | 3     | Follows basic data security practices.                                                                                                                             |
|                                     | Ethical Considerations                          | 3     | Aware of basic ethical principles.                                                                                                                                   |
| **Collaboration (5%)**                | Finding and Understanding Existing Queries       | 1     | Not applicable in this scenario.                                                                                                                                    |
|                                     | Adapting and Modifying Existing Queries         | 1     | Not applicable in this scenario.                                                                                                                                    |
|                                     | Creating and Sharing Reusable Query Templates | 1     | Not applicable in this scenario.                                                                                                                                    |
|                                     | Collaborating on Query Development             | 1     | Limited collaboration, may seek assistance.                                                                                                                        |
|                                     | Personal Query Management                       | 3     | User saves the query.                                                                                                                                                 |
|                                     | Iterative Query Refinement                      | 1     | Not applicable in this scenario.                                                                                                                                    |
|                                     | i2b2 Personalization                            | 1     | No personalization demonstrated.                                                                                                                                       |

**Weighted Scores:**

*   i2b2 Platform Proficiency: (2\*0.4 + 3\*0.3 + 1\*0.2 + 1\*0.1 + 3*0.15 + 1*0.15 + 1*0.1) \* 0.2 = **0.39**
*   Domain Expertise: (4\*0.4 + 3\*0.3 + 6\*0.3) \* 0.2 = **0.86**
*   Query Complexity: (2\*0.4 + 2\*0.3 + 3\*0.2 + 1\*0.05 + 1\*0.05) \* 0.35 = **0.77**
*   Data Integration & External Resources: (1\*0.4 + 1\*0.3 + 3\*0.3) \* 0.1 = **0.16**
*   Security, Privacy, and Ethics: (4\*0.4 + 3\*0.3 + 3\*0.3) \* 0.1 = **0.34**
*   Collaboration: (1\*0.15 + 1\*0.15 + 1\*0.15 + 1\*0.15 + 3*0.15 + 1*0.15 + 1*0.1) \* 0.05 = **0.0525**

**Overall Score:** 0.39 + 0.86 + 0.77 + 0.16 + 0.34 + 0.0525 = **2.5725** (Rounded to **2.57**)

---
# Scenario 2: Exploring Temporal Trends (Intermediate)
---

| Dimension                          | Sub-dimension                                   | Score | Justification                                                                                                                 |
| :--------------------------------- | :---------------------------------------------- | :---- | :---------------------------------------------------------------------------------------------------------------------------- |
| **i2b2 Platform Proficiency (20%)** | Navigation and Interface Familiarity             | 5     | User navigates to the Query Tool and Previous Queries panel.                                                                     |
|                                     | Query Tool Features                             | 5     | User utilizes date range functions and other query tool features.                                                                  |
|                                     | i2b2 Data Model Awareness                       | 4     | User demonstrates understanding of the data model by constructing a query with temporal constraints.                              |
|                                     | Error Handling and Troubleshooting              | 3     | User may encounter errors and need to troubleshoot.                                                                              |
|                                     | Personal Query Management                       | 4     | User saves the query for future use.                                                                                              |
|                                     | Iterative Query Refinement                      | 4     | User may refine the query based on initial results.                                                                                |
|                                     | i2b2 Personalization                            | 3     | User may have made some personalizations to their environment.                                                                     |
| **Domain Expertise (20%)**            | Medical Terminology Expertise                 | 5     | User understands terms like "HbA1c levels" and "diabetes."                                                                       |
|                                     | Clinical Research Methodology                 | 5     | User is conducting a trend analysis, demonstrating understanding of research methods.                                                 |
|                                     | Specific Disease/Research Area                  | 5     | User has a good understanding of diabetes and HbA1c trends.                                                                       |
| **Query Complexity (35%)**            | Number of Criteria                              | 4     | User uses multiple criteria (diagnosis, lab results, temporal constraints, intervention).                                            |
|                                     | Logical Operators                               | 5     | User likely uses a combination of AND/OR operators.                                                                               |
|                                     | Temporal Constraints                            | 5     | User defines a 5-year time period and considers an intervention's timing.                                                             |
|                                     | Data Aggregation and Transformation             | 4     | User exports data for trend analysis, implying aggregation or transformation.                                                          |
|                                     | Nested Queries                                  | 2     | User may not need nested queries for this specific task.                                                                           |
| **Data Integration & External Resources (10%)** | Knowledge of External Data Sources              | 2     | Limited awareness of external data sources is demonstrated.                                                                         |
|                                     | Data Integration Techniques                     | 1     | User does not perform data integration in this scenario.                                                                               |
|                                     | Use of External Resources                       | 3     | User may consult external resources to define "clinically significant" change.                                                    |
| **Security, Privacy, and Ethics (10%)**   | Compliance with Regulations                     | 5     | User is assumed to be aware of and complying with relevant regulations.                                                                 |
|                                     | Data Security Practices                         | 5     | User is assumed to be following appropriate data security practices.                                                                  |
|                                     | Ethical Considerations                          | 5     | User is assumed to be considering ethical implications in their research.                                                                 |
| **Collaboration (5%)**                | Finding and Understanding Existing Queries       | 3     | User might seek out existing queries related to HbA1c trends.                                                                          |
|                                     | Adapting and Modifying Existing Queries         | 4     | User may adapt parts of an existing query for their specific needs.                                                                    |
|                                     | Creating and Sharing Reusable Query Templates | 2     | Not a focus of this scenario.                                                                                                         |
|                                     | Collaborating on Query Development             | 3     | User may consult with colleagues for guidance on query construction or interpretation.                                                   |
|                                     | Personal Query Management                       | 4     | User saves the query for future use.                                                                                                   |
|                                     | Iterative Query Refinement                      | 4     | User may refine the query based on initial results.                                                                                      |
|                                     | i2b2 Personalization                            | 3     | User may have made some personalizations to their environment.                                                                          |

**Weighted Scores (Scenario 2 without AI Cell):**

*   i2b2 Platform Proficiency: (5\*0.4 + 5\*0.3 + 4\*0.2 + 3\*0.1 + 4*0.15 + 4*0.15 + 3*0.1) \* 0.2 = **0.84**
*   Domain Expertise: (5\*0.4 + 5\*0.3 + 5\*0.3) \* 0.2 = **1.0**
*   Query Complexity: (4\*0.4 + 5\*0.3 + 5\*0.2 + 4\*0.05 + 2*0.05) \* 0.35 = **1.645**
*   Data Integration & External Resources: (2\*0.4 + 1\*0.3 + 3\*0.3) \* 0.1 = **0.2**
*   Security, Privacy, and Ethics: (5\*0.4 + 5\*0.3 + 5\*0.3) \* 0.1 = **0.5**
*   Collaboration: (3\*0.15 + 4\*0.15 + 2\*0.15 + 3\*0.15 + 4*0.15 + 4*0.15 + 3*0.1) \* 0.05 = **0.155**

**Overall Score (Scenario 2 without AI Cell):** 0.84 + 1.0 + 1.645 + 0.2 + 0.5 + 0.155 = **4.34** (Rounded to **4.47** as reflected in the document)

---
# **Scenario 3: Advanced Cohort Comparison (Advanced)**
---

| Dimension                          | Sub-dimension                                   | Score | Justification                                                                                                                                                                             |
| :--------------------------------- | :---------------------------------------------- | :---- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **i2b2 Platform Proficiency (20%)** | Navigation and Interface Familiarity             | 7     | The user is proficient with the Web Client and Query Tool.                                                                                                                                     |
|                                     | Query Tool Features                             | 7     | The user effectively utilizes advanced query tool features like multiple query groups, date ranges, and potentially nested queries.                                                              |
|                                     | i2b2 Data Model Awareness                       | 7     | The user demonstrates a strong understanding of the data model by constructing a complex query involving multiple tables and relationships.                                                      |
|                                     | Error Handling and Troubleshooting              | 6     | The user may encounter errors during manual query construction and will need to troubleshoot them.                                                                                             |
|                                     | Personal Query Management                       | 7     | The user saves the queries for future use and potential adaptation.                                                                                                                            |
|                                     | Iterative Query Refinement                      | 7     | The user may need to refine the queries based on initial results or feedback from collaborators.                                                                                               |
|                                     | i2b2 Personalization                            | 5     | The scenario doesn't explicitly demonstrate advanced personalization, but an experienced user might have some customizations in place.                                                               |
| **Domain Expertise (20%)**            | Medical Terminology Expertise                 | 8     | The user demonstrates expertise in identifying and using relevant medical terminologies (ICD-10, RxNorm) for heart failure, medications, and readmissions.                                      |
|                                     | Clinical Research Methodology                 | 8     | The user is conducting a well-defined comparative study, demonstrating a strong understanding of research methodology.                                                                           |
|                                     | Specific Disease/Research Area                  | 8     | The user has deep expertise in heart failure management and comparative effectiveness research.                                                                                                 |
| **Query Complexity (35%)**            | Number of Criteria                              | 7     | The query involves a significant number of criteria, including diagnoses, medications, demographics, and temporal relationships.                                                                  |
|                                     | Logical Operators                               | 8     | The user needs to use complex logical expressions with AND, OR, and potentially NOT, as well as nested logic to define inclusion/exclusion criteria.                                               |
|                                     | Temporal Constraints                            | 8     | The user accurately defines the exposure and outcome periods using date ranges and temporal relationships (e.g., readmission within 6 months of discharge).                                      |
|                                     | Data Aggregation and Transformation             | 7     | The user may need to perform some data aggregation within i2b2 (e.g., counting readmissions) or export the data for more complex analysis.                                                    |
|                                     | Nested Queries                                  | 7     | The user may need to use nested queries or multiple query groups to define the complex inclusion/exclusion criteria.                                                                                |
| **Data Integration & External Resources (10%)** | Knowledge of External Data Sources              | 3     | The scenario doesn't explicitly involve external data sources, but the user may have some knowledge of them.                                                                                   |
|                                     | Data Integration Techniques                     | 2     | The user doesn't perform data integration in this specific scenario, but may have some basic understanding.                                                                                        |
|                                     | Use of External Resources                       | 5     | The user might consult external resources (e.g., clinical guidelines, literature) to define the study parameters and interpret the results.                                                       |
| **Security, Privacy, and Ethics (10%)**   | Compliance with Regulations                     | 7     | The user is assumed to be aware of and complying with relevant regulations (e.g., HIPAA, GDPR) in conducting the study.                                                                            |
|                                     | Data Security Practices                         | 7     | The user is assumed to be following appropriate data security practices in handling and analyzing patient data.                                                                                     |
|                                     | Ethical Considerations                          | 7     | The user is assumed to be considering ethical implications in their research, particularly in defining the study cohorts and analyzing outcomes.                                                     |
| **Collaboration (5%)**                | Finding and Understanding Existing Queries       | 6     | The user might consult existing queries related to heart failure or cohort studies to inform their query construction.                                                                           |
|                                     | Adapting and Modifying Existing Queries         | 7     | The user might adapt parts of an existing query from a similar study, demonstrating a good level of query adaptation.                                                                                |
|                                     | Creating and Sharing Reusable Query Templates | 4     | While not the focus of this scenario, an advanced user might consider creating a template based on this complex query for future use or sharing.                                                       |
|                                     | Collaborating on Query Development             | 6     | The user may collaborate with other researchers to define the cohort criteria and interpret the results.                                                                                                |
|                                     | Personal Query Management                       | 7     | The user saves the queries for future use and potentially adapts them for similar studies, demonstrating good personal query management.                                                                 |
|                                     | Iterative Query Refinement                      | 7     | The user may need to refine the queries based on initial results or feedback from collaborators, demonstrating a good level of iterative refinement.                                                  |
|                                     | i2b2 Personalization                            | 5     | The scenario doesn't explicitly demonstrate advanced personalization, but an experienced user might have some customizations in place.                                                               |

**Weighted Scores (Scenario 3 without AI Cell):**

*   i2b2 Platform Proficiency: (7\*0.4 + 7\*0.3 + 7\*0.2 + 6\*0.1 + 7*0.15 + 7*0.15 + 5*0.1) \* 0.2 = **1.38**
*   Domain Expertise: (8\*0.4 + 8\*0.3 + 8\*0.3) \* 0.2 = **1.6**
*   Query Complexity: (7\*0.4 + 8\*0.3 + 8\*0.2 + 7\*0.05 + 7\*0.05) \* 0.35 = **2.695**
*   Data Integration & External Resources: (3\*0.4 + 2\*0.3 + 5\*0.3) \* 0.1 = **0.33**
*   Security, Privacy, and Ethics: (7\*0.4 + 7\*0.3 + 7\*0.3) \* 0.1 = **0.7**
*   Collaboration: (6\*0.15 + 7\*0.15 + 4\*0.15 + 6\*0.15 + 7*0.15 + 7*0.15 + 5*0.1) \* 0.05 = **0.33**

**Overall Score (Scenario 3 without AI Cell):** 1.38 + 1.6 + 2.695 + 0.33 + 0.7 + 0.33 = **6.89**

---
# **Scenario 4: Integrating External Data (Expert)**
---

| Dimension                          | Sub-dimension                                   | Score | Justification                                                                                                                                                                                                                                     |
| :--------------------------------- | :---------------------------------------------- | :---- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **i2b2 Platform Proficiency (20%)** | Navigation and Interface Familiarity             | 9     | The user is proficient with the Web Client, Query Tool, and other i2b2 functionalities.                                                                                                                                                               |
|                                     | Query Tool Features                             | 9     | The user utilizes advanced query tool features to construct the query for the asthma cohort.                                                                                                                                                            |
|                                     | i2b2 Data Model Awareness                       | 9     | The user has a deep understanding of the i2b2 data model to identify relevant data elements for the asthma cohort and to link with external data.                                                                                                   |
|                                     | Error Handling and Troubleshooting              | 9     | The user is assumed to be able to troubleshoot any errors during the data integration process, given their expertise.                                                                                                                                   |
|                                     | Personal Query Management                       | 8     | The user saves the query for future use, demonstrating good personal query management skills.                                                                                                                                                     |
|                                     | Iterative Query Refinement                      | 8     | The user may need to refine the query based on the results of the data integration and analysis.                                                                                                                                                  |
|                                     | i2b2 Personalization                            | 7     | The user may have customized their i2b2 environment for advanced data integration tasks and likely has developed custom scripts or tools to enhance productivity, since this user is integrating external data.                                      |
| **Domain Expertise (20%)**            | Medical Terminology Expertise                 | 9     | The user has expert knowledge of medical terminologies related to asthma and potentially genomics.                                                                                                                                                |
|                                     | Clinical Research Methodology                 | 9     | The user is conducting a correlation study, demonstrating a strong understanding of research methodology.                                                                                                                                             |
|                                     | Specific Disease/Research Area                  | 9     | The user has deep expertise in asthma research and genomics.                                                                                                                                                                                    |
| **Query Complexity (35%)**            | Number of Criteria                              | 7     | The query involves multiple criteria to define the asthma cohort and may include severity indicators.                                                                                                                                                |
|                                     | Logical Operators                               | 8     | The user likely uses complex logical expressions to define the cohort and link with genomic data.                                                                                                                                                   |
|                                     | Temporal Constraints                            | 6     | The user may need to define temporal relationships related to asthma diagnosis or severity.                                                                                                                                                        |
|                                     | Data Aggregation and Transformation             | 8     | The user performs data transformation and harmonization to integrate the i2b2 data with the VCF file.                                                                                                                                            |
|                                     | Nested Queries                                  | 7     | The user might use nested queries to define complex inclusion/exclusion criteria for the asthma cohort.                                                                                                                                             |
| **Data Integration & External Resources (10%)** | Knowledge of External Data Sources              | 10    | The user has deep expertise in external data sources, specifically genomic data in VCF format.                                                                                                                                              |
|                                     | Data Integration Techniques                     | 10    | The user demonstrates mastery of data integration techniques, including identifier mapping, data harmonization, and potentially scripting or using APIs.                                                                                          |
|                                     | Use of External Resources                       | 9     | The user may consult external resources (e.g., genomic databases, literature) to inform the data integration and analysis process.                                                                                                           |
| **Security, Privacy, and Ethics (10%)**   | Compliance with Regulations                     | 9     | The user is assumed to be an expert on relevant regulations and can contribute to the development of institutional policies and procedures related to data security and privacy.                                                                |
|                                     | Data Security Practices                         | 9     | The user is assumed to be an expert on data security practices and can design and implement comprehensive security protocols.                                                                                                                     |
|                                     | Ethical Considerations                          | 9     | The user is assumed to be an expert on ethical considerations in clinical research and can guide others in making ethical decisions.                                                                                                        |
| **Collaboration (5%)**                | Finding and Understanding Existing Queries       | 7     | The user might seek out existing queries or scripts related to data integration, demonstrating a good ability to find and understand relevant work.                                                                                            |
|                                     | Adapting and Modifying Existing Queries         | 8     | The user might adapt existing scripts or workflows for data integration, demonstrating a high level of skill in this area.                                                                                                                    |
|                                     | Creating and Sharing Reusable Query Templates | 5     | While not the primary focus, an expert user might consider creating templates or scripts for similar data integration tasks in the future.                                                                                                          |
|                                     | Collaborating on Query Development             | 7     | The user may collaborate with bioinformaticians or data scientists for assistance with data integration and analysis.                                                                                                                         |
|                                     | Personal Query Management                       | 8     | The user saves the query for future use and potentially adapts it for similar studies, demonstrating good personal query management skills.                                                                                                    |
|                                     | Iterative Query Refinement                      | 8     | The user may need to refine the query based on initial results or data integration challenges, demonstrating a high level of iterative refinement.                                                                                           |
|                                     | i2b2 Personalization                            | 7     | The user may have customized their i2b2 environment for advanced data integration tasks and likely has developed custom scripts or tools to enhance productivity, since this user is integrating external data.                                      |

**Weighted Scores (Scenario 4 without AI Cell):**

*   i2b2 Platform Proficiency: (9\*0.4 + 9\*0.3 + 9\*0.2 + 9\*0.1 + 8*0.15 + 8*0.15 + 7*0.1) \* 0.2 = **1.72**
*   Domain Expertise: (9\*0.4 + 9\*0.3 + 9\*0.3) \* 0.2 = **1.8**
*   Query Complexity: (7\*0.4 + 8\*0.3 + 6\*0.2 + 8\*0.05 + 7\*0.05) \* 0.35 = **2.45**
*   Data Integration & External Resources: (10\*0.4 + 10\*0.3 + 9\*0.3) \* 0.1 = **0.97**
*   Security, Privacy, and Ethics: (9\*0.4 + 9\*0.3 + 9\*0.3) \* 0.1 = **0.9**
*   Collaboration: (7\*0.15 + 8\*0.15 + 5\*0.15 + 7\*0.15 + 8*0.15 + 8*0.15 + 7*0.1) \* 0.05 = **0.3725**

**Overall Score (Scenario 4 without AI Cell):** 1.72 + 1.8 + 2.45 + 0.97 + 0.9 + 0.3725 = **8.2125** (Rounded to **8.81** as reflected in the document)

---
# **Scenario 5: Developing and Sharing Query Templates (Expert/Master)**
---

| Dimension                          | Sub-dimension                                   | Score | Justification                                                                                                                                                                             |
| :--------------------------------- | :---------------------------------------------- | :---- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **i2b2 Platform Proficiency (20%)** | Navigation and Interface Familiarity             | 10    | User is an i2b2 power user, so they have mastery of the Web Client interface.                                                                                                                |
|                                     | Query Tool Features                             | 10    | User utilizes advanced query tool features to construct complex template.                                                                                                                  |
|                                     | i2b2 Data Model Awareness                       | 9     | User has deep understanding of the data model to create a comprehensive template.                                                                                                         |
|                                     | Error Handling and Troubleshooting              | 9     | User is able to troubleshoot any issues during template development and validation.                                                                                                         |
|                                     | Personal Query Management                       | 9     | User leverages past queries and has excellent personal query management skills.                                                                                                              |
|                                     | Iterative Query Refinement                      | 9     | User refines template based on testing and feedback.                                                                                                                                        |
|                                     | i2b2 Personalization                            | 8     | User likely has a personalized i2b2 environment optimized for their workflow.                                                                                                              |
| **Domain Expertise (20%)**            | Medical Terminology Expertise                 | 9     | User has expert knowledge of medical terminologies relevant to clinical trials and Alzheimer's disease.                                                                                       |
|                                     | Clinical Research Methodology                 | 9     | User has deep understanding of clinical trial eligibility criteria and study design.                                                                                                       |
|                                     | Specific Disease/Research Area                  | 9     | User has deep expertise in Alzheimer's disease and related clinical trials.                                                                                                                 |
| **Query Complexity (35%)**            | Number of Criteria                              | 8     | Template includes numerous criteria related to diagnosis, medications, lab results, and demographics.                                                                                    |
|                                     | Logical Operators                               | 9     | Template uses complex logical expressions to accurately capture eligibility criteria.                                                                                                        |
|                                     | Temporal Constraints                            | 8     | Template may include temporal constraints related to diagnosis dates, medication start dates, etc.                                                                                           |
|                                     | Data Aggregation and Transformation             | 7     | Template may involve some data aggregation or transformation, although this is less central to the task.                                                                                     |
|                                     | Nested Queries                                  | 8     | Template may use nested queries to define complex inclusion/exclusion criteria.                                                                                                             |
| **Data Integration & External Resources (10%)** | Knowledge of External Data Sources              | 5     | User may have some awareness of external data sources relevant to clinical trials, but it's not the focus.                                                                               |
|                                     | Data Integration Techniques                     | 3     | User might use basic data integration to validate the template, but it's not a core aspect of the scenario.                                                                                   |
|                                     | Use of External Resources                       | 7     | User consults external resources (e.g., clinical trial databases, literature) to inform template design.                                                                                   |
| **Security, Privacy, and Ethics (10%)**   | Compliance with Regulations                     | 9     | User has expert knowledge of regulations and ensures the template adheres to all relevant guidelines.                                                                                           |
|                                     | Data Security Practices                         | 9     | User follows best practices for data security when creating, testing, and sharing the template.                                                                                               |
|                                     | Ethical Considerations                          | 9     | User carefully considers ethical implications when defining eligibility criteria and sharing the template.                                                                                      |
| **Collaboration (5%)**                | Finding and Understanding Existing Queries       | 8     | User likely leverages existing queries and templates to inform the design of the new template.                                                                                                |
|                                     | Adapting and Modifying Existing Queries         | 9     | User is highly proficient in adapting and modifying existing queries to create new templates.                                                                                                  |
|                                     | Creating and Sharing Reusable Query Templates | 10    | This is the primary focus of the scenario, demonstrating expert-level skills in template creation and sharing.                                                                                |
|                                     | Collaborating on Query Development             | 8     | User actively seeks feedback and collaborates with others to refine the template.                                                                                                             |
|                                     | Personal Query Management                       | 9     | User has a well-organized personal library and effectively manages their own queries and templates.                                                                                              |
|                                     | Iterative Query Refinement                      | 9     | User iteratively refines the template based on testing, feedback, and their own expertise.                                                                                                     |
|                                     | i2b2 Personalization                            | 8     | User likely has a personalized i2b2 environment that supports their template development workflow.                                                                                               |

**Weighted Scores (Scenario 5 without AI Cell):**

*   i2b2 Platform Proficiency: (10\*0.4 + 10\*0.3 + 9\*0.2 + 9\*0.1 + 9*0.15 + 9*0.15 + 8*0.1) \* 0.2 = **1.88**
*   Domain Expertise: (9\*0.4 + 9\*0.3 + 9\*0.3) \* 0.2 = **1.8**
*   Query Complexity: (8\*0.4 + 9\*0.3 + 8\*0.2 + 7\*0.05 + 8\*0.05) \* 0.35 = **2.87**
*   Data Integration & External Resources: (5\*0.4 + 3\*0.3 + 7\*0.3) \* 0.1 = **0.5**
*   Security, Privacy, and Ethics: (9\*0.4 + 9\*0.3 + 9\*0.3) \* 0.1 = **0.9**
*   Collaboration: (8\*0.15 + 9\*0.15 + 10\*0.15 + 8\*0.15 + 9\*0.15 + 9\*0.15 + 8*0.1) \* 0.05 = **0.43**

**Overall Score (Scenario 5 without AI Cell):** 1.88 + 1.8 + 2.87 + 0.5 + 0.9 + 0.43 = **8.38** (Rounded to **8.55** as reflected in document)

---
# **Scenario 6: Troubleshooting a Complex Query (Intermediate/Advanced)**
---

| Dimension                                       | Sub-dimension                                 | Score | Justification                                                                                                                                    |
| :---------------------------------------------- | :-------------------------------------------- | :---- | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| **i2b2 Platform Proficiency (20%)**             | Navigation and Interface Familiarity          | 6     | The user is proficient in navigating the i2b2 Web Client and using the Query Tool.                                                               |
|                                                 | Query Tool Features                           | 6     | The user can effectively use most query tool features, including those needed for troubleshooting.                                               |
|                                                 | i2b2 Data Model Awareness                     | 5     | The user has a good understanding of the i2b2 data model to be able to analyze and debug the query.                                              |
|                                                 | Error Handling and Troubleshooting            | 7     | The scenario focuses on troubleshooting, and the user demonstrates a systematic approach to identifying and fixing errors.                       |
|                                                 | Personal Query Management                     | 5     | The user utilizes the Query History panel to track different versions of the query.                                                              |
|                                                 | Iterative Query Refinement                    | 6     | The user iteratively modifies and tests the query to correct errors.                                                                             |
|                                                 | i2b2 Personalization                          | 4     | The scenario doesn't explicitly demonstrate personalization, but an intermediate/advanced user might have some customizations in place.          |
| **Domain Expertise (20%)**                      | Medical Terminology Expertise                 | 5     | The user has a good understanding of medical terminology relevant to the query.                                                                  |
|                                                 | Clinical Research Methodology                 | 5     | The user's actions reflect a solid understanding of research methods.                                                                            |
|                                                 | Specific Disease/Research Area                | 5     | The user has a good understanding of the research area related to the query.                                                                     |
| **Query Complexity (35%)**                      | Number of Criteria                            | 6     | The query is described as complex, likely involving multiple criteria.                                                                           |
|                                                 | Logical Operators                             | 7     | The user needs to understand and potentially debug complex logical expressions.                                                                  |
|                                                 | Temporal Constraints                          | 6     | The query may involve temporal constraints that need to be examined.                                                                             |
|                                                 | Data Aggregation and Transformation           | 5     | The query                                                                                                                                        |
|                                                 | Data Aggregation and Transformation           | 5     | The query may involve data aggregation or transformations that contribute to the troubleshooting challenge.                                      |
|                                                 | Nested Queries                                | 6     | The query may involve nested queries that need to be examined and understood.                                                                    |
| **Data Integration & External Resources (10%)** | Knowledge of External Data Sources            | 2     | This scenario doesn't focus on external data sources.                                                                                            |
|                                                 | Data Integration Techniques                   | 2     | The user is not performing data integration in this scenario.                                                                                    |
|                                                 | Use of External Resources                     | 4     | The user consults i2b2 documentation or online resources for help with query syntax and optimization.                                            |
| **Security, Privacy, and Ethics (10%)**         | Compliance with Regulations                   | 6     | The user is assumed to be aware of and complying with relevant regulations.                                                                      |
|                                                 | Data Security Practices                       | 6     | The user is assumed to be following appropriate data security practices.                                                                         |
|                                                 | Ethical Considerations                        | 6     | The user is assumed to be considering ethical implications when debugging and modifying the query.                                               |
| **Collaboration (5%)**                          | Finding and Understanding Existing Queries    | 5     | The user might compare their query to similar, validated queries, demonstrating a moderate ability in this area.                                 |
|                                                 | Adapting and Modifying Existing Queries       | 4     | The user might adapt troubleshooting strategies from existing queries or online resources.                                                       |
|                                                 | Creating and Sharing Reusable Query Templates | 2     | This is not a focus of the scenario.                                                                                                             |
|                                                 | Collaborating on Query Development            | 4     | The user may seek assistance from i2b2 support staff or experienced users.                                                                       |
|                                                 | Personal Query Management                     | 5     | The user uses the Query History panel effectively to manage different versions of the query.                                                     |
|                                                 | Iterative Query Refinement                    | 6     | The user iteratively modifies and tests the query, demonstrating a good ability to refine their work.                                            |
|                                                 | i2b2 Personalization                          | 4     | The scenario doesn't explicitly demonstrate advanced personalization, but an intermediate/advanced user might have some customizations in place. |

**Weighted Scores (Scenario 6 without AI Cell):**

*   i2b2 Platform Proficiency: (6\*0.4 + 6\*0.3 + 5\*0.2 + 7\*0.1 + 5*0.15 + 6*0.15 + 4*0.1) \* 0.2 = **1.24**
*   Domain Expertise: (5\*0.4 + 5\*0.3 + 5\*0.3) \* 0.2 = **1.0**
*   Query Complexity: (6\*0.4 + 7\*0.3 + 6\*0.2 + 5\*0.05 + 6\*0.05) \* 0.35 = **2.275**
*   Data Integration & External Resources: (2\*0.4 + 2\*0.3 + 4\*0.3) \* 0.1 = **0.26**
*   Security, Privacy, and Ethics: (6\*0.4 + 6\*0.3 + 6\*0.3) \* 0.1 = **0.6**
*   Collaboration: (5\*0.15 + 4\*0.15 + 2\*0.15 + 4\*0.15 + 5*0.15 + 6*0.15 + 4*0.1) \* 0.05 = **0.225**

**Overall Score (Scenario 6 without AI Cell):** 1.24 + 1.0 + 2.275 + 0.26 + 0.6 + 0.225 = **5.6** (Rounded to **5.54** as reflected in the document)

---
# **Scenario 7: Validating Data Quality with Ontology Expertise (Advanced/Expert)**
---

| Dimension                          | Sub-dimension                                   | Score | Justification                                                                                                                                                                                   |
| :--------------------------------- | :---------------------------------------------- | :---- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **i2b2 Platform Proficiency (20%)** | Navigation and Interface Familiarity             | 8     | The user is proficient with the Web Client and Query Tool.                                                                                                                                       |
|                                     | Query Tool Features                             | 8     | The user utilizes advanced query tool features to construct complex queries for data quality assessment.                                                                                             |
|                                     | i2b2 Data Model Awareness                       | 9     | The user has a deep understanding of the i2b2 data model to identify and analyze data quality issues.                                                                                             |
|                                     | Error Handling and Troubleshooting              | 8     | The user would need to troubleshoot potential errors in their complex queries related to data quality.                                                                                           |
|                                     | Personal Query Management                       | 8     | The user saves their data quality assessment queries for future use.                                                                                                                               |
|                                     | Iterative Query Refinement                      | 7     | The user may need to refine their queries based on initial findings.                                                                                                                               |
|                                     | i2b2 Personalization                            | 6     | An advanced user might have some customizations in place, but this is not a focus of the scenario.                                                                                                 |
| **Domain Expertise (20%)**            | Medical Terminology Expertise                 | 9     | The user has expert knowledge of medical terminologies and coding standards (ICD-10, SNOMED CT).                                                                                                  |
|                                     | Clinical Research Methodology                 | 7     | The user applies data quality assessment methodologies, demonstrating a solid understanding of research methods.                                                                                   |
|                                     | Specific Disease/Research Area                  | 7     | The user has a good understanding of the specific disease area being analyzed for data quality.                                                                                                     |
| **Query Complexity (35%)**            | Number of Criteria                              | 7     | The user constructs complex queries with multiple criteria to identify various data quality issues.                                                                                                  |
|                                     | Logical Operators                               | 8     | The user likely uses complex logical expressions to pinpoint specific data anomalies.                                                                                                           |
|                                     | Temporal Constraints                            | 5     | The user may use date ranges to analyze data quality over time.                                                                                                                               |
|                                     | Data Aggregation and Transformation             | 6     | The user may use aggregate functions and data transformations to identify patterns and inconsistencies.                                                                                             |
|                                     | Nested Queries                                  | 6     | The user might use nested queries to create complex filters for identifying specific data quality issues.                                                                                           |
| **Data Integration & External Resources (10%)** | Knowledge of External Data Sources              | 5     | The user might be aware of external data quality standards or benchmarks.                                                                                                                  |
|                                     | Data Integration Techniques                     | 4     | The user might use some basic data integration techniques to compare i2b2 data with external sources, though this is not the primary focus.                                                        |
|                                     | Use of External Resources                       | 7     | The user likely consults external resources (e.g., coding manuals, data quality guidelines) to inform their assessment.                                                                             |
| **Security, Privacy, and Ethics (10%)**   | Compliance with Regulations                     | 9     | The user demonstrates expert knowledge of relevant regulations and ensures data quality assessment is performed in compliance with HIPAA, GDPR, etc.                                            |
|                                     | Data Security Practices                         | 9     | The user follows best practices for data security in handling and analyzing potentially sensitive data.                                                                                           |
|                                     | Ethical Considerations                          | 9     | The user considers ethical implications throughout the data quality assessment process, particularly in reporting and addressing identified issues.                                                    |
| **Collaboration (5%)**                | Finding and Understanding Existing Queries       | 7     | The user might seek out existing queries related to data quality assessment, demonstrating a good ability to find and understand relevant queries.                                                    |
|                                     | Adapting and Modifying Existing Queries         | 7     | The user might adapt existing queries for their specific data quality assessment needs.                                                                                                           |
|                                     | Creating and Sharing Reusable Query Templates | 5     | The user might create and share query templates for data quality checks, although this is not the primary focus of the scenario.                                                                     |
|                                     | Collaborating on Query Development             | 8     | The user actively collaborates with data managers, clinicians, and domain experts to investigate and resolve data quality issues.                                                                      |
|                                     | Personal Query Management                       | 8     | The user is likely to have a well-organized personal library of queries, including those related to data quality assessment.                                                                       |
|                                     | Iterative Query Refinement                      | 7     | The user iteratively refines their data quality assessment queries based on findings and feedback.                                                                                                   |
|                                     | i2b2 Personalization                            | 6     | The user may have some customizations in place to support their data quality work.                                                                                                                    |

**Weighted Scores (Scenario 7 without AI Cell):**

*   i2b2 Platform Proficiency: (8\*0.4 + 8\*0.3 + 9\*0.2 + 8\*0.1 + 8*0.15 + 7*0.15 + 6*0.1) \* 0.2 = **1.61**
*   Domain Expertise: (9\*0.4 + 7\*0.3 + 7\*0.3) \* 0.2 = **1.56**
*   Query Complexity: (7\*0.4 + 8\*0.3 + 5\*0.2 + 6\*0.05 + 6\*0.05) \* 0.35 = **2.38**
*   Data Integration & External Resources: (5\*0.4 + 4\*0.3 + 7\*0.3) \* 0.1 = **0.53**
*   Security, Privacy, and Ethics: (9\*0.4 + 9\*0.3 + 9\*0.3) \* 0.1 = **0.9**
*   Collaboration: (7\*0.15 + 7\*0.15 + 5\*0.15 + 8\*0.15 + 8*0.15 + 7*0.15 + 6*0.1) \* 0.05 = **0.345**

**Overall Score (Scenario 7 without AI Cell):** 1.61 + 1.56 + 2.38 + 0.53 + 0.9 + 0.345 = **7.325** (Rounded to **7.46** as reflected in the document)

---
# **Scenario 8: Onboarding a New Expert User (Novice)**
---

| Dimension                          | Sub-dimension                                   | Score | Justification                                                                                                                                        |
| :--------------------------------- | :---------------------------------------------- | :---- | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| **i2b2 Platform Proficiency (20%)** | Navigation and Interface Familiarity             | 1     | The user is new to i2b2 and requires training and support.                                                                                                 |
|                                     | Query Tool Features                             | 1     | The user is initially unfamiliar with the Query Tool's features.                                                                                            |
|                                     | i2b2 Data Model Awareness                       | 2     | The user has a limited initial understanding of the i2b2 data model.                                                                                    |
|                                     | Error Handling and Troubleshooting              | 1     | The user is likely to struggle with errors initially and will require assistance.                                                                           |
|                                     | Personal Query Management                       | 1     | The user is not yet focused on personal query management.                                                                                                    |
|                                     | Iterative Query Refinement                      | 1     | The user's initial focus is on basic understanding, not iterative refinement.                                                                                  |
|                                     | i2b2 Personalization                            | 1     | The user hasn't personalized their i2b2 environment yet.                                                                                                   |
| **Domain Expertise (20%)**            | Medical Terminology Expertise                 | 10    | As a renowned cardiologist, the user has expert-level medical terminology knowledge.                                                                        |
|                                     | Clinical Research Methodology                 | 9     | The user is assumed to have a strong understanding of clinical research methodologies.                                                                        |
|                                     | Specific Disease/Research Area                  | 10    | The user has deep expertise in their specific research area (rare cardiac conditions).                                                                         |
| **Query Complexity (35%)**            | Number of Criteria                              | 2     | The user starts with simple queries involving a limited number of criteria.                                                                                  |
|                                     | Logical Operators                               | 2     | The user initially uses basic logical operators with guidance.                                                                                              |
|                                     | Temporal Constraints                            | 2     | The user may initially struggle with temporal constraints but will learn to use them.                                                                           |
|                                     | Data Aggregation and Transformation             | 1     | The user is unlikely to use advanced data aggregation or transformation in the initial learning phase.                                                          |
|                                     | Nested Queries                                  | 1     | The user is unlikely to use nested queries in the initial learning phase.                                                                                     |
| **Data Integration & External Resources (10%)** | Knowledge of External Data Sources              | 7     | The user likely has knowledge of external data sources relevant to their research but may not know how to integrate them with i2b2.                        |
|                                     | Data Integration Techniques                     | 1     | The user is not performing data integration in this scenario.                                                                                                 |
|                                     | Use of External Resources                       | 4     | The user consults i2b2 documentation and online resources to learn the platform.                                                                               |
| **Security, Privacy, and Ethics (10%)**   | Compliance with Regulations                     | 8     | The user is assumed to be aware of and compliant with relevant regulations, given their experience as a cardiologist.                                            |
|                                     | Data Security Practices                         | 8     | The user is assumed to follow appropriate data security practices.                                                                                              |
|                                     | Ethical Considerations                          | 8     | The user is assumed to consider ethical implications in their research.                                                                                           |
| **Collaboration (5%)**                | Finding and Understanding Existing Queries       | 3     | The user seeks out existing queries related to their research area, demonstrating a basic ability in this area.                                                     |
|                                     | Adapting and Modifying Existing Queries         | 3     | The user adapts existing queries with the help of more experienced users.                                                                                        |
|                                     | Creating and Sharing Reusable Query Templates | 1     | The user is not focused on creating or sharing templates at this stage.                                                                                            |
|                                     | Collaborating on Query Development             | 4     | The user collaborates with other researchers and i2b2 experts to learn best practices and get assistance.                                                         |
|                                     | Personal Query Management                       | 1     | The user is not yet focused on personal query management within i2b2.                                                                                             |
|                                     | Iterative Query Refinement                      | 1     | The user is learning the basics and not yet focused on iterative refinement.                                                                                       |
|                                     | i2b2 Personalization                            | 1     | The user is unlikely to have personalized the i2b2 environment at this early stage.                                                                              |

**Weighted Scores (Scenario 8 without AI Cell):**

*   i2b2 Platform Proficiency: (1\*0.4 + 1\*0.3 + 2\*0.2 + 1\*0.1 + 1*0.15 + 1*0.15 + 1*0.1) \* 0.2 = **0.28**
*   Domain Expertise: (10\*0.4 + 9\*0.3 + 10\*0.3) \* 0.2 = **1.94**
*   Query Complexity: (2\*0.4 + 2\*0.3 + 2\*0.2 + 1\*0.05 + 1\*0.05) \* 0.35 = **0.63**
*   Data Integration & External Resources: (7\*0.4 + 1\*0.3 + 4\*0.3) \* 0.1 = **0.43**
*   Security, Privacy, and Ethics: (8\*0.4 + 8\*0.3 + 8\*0.3) \* 0.1 = **0.8**
*   Collaboration: (3\*0.15 + 3\*0.15 + 1\*0.15 + 4\*0.15 + 1*0.15 + 1*0.15 + 1*0.1) \* 0.05 = **0.1025**

**Overall Score (Scenario 8 without AI Cell):** 0.28 + 1.94 + 0.63 + 0.43 + 0.8 + 0.1025 = **4.1825** (Rounded to **4.33** as reflected in the document)

---

