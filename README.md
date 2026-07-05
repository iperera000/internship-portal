# Smart Internship Placement Portal

An enterprise-grade, end-to-end web application built using **Spring Boot 3.5.x** and **Java 25** designed to streamline the university-to-corporate internship recruitment ecosystem. The portal automates student profiles, company job postings, applications, step-by-step mock interview assessments, and final placement metrics.

---

### 👥 Module Engineering Assignments

#### 🔒 Core Infrastructure & Access (Members 1 & 2)
* **Member 1 (Database Architect):** Configured schema generation strategies, continuous delivery profiles, database connectivity layers, and structural audit wrappers.
* **Member 2 (Security Engineer):** Enforced authorization filters, JWT/Session lifecycle guards, registration hashing mechanisms, and path routing permissions.

#### ⚙️ Backend Module Engineers (Members 3 - 8)
* **Member 3 (Student Profile Manager):** Manages student data domains, curriculum vitae metrics, GPA mappings, and skills matrices.
* **Member 4 (Company & Job Coordinator):** Handles company corporate validation fields and specific vacancy listing pipelines.
* **Member 5 (Application System Engineer):** Tracks student application states, timeline lifecycle milestones, and resume evaluation logs.
* **Member 6 (Interview Framework Engineer):** *[Your Module]* Owns the mock evaluation runtime, sequential question steps, and automated metrics logic.
* **Member 7 (Placement & Contract Lead):** Converts verified entries into legal internship contract bounds and definitive acceptance tracking states.
* **Member 8 (Analytics & Reports Engine):** Aggregates data arrays across the platform to yield metrics, passage rates, and strategic charts.

#### 🎨 Frontend Interface Engineers (Members 9 & 10)
* **Member 9 (Student Portal Lead):** Generates interactive view paths under `templates/student/`, including profile dashboards, search criteria tables, and the question-by-question interview screen.
* **Member 10 (Company Portal Lead):** Generates recruiter interaction control dashboards under `templates/company/`, tracking vacancy sheets, applicant scoring trackers, and question management boards.

---

## 🔒 Platform Guardrails & Validation Logic
1. **Concurrent Session Prevention:** Students are explicitly limited to a single active, open-ended evaluation attempt per job listing to ensure accurate tracking.
2. **Workflow Immutability Lock:** Once an interview or an application has reached a completed timestamp status, any subsequent attempts to push mutations or append questions reject immediately with a `400 Bad Request`.
3. **Database Relational Integrity:** Built-in SQL foreign-key constraints ensure clean cascades and reference tracking between `students`, `job_postings`, and secondary analytics data structures.

---

## 🛠️ Installation & Setup Guide

Follow these steps to set up and run the Smart Internship Placement Portal on your local machine.

### 1. Prerequisites
Before getting started, ensure you have the following software installed:
* **Java Development Kit (JDK):** Version 25 or above
* **Apache Maven:** Version 3.9 or above
* **Git:** For cloning the repository
* **An IDE (Optional):** IntelliJ IDEA (highly recommended), Eclipse, or VS Code

---

### 2. Step-by-Step Installation

#### Step 2.1: Clone the Repository
Open your terminal or command prompt and run the following command to clone the project:
```bash
git clone [https://github.com/your-organization/smart-internship-portal.git](https://github.com/your-organization/smart-internship-portal.git)
cd smart-internship-portal

---

#### Step 2.2: Verify Environment Configurations
Ensure your Java and Maven paths are configured correctly by verifying their versions:

Bash
java -version
mvn -version

---

#### Step 2.3: Build the Project
Compile the source files and download all necessary Spring Boot dependencies using Maven:

Bash
mvn clean install
Note: If the build completes successfully, you will see a BUILD SUCCESS message in your terminal.
