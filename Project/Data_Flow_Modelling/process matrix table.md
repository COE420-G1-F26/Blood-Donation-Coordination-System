| **Process No. and Name**      | **Input Data**                                                           | **Output Data**                     | **Rules**                                        |
| ----------------------------- | ------------------------------------------------------------------------ | ----------------------------------- | ------------------------------------------------ |
| P1 – Handle Hospital Requests | Blood Requests, Alerts, Stock Level                                      | Stock Level, Shortage Alerts        | Check blood stock before accepting request       |
| P2 –  Manage Blood Inventory  | Blood Unit Details, Stock Data                                           | Blood Inventory, Stock Data         | only update when blood stock changes             |
| P3 – Manage Donors            | Donor data and history, donation                                         | Donor data and donation history     | update donor history after  donation             |
| P4 – Manage Blood Drives      | Shortage Alerts, Notify Drives, Donor List, Manage Drivers, Data Drivers | Registered Donors, Data Drivers     | only authorize scheduled in advance blood drives |
| P5 –  Manage Donations        | donation data (data amount type id)                                      | donation data (data amount type id) | update donor history after donation              |
