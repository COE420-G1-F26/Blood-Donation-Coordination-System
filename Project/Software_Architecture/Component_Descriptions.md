# Lab 8 – Exercise 3: Component Descriptions

**Project:** Blood Donation Drive and Inventory System  
**Architectural Style:** Client–Server

The system is divided into four components based on the four functional sections in Lab 5.

## CO1 – Blood Bank

The Blood Bank component manages blood inventory and availability. It handles blood transactions, tracks blood stored at different locations through forward inventory, and sends notifications about blood shortages.

## CO2 – Hospital

The Hospital component manages hospital information and blood requests. It allows hospital staff to view, submit, modify, and cancel requests, save default request options, receive alerts, and view donor test results.

## CO3 – Donation Drive Organizer

The Donation Drive Organizer component manages donation drives. It allows organizers to create and update drives, manage registrations, track blood collection targets and progress, and send announcements and organizer alerts.

## CO4 – Donor

The Donor component manages donor registration, profiles, donations, and donation history. It supports updating donor details, recording donations, and viewing past donations.

These components organize related functionality into separate parts of the system. Their classes are listed in `Class_Distribution.md`, and the components will communicate through interfaces defined in Exercise 4.
