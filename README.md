# Security Caterization

Overview
This project documents the full lifecycle of performing a FIPS 199 Security Categorization for the OneDrive Platform System (OPS) used by the United States Agency of Data Security (UADS). The categorization determines the system’s Confidentiality, Integrity, and Availability (CIA) impact levels and establishes the overall security category required for RMF Step 1 (Categorize the System).
 
The work follows federal standards:
•	FIPS 199 – Standards for Security Categorization of Federal Information and Information Systems
•	NIST SP 800 60 Vol. I & II – Mapping Information Types to Security Categories
Project Objectives
•	Understand the OPS system architecture and data flows
•	Identify all information types processed, stored, or transmitted
•	Determine provisional impact levels using NIST SP 800 60
•	Validate categorization with the system owner
•	Adjust impact levels based on system specific risks
•	Establish the final overall security impact level
 
# 1. System Description Review
To begin the categorization, I analyzed the OPS system description to understand its purpose, data flows, and user interactions.
From the document:
“OPS is a Microsoft service that connects you to all your files… lets you store and protect your files, facilitates sharing with organizational and non organizational users… OPS is hosted on SharePoint Server in the UADS Data Center.”
Key observations:
•	OPS stores Higher Education, Training and Employment, and Information Sharing data
•	Contains user personal data (names, email addresses)
•	Accessible across devices; sharing permissions vary
•	No external system connections
•	Major application hosted internally
This analysis allowed me to identify the information types relevant to FIPS 199.
 
# 2. Identify Information Types
Using NIST SP 800 60 Volume II and the system description, I identified three applicable information types:
1.	Higher Education Information Type
2.	Training and Employment Information Type
3.	Information Sharing Information Type
These categories reflect the mission and business functions supported by OPS.
 
# 3. Determine Provisional Impact Levels
Following NIST SP 800 60 recommendations, I assigned provisional CIA impact levels for each information type.
Example from the template:
“Higher Education Information Type – Confidentiality: Low, Integrity: Low, Availability: Low.”
Provisional levels were recorded for all three categories.
 
# 4. Obtain System Owner Concurrence
I reviewed the provisional impact levels with the system owner to ensure:
•	Information types were correctly identified
•	Business impacts were accurately represented
•	Mission critical functions were understood
•	Risk tolerance aligned with UADS expectations
This collaboration ensured the categorization reflected real operational risk, not just theoretical mapping.
 
# 5. Adjust Impact Levels
Based on system owner feedback and sensitivity of stored data, I adjusted the impact levels where necessary.
Example from the assessment:
“Training and Employment Information Type – Adjusted Confidentiality: Moderate.”
Rationale:
•	OPS stores user personal data (names, email addresses)
•	Unauthorized disclosure could cause harm to individuals
•	Sharing features increase exposure risk
These adjustments were documented with justification to support audit and ATO review.
 
# 6. Determine Overall Security Impact
Using FIPS 199 rules:
The highest impact value among Confidentiality, Integrity, or Availability becomes the overall system security category.
From the completed assessment:
•	Confidentiality: Moderate
•	Integrity: Low
•	Availability: Low
Final System Security Category: MODERATE
This rating drives the selection of the NIST SP 800 53 Moderate baseline for OPS.
Deliverables Produced
This project generated the following artifacts:
•	System description analysis
•	Information type identification table
•	Provisional impact level matrix
•	System owner concurrence notes
•	Adjusted impact level rationale
•	Final FIPS 199 categorization statement
•	Completed FIPS 199 Assessment form (signed)
 
# Conclusion
This project demonstrates a complete, audit ready FIPS 199 categorization aligned with federal standards and RMF best practices. It showcases practical GRC skills including documentation analysis, impact determination, stakeholder engagement, and compliance reporting.
