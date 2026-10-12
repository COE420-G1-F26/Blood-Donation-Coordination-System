# Work Breakdown Structure (WBS) - Blood Inventory Management System (BIMS)

| ID | Task Name | Description | Predecessor(s) | Duration (Days) |
| :--- | :--- | :--- | :--- | :--- |
| **T1** | exploring the concept | Explore the concept of blood system requirement needs for a Blood Inventory Management System (BIMS) that can communicate with different stakeholders that use the system such as donors, hospitals, and blood banks. | — | 3 days |
| **T2** | Gathering from user | Survey and interviews: interview the different stakeholders to identify the essential and additional functions of the system. | T1 | 3 days |
| **T3** | Deploy Software Description | Study collected data and build a software description document. | T2 | 3 days |
| **T4** | Refine Software Description | Meet with stakeholders to show and refine the software description. | T3 | 2 days |
| **T5** | Subsystem-ing | Divide the project into subsystems via stakeholder POV, identifying each subsystem's core features ("IC feature"):<br>- Blood Bank subsystem: `BldBnk`<br>- Hospital subsystem: `Hosptl`<br>- All subsystems: `Allsub` | T4 | 2 days |
| **T6** | Deploy Specification | Create the specification document for the BIMS that includes a feasibility study of the overall system, use-cases of the BIMS for all different stakeholders combined, and the functional (FR) and non-functional requirements (NFR) for each stakeholder. | T5 | 2 days |
| **T7** | Allsub: Design DFD | design a DFD to show major processes and their details for BIMS. | T6 | 4 days |
| **T8** | Allsub: Refine DFD | Meet to refine and label merge points within the subsystems. | T7 | 2 days |
| **T9** | DnrDrv: Inventory Database | Design the blood storage database's relation scheme. | T6 | 2 days |
| **T10** | BldBnk: UI | Design using Figma (or similar professional software) the UI and the user journey of the core feature (blood inventory system and donor drive) based on the documentation using the FR document. | T8 | 3 days |
| **T11** | Hosptl: UI | Design the hospital blood request user journey UI using the FR document. | T8 | 3 days |
| **T12** | BldBnk: Refine UI | Meet their determined stakeholder and refine UI to ensure usability while staying within agreed software description. | T10 | 14 days |
| **T13** | Hosptl: Refine UI | Meet their determined stakeholder and refine UI to ensure usability while staying within agreed software description. | T11 | 14 days |
| **T14** | Build Database | Build the refined database on specified Database Management System. | T9 | 6 days |
| **T15** | Allsub: Security !! | Develop the security and access restriction of the database. | T14 | 3 days |
| **T16** |  BldBnk: Code Implementation | Build pages, using the UI and FR, that interact with the database first and move upwards, integrating needed API, database, and security controls. | T12 | 10 days |
| **T17** | Hosptl: Code Implementation | Code the pages starting from the blood request action (that interacts with database firstly), integrating needed API, database, and security controls. | T13 | 10 days |
| **T18** | DnrDrv: Code Implementation | Implement the user journey UI and backend from registering to adding the data into the blood drive, integrating needed API, database, and security controls. | T15 | 7 days |
| **T19** | Merger Point (MP) | Build the backend that allows communication between the `BldBnk`, `DnrDrv`, and `Hosptl` donor systems. | T21, T22 | 5 days |
| **T20** | MP Security | Deploy the security measures and restrictions as stated in the specification documentation. | T19 | 3 days |
| **T21** | BldBnk: Test | Create and document test cases with labels via scenarios, NFR used, expected and actual results, high error with code (if possible). | T16 | 12 days |
| **T22** | Hosptl: Test | Create and document test cases with labels via scenarios, NFR used, expected and actual results, high error with code (if possible). | T17 | 12 days |
| **T23** | DnrDrv: Test | Create and document test cases with labels via scenarios, NFR used, expected and actual results, high error with code (if possible). | T18 | 12 days |
| **T24** | MP: Test | Create and document test cases with labels via scenarios, NFR used, expected and actual results, high error with code (if possible). | T19 | 12 days |
| **T25** | BldBnk: Fix | Review test cases and fix the bugs reported. | T21 | 8 days |
| **T26** | Hosptl: Fix | Review test cases and fix the bugs reported. | T22 | 8 days |
| **T27** | DnrDrv: Fix | Review test cases and fix the bugs reported. | T23 | 8 days |
| **T28** | MP: Fix | Review test cases and fix the bugs reported. | T24 | 8 days |
| **T29** | Final Check | Measure the current overall system code using NFR to ensure software requirements and quality standard compliance. | T28 | 3 days |
