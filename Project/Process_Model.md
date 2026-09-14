<b>Process Model Selected: Increment</b>

## Justification
The system can be broken into subsystems depending on core features (blood info) and add-on. These core features and add-ons can be viewed from the stakeholder perspective. For example, core features are blood info created from donor,while add-on info could be location donated and blood bank info then requestor , supplier and so on.These subsystems are independent from each other, which makes it easy to manage risk as early feedback can be obtained on each subsystem before moving to another. Additionally these subsystems are flexible for change as they’re unlikely to affect other subsystems pre-merge.

Inventory, donation drive, donor registration, and hospital request features can be developed separately and combined later

## Drawbacks and Mitigation Strategy
This method has overhead due to upfront planning which could increase costs such as time. Therefore, as a solution, the system would be broken into sub-parts via stakeholder to reduce time starting from end customer pov to blood bank pov to hospital pov  similar to the  journey for blood for donor to patient. For example:
User give blood => create a database for donor blood information 
Blood bank staff add donor blood information in software system => system interface to view & interact with blood informations database
Hospital request blood => request system in the system interface 
