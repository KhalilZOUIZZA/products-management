# Products‑Management

A full‑stack product management system (frontend + backend) with CI/CD and containerisation.

## Tech Stack

* Backend: Java 17 + Maven
* Frontend: TypeScript + HTML + CSS
* Containerisation: Docker & Docker Compose
* CI/CD: GitLab pipelines
* Deployment files included (in `deploy/` folder)

## Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/KhalilZOUIZZA/products-management.git
cd products-management
```

### 2. Run backend

```bash
cd backend-ms1
mvn clean install
mvn spring-boot:run
```

### 3. Run frontend

```bash
cd frontend
npm install
npm run dev
```

### 4. Optionally with Docker Compose

From the root folder:

```bash
docker-compose up --build
```

## Folder structure

```
/
├── backend-ms1/      # Java backend
├── frontend/         # Web UI
├── deploy/           # Deployment
├── pipelines/        # CI/CD definitions
└── docker-compose.yml
```

Thanks for checking out this project!
– Khalil
