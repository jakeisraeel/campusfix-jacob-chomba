# CampusFix Software Requirements Specification

## 1. Introduction

### 1.1 System Name

**CampusFix**

### 1.2 Purpose

CampusFix is a proposed software system for reporting and managing university facilities maintenance problems.

The system is intended to provide an organized process through which students and staff can report facility problems and through which maintenance personnel can manage those reports from initial submission through resolution and closure.

### 1.3 Scope

The CampusFix system will focus on the reporting and management of university facilities maintenance requests.

The system will support the process of:

- Reporting a facility problem.
- Recording the maintenance request.
- Reviewing and prioritizing requests.
- Assigning requests for handling.
- Updating request status.
- Recording resolution.
- Closing completed requests.

Examples of problems that may be reported include broken computers, faulty projectors, laboratory lights that are not working, water leaks, and faulty classroom doors.

## 2. Users and Stakeholders

### 2.1 Students

Students will use CampusFix to report problems they encounter in university facilities.

### 2.2 Staff

University staff will use the system to report facility problems and follow the progress of their maintenance requests.

### 2.3 Maintenance Personnel

Maintenance personnel will use the system to receive maintenance requests, handle reported problems, and update their status.

### 2.4 University Management

University management or responsible personnel may use information from the system to monitor maintenance activities and unresolved problems.

## 3. Functional Requirements

Functional requirements describe what the CampusFix system should do.

### FR-01: Report a Problem

The system shall allow a student or staff member to report a university facilities problem.

### FR-02: Record a Maintenance Request

The system shall record submitted maintenance requests.

### FR-03: Store Problem Information

The system shall store relevant information about a reported problem.

### FR-04: Identify the Reported Problem

The system shall allow the reported maintenance problem to be identified and described.

### FR-05: Prioritize Requests

The system shall support the prioritization of maintenance requests according to their urgency.

### FR-06: Assign Responsibility

The system shall support assigning a maintenance request to responsible maintenance personnel.

### FR-07: View Maintenance Requests

The system shall allow authorized users to view recorded maintenance requests.

### FR-08: Update Request Status

The system shall allow the status of a maintenance request to be updated as work progresses.

### FR-09: Record Resolution

The system shall allow information about the resolution of a maintenance problem to be recorded.

### FR-10: Close a Request

The system shall allow a resolved maintenance request to be closed.

### FR-11: Track Unresolved Problems

The system shall allow unresolved maintenance requests to be identified and tracked.

### FR-12: Track Waiting Time

The system should support tracking how long a maintenance request has remained unresolved.

### FR-13: Identify Urgent Problems

The system should support identifying maintenance requests that require urgent attention.

### FR-14: Identify Recurring Problems

The system should support identifying recurring types of maintenance problems.

### FR-15: Monitor Maintenance Response

The system should support monitoring maintenance response times.

## 4. Non-Functional Requirements

Non-functional requirements describe qualities and constraints of the CampusFix system.

### NFR-01: Usability

The system should provide an interface that students, staff, and maintenance personnel can understand and use without unnecessary complexity.

### NFR-02: Performance

The system should respond to normal user actions within a reasonable period.

### NFR-03: Reliability

The system should reliably record maintenance requests and their status information.

### NFR-04: Security

The system should restrict access to functions and information according to the user's role.

### NFR-05: Maintainability

The system should be organized in a way that makes it possible to maintain and modify the software.

### NFR-06: Availability

The system should be available to authorized users when they need to report or manage maintenance requests.

### NFR-07: Data Integrity

The system should maintain accurate and consistent maintenance request information.

## 5. Basic Maintenance Request Information

A maintenance request should contain relevant information that allows the problem to be identified and managed.

Possible information includes:

- Request identification.
- Problem description.
- Location of the problem.
- Person who reported the problem.
- Date and time of the report.
- Priority.
- Assigned maintenance personnel.
- Current status.
- Resolution information.
- Date and time of resolution.

## 6. Maintenance Request Status

CampusFix should support the progression of a request through different stages.

The general process is:

**Reported → Recorded → Prioritized → Assigned → In Progress → Resolved → Closed**

The status should be updated as the maintenance request progresses.

## 7. System Process

The basic CampusFix process is:

1. A student or staff member reports a problem.
2. The system records the request.
3. The request is reviewed and prioritized.
4. Maintenance personnel receive the request.
5. The maintenance personnel handle the problem.
6. The request status is updated.
7. The problem is marked as resolved when the work is completed.
8. The request is closed.

## 8. Assumptions

The initial CampusFix requirements are based on the following assumptions:

- Students and staff will have access to the system when reporting facility problems.
- Maintenance personnel will be responsible for handling assigned maintenance requests.
- Reported problems will contain enough information for maintenance personnel to understand and investigate them.
- The system will maintain information about the progress of maintenance requests.

## 9. Constraints

The CampusFix project is a semester software engineering project and will initially be developed as a prototype.

The project must therefore be developed within the available semester time and resources.

The system requirements may also be refined as the project progresses through analysis, design, implementation, testing, and feedback.

## 10. Conclusion

This Software Requirements Specification defines the initial requirements for CampusFix.

The requirements describe the intended users, system purpose, functional capabilities, non-functional qualities, maintenance request information, and general process from reporting a problem through resolution and closure.

These requirements will provide a foundation for subsequent analysis, modelling, design, implementation, and testing of the CampusFix prototype.