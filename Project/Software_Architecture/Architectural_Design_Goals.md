## architectural design goals 1

| Field | Description |
|:---------|:---------|
| Goal ID  | G01 |
|Design Goal | Modular &Maintainable |
| Description | Decompose the architecture into 4 to 6 loosely coupled components (Hospital Subsystem, Blood Bank Subsystem, Donor Management, Drive Organization) so individual modules can be updated or maintained independently |
| Related | NFR-05 |
| Priority | Medium |
| Justification | maintain and update their respective subsystem codebases without breaking adjacent services


## architectural design goals 2
| Field | Description |
|:---------|:---------|
| Goal ID | G02
| Design Goal | urgent, correct & consistent 
| Description | Reliability, Consistency 
| Related | NFR-07 , NFR-13 , NFR-01 , NFR-21
| Priority | High |
| Justification | Inconsistent stock data could lead to false blood availability reporting during critical Urgent surgical blood requests (such as emergency surgery in Scenario S-05) where immediate validation and confirmation is required |



