# Testing
- First thing first **Analyze documentation**
- 3 big components 
  - Architect how the application is
  - Dev implements
  - Testing spots inconsistencies and how to test
  
- tip don't talk to the dev about testing. Just test the functionality, respect the business specs
- make a test plan **important**
- over 30% of anomalies are found that there are not in the test plan
- think of new ways of playing with buttons
- derulare a planurilor de test
- Regression tests **very important**
   
###### Waterfall - 3month, in 3 months application is done

###### Agile - release app in stages, defined or not, new functionality/slice

### 66% Acceptance tests  - primary functionality
- Cannot deploy without running these tests

### 81-100% We are required to do assembly testing
- need to test how applications function between them

#### Manual testing
- cmmi ???

### How to write test cases

- Requirements - analyzing specifications -- can it be tested? 
   - this is the first step. Understanding the business is **very important**
   - ask for clarifications if needed (not from devs): moa or moe
   - questions are always welcome
- Use cases 
- Design testing
  - test the system as it should work
  - **test the limits**
    - example: if html is entered in a form, it crashes.
  - check for empty value
  - check for close limits [1,20] test 0 1 20 21
    - just above the boundry and just below
- risk analysis
  - where are the most risky spots, thinking of how the application can crash
    - document formating, pdf reading and creating etc.
  - design tests for those risky spots

### How to write test cases

- choonse meaningful names and be specific
- the names should contain the action or the aim of the test case
  - ex: create a new Risk Event
- keep the test steps clear and concise
  - the tests steps should include the data and information on how to execute the test
  - the spteps in the test cases should be detailed and to the point, so new testers can easily execute the test with ease
- ensure 100% coverage of the requierements
  - cover all the verification points for feature under test
  - write test cases for all software requirements mentioned in the specification document

- be specific with how you got to that poin (push that specific button, write the speicific text, get the speicifc error) **should be easy to reproduce by someone else**

- **Be creative**
  - test a variety of conditions that the software will be expected to handle
  - The test case must be able to comprehensively test the software module with almost all possible combinations of main conditions

- Avoid assumptions
  - do not miss steps in the test cases
  - can produc inaccurate tests
  
- use brainsorming when definig the test cases
  - after reaidng the requirements, write as many scenarios you can write within 5 minutes
  - beneficial because:
    - you don't focus on writin the details of the test cases
    - you can quickly see if you have any questions regarding the business (un-clear specifications)
    
### Exercise

### Requirements Analysis
- Analyze all the documents: FEX, FCU, User Stories, Chart Graphique, mock-ups, UI guidelines, technical specifications etc-> this will help you understand th application from a functional point of view

- Look for:
	- Completneness
	- Clearness
	- Correctness
	- Consistency
	- Testability
- Ask for clarifications
- Ask yourself about:
	- Function ( what the product does)
	- Operations (how will it be used)
	- Data (what is processes0
	- Structure (what the product is)

### ALM
- ask for rights to the projects
	- test plan
	- test lab
	- requirements
	- management
	- defects
- create test plan using excel template

# Testing course 2

- afla structura aplicatiei

# agile
- pre delivery test
- post delivery test

- always test overflow, null, empty value
- cucumber - feature files TORESEARCH
- a se cere access la tot ce trebe alm/ FULL ACCES
- sa am cont admin

# Alm

- install hp ALM add-in in Excel

# Denumire foldere foarte important ALM
- Test evidence is imporant
	- print screens
	- fisier word

- gasesti un bug
	- fa pasii pana la bug
	- am facut urmatorii pasi, am completat aia
	- fa un print screen
	
# TODO
- completeaza excelul cu sprint total amount of bugs in this spring, corrected bugs this spring, si trimitel la raluca
- luati buguri in sprint

- convis clientul sa ia si bugurile in considerare in sprint
