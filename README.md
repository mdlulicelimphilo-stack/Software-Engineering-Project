# Smart Gate Access Control System

**University of Eswatini - Department of Computer Science**

## Team Members
| Name | Role |
|------|------|
| Celimpilo Mdluli | Project Manager |
| Nomsa Manana | Backend Developer / QA |
| Sizolwethu Dlamini | Database Administrator / Hardware |
| Nomkhosi Myeni | System Analyst / UI/UX |

## Project Overview
A Java desktop application that automates campus gate access using barcode/QR card scanning with MySQL database integration.

## Problem Statement
UNESWA currently relies on manual gate operations with:
- No digital tracking mechanism
- Manual identity verification
- No recorded history of campus movement

## Solution
The Smart Gate System provides:
- Barcode/QR card scanning (under 2 seconds)
- Real-time entry/exit logging
- Administrator dashboard with reports
- Guest management with numbered tags
- Manual fallback mode

## Technology Stack

| Component | Technology |
|-----------|------------|
| Language | Java SE (JDK 11+) |
| GUI | Java Swing |
| Database | MySQL 8.x |
| Connectivity | JDBC PreparedStatements |
| Barcode Scanner | ZXing Library |
| Build Tool | Apache Maven |
| Version Control | Git / GitHub |

## Key Features
- **Card Scanning**: Sub-2 second response time
- **Digital Audit Trail**: 100% event capture
- **Admin Dashboard**: Real-time statistics
- **Role-Based Access Control**: ADMIN, STAFF, STUDENT
- **Reports**: CSV export under 60 seconds
- **Fallback Mode**: Works when scanner fails

## System Requirements
- Windows 10/11 or Ubuntu Server 22.04
- Java Runtime Environment (JRE) 11+
- MySQL 8.0+
- USB port for barcode scanner

## Database Schema
- **users**: User credentials and profiles
- **cards**: Card-to-user associations
- **gate_activity**: Complete audit log of all entries/exits
- **security_log**: Failed logins and security events

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/smart-gate-system.git
