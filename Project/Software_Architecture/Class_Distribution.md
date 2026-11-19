# Lab 8 – Exercise 3: Class Distribution

**Project:** Blood Donation Drive and Inventory System  
**Architecture:** Client–Server

Every class from the reported consolidated Lab 5 diagram is assigned to one primary component.

| ID | Component Name | Included Classes |
|---|---|---|
| CO1 | Blood Bank | `Inventory`, `Blood`, `Transaction`, `ForwardInventory`, `BloodBankNotification` |
| CO2 | Hospital | `Hospital`, `PhlebotomyManager`, `BloodRequest`, `DefaultRequest`, `Alert`, `DonorTestResult` |
| CO3 | Donation Drive Organizer | `DriveOrganizer`, `DonationDrive`, `DriveBloodTarget`, `DriveRegistration`, `Notification`, `DriveAnnouncement`, `OrganizerAlert` |
| CO4 | Donor | `Donor`, `Donation`, `DonationHistory`, `DonorManagement` |

## Class counts

| Component | Number of Classes |
|---|---:|
| CO1 – Blood Bank | 5 |
| CO2 – Hospital | 6 |
| CO3 – Donation Drive Organizer | 7 |
| CO4 – Donor | 4 |
| **Total** | **22** |

All 22 classes are included once, with no duplicate assignments. The classes are grouped according to the four functional sections in Lab 5.
