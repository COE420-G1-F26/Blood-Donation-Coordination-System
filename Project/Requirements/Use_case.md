* **Maha's Contribution:** UC-01, UC-02, UC-03, UC-04, UC-05, UC-06
* **Fadil's Contribution:** UC-09, UC-10, UC-11, UC-12, UC-13
* **Shawky's Contribution:** UC-07, UC-08, UC-14, UC-15, UC-16
* **Sidrah's Contribution:** UC-17, UC-18, UC-19, UC-20, UC-21

**Use Cases**

| UC ID | Use Case Name | Primary Actor | Short Description | Contributor |
|-------|---------------|---------------|-------------------|-------------|
| UC-01 | Alert unavailability of blood type or amount | Hopital | Hospital Alerts Blood bank if blood of a type is not available | Maha |
| UC-02 | Request Blood | Hospital | Hospital Requests blood | Maha |
| UC-03 | Submit/Cancel request | Hospital | Hospital submits or cancels requests to blood bank. | Maha |
| UC-04 | Review Blood Request | Hospital | Hospital can review details of blood request | Maha |
| UC-05 | Store default options | Hospital | Hospital can store frequently requested blood types as default | Maha |
| UC-06 | Donate Money | Donor | user would be able to donate money to the hospital for the blood donation system | Shawky |
| UC-07 | Urgent donation | Donor | user will receive an alert that there is an urgent matter happening that requires a donation | Shawky |
| UC-08 | Show Inventory | Blood Bank | Show inventory of blood to staff | Fadil |
| UC-09 | Send Blood | Blood Bank | Allow blood bank staff to send blood to hospitals | Fadil |
| UC-10 | Notify Drives | Blood Bank | Notify donor drives about missing blood groups | Fadil |
| UC-11 | Pre-position stocks | Blood Bank | Allow blood banks to pre-position stocks of blood at hospitals, etc. | Fadil |
| UC-12 | Prioritize Delivery | Blood Bank | Allow banks to prioritise blood delivery based on criteria. | Fadil |
| UC-13 | View History | Donor | The system shall allow donors to view their donation history. | Shawky |
| UC-14 | Track Status | Donor | The system shall allow donors to see whether their donated blood has helped save people, to help motivate them to donate again. | Shawky |
| UC-15 | View Results | Donor | The system shall allow donors to view testing statistics and results regarding their blood work. | Shawky |
| UC-16 | Create Drive | Drive Organizers | The organizer creates and publishes a new donation drive. | Sidrah |
| UC-17 | Manage Drive | Drive Organizers | The organizer edits or closes an existing donation drive. | Sidrah |
| UC-18 | Track Drive Progress | Drive Organizers | The organizer checks how many donations the drive has received so far. | Sidrah |
| UC-19 | Review Registrations | Drive Organizer | The organizer looks through donors who signed up for the drive. | Sidrah |
| UC-20 | Announce Drive Update | Drive Organizers | The organizer sends an update (venue change, time change, etc.) to signed-up donors. | Sidrah |

**Use Case Relationship Table**
| Relationship ID | Base Use Case | Related Use Case | Relationship | Justification |
|-----------------|---------------|------------------|--------------|---------------|
| R-01 | Request Blood | Send Blood | `<<include>>` | A request for blood from the hospital will frequently result in blood bank sending blood |
| R-02 | Notify Drive | Create Drive | `<<extend>>` | Notification by blood bank to the drive organizers may lead to creation of drives. |
| R-03 | Alert if Blood is unavailable | Notify Drive | `<<extend>>` | Alert from hospital can lead to drive notification if blood is unavailable |
