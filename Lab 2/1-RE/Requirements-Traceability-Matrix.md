# Requirements Traceability Matrix (RTM)
## Project
Corporate Mental Wellness & Counseling Platform
## Problem Statement
Problem Statement #14 — Healthcare & Telemedicine
## Student Details
- Name: Manasi Manoj Jadhav
- SRN: PES1UG24CS259
## Purpose
The Requirements Traceability Matrix maps each requirement to the relevant use case(s), helping verify that the planned system functions address the documented requirements.

| Requirement ID | Requirement | Priority | Related Use Case(s) | Verification Approach |
|---|---|---|---|---|
| FR-001 | Generate anonymized employee pseudo-ID | High | UC-03 Verify Employee Anonymity | Verify that a pseudonymous identifier is generated and direct identity is not unnecessarily exposed. |
| FR-002 | Complete confidential stress assessment | High | UC-01 Complete Stress Assessment | Test assessment submission and severity-score calculation and access restrictions. |
| FR-003 | Browse therapists and schedule confidential sessions | High | UC-02 Book Counseling Session; UC-05 Conduct Tele-Counselling Session | Test therapist browsing, availability, booking, and session access. |
| FR-004 | Record anonymized clinical progress notes | Medium | UC-06 Record Anonymized Progress Notes | Verify that authorized therapists can record notes and unauthorized users cannot access them. |
| FR-005 | Track personal wellness indicators | Medium | UC-07 Track Personal Wellness Indicators | Verify opt-in tracking, display of indicators, and access restrictions. |
| NFR-001 | Ensure scheduling reliability and accurate time-zone conversion | High | UC-02 Book Counseling Session; UC-08 Manage Therapist Schedules and Profiles | Test appointment-time conversion across selected time zones and check for scheduling inconsistencies. |
| NFR-002 | Protect information through encryption and applicable compliance controls | High | UC-03 Verify Employee Anonymity; UC-06 Record Anonymized Progress Notes; platform-wide | Review security design and test access controls and encryption configuration. |

## Traceability Summary
- Total functional requirements: 5
- Total non-functional requirements: 2
- Total requirements mapped: 7

## Notes
The verification approaches describe planned checks. They should not be interpreted as evidence that the checks have already been performed or passed.
