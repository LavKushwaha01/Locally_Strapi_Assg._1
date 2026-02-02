# Strapi Local Setup – Assignment

### Loom video: https://www.loom.com/share/0228359814c34d7f83c2d7779e8d34b7

## Overview
This repository contains a **locally running Strapi project** created as part of an assignment to understand Strapi’s setup, admin panel, and content management workflow.

The goal of this assignment was to:
- Run Strapi locally
- Explore the project folder structure
- Start and use the Admin Panel
- Create a sample content type
- Push the setup to GitHub
- Document all steps
- Share a Pull Request and Loom video

---

## Note on Strapi Repository Usage
The official Strapi repository was explored to understand the framework structure.  
For running the Admin Panel and creating content types, a **Strapi project was generated using the official CLI (`create-strapi-app`)**, which is the recommended and supported approach.

This avoids monorepo workspace issues and ensures a clean, runnable local setup.

---

## Project Setup Steps

### Step 1: Create Strapi Project
```bash
npx create-strapi-app@latest lav-kumar-strapi

cd lav-kumar-strapi

npm run develop

```

This command:

Starts the Strapi server

Builds and serves the Admin Panel

Enables hot reload

---

Open the Admin Panel in the browser:

```bash
http://localhost:1337/admin

```

---

Create an Admin User by providing:
Name
Email
Password

---

Sample Data :- 

A sample Blog Post entry was created using the Content Manager to verify:

Admin panel functionality

Content creation flow

Data persistence
