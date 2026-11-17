# Requirements Engineering: Functional and Non-Functional Requirements

## Project
Corporate Mental Wellness & Counseling Platform

## Problem Statement
Problem Statement #14 — Healthcare & Telemedicine

## Student Details
- Name: Manasi Manoj Jadhav
- SRN: PES1UG24CS259

## 1. Purpose
This document specifies the functional and non-functional requirements of the Corporate Mental Wellness & Counseling Platform. The system is designed to help corporate employees assess stress, access confidential counselling, book sessions with licensed therapists, and monitor personal wellness while protecting sensitive information.

## 2. Functional Requirements

### FR-001: Anonymized Employee Pseudo-ID
**Priority:** High
The system shall generate a unique pseudonymous identifier for each employee so that counselling and wellness activities can be handled without unnecessarily exposing the employee's direct identity.

### FR-002: Confidential Stress Assessment
**Priority:** High
The system shall allow employees to complete a self-administered stress assessment and receive a confidential severity score based on their responses.

### FR-003: Therapist Browsing and Session Scheduling
**Priority:** High
The system shall allow employees to browse available therapists and schedule confidential counselling sessions using real-time video or chat, subject to therapist availability.

### FR-004: Anonymized Clinical Progress Notes
**Priority:** Medium
The system shall allow licensed therapists to record clinical progress notes using appropriate anonymization and access controls to protect employee confidentiality.

### FR-005: Personal Wellness Indicators
**Priority:** Medium
The system shall allow employees to opt in to tracking personal wellness indicators and reviewing their progress over time.

## 3. Non-Functional Requirements

### NFR-001: Scheduling Reliability and Time-Zone Accuracy
**Priority:** High
The scheduling component shall convert and display appointment times accurately across relevant time zones and help prevent incorrect appointment times.

### NFR-002: Security, Encryption and Compliance
**Priority:** High
The system shall protect sensitive information using AES-256 encryption for stored data and TLS 1.3 for data in transit, where supported by the deployment environment. The design shall address applicable privacy and security obligations, including relevant HIPAA and GDPR requirements where applicable.

## 4. Requirement Priorities
- High: Essential functionality or protection that should be addressed first.
- Medium: Important functionality that supports the platform but can follow higher-priority requirements.

## 5. Confidentiality Considerations
The platform should apply role-based access controls, pseudonymous employee identification, secure communication, and restricted access to assessment results and clinical notes. Employee participation in personal wellness tracking should be opt-in.

## 6. Scope Note
These requirements describe the intended system. They do not claim that encryption, regulatory compliance, or any other security control has already been implemented or independently verified.
