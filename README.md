# CityCare Staff — Android Application

**Official APK Distribution Repository**

CityCare Staff is a dedicated Android application developed as part of the **CityCare Civic Issue Management Platform**. It enables authorized municipal personnel to manage civic complaints, coordinate field operations, and monitor issue resolution through a centralized mobile interface.

This repository serves as the official distribution and release management location for the Android APK builds of the CityCare Staff application.

## Overview

The CityCare Staff application is designed to streamline municipal operations by providing Unit Officers and Field Officers with mobile access to essential complaint management workflows.

The application integrates with the CityCare platform to facilitate issue verification, task assignment, field activity tracking, and resolution management.

### Application Objectives

- Improve coordination between municipal staff and field personnel.
- Simplify the management of assigned civic complaints.
- Enable efficient tracking of field operations and issue resolution.
- Support transparent and accountable complaint handling.
- Provide a mobile-first interface for essential administrative workflows.

## Features

### Staff Authentication and Access Control

- Secure authentication for authorized municipal personnel.
- Role-based access for Unit Officers and Field Officers.
- Dedicated workflows based on assigned staff responsibilities.

### Unit Officer Functionality

- Review and verify submitted civic complaints.
- Assign and reassign issues to available Field Officers.
- Monitor the progress of assigned complaints.
- Review submitted resolution reports.
- Approve completed work or request additional action.

### Field Officer Functionality

- Access assigned complaints and task details.
- View issue descriptions, categories, severity, and locations.
- Update work progress and task status.
- Submit resolution notes and completion reports.
- Upload before-and-after photographs as evidence of completed work.

### Issue Tracking and Management

- Track complaints throughout their resolution lifecycle.
- Access relevant complaint information and status updates.
- View geographically referenced issue locations.
- Maintain synchronized information with the CityCare platform.

## Download

The latest available Android APK can be downloaded from the repository's GitHub Releases section.

**[Download Latest Release](../../releases/latest)**

### Available Distribution

| Property | Details |
|---|---|
| Application | CityCare Staff |
| Platform | Android |
| Package Format | APK |
| Initial Version | v1.0.0 |
| Framework | React Native |
| Development Platform | Expo |
| Build System | Expo Application Services |
| Distribution Method | GitHub Releases |

The application is distributed as a directly installable Android APK and does not require downloading or compiling the source code.

## Installation Guide

### Requirements

Before installing the application, ensure that:

- An Android smartphone or compatible device is available.
- The device has sufficient storage space.
- An internet connection is available for backend communication.
- Valid CityCare staff credentials have been provided.

### Installation Steps

1. Navigate to the **Releases** section of this repository.
2. Open the latest available release.
3. Download the attached `citycare.apk` file.
4. Locate the downloaded APK on your Android device.
5. Open the file to begin installation.
6. If prompted, allow installation from the selected source in Android settings.
7. Complete the installation process.
8. Launch the CityCare Staff application.
9. Sign in using authorized staff credentials.

**Important:** APK files should only be downloaded from the official repository. Android may display an installation warning because the application is distributed outside the Google Play Store.

## Application Roles

The mobile application supports two primary municipal staff roles.

### Unit Officer

Unit Officers oversee the verification, assignment, and resolution of civic complaints within their assigned administrative responsibilities.

Their workflow includes:

1. Reviewing reported civic issues.
2. Verifying complaint information.
3. Assigning issues to Field Officers.
4. Monitoring ongoing resolution activities.
5. Reviewing completion reports.
6. Approving resolutions or requesting rework.

### Field Officer

Field Officers are responsible for executing assigned tasks and documenting field operations.

Their workflow includes:

1. Viewing assigned complaints.
2. Reviewing issue details and locations.
3. Beginning assigned fieldwork.
4. Updating task progress.
5. Uploading photographic evidence.
6. Submitting completed work for verification.

## Technology Stack

| Component | Technology |
|---|---|
| Mobile Framework | React Native |
| Development Platform | Expo |
| Target Platform | Android |
| Build Service | Expo Application Services (EAS) |
| Distribution Format | Android Package (APK) |
| Release Hosting | GitHub Releases |
| Backend Integration | CityCare Platform |

## Release Management

This repository maintains downloadable builds of the CityCare Staff application through GitHub Releases.

### Versioning

Application releases follow a versioning convention based on:

`MAJOR.MINOR.PATCH`

For example:

- `v1.0.0` — Initial Android release.
- `v1.0.1` — Maintenance update containing bug fixes.
- `v1.1.0` — Feature update with backward-compatible improvements.
- `v2.0.0` — Major release introducing significant changes.

### Release Contents

Each published release should include:

- Version number and release title.
- Android APK attachment.
- Summary of changes and improvements.
- Installation or upgrade instructions, where necessary.
- Known issues or compatibility notes, when applicable.

### Updating the Application

To install an updated version:

1. Visit the Releases section.
2. Download the latest APK.
3. Open the APK on the Android device.
4. Follow the installation prompts to update the existing application.

An in-place update requires a compatible package identifier and signing certificate. Otherwise, Android may require uninstalling the existing application.

## Repository Structure

```text
citycare-staff-apk/
├── README.md
├── LICENSE                 # If applicable
└── .gitignore              # Optional
```

APK binaries are hosted under **GitHub Releases** rather than committed directly to the repository.

This approach keeps the repository lightweight while providing centralized access to published application versions.

## Security and Access

CityCare Staff is intended for authorized municipal personnel.

- Application access is restricted through staff authentication.
- Users should avoid sharing their login credentials.
- APK files should be obtained only from trusted release sources.
- Staff members should keep the application updated.
- Operational data should be accessed only within assigned responsibilities.

This repository is intended for binary distribution and does not expose the application's private credentials, backend configuration, or production secrets.

## About CityCare

CityCare is a civic issue management platform designed to improve communication, transparency, and operational efficiency between citizens and municipal authorities.

The platform supports civic complaint reporting, issue verification, task assignment, field operations, resolution tracking, and administrative oversight.

The CityCare Staff Android application extends these capabilities to municipal personnel operating in the field.

### Related Links

- **CityCare Official Website:** https://citycare.dev/
- **CityCare Platform Demo:** https://citycare.dev/demo
- **Android Releases:** [View All Releases](../../releases)

## Disclaimer

This repository is maintained for the distribution of CityCare Staff Android application builds.

The APK is provided for authorized installation and operational use. Availability of individual features depends on the installed application version, staff permissions, and connectivity to the CityCare backend services.

---

**CityCare Staff**

*Supporting efficient municipal operations through accessible, coordinated, and accountable civic issue management.*
