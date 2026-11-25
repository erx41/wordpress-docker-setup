# WordPress, MySQL & phpMyAdmin (Docker & Dockerfile)

Automated WordPress development and testing environment using a custom Dockerfile (to increase PHP upload limits to 64MB) and Docker Compose for multi-container orchestration.

## Included Services
- **WordPress** (built from a custom Dockerfile, port 80)
- **MySQL 8.0** (with persistent volume db_data)
- **phpMyAdmin** (database management interface, port 8080)

## Quick Start
1. Clone this repository to your local machine
2. Run in terminal:
   `ash
   docker compose up -d --build
   `
3. Open in your browser:
   - WordPress: http://localhost
   - phpMyAdmin: http://localhost:8080
