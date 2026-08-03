# Reflection: Cloud Services in Daily Life and the Importance of Version Control

## Cloud Services in Daily Life

Cloud computing underpins many of the applications I rely on daily for productivity and communication. Three specific services I interact with regularly are Google Drive, Canva, and GCash.

### 1. Google Drive
* **Service Model:** *Software as a Service (SaaS)* — It provides a fully functional cloud storage and document management solution ready for end-use without requiring management of underlying infrastructure.
* **Deployment Model:** *Public Cloud* — Hosted on Google's multi-tenant infrastructure accessible to the general public over the internet.

### 2. Canva
* **Service Model:** *Software as a Service (SaaS)* — Delivers complete graphic design software through a browser, processing asset rendering and storage on cloud servers.
* **Deployment Model:** *Public Cloud* — Utilizes scalable public cloud architecture to serve millions of global users simultaneously.

### 3. GCash
* **Service Model:** *Software as a Service (SaaS)* — Provides accessible mobile financial services where payment processing and database operations occur in the background.
* **Deployment Model:** *Public Cloud* — Operates within secure, high-concurrency public cloud environments optimized for consumer mobile access.

---

## The Role of Git & GitHub in Cloud Computing

In modern IT environments, cloud infrastructure is frequently managed through configuration code rather than manual setups. Version control systems like **Git** and platform hosts like **GitHub** are critical for managing cloud resources safely and efficiently.

First, version control provides an precise history of all infrastructure modifications. If a configuration error breaks a server instance or introduces a security vulnerability, developers can quickly perform a rollback to a stable prior state, minimizing downtime. 

Second, GitHub enhances team collaboration. Feature branching enables multiple team members to work on separate components of a cloud system independently. Pull requests require peer review and automated testing before merging changes into production. This pipeline prevents configuration errors, maintains security standards, and ensures accountability across complex cloud projects.
