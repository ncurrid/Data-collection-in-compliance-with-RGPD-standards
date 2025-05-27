# Data collection in compliance with RGPD standards
# I. Context
As part of a consulting mission, I worked as a Business Intelligence (BI) Analyst for Dev'Immediat, an automobile insurance brokerage firm.

The company, whose core business lies in developing partnerships and generating margins on insurance contracts, requested assistance in processing their automobile insurance data safely.

A data protection issue had recently arisen following a customer complaint. As a result, Dev'Immediat faced the risk of sanctions from the CNIL (the French authority responsible for personal data protection). This situation prompted the company to initiate a compliance effort with the General Data Protection Regulation (GDPR).

The goal of the mission was to analyse their data processing practices and help them achieve GDPR compliance, particularly regarding the handling of personal customer data.

# II. Methodology
## 1. Defining the ccope
The first step was to establish a clear framework for the mission:

- Familiarise with GDPR regulations, especially those concerning customer data collection, storage, and usage.

- Identify the applicable rules based on the nature of the data collected and processed by the company.

- Determine the internal point of contact responsible for data confidentiality, typically the Data Protection Officer (DPO).

- Connect to the company’s Customer Relationship Management (CRM) system and analyze the database using SQLite Studio.

- Draft at least five actionable recommendations regarding CRM data management, with the goal of aligning with GDPR standards.

## 2. Data extraction
- Extract customer data only for the current year and only for complete customer files.

- Select strictly necessary data for the analysis (data minimisation principle).

- Ensure that no unnecessary or excessive personal data was included in the process.

## 3. Data cleaning
To comply with GDPR principles, the dataset needed to be prepared carefully. Actions taken included:

- Anonymising or generalising sensitive data: replacing precise values with categories (eg: annual income converted into income brackets).

- Converting numerical data into binary categories (eg: number of children changed to “has children: yes/no”).

- Replacing customer IDs with randomly generated indexes to prevent identification.

- Adapting the dataset to ensure pricing data complied with fair and lawful processing principles.

- Documenting any limitations or non-compliant practices that could not be immediately resolved, along with recommendations for improvement.

## 4. Documentation and recommendations
Wrote a detailed report using the template provided by the DPO, documenting:

- The quality and compliance of data collection and processing.

- Measures taken to align with GDPR requirements.

- Suggestions for continuous improvement and long-term compliance.

Included recommendations for CRM data governance, such as:

- Data retention policies

- Access restrictions

- Audit procedures

- User consent management

- Data minimisation strategies

## 5. Presentation to general management
Prepared a clear and concise presentation for the General Manager, focusing on:

- The importance of GDPR compliance for risk reduction and brand trust.

- The actions already taken and their impact.

- Key recommendations.

Maintain a reassuring and constructive tone, emphasising progress and practical steps forward.

# III. Tools used
Microsoft Excel & Power Query: for data cleaning, transformation, and anonymisation

SQLite Studio: for data extraction and structure analysis

Microsoft PowerPoint: for the final presentation
