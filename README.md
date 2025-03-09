# Centalized-Location-API
This project is focused on building a backend system that serves location-based data in Cameroon to client applications and services.

# Project Scope & Features
 - Core Features:
📍 Location Storage & Management – Save hierarchical location data (Country → Region → City → District).
🔍 Auto-complete Search – Enable fast location lookup using search queries.
📊 Geo-Tagging Support – Store latitude & longitude for precise location mapping.
🔄 Location API Integration – Optionally integrate OpenStreetMap, Google Places, or another geolocation service.
🔐 Access Control – Implement authentication & role-based permissions (e.g., admin can create locations, users can search).
2️⃣ Tech Stack & Tools
🔹 Framework: Symfony
 🔹 Database: PostgreSQL (ideal for hierarchical & spatial data)
 🔹 ORM: Doctrine ORM
 🔹 API Auth: JWT (LexikJWTAuthenticationBundle)
 🔹 Caching: Redis for faster location lookups
 🔹 Containerization: Docker & Docker Compose
 🔹 CI/CD & Deployment: GitHub Actions + AWS/GCP
