# Vacation-Tracking-System (VTS)

## Content
   - [Vision](#project-vision)
   - [Functional Requirements](#functional-requirements)
   - [Non-Functional Requirements](#non-functional-requirements)
   - [Constraints](#constraints)
   - [Domain](#domain)
   - [Actors](#actors-of-the-system)
   - [Manage Time Use Case](#use-case)
     - [Flow Chart](#flowchart)
     - [Sequence Diagram](#sequence-diagram)
     - [Database Model](#entities)
     - [PseudoCode](#pseudocode)
    
## Project Vision
A Vacation Tracking System (VTS) will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.
The main goal of this application is to improve the internal business processes of this organization, at least with respect to the time it takes to manage vacation time requests.
## Functional Requirements
 1. Provides access to requests for the previous calendar year, and allows requests to be made up to a year and a half in the future.
 2. Uses e-mail notification to request manager approval and notify employees of request status changes.
 3. Keeps activity logs for all transactions.
 4. Enables the HR and system administration personnel to override all actions restricted by rules, with logging of those overrides.
 5. Allows managers to directly award personal leave time (with system-set limits).
 6. Provides a Web service interface for other internal systems to query any given employee’s vacation request summary.
 7. Interfaces with the HR department legacy systems to retrieve required employee information and changes.
 8. Implements a flexible rules-based system for validating and verifying leave time requests.
 9. Enables manager approval (optional).



 



## Non-Functional Requirements
- **Usability**: The system must be easy to use
- **Compatibility**: Uses existing hardware and middleware

## Constraints

## Domain 
**(Problem definition)**
For many businesses today, the independence of workers has been ever increasing. 
It is not uncommon for workers to divide their time across multiple projects and to report to multiple project managers. 
As a result, managers have fewer informal interactions with their workers and find it
increasingly difficult to be aware of and manage their workers’ vacation time.
In the past, all vacation time had to be approved by an immediate manager and then checked by a clerk in the HR department before it was authorized. Sometimes this manual process could take days. An automated system will speed up this process and will require at most one manual approval by the immediate manager (some high-level employees may not require manager approval).

## Actors of the system
- **Employee**: The main user of this system. An employee uses this system to manage his or her vacation time.
- **Manager**: An employee who has all the abilities and goals of a regular employee, but with the added responsibility of approving vacation requests for immediate subordinates. A manager may award subordinates comp time, subject to certain limits set in the system.
- **HR Clerk**: A member of the HR department who has sufficient rights to view employees’ personal data and is responsible for ensuring that employees’ information in all HR systems is up to date and correct. An HR clerk can add or remove nearly any record in the system.
- **System Admin**: A role responsible for the smooth running of the system’s technical resources (e.g., Web server, database) and for collecting and archiving all log files.

## Manage Time

## Use case
the use case Manage Time describes functionality, invoked by the Employee, that includes viewing, creating, and canceling vacation time requests.

**Use case name**: Manage Time

**Actor**: Employee

**Goal**: The employee wishes to submit a new request for vacation time.

**Preconditions**: The employee is authenticated by the portal framework and
identified as an employee of the company with privileges to manage his or her
own vacation time.

**Description**: This use case by far is the most frequently invoked and the one most
viewed by all the actors of the system. 

![Manage Time Use Case](https://github.com/MariamSalamah/Vacation-Tracking-System/blob/main/Use%20Case.drawio.svg)

## Entities **(Data Model)**

## Flowchart [Flow]

## Sequence diagram

## Pseudocode
