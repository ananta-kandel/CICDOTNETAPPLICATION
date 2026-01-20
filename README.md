
# 🧠 CICD .NET Application

Dockerized the .net web API application with database SQL server and front-end framework react.

After you run docker compose up, you can see three containers run for API, database, and frontend.

<img width="1120" alt="Screenshot 2025-02-23 at 11 08 03 am" src="https://github.com/user-attachments/assets/10a00ab4-09f4-4fa0-8b0a-04a417994e93" />

A sample .NET web application configured with **Continuous Integration and Continuous Deployment (CI/CD)** using **GitHub Actions**.  
This project demonstrates automated build, test, and deployment workflows for a .NET application — helping you maintain quality while releasing code rapidly.

---

## 🛠️ Features

- 🚀 Automatic build on every push
- ✅ Runs tests (if included)
- 📦 Publishes artifacts or deployable code
- 🔁 CI/CD pipeline managed via GitHub Actions
- 🧩 Ideal learning example for .NET + DevOps workflows

---

## 📌 Project Overview

This repository contains a .NET application that is configured to build and deploy automatically using GitHub Actions. The workflow includes:

1. Fetching the latest source code on push
2. Restoring dependencies
3. Compiling the application
4. Running tests (if present)
5. Optional deployment steps

You can extend this setup to deploy to Azure App Service, IIS, Docker containers, or cloud platforms using GitHub Actions workflows. :contentReference[oaicite:0]{index=0}

---

## 🧱 Technologies Used

- **.NET (Core/Framework)** — application framework  
- **GitHub Actions** — CI/CD automation  
- **GitHub Secrets** — secure credentials management

---

## 🚀 Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/ananta-kandel/CICDOTNETAPPLICATION.git
   cd CICDOTNETAPPLICATION




