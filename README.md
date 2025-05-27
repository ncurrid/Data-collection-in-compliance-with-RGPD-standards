# Collect data in compliance with RGPD standards
# I. Context
As part of a consulting mission, I worked as a Business Intelligence (BI) Analyst for Dev'Immediat, an automobile insurance brokerage firm.

The company, whose core business lies in developing partnerships and generating margins on insurance contracts, requested assistance in processing their automobile insurance data securely.

A data protection issue had recently arisen following a customer complaint. As a result, Dev'Immediat faced the risk of sanctions from the CNIL (the French authority responsible for personal data protection). This situation prompted the company to initiate a compliance effort with the General Data Protection Regulation (GDPR).

The goal of the mission was to analyze their data processing practices and help them achieve GDPR compliance, particularly regarding the handling of personal customer data.

# II. Methodology
## 1. Defining the Scope
The first step was to establish a clear framework for the mission:

Familiarize with GDPR regulations, especially those concerning customer data collection, storage, and usage.

Identify the applicable rules based on the nature of the data collected and processed by the company.

Determine the internal point of contact responsible for data confidentiality, typically the Data Protection Officer (DPO).

Connect to the company’s Customer Relationship Management (CRM) system and analyze the database using SQLite Studio.

Draft at least five actionable recommendations regarding CRM data management, with the goal of aligning with GDPR standards.

## 2. Data Extraction
Extract customer data only for the current year and only for complete customer files.

Select strictly necessary data for the analysis (data minimization principle).

Ensure that no unnecessary or excessive personal data is included in the processing.

## 3. Data Cleaning
To comply with GDPR principles, the dataset needed to be prepared carefully. Actions taken included:

Anonymizing or generalizing sensitive data:

Replace precise values with categories (e.g., annual income converted into income brackets).

Convert numerical data into binary or simplified categories (e.g., number of children changed to “has children: yes/no”).

Replace customer IDs with randomly generated indexes to prevent identification.

Adapt the dataset to ensure pricing data complies with fair and lawful processing principles.

Document any limitations or non-compliant practices that could not be immediately resolved, along with recommendations for improvement.

## 4. Documentation and Recommendations
Write a detailed report using the template provided by the DPO, documenting:

The quality and compliance of data collection and processing.

Measures taken to align with GDPR requirements.

Suggestions for continuous improvement and long-term compliance.

Include recommendations for CRM data governance, such as:

Data retention policies

Access restrictions

Audit procedures

User consent management

Data minimization strategies

## 5. Presentation to General Management
Prepare a clear and concise presentation for the General Manager, focusing on:

The importance of GDPR compliance for risk reduction and brand trust.

The actions already taken and their impact.

Key recommendations in accessible language.

Avoid overly technical language, and explain any necessary terminology.

Maintain a reassuring and constructive tone, emphasizing progress and practical steps forward.

# III. Technologies & Skills
## 1. Tools Used
Microsoft Excel & Power Query – for data cleaning, transformation, and anonymization

SQLite Studio – for data extraction and structure analysis

Microsoft PowerPoint – for preparing and delivering the final presentation

## 2. Skills Applied
GDPR regulation understanding

Data extraction and filtering using SQL

Data anonymization and ethical handling

Clear and non-technical communication

Professional reporting and documentation
