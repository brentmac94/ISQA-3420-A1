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
##Title: Retrieve and upate polcy for software project## -- This Use Case needs a bit of work. Right now, your DFD supports the ability for the manager to only update. You'll see this in your Dataflows. Also, there is no support in your DFD to create new policy. 

**Primary Actor:** Corporate Manager
**Goal in Context:** The corporate manager is able to retrieve and update or create policy documents for a software project.
**Stakeholders:**
  - Coroprate Manager: To provide new or updated software policy information.

**Preconditions:** Relevant file/package information is in Software Project License and Vulnerability Policy
 Database and is up and running.
  
**Main Success Scenario:** Corporate Manager recieves software project policy information and updates the policy for the software project.

**Failed End Conditions:** <br>
Corporate Manager receives inaccurate or corrupt policy information from the Software Package License and Vulnerability Policy Database.
<br>
Software Package License and Vulnerability Policy is not up and running.

**Trigger:** Corporate manager sends request to Software Project License and Vulnerability Polic Database


<br> <br>
##Title: Determine Policies for Corresponding Software Packages## -- Don't connect this use case with the Update part. Just use this use case to retrieve policy information 

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

