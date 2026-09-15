# Real-Time Campus Parking & Spot Finder

A web-based application that helps students, lecturers, and visitors find available campus parking in real time — reducing search time, fuel waste, and late arrivals to class.

**Software Engineering — Facilities & Resource Management Project**

## Team

| Name | Student ID |
|---|---|
| Deva Zukananda | 24/546873/TK/60780 |
| Rafi Busthami | 24/532760/TK/58998 |

## Problem Statement

Every day, students, faculty, and visitors circle campus parking zones searching for a space — wasting time and fuel, increasing emissions, and causing late arrivals. This system provides a centralized platform showing real-time parking occupancy on an interactive map, so users can find and navigate to the nearest available spot.

**Business goals:** reduce average parking-search time by ≥50%, and improve utilization of underused parking zones.

## User Roles

- **End-User** (students, lecturers, visitors) — view live occupancy, search by proximity, get notified when a zone fills, report inaccurate info.
- **System Operator** (parking staff) — update occupancy status, manage user reports, generate daily zone summaries.
- **Administrator** (campus facilities) — manage zones/spots, view analytics & peak-hour heatmaps, control access permissions.

## Key Features (from Product Backlog)

| Module | Highlights |
|---|---|
| Real-Time Map & Search | Live occupancy display, proximity search, full-zone notifications, guest (no-login) quick view, nearest-alternate suggestion |
| Occupancy & Operator Management | Manual status updates, operator audit logging, auto-flagged unresolved reports, daily summaries |
| Administration & Analytics | Zone/spot CRUD, peak-hour heatmaps (morning + midday), analytics export |

Full backlog with acceptance criteria: see [`docs/Agile_Framework_Proposal.pdf`](./docs/Agile_Framework_Proposal.pdf).

## Agile Process

This project follows **Scrumban** — a hybrid of Scrum's lightweight planning cadence and Kanban's continuous, WIP-limited flow. Chosen to fit a two-person team with variable availability and an uneven, stakeholder-driven backlog.

- **Board:** [GitHub Projects — Campus Parking Spot Finder Flow Board](#) <!-- replace with live board link -->
- **Workflow:** Backlog → Ready (WIP ≤ 3) → In Progress (WIP ≤ 2) → In Review (WIP ≤ 2) → Done
- **Roles:** Deva — Backlog Manager + Developer · Rafi — Service Delivery Manager + Developer
- **Cadence:** Replenishment on demand, daily async check-ins, weekly combined flow review & retrospective

## Repository Structure

