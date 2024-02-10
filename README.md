The project focused on Cisco in Business Intelligence (BI). It began with exploring the ERP database and establishing table relationships, analyze the data, the connection between the columns and the tables in SQL. followed by creating ERD diagrams, Source2Target mappings, and Gantt charts. 

Next, an ETL process was executed in the SSIS in order to transfer data from mirror tables, combine them into staging tables and build them into fact table and dimensions.  In the process, some data quality assurance tests were made, Additionally, a support table was created to track the upcoming rows and to verify the successful flow of data. This table serves as a tool for monitoring the process's integrity, allowing developers to identify any potential failures and make necessary corrections to ensure smooth operation.

After that, the project was deployed into SSMS, where SQL Agent was employed to use the packages from SSIS (SQL Server Integration Services) and load them in a specific order. Initially, the agents were configured to operate in the Development environment for testing purposes and to verify the PQA tests. Once the tests were successfully completed and confirmed, the agents were transitioned to operate in the production environment. Lastly, the ETL Process was scheduled to occur every Sunday at 02:00 AM.

Later on, Power BI was used to create visualizations aimed at providing valuable insights for business users. 
The Power bi file includes 3 pages:
1. Management dashboard which shows general informative details about the company from 2 aspects - customers and agents.
2. Employees Report which shows details about employees sales and measures that help estimate % revenue change and more.
3. Customers Report which show details in the customers aspect, purchasing habits, country purchase activities and more information.

 Finally, the Power BI application was uploaded for easy access.
