**📊 Apache JMeter Performance Testing – PitShirts.in**
=========================================================
This project contains a complete performance testing suite built using Apache JMeter for the e-commerce website PitShirts.in. The objective of this project is to evaluate the website’s search functionality, collections pages, and overall performance under different loads.

🚀 Project Overview
==========================

In this JMeter test plan, the following checks were performed:

✔️ 1. Search Functionality Test
------------------------------------

a) Opened the website: https://pitshirts.in
b) Searched for multiple product keywords
c) Validated search response codes and response times

✔️ 2. Collections Page Testing
---------------------------------

a) Navigated to various Collections pages (Men, Women, Kids, Accessories, etc.)
b) Performed Data-Driven Testing (DDT) using a CSV Data Set Config
c) Passed each collection slug/keyword dynamically
d) Verified correct page loads and monitored for 404 or 500 errors

✔️ 3. Concurrent User Load
----------------------------

a) Configured Thread Group for multiple virtual users
b) Measured performance metrics:
c) Response Time
d) Throughput
e) Error Rate

Active Threads
=============================================================================================================
 File / Folder              | Description                                                               
 -------------------------- | ------------------------------------------------------------------------- 
 **PitShirts_TestPlan.jmx** | Full JMeter test plan containing Search + Collections + Data-Driven tests 
 **collection_slugs.csv**   | Data file used for Data Driven Testing (DDT)                              
 **/results/**              | Contains test result logs, .jtl files, screenshots, etc.                  
 **README.md**              | Project documentation (this file)                                         

===============================================================================================================
🛠️ Tools & Technologies
==========================

a) Apache JMeter (Performance Testing)
b) CSV Data Set Config (DDT)
c) Listeners: View Results Tree, Summary Report, Aggregate Report
d) Git & GitHub (Version control and repository management)

=================================================================================================================
🧪 Test Scenarios Covered
============================

🔍 Search Scenarios
---------------------

a) Search with product names
b) Response code verification (200 OK)
c) Response time monitoring

🗂️ Collections Scenarios
-------------------------

a) Open each collection page using data from CSV
b) Validate response codes
c) Capture failed URLs (404/500)

👥 Load Scenarios
------------------

a) Simulated multiple users accessing collections simultaneously
b) Measured system performance under load

================================================================================================
👨‍💻 Author
--------------
Veni CK
Performance Testing & QA Automation Enthusiast
LinkedIn: https://www.linkedin.com/in/veni-ck-nair-4a6852152/



