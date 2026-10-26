# List of All Classes In the Project

| Class ID | Class Name | Purpose/Responsibility | Related Use Case(s) | Contributor |
| --- | --- | --- | --- | --- |
| C01 | Inventory | Models the Blood bank inventory | UC08 | Fadil |
| C02 | Transaction | Models a unit of blood that has to be sent | UC09, UC12 | Fadil |
| C03 | Notification | Models the notification that is sent to drive organizers | UC10 | Fadil |
| C04 | ForwardInventory | Models the pre-positioning of blood stocks | UC12 | Fadil |
| C05 | Hospital | Model a hospital information | UC-01:05 , UC-21 | Maha |
| C06 | Alert | Model the Alert system sending or dismiss Alert issued with the system (mostly for blood shortage) | UC-01 | Maha |
| C07 | PhlebotomyManager | Model a person (manager ) who queries by other stakeholder and manage blood request within the hospital | UC-21 | Maha |
| C08 | BloodRequest | Models the Blood requests process to view , submit , cancel , modify the request information | UC-03 , UC-04, UC-02 | Maha |
| C09 | DefaultRequest | Models the frequently blood requests options and their details | UC-05 | Maha |
| C10 | DonorTestResult | Models the Donor blood used within the system and their operation result of the blood used | UC-15 | Maha |
| C11 | DriveOrganizer | Organizer account that creates, edits, closes and monitors drives and posts updates to donors | UC-16, UC-17, UC-18, UC-19, UC-20 | Sidrah |
| C12 | DonationDrive | Core entity storing title, location, dates, goal and status. Tracks its own progress and deadline | UC-16, UC-17, UC-18 | Sidrah |
| C13 | DriveBloodTarget | Stores the target quantity for one blood type in a drive (e.g. O+: 40 units) | UC-16, UC-18 | Sidrah |
| C14 | DriveRegistration | Records a donor’s sign-up for a drive and supplies the registration counts shown to organizers | UC-18, UC-19 | Sidrah |
| C15 | Notification (abstract) | Common message text, timestamp and send behavior for notifications | UC-20 | Sidrah |
| C16 | DriveAnnouncement | Update an organizer sends to signed-up donors (time change, reminder) | UC-20 | Sidrah |
| C17 | OrganizerAlert | System alert telling the organizer a drive reached its goal or its deadline is approaching | UC-18 | Sidrah |
| C18 | Donor | Stores Donor information and details | UC-06, UC-07, UC-13, UC-14, UC-15 | Shawky |
| C19 | Donation | Records Donation time and details | UC-13, UC-14 | Shawky |
| C20 | DonationHistory | Records History of donor Donations | UC-13 | Shawky |
| C21 | DonationManagement | Handles Donor registration and profile | UC-13, UC-14, UC-15 | Shawky |