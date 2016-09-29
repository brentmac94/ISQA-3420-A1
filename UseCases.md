**Use Case Diagram File (There will be 3 use cases).**

##Title: Determine License and Vulnerability Infomation##
**Primary Actor:** Corporate Manager
**Goal in Context:** The Corporate Manager is able to determine license and vulnerability information from provided project information.
**Stakeholders:**
  - Coroporate Manager: To recieve clear and relevant OSS license and vulnerability information
  - Coroprate Developer: To provide the revelevant file/package level information

**Preconditions:**
  - Relevant file/package information is in the NIST Vulnerability database
  - License and Vulnerability database is current and up to date
  
**Main Success Scenario:** Corporate Manager receives Accurate and Valid license and vulnerability information for the requested project packages

**Failed End Conditions:**  Corporate manager receives inaccurate or invalid license and vulnerability information for the requested project packages

**Trigger:** Corporate Manager identifies project informatmion to which license and vulnerability information is provided.


<br> <br>
##Title: Determine OSS Software Components##
**Primary Actor:** Corporate Developer
**Goal in Context:** The Corporate Developer is able to determine Open Soure Software Package Components from provided project information. With this, the Coporate Developer can provide the database an updated Software Package.
**Stakeholders:**
  - Coroporate Manager: To recieve software package and license information.
  - Coroprate Developer: To provide the revelevant file/package level information

**Preconditions:**
  - Relevant file/package information is in the NIST Vulnerability database and the Software Package Info Database
  - Database is up and running
  - FOSSology is up and runnning
  
**Main Success Scenario:** Corporate Developer recieves required OSS components based on corresponding request.

**Failed End Conditions:** Corporate Developer receives inaccurate or corrupt software package

**Trigger:** Corporate Developer is able to enchance the existing OSS by uploading updated software package.

