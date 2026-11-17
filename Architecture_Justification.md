
# Lab 3 – Architecture Selection and Justification

**Scenario:** Corporate Mental Wellness & Counseling Platform

### Selected Architecture
We selected Layered Architecture for this platform.

### Reason 1
The system has different users, such as employees, therapists and administrators. It also has separate functions like stress assessment, appointment booking and wellness tracking. Dividing the system into layers makes it easier to understand and maintain.

### Reason 2
The Application API connects the portals to different modules. For example, an employee can complete a stress assessment or book a counselling session through the portal. The API sends the request to the correct module.

### Security Advantage
The Authentication and Privacy component checks who is using the system and what they are allowed to access. Pseudo-ID Management helps keep employee identity separate from counselling records. This protects confidential information.

### Performance Benefit
Different modules handle different functions independently. Assessment requests, appointment bookings and wellness tracking can be managed separately. This makes the system easier to maintain and improve.

### Conclusion
Layered Architecture is suitable for this system because it separates responsibilities, supports privacy controls and keeps the main functions organised.
