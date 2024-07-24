# FINANCIAL HEALTH MONITOR 
## Objective
This project aims to enhance customer relationship management (CRM) by leveraging Microsoft SQL Server. By creating integrated tables, analyzing customer satisfaction, and detecting fraudulent transactions, the project seeks to improve operational efficiency and customer satisfaction.

## Prerequisites
* Microsoft SQL Server installed on your system.
* CSV files containing customer data.
## Steps
* Create a new database in Microsoft SQL Server.
* Run the provided SQL scripts to create tables.
* Use the BULK INSERT command to populate tables from CSV files.
* Execute the provided SQL scripts to implement stored procedures and triggers.
## Usage
The database provides a comprehensive 360-degree view of customers by linking tables through primary keys and joins. Surveys are conducted and analyzed within the system to assess stock availability and customer satisfaction. Stored procedures manage transactions between accounts and evaluate loan eligibility. Triggers automatically update audit tables and prevent below-zero balances. Queries identify potentially fraudulent transactions by detecting unusual patterns.

## Configuration
Ensure your database connection settings are correctly configured in your SQL Server instance. Import the provided dataset using BULK INSERT and adjust any paths in the scripts to match your environment.

## Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request with your changes.

## Key Achievements
* Created tables for a 360-degree customer view and populated them via bulk insert from CSV files.
* Linked tables using primary keys and joins for seamless data integration.
* Created and analyzed surveys to measure stock availability and customer satisfaction.
* Implemented stored procedures for transactions and loan eligibility evaluation.
* Utilized triggers to update audit tables and prevent negative balances.
* Identified potentially fraudulent transactions through query analysis.

## Authors and Acknowledgments
Author: Praneeth
Acknowledgments: Thanks to all contributors and those who provided insights and feedback.

## Project Status
The project is currently in its final stages, with all major functionalities implemented and tested. Future improvements may include additional features and performance optimizations.

## Skills Used
* SQL Server
* Data Integration
* Stored Procedures
* Customer Satisfaction Analysis
* Fraud Detection
* Triggers
* Additional Resources
* Microsoft SQL Server Documentation
* SQL Server BULK INSERT
* Stored Procedures

## Conclusion
This project effectively demonstrates the potential of Microsoft SQL Server in optimizing customer relationship management. By integrating data from multiple sources, conducting thorough analyses, and implementing robust transaction management and fraud detection mechanisms, we have significantly enhanced operational efficiency and customer satisfaction. The use of stored procedures, triggers, and detailed queries ensures a seamless and secure database environment, highlighting the power and versatility of SQL Server in managing complex CRM systems
