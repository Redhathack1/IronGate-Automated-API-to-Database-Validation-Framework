# IronGate-Automated-API-to-Database-Validation-Framework
Developed a synchronization testing tool using Java, TestNG, and Maven. Built to ensure that REST API responses (Producer) align with SQL database records (Consumer), eliminating data integrity risks in transaction processing.
Layer,Technology,Purpose
Test Engine,TestNG,"Handles test sequencing, priorities, and reporting."
API Layer,Rest-Assured,Simulates the fintech client making a payment request.
DB Layer,JDBC / H2,"Performs the ""Ground Truth"" check on the persistent data."
Build Tool,Maven,Manages dependencies and the project lifecycle.
