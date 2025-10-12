# Trip Sharing App

## 1. Introduction

This project aims to create a **Trip Sharing Mobile App** that helps groups plan trips together in a single place. Instead of juggling chats, spreadsheets, and screenshots, users will be able to create or join a trip, invite friends, discuss in real time, propose activities, vote on options, and build a shared itinerary that everyone can see.

*October 9th, 2025*  
*Current Version: 1.0*  
*Project Manager (and sponsor): Kanwar Singh Sandhu, Shashank Nanda, Krish Jitesh Gohil*

## 2. Overview

The Trip Sharing App will provide a centralized, mobile-first experience for collaborative trip planning. Users will manage trips, members, activities, and decisions in one app, with secure authentication and reliable data storage.

### 2.1 Objective

Have a production-ready mobile application that allows a group to (a) sign up / log in, (b) create or join a trip, (c) chat and propose activities, (d) vote to decide, and (e) maintain a shared itinerary—with data persisted securely and available across sessions.

## 3. Milestones

The following milestones correspond directly to the team’s sprint structure on GitHub, representing the logical progression of development phases for the Trip Sharing App:

Sprint 1 — Authentication & First Trip

Set up the user authentication system, including sign-up, login, logout, and password reset. Implement JWT or Firebase Authentication for secure credential management. Once authenticated, users can create or join their first trip, establishing the foundation for personalized trip data.

Sprint 2 — Invitations & Roles

Introduce trip collaboration features. Users can invite others via email or shareable code. Define role-based permissions such as Owner (full control), Editor (can modify trip data), and Viewer (read-only). This sprint ensures structured collaboration among users.

Sprint 3 — Itinerary (List & Calendar View)

Develop the itinerary management module to let users add, update, and delete trip activities. Activities will be displayed in list format for quick edits and calendar view for visual organization. This phase enhances trip planning clarity.

Sprint 4 — Real-time Chat

Implement an in-app messaging system using technologies like Firebase Realtime Database or WebSockets. Each trip will have its own chat room for discussions, enabling members to coordinate instantly without switching platforms.

Sprint 5 — Voting System

Add a voting mechanism where members can create polls (e.g., choosing destinations or travel dates). Votes will be displayed transparently with real-time result updates, supporting democratic decision-making within groups.

Sprint 6 — Travel Integration (Skyscanner API)

Integrate third-party travel APIs, such as Skyscanner, to allow users to search for flights and accommodations directly in the app. This streamlines trip planning by connecting decision-making with real-world travel options.

Sprint 7 — Media & Notifications

Add a photo-sharing module for users to upload pictures related to their trips. Implement push notifications for updates like new messages, itinerary edits, or votes. This enhances engagement and keeps everyone informed.

Sprint 8 — CI/CD, Docker & Final Polish

Focus on deployment readiness and optimization. Containerize the app using Docker and implement CI/CD pipelines via GitHub Actions for automated testing and delivery. Perform bug fixes, UI refinements, and performance tuning before release.

### 3.1 Work Breakdown Structure

*(The detailed diagram will be added in a later workshop.)*

### 3.2 Requirements Traceability Matrix

| Req ID | Requirement | Del ID | Deliverable | Owner | Status |
|---------|--------------|--------|--------------|--------|---------|
| — | — | — | — | — | — |

*(Table placeholder – will be completed in a future workshop once requirements are locked.)*

# 4. Deliverables

The Trip Sharing App project will produce several key deliverables that ensure the functionality, usability, and maintainability of the system. Each deliverable represents a major outcome of development, testing, or integration work completed during specific sprints.

| # | Deliverable | Description |
|---|--------------|-------------|
| 1 | **Authentication Module** | Implements secure user sign-up, login, logout, and password reset functionality using modern authentication standards (e.g., JWT or Firebase Auth). Includes email verification and encrypted credential storage. |
| 2 | **Trip Management Module** | Enables users to create, join, and manage trips. Supports trip ownership roles (owner, editor, viewer), invitation management, and basic trip metadata (title, dates, description). |
| 3 | **Itinerary Module** | Provides functionality to create, edit, and organize trip activities. Displays data both in a chronological list view and calendar view to help groups visualize their plans. |
| 4 | **Collaboration Tools** | Adds real-time chat and group messaging within each trip, allowing participants to discuss plans and updates. Also includes push notifications for activity changes and important updates. |
| 5 | **Voting Feature** | Allows group members to propose and vote on trip decisions such as destination, travel dates, or activities. Displays results transparently to promote consensus-based planning. |
| 6 | **API Integration Layer** | Integrates with third-party travel APIs (e.g., Skyscanner) for flight and accommodation search, and supports media upload functionality for photos and shared trip galleries. |
| 7 | **Automation & Deployment Pipeline** | Includes a Dockerized environment for consistent builds, along with CI/CD workflows (e.g., GitHub Actions) to automate testing, deployment, and delivery to hosting platforms. |
| 8 | **Documentation Package** | Provides detailed user documentation, developer setup instructions, and API references. Ensures maintainability and scalability for future iterations of the app. |
| 9 | **Testing Suite** | Includes automated unit, integration, and UI tests to validate app stability, data integrity, and user experience across devices. |

---

### 4.1 Gantt Chart  
*(To be added in later workshops)*  

## 5. Preliminary Budget  
*(To be added in later workshops)*  

## 6. Organization and Stakeholders  
*(To be added in later workshops)*    

## 7. Risks, Assumptions, and Constraints  
*(To be added in later workshops)*    
