# Vault

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
[![Node Version](https://img.shields.io/badge/node-22.16.0-brightgreen)]()
[![pnpm](https://img.shields.io/badge/pnpm-10.12.3-blue)]()
[![NestJS](https://img.shields.io/badge/NestJS-latest-red)]()
[![Prisma](https://img.shields.io/badge/Prisma-latest-lightgrey)]()
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Docker-blue)]()
[![Jest](https://img.shields.io/badge/Jest-latest-purple)]()

**User Management API** built with Node.js, TypeScript and NestJS.  
PostgreSQL via Docker. Testing with Jest.

---

## Table of Contents

- [About](#about)  
- [Resumo em Português](#resumo-em-português)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  

---

## About

Vault is a modular, secure and scalable **User Management API**, designed following Hexagonal Architecture and TDD principles.

---

## Resumo em Português

Vault é uma API de Gestão de Usuários modular, segura e escalável, construída com NestJS e seguindo arquitetura hexagonal e testes TDD.

---

## Features

- CRUD de Usuários  
- Autenticação JWT  
- Validação de dados (Zod ou class-validator)  
- Testes unitários e integração com Jest  
- Documentação Swagger  

---

## Tech Stack

- **Node.js** 22.16.0  
- **TypeScript**  
- **pnpm** 10.12.3  
- **NestJS** (latest)  
- **Prisma** (latest) + PostgreSQL (Docker)  
- **Jest** (latest)  
- **ESLint** + **Prettier**  

---

## Getting Started

### Prerequisites

- Git  
- Node.js 22.16.0 (use `nvm use`)  
- pnpm ≥10.12.3  
- Docker & Docker Compose  

### Installation

```bash
git clone https://github.com/Lucca-gv/vault.git
cd vault
nvm use
pnpm install
cp .env.example .env
docker-compose up -d
pnpm run start:dev