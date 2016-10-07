**Use Case Diagrams (3)**

##Title: Determine License and Vulnerability Infomation##
**Primary Actor:** Corporate Manager <br>
**Goal in Context:** The Corporate Manager is able to determine license and vulnerability information from provided project information.

**Stakeholders:**
  - Coroporate Manager: To recieve clear and relevant OSS license and vulnerability information
  - Coroprate Developer: To provide the revelevant file/package level information

**Preconditions:**
  - Relevant file/package information is in the NIST Vulnerability database 
  - Scanner provides proper OSS license information
  - License and Vulnerability database is current and up to date
  
**Main Success Scenario:** Corporate Manager receives accurate and valid license and vulnerability information for the requested project packages

**Failed End Conditions:**  Corporate manager receives inaccurate or invalid license and vulnerability information for the requested project packages

**Trigger:** Corporate Manager identifies project informatmion to which license and vulnerability information is provided.



<br> <br>
##Title: Retrieve and upate polcy for software project##

**Primary Actor:** Corporate Manager

**Goal in Context:** The corporate manager is able to retrieve and update policy documents for a software project.

**Stakeholders:**
  - Coroprate Manager: To provide updated software policy information.

**Preconditions:** Relevant file/package information is in Software Project License and Vulnerability Policy
 Database and is up and running.
  
**Main Success Scenario:** Corporate Manager recieves software project policy information and updates the policy for the software project.

**Failed End Conditions:** <br>
Corporate Manager receives inaccurate or corrupt policy information from the Software Package License and Vulnerability Policy Database.
<br>
Software Package License and Vulnerability Policy is not up and running.

**Trigger:** Corporate manager sends request to Software Project License and Vulnerability Polic Database


<br> <br>
##Title: Determine Policies for Corresponding Software Packages## 

**Primary Actor:** Corporate Manager

**Goal in Context:** The Corporate Manager is able to determine Open Soure Software Package Policies from provided project information. With this, the Coporate Manager can recieve and update current policy documents.

**Stakeholders:**
  - Coroporate Manager: To retrieve and update software package policy information.
  - Coroprate Developer: To request and retrieve associated software policies

**Preconditions:**
  - Relevant file/package information is in the Software Package License and Vulnerability Policy database 
  - Software Package Info Database and NIST Vulnerability Database is up and running
  - FOSSology is up and runnning
  
**Main Success Scenario:** Corporate Manager recieves associated policy for corresponding software based on corresponding request.

**Failed End Conditions:** Corporate Manager receives inaccurate or corrupt software package policy.

**Trigger:** Corporate Manager request and retrieves accurate policy information.

