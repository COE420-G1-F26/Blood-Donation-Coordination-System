* **Maha's Contribution:** NFR-01, NFR-02, NFR-03, NFR-04, NFR-05, NFR-06
* **Fadil's Contribution:** NFR-07, NFR-08, NFR-09, NFR-10, NFR-11
* **Shawky's Contribution:** NFR-12, NFR-13, NFR-14, NFR-15, NFR-16
* **Sidrah's Contribution:** NFR-17, NFR-18, NFR-19, NFR-20, NFR-21



**Non-Functional Requirements**

| NFR ID | Category | Non-Functional Requirement | Contributor |
|--------|----------|----------------------------|-------------|
| NFR-01 | Performance | The system shall respond to hospital requests within 4 seconds under normal operating conditions. | Maha |
| NFR-02 | Security | The system shall encrypt sensitive requests during transmission and storage | Maha |
| NFR-03 | Security | The system provide 2 step user authentication upon login | Maha |
| NFR-04 | Scalability | The system shall support up to 10,000 concurrent hospital and requests | Maha |
| NFR-05 | Maintainability | The system updates the software with a new version at least every 6 months to resolve software defects and system issues without significantly affecting existing functionality | Maha |
| NFR-06 | Usability | System shall provide a help icon with interface or tutorial page on first usage to familiar the users with the system. | Maha |
| NFR-07 | Reliability | The inventory data should be correctly visible to the blood bank, donor drive organizations, and hospitals. The three departments will always have the same inventory information; therefore, we are prioritizing consistency more than speed of read/writes to the database. | Fadil |
| NFR-08 | Availability | Systems must have good availability, such as being available 99% of the time. | Fadil |
| NFR-09 | Robustness | It should be robust; it should be able to show blood inventories and allow hospitals to receive blood even if 60-70% of the infrastructure hosting it is damaged or unavailable. | Fadil |
| NFR-10 | Usability | System should have an intuitive UI/UX layer so blood bank staff can use it with only an hour or 2 of training at most. | Fadil |
| NFR-11 | Security | The system must be resilient to denial of service (DoS) attacks and be able to distinguish between genuine requests of blood from hospitals and requests made to drain compute resources; it should have rate limiting. | Fadil |
| NFR-12 | Portability | The system shall be available on both desktop and mobile across different operating systems. | Shawky |
| NFR-13 | Reliability | The system should have reliable error handling and not crash due to an incorrect input in a submission field | Shawky |
| NFR-14 | Size | The system size should not be over 1GB in storage | Shawky |
| NFR-15 | Usability | The System shall support multiple languages on the app | Shawky |
| NFR-16 | Usability | The System should have an accessibility mode to support users with visual impairments | Shawky |
| NFR-17 | Privacy | The system shall allow drive organizers to view only aggregate donor statistics (counts, blood types) and never individual donor identities. | Sidrah |
| NFR-18 | Usability | The system should let a drive organizer set up a new drive without needing training. | Sidrah |
| NFR-19 | Availability | The system should be online during drive hours so organizers can check registrations. | Sidrah |
| NFR-20 | Capacity | The system should always show the correct number of donors registered for a drive. | Sidrah |
| NFR-21 | Responsiveness | The system should update the drive page within a few seconds after a donor registers. | Sidrah |

