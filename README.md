# CS-305-Software-Security
This course teaches how to develop secure code that complies with security testing protcols through analysis of advanced security concepts. 

# Scenario
You work as a developer for a software engineering company called Global Rain. Global Rain specializes in custom software design and development. The software is for entrepreneurs, businesses, and government agencies around the world. Part of the company’s mission is “Security is everyone’s responsibility.” Global Rain has promoted you to its new agile scrum team.

At Global Rain, you work with a client, Artemis Financial. Artemis Financial is a consulting company that develops individualized financial plans for its customers. The financial plans include savings, retirement, investments, and insurance.

Artemis Financial wants to modernize its operations. As a crucial part of the success of its custom software, the company also wants to use the latest and most effective software security. Artemis Financial has a RESTful web application programming interface (API). The company is seeking Global Rain’s expertise about how to protect the organization from external threats.

As part of the team, you must examine Artemis Financial’s web-based software application to identify any security vulnerabilities. You’ll document what you learn in a vulnerability assessment report used to mitigate the security vulnerabilities you find.

# Project One

## Requirements
You must conduct a vulnerability assessment. In the assessment, you will examine Artemis Financial’s web-based software application. Use what you have learned so far, the resources in the Supporting Materials section, and the resources in the Resources section of this module to help you. Review and analyze the security vulnerabilities specific to Artemis Financial’s web-based software application. Use the Project One Template linked in the What to Submit section to document the following items for your vulnerability assessment report:

### Interpreting Client Needs: 
Review the scenario to determine your client’s needs and potential threats and attacks associated with its application and software security requirements. Document your findings in your vulnerability assessment report. Consider the scenario information and the following questions regarding how companies protect against external threats:

What is the value of secure communications to the company?

Does the company make any international transactions?

Are there governmental restrictions about secure communications to consider?

What external threats might be present now and in the immediate future?

What are the modernization requirements that you must consider? For example:
The role of open-source libraries
Evolving web application technologies

### Areas of Security: 
Use what you have learned in step 1 and refer to the vulnerability assessment process flow diagram provided in the Supporting Materials section. Think about the functionality of the software application to identify which areas of security apply to Artemis Financial’s web application. Document your findings in your vulnerability assessment report and justify why each area is relevant to the software application.

Note: Not all seven areas of security in the vulnerability assessment process flow diagram apply to the company’s software application.

### Manual Review: 
Refer to the seven security areas outlined in the vulnerability assessment process flow diagram. Use what you’ve learned in steps 1 and 2 to guide your manual review. Identify all vulnerabilities in the Project One Code Base linked in the Supporting Materials section by manually inspecting the code. Document at least 7 to 10 findings in your vulnerability assessment report. Include a description that identifies where the vulnerabilities are found. Provide the specific class file, if applicable.

### Static Testing:
Integrate the dependency-check plug-in into Maven by following the instructions in the Integrating the Maven Dependency-Check Plug-in tutorial provided in the Supporting Materials section. Run a dependency check on Artemis Financial’s software application to identify all security vulnerabilities in the code. Specifically, identify all vulnerabilities in the code base by analyzing results from running the code through a static test. Include the following items from the dependency-check report in your vulnerability assessment report:

The names or vulnerability codes of the known vulnerabilities

A brief description and recommended solutions that are found in the dependency-check report

Any attribution that documents how this vulnerability has been identified or how it was documented in the past

# Project Two
## Requirements
You must examine Artemis Financial’s software to address any security vulnerabilities. This examination will require you to refactor the Project Two Code Base linked in the Supporting Materials section to add functionality to meet software security requirements for Artemis Financial’s application. Specifically, you must follow the steps outlined below to facilitate your findings and address and remedy all areas. Use the Project Two Template linked in the What to Submit section to document your work for your practices for secure software report. You will also submit zipped files that contain the refactored code. Review this module’s Resources section to help you with this assignment. 

### Algorithm Cipher: 
Recommend an appropriate encryption algorithm cipher to deploy, given the security vulnerabilities, and justify your reasoning. Review the scenario and the supporting materials to support your recommendation. In your practices for secure software report, be certain to address the following actions:

Provide a brief, high-level overview of the encryption algorithm cipher.

Discuss the hash functions and bit levels of the cipher.

Explain the use of random numbers, symmetric versus non-symmetric keys, and so on.

Describe the history and current state of encryption algorithms.

### Certificate Generation: 
Generate appropriate self-signed certificates using the Java Keytool in Eclipse.
Complete the following steps to demonstrate that the certificate was correctly generated:

Export your certificates as a CER file.

Submit a screenshot of the CER file in your practices for secure software report.

### Deploy Cipher: Deploy and implement the cryptographic hash algorithm by refactoring code. Demonstrate functionality with a checksum verification.

Submit a screenshot of the checksum verification in your practices for secure software report. The screenshot must show your name and a unique data string that has been created.

### Secure Communications: 
Verify secure communication. In the application properties file, refactor the code to convert HTTP to the HTTPS protocol. Compile and run the refactored code. Once the server is running, type “https://localhost:8443/hash” in a new browser to demonstrate that the secure communication works.

Create a screenshot of the web browser that shows a secure webpage and include it in your practices for secure software report.

### Secondary Testing: 
Run a secondary static testing of the refactored code using the dependency-check tool to make certain the code complies with software security enhancements. You need to focus only on the code you have added as part of the refactoring. Complete the dependency check and review the output to make certain you did not introduce additional security vulnerabilities. Refer to the resources in the module’s Resources section for help on this action. In your practices for secure software report, include the following items:

A screenshot of the refactored code executed without errors

A screenshot of the report of the output from the dependency-check static tester

### Functional Testing:
Identify the software application's syntactical, logical, and security vulnerabilities by manually reviewing the code.
Complete this functional testing and include a screenshot of the refactored code, executed without errors, in your practices for secure software report.
