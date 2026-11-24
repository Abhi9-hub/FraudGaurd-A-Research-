# FraudGuard - Technical Decision Log

## Decision 001: Modular Monorepo
Choice: One Git repository containing separate modules and services.

Reason: Easier project management while learning modular architecture.

## Decision 002: Docker
Choice: Docker and Docker Compose for databases and supporting infrastructure.

Reason: Reproducible infrastructure and easier service management.

## Decision 003: PostgreSQL
Choice: PostgreSQL as the application database.

Reason: Relational storage for transactions, predictions and alerts.

## Decision 004: Python
Choice: Dedicated Python environment for FraudGuard.

Reason: Isolated and reproducible machine-learning dependencies.
