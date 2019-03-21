---
group: cloud-guide
title: Testing Store
functional_areas:
  - Cloud
  - Testing
  - Services
---

<!-- Check if adding to all versions. Needs to be added to the navigation TOC in most appropriate place. -->

It is a best practice to test your store thoroughly prior launching the website. 

<!--Out of the box you've been provisioned Cloud environment per estimated parameters of your store with vanilla magneto.
Any customizations on top can improve or not performance of the final store in conjunction with provided environment;
-->

Perform the following tests before launch:

-   **Load test**—Conduct a load test to understand the behavior of the system under an expected load.

    An expected load such as a concurrent number of users on the application performing a specific number of transactions within the set duration. 

    This test reveals the response times of all the important business critical transactions  The database, application server, etc. are also monitored during the test,  this will assist in identifying bottlenecks in the application software and the hardware that the software is installed on.

-   **Stress test**—Use stress testing to understand the upper limits of capacity within the system.

    This kind of test is done to determine the system's robustness in terms of extreme load and helps application administrators to determine if the system will perform sufficiently if the current load goes well above the expected maximum.

-   **Penetration test**—Use an authorized simulated cyber attack to evaluate the security of the system.

    The test is performed to identify both weaknesses (also referred to as vulnerabilities), including the potential for unauthorized parties to gain access to the system's features and data.
    
    To perform a penetration test, you need to [submit a support ticket](https://support.magento.com/hc/en-us/articles/360000913794#submit-ticket).

-   **Security test**—Use the Security Scanner from the `account.Magento.com` site.

<!--
MMMMMMMMMMMMMMMMMMMMM

This topic discusses testing your store prior launching website  in order to properly manage expectation from the provided cluster size and appropriately scale in future upon to the business needs;

In this section, we discusses types of testing that need to be performed prior launching website as well as business objectives and benefits of doing each type of tests and tools;

Out of the box you've been provisioned Cloud environment per estimated parameters of your stove with vanilla magneto.
Any customizations on top can improve or not performance of the final store in conjunction with provided environment;
It is considered as a best practice  to evaluate your store based on the following type of tests:


1. Load 
	A load test is usually conducted to understand the behaviour of the system under a specific expected load. This load can be the expected concurrent number of users on the application performing a specific number of transactions within the set duration. 
	This test will give out the response times of all the important business critical transactions  The database, application server, etc. are also monitored during the test,  this will assist in identifying bottlenecks in the application software and the hardware that the software is installed on.
	
2. Stress 
	Stress testing is normally used to understand the upper limits of capacity within the system. This kind of test is done to determine the system's robustness in terms of extreme load and helps application administrators to determine if the system will perform sufficiently if the current load goes well above the expected maximum.

3. Penetration 
 	Is an authorized simulated cyber attack on a computer system, performed to evaluate the security of the system. The test is performed to identify both weaknesses (also referred to as vulnerabilities), including the potential for unauthorized parties to gain access to the system's features and data.
 Please note for the penetration testing you need to submit the appropriate Support ticket in advance .
 [Submit a support ticket](https://support.magento.com/hc/en-us/articles/360000913794#submit-ticket) article for detailed instructions.

4. Security 
	Use Security Scanner under account.Magento.com
	

	
	
For the Load and Stress testing you can use the following tools
1. Magento Performance toolkit 
-  Generate Data [Magento Performance Toolkit] (https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands-perf-data.html)
- Use Jmeter to run scenarios 
2. NewRelic 
3. Blackfire

-->