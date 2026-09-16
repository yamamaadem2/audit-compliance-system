# Automated Financial Audit & Compliance System

> A full-stack system that ingests financial documents, flags anomalies, enforces maker-checker approval workflows, and maintains a tamper-evident audit trail — modeled on real audit/risk/compliance software.

## 🚧 Status
In active development. See [Roadmap](#roadmap) below.

## Overview
This system automates parts of the manual audit process: uploading invoices/receipts, extracting structured data via OCR, flagging duplicate or anomalous transactions, and routing every change through a maker-checker approval flow — all logged in a hash-chained, tamper-evident audit trail.

## Why this project
Built to demonstrate practical skills relevant to audit, risk, and compliance technology: data integrity, segregation of duties, anomaly detection, and process automation — not just CRUD.

## Architecture
_(diagram coming in Phase 6 — will show frontend, backend, DB, and OCR/ML pipeline)_

## Tech Stack
- **Backend:** FastAPI (Python), SQLAlchemy, Alembic
- **Database:** PostgreSQL (Supabase)
- **Auth:** JWT, role-based access control (admin / auditor / approver)
- **OCR:** Tesseract
- **ML:** scikit-learn (Isolation Forest for anomaly detection)
- **Frontend:** React + Vite
- **Deployment:** Render/Railway (backend), Vercel (frontend), Supabase (DB)

## Features
- [ ] Document upload + OCR extraction
- [ ] Duplicate & anomaly detection
- [ ] Maker-checker approval workflow
- [ ] Hash-chained immutable audit log
- [ ] Role-based dashboards
- [ ] Exportable compliance reports

## Roadmap
- [x] Phase 0 — Project setup
- [ ] Phase 1 — Database design
- [ ] Phase 2 — Backend core (auth, CRUD, audit log)
- [ ] Phase 3 — Intelligence layer (OCR, anomaly detection)
- [ ] Phase 4 — Frontend
- [ ] Phase 5 — Deployment
- [ ] Phase 6 — Polish (docs, diagram, demo data)

## Local Setup
_(instructions will be added as each part is built)_

## Live Demo
_(link coming after Phase 5)_

## Author
Yamama Adem — [LinkedIn] · [Email]