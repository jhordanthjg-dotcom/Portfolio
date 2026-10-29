# Portfolio

Personal portfolio with a private workspace.
Built with Next.js, Spring Boot and Keycloak.

## Stack
 
| Layer     | Technology                                   |
|-----------|----------------------------------------------|
| Frontend  | Next.js, TypeScript, Auth.js                 |
| Backend   | Java 21, Spring Boot 3 (OAuth2 Resource Server) |
| Auth      | Keycloak (OpenID Connect)                    |
| Database  | PostgreSQL, Flyway migrations                |
| Infra     | Docker Compose, GitHub Actions               |

## Architecture



## Getting started



## Key decisions
- Keycloak for identity instead of custom authentication
- Monorepo to keep frontend, backend and infrastructure changes atomic.
- 

## Project structure
portfolio/
├── frontend/    # Next.js application
├── backend/     # Spring Boot API
├── infra/       # Keycloak realm export, proxy config
├── docs/        # Architecture notes and ADRs
├── .github/     # CI workflows and templates
└── docker-compose.yml

## Roadmap
- [x] CI pipeline
- [ ] Workspace: authorization per resource

## Contact
 
**Jhordanth Fabian Villamizar Peñaranda** · [LinkedIn](linkedin.com/in/jhordanth-fabian-villamizar-peñaranda-66a769225) · [jhordanthjg@gmail.com](mailto:jhordanthjg@gmail.com).
