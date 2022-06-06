# Background

You have defined Henry’s HESG problem as answering: “How effective is our back-office capability for processing student claims?”

Your analysis indicates that the answer seeks to balance the issues of Customer Experience with Back-Office Operations. Collectively, the answers to these issues should address most stakeholder concerns.

Customer Experience relies on:

    Net Promoter Score (student’s NPS upon closing each claim);
    Claim-to-cash time (time from submission to paying claims);
    Accuracy of payment (% of claims that reopened after closure to fix remittance).

Back-Office Operations relies on:

    Claims Processed per Team Member (volume/ FTEs);
    Fraudulent Claim Payments ($ paid to claims that were later discovered to not have been eligible for rebate);
    Employee Satisfaction Score (measured weekly to gauge employee engagement).

You will need to choose KPI-relevant data extracts from the available systems, as per the previous information (i.e., Claims Case System, Payment System, Fraud Management System, Employee Satisfaction Scores, and/ or Net Promoter Score). You will then need to enhance the data quality in order to prepare to build the dashboard. The key performance indicators identified in the previous task can be used as a starting point for considering data sources.

# Task
You are in charge of preparing for a client kick-off workshop to develop the analytics dashboard. You will receive data from all the systems identified in task 1. This data will need to be assessed and improved in preparation for building the analytics dashboard. 

Review all the available data as per the activities below to guide you to prepare for designing the dashboard, and to answer four related questions: 

    Q1: Which data set pair (within the list provided) is not required to inform and calculate the key performance indicators of Net Promotor Score, Claim-To-Cash Time, Accuracy of Payment, Claims Processed Per Team Member, Fraudulent Claim Payments and Employee Satisfaction Score? 

    Q2: Using the remaining data sets, what is the recommended reporting time period for all KPIs? (Enhance data quality by removing unneeded data, deduplication, and ensuring fields are optimised for calculations. Keep the quality data ready for the next task and answer the remaining questions in this task.)

    Q3: After improving the data quality, what is the number of employees (FTEs) working in the Back-Office during the week starting 21 March 2021 (week 13)? 

    Q4: After improving the data quality, what is the number of claims that were processed during the week starting 28 March 2021 (week 14)? 
    
    
## Resources
Data Stewardship

Jane forwarded a summary document about Henry’s approach to planning and data stewardship and frequency that was done for another project. See below the notes: 

Notes from Henry’s Planning and Data Stewardship

Planning cycles include:

    Weekly planning for staffing and resource allocation with HESG and Operations leads
    Monthly budget spend reviews with HESG and Finance
    Monthly performance reports to Government
    Quarterly budget forecasts with all stakeholders

Henry reports that DSS has Four-C Data Principles. This means that data is:

    Complete: Results reflect all data, and thus there no gaps of missing elements. Closure of missing data is always noted and reported to business owners for remediation.
    Correct: Results can be traced back to input data to ensure audit trails exist for all DSS results
    Comparable: Results can be compared and actioned across multiple DSS dimensions and elements to ensure changes are uniformly considered.
    Current: Results are based on the latest data and reflect DSS's present supply and demand.

**General Notes:**<br>

Claims are counted as processed in the period in which they are paid or closed. So, if we start a claim in t(n), but only close it in t(n+1), it is counted as processed in t(n+1). If we then reopen the claim and do query work on it in t(n+3), the claim is counted as processed in t(n+3).

There are on-going interventions that may result in processing increases or decreases.

Both Henry and the Director of Operations seek weekly reports to action with team leads.
