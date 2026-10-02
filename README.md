# Software Installation Request ServiceNow

A ServiceNow-based solution that automates licensed software installation requests through the Service Catalog, approval workflows, fulfillment tasks, and request tracking.

## Project Overview

This project provides a structured process for employees to request licensed software through the ServiceNow Service Catalog. Employees submit the required software details, which are routed through an approval workflow. Once approved, a fulfillment task is created and assigned to the Software Support Team.

## Key Features

- Service Catalog item for software installation requests
- Fields for software name, version, license justification, and urgency
- Automated approval workflow
- Automatic creation of fulfillment tasks
- Request tracking through REQ, RITM, and SCTASK records
- Email notifications for submitted requests
- Business Rules and workflow automation
- Update Set support for capturing and deploying configurations

## Workflow

1. Employee submits a request through the Service Catalog.
2. ServiceNow creates the REQ and RITM records.
3. The request is routed for approval.
4. The employee receives an email notification.
5. Following approval, a catalog task (SCTASK) is created.
6. The Software Support Team fulfills the request.
7. The request is completed and tracked in ServiceNow.

## Technologies Used

- ServiceNow
- Service Catalog
- Flow Designer / Workflow
- Business Rules
- Update Sets
- IT Service Management (ITSM)

## Project Documentation

The repository is organized into the following project phases:

1. Ideation Phase
2. Requirement Analysis
3. Project Design Phase
4. Project Planning Phase
5. Project Development Phase
6. Project Documentation
7. Project Demonstration

## Project Demonstration

[Open the project demonstration link](Project%20Demonstration%20Link.txt).

## Project Outcome

The solution standardizes licensed software installation requests, improves request visibility, reduces manual coordination, and provides a structured approval and fulfillment process.
