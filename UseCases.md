**======Use Case Diagrams (3)======**

##Title: Determine License and Vulnerability Infomation##
**Primary Actor:** Corporate Manager
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

(Not everything in the prior use case was formatted perfectly)


<br> <br>
##Title: Determine OSS Software Components##
**Primary Actor:** Corporate Developer
**Goal in Context:** The corporate developer is able to determine Open Soure Software Package Components from provided project information. 
**Stakeholders:**
  - Coroprate Developer: To provide the revelevant file/package level information

**Preconditions:**
  - Relevant file/package information is in the NIST Vulnerability database and the Software Package Info Database is up and running (watch your use of CAPS)
  - FOSSology is up and runnning
  
**Main Success Scenario:** Corporate Developer recieves required OSS components based on corresponding request.

**Failed End Conditions:** Corporate Developer receives inaccurate or corrupt software package (This is different from the main success scenario). 

**Trigger:** Corporate developer sends request for open source software license and vulnerability information


<br> <br>
(Didn't look at this one yet)
##Title: Determine Policies for Corresponding Software Packages##
**Primary Actor:** Corporate Manager
**Goal in Context:** The Corporate Manager is able to determine Open Soure Software Package Policies from provided project information. With this, the Coporate Manager can recieve and update current policy documents.
**Stakeholders:**
  - Coroporate Manager: To request, recieve and update software package policy information.
  - Coroprate Developer: To request and recieve associated software policies

**Preconditions:**
  - Relevant file/package information is in the Software Package License and Vulnerability Policy database 
  - Software Package Info Database and NIST Vulnerability Database is up and running
  - FOSSology is up and runnning
  
**Main Success Scenario:** Corporate Manager recieves associated policy for corresponding software based on corresponding request. Policy document is updated.

**Failed End Conditions:** Corporate Manager receives inaccurate or corrupt software package policy.

**Trigger:** Corporate Manager is able to update policy document for corresponding software package.

