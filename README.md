# Project Requests App

A Microsoft Power Platform solution for managing client project requests, built as part of the Low Code Development course.

## Business Problem

Project requests from (potential) clients arrive through various channels such as email, phone, and personal contact, making it difficult for the sales team to maintain clear overview and follow up on requests in a timely manner.

## Objective

- Collect project requests from clients in a structure way
- Give clients insight into the status of their submitted requests
- Support the sales team in managing and progressing requests through different project phases

## Solution Components

| Component | Purpose |
|---|---|
| **Dataverse** | Central data storage for all project requests |
| **Canvas App** | Client-facing app to submit and track requests |
| **Model-Driven App** | Sales-facing app to manage and update requests |
| **Power Automate** | Automated notifications for clients and the sales team |


## Users

| Role | Description |
|---|---|
| **Client** | Submits project requests and tracks their status |
| **Sales Team** | Manages requests and updates project status |

## Repository Contents

This repository holds the unpacked source of the Dataverse solution, exported from Power Platform and unpacked with the Power Platform CLI into readable XML/JSON, so the project survives independently of an active Power Platform license. 

| Folder | Description |
|---|---|
| `CanvasApps/` | The client-facing Canvas App (including the `.msapp` file) |
| `Entities/` | Dataverse tables (`fy_ProjectRequest`), forms, and views |
| `Workflows/` | Power Automate flows and business rules |
| `AppModules/` | App module and site map definitions |
| `Other/` | Solution metadata, relationships, and customizations |

## Built With

- **Power Apps** (Canvas App)
- **Power Automate** (cloud flows: client confirmation email, sales team notification)
- **Dataverse** (`fy_ProjectRequest` table with business rules)
- **Publisher**: FarahsPublisher

