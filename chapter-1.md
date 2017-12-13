## Data Warehousing, Business Intelligence, and Dimensional Modeling Primer

### Different Worlds of Data Capture and Data Analysis
- two purposes: 1) operation record keeping, 2) analytical decision making 
- operational systems: optimized to process transactions quickly
 - typically do not maintain history
- DW/BI systems: optimized for high-performance queries that require hundreds of thousands of transactions to be searched.
 - worry about whether operational processes are working correctly 
 - typically demands that historical context be preserved to accurately evaluate the organization's performance over time.

### Goals of Data Warehousing and Business Intelligence.
- must make information easily accessible - simple and fast
- must present information consistently - 
- must adapt to change
- must present information in a timely way
- must be a secure bastion that protects the information
- must serve as the authoritative and trustworthy foundation for improved decision making
  - must have right data to support decision making
- the business community must accept the DW/BI system to deem it successful. 
  - if it is the "simple and fast" source for actionable information
  
### Publishing Metaphor for DW/BI Managers
- as the editor of a high-quality magazine - content, style, and delivery.
- understand the readers => understand the business user
- ensure the magazine appeals to the readers => deliver high-quality, relevant, and accessible information and analytics to the business users
- sustain the publication => sustain the DW/BI environment

### Dimensional Modeling Introduction
- for presenting analytic data - addresses following requirements
  - deliver data that's understandable to the business users.
  - deliver fast query performance
- simple dimensional structure to match the fundamental human need for simplicity
- key difference between 3NF and dimensional models is the degree of normalization.
  - the user of normalized modeling in the DW/BI presentation area defeats the intuitive and high-performance retrieval of data.
  - DM contains the same information as a normalized model, bug package the data in a format that delivers users understandability, query perforance, and resilience to change
  

