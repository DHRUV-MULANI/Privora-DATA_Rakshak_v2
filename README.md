# Privora - DATA Rakshak v2

<div align="center">

# Privora

### Privacy Intelligence & Mobile Security Platform

A privacy-focused Android application that helps users analyze app permissions, evaluate privacy risks, remove metadata from files, and improve overall digital security through actionable recommendations.

</div>

---

## Table of Contents

* Introduction
* Problem Statement
* Objectives
* Features
* Technology Stack
* System Architecture
* Modules
* Installation
* Project Structure
* Security Principles
* Testing
* Roadmap
* Future Enhancements
* Team
* Contributing
* License

---

# Introduction

Privora – DATA Rakshak v2 is an Android privacy and security platform designed to provide users with greater visibility and control over their digital footprint.

The application analyzes installed applications, evaluates permission risks, generates privacy scores, removes sensitive metadata from files, and delivers personalized privacy recommendations.

Privora aims to simplify cybersecurity concepts and make privacy protection accessible to everyday users.

---

# Problem Statement

Modern mobile applications frequently request sensitive permissions that many users do not fully understand.

Common challenges include:

* Excessive permission requests
* Lack of permission transparency
* Hidden metadata in shared files
* Limited visibility into privacy risks
* Difficulty identifying potentially risky applications

Privora addresses these challenges through automated privacy analysis and user-friendly security insights.

---

# Objectives

* Improve user awareness of privacy risks
* Analyze application permissions
* Generate privacy scores
* Detect high-risk applications
* Remove metadata before sharing files
* Provide privacy recommendations
* Promote secure mobile practices
* Increase transparency in mobile privacy

---

# Features

## Privacy Scoring Engine

Analyze installed applications and generate privacy ratings based on:

* Permission sensitivity
* Data access behavior
* Tracking indicators
* Privacy risk level
* Security posture

Risk Categories:

| Score  | Status        |
| ------ | ------------- |
| 80-100 | Safe          |
| 50-79  | Moderate Risk |
| 0-49   | High Risk     |

---

## Permission Analysis

Detailed analysis of:

* Camera Access
* Microphone Access
* Location Access
* Contacts Access
* SMS Access
* Storage Access
* Call Logs
* Notifications
* Calendar Data

Users receive explanations about each permission and associated privacy implications.

---

## Metadata Cleaner

Remove hidden information before sharing files.

Supported File Types:

### Images

* GPS Coordinates
* Camera Information
* Device Information
* Creation Timestamp
* Author Details

### Documents

* Author Information
* Document Properties
* Editing History
* Embedded Metadata

Benefits:

* Reduced information leakage
* Enhanced privacy
* Safer file sharing

---

## Secure Testing Environment

Controlled environment for privacy assessment.

Capabilities:

* Permission Monitoring
* Access Tracking
* Risk Observation
* Security Reporting

---

## Privacy Dashboard

Centralized privacy management panel.

Includes:

* Overall Privacy Score
* Permission Statistics
* Application Risk Levels
* Security Recommendations
* Privacy Insights

---

## Smart Recommendations

Generate privacy suggestions based on:

* Installed Applications
* Permission Usage
* Device Configuration
* Privacy Risk Assessment

---

# Technology Stack

## Frontend

```text
Kotlin
Jetpack Compose
Android SDK
Material Design
```

## Backend

```text
Python
Flask
REST APIs
```

## Database

```text
SQLite
Room Database
```

## Development Tools

```text
Android Studio
Git
GitHub
Gradle
```

---

# System Architecture

```text
+------------------------------------------------+
|                 Android Client                 |
+------------------------------------------------+
                        |
                        v
+------------------------------------------------+
|               Privacy Analysis Layer           |
+------------------------------------------------+
| Permission Analysis                            |
| Privacy Scoring                                |
| Metadata Processing                            |
| Risk Assessment                                |
+------------------------------------------------+
                        |
                        v
+------------------------------------------------+
|           Recommendation & Reporting           |
+------------------------------------------------+
                        |
                        v
+------------------------------------------------+
|                Local Data Storage              |
+------------------------------------------------+
```

---

# Core Modules

## Permission Analyzer

Responsible for:

* Scanning installed applications
* Collecting permissions
* Categorizing permission types
* Risk evaluation

---

## Privacy Score Engine

Responsible for:

* Privacy calculation
* Risk classification
* User-friendly scoring
* Security reporting

---

## Metadata Cleaner

Responsible for:

* Metadata extraction
* Metadata removal
* File sanitization
* Privacy protection

---

## Recommendation Engine

Responsible for:

* Privacy suggestions
* Security improvements
* Risk mitigation advice
* User awareness

---

# Project Structure

```text
Privora-DATA_Rakshak_v2/

├── app/
├── ui/
├── screens/
├── components/
├── permission_analyzer/
├── privacy_score_engine/
├── metadata_cleaner/
├── recommendation_engine/
├── database/
├── assets/
├── docs/
├── tests/
├── requirements.txt
└── README.md
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Privora-DATA_Rakshak_v2.git
```

## Open Project

```bash
Android Studio
```

## Build Project

```bash
Gradle Build
```

## Run Application

```bash
Android Emulator
or
Physical Android Device
```

---

# Security Principles

Privora follows:

* Privacy by Design
* Secure by Default
* Least Privilege Principle
* Local-First Processing
* User Transparency
* Data Minimization

---

# Testing

Testing Strategy:

### Unit Testing

* Privacy Scoring
* Permission Analysis
* Metadata Cleaning

### Integration Testing

* Module Communication
* Data Flow Validation

### Security Testing

* Permission Validation
* Risk Assessment Accuracy

### Performance Testing

* Scan Performance
* Resource Consumption

---

# Development Roadmap

## Phase 1

Research & Planning

* Problem Analysis
* Feature Planning
* Architecture Design

## Phase 2

Design & Setup

* UI/UX Design
* Repository Setup
* Development Environment

## Phase 3

Core Development

* Privacy Scoring Engine
* Permission Analyzer
* Metadata Cleaner
* Recommendation Engine

## Phase 4

Testing & Optimization

* Bug Fixes
* Performance Improvements
* Security Validation

## Phase 5

Deployment

* Play Store Preparation
* Documentation
* Public Release

---

# Future Enhancements

* AI-Based Privacy Analysis
* Threat Detection Engine
* Behavioral Risk Monitoring
* Multi-Language Support
* Cloud Synchronization
* Enterprise Privacy Dashboard
* Cross-Platform Expansion

---

# Team

| Member            | Role                    |
| ----------------- | ----------------------- |
| Dhruvkumar Mulani | Frontend Lead           |
| Parin Solanki     | Backend Lead            |
| Shyam Chopda      | Security & Privacy Lead |

---

# Contributing

Contributions are welcome.

```bash
Fork Repository
Create Branch
Commit Changes
Push Updates
Open Pull Request
```

---

# License

MIT License

Copyright (c) 2026

Privora – DATA Rakshak v2

---

<div align="center">

## Privacy Intelligence for Everyone

Secure • Analyze • Protect

</div>
