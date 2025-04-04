# Keycloak-sso

## Setup instructions

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd <repository-folder>
cp .env.example .env
```

### 2. Create Docker network (First run only)
```bash
docker network create keycloak-network
```

### 3. Start services
```bash
docker compose up -d
```

### 4. Access Keycloak in your browser
Open http://localhost:8080 in your browser. Login with username: KEYCLOAK_ADMIN & password: KEYCLOAK_ADMIN_PASSWORD from your environment variables.

### 5. Stop services
```bash
docker compose down
```
