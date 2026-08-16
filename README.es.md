<div align="center">

# Gerardo Maidana

### Backend Engineer · Java / Spring Boot · Sistemas Reactivos & Microservicios

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gerardomaidana)
[![Location](https://img.shields.io/badge/Santa%20Fe-Argentina-75AADB?style=for-the-badge)](#)

🇬🇧 [Read in English](README.md)

</div>

---

## Sobre mí

Backend engineer enfocado en **arquitectura event-driven**, **domain-driven design** y **sistemas reactivos, no bloqueantes**. Construyo software de la forma en la que me gustaría mantenerlo dentro de un año: decisiones documentadas, contratos claros, sin atajos.

Trabajo principalmente solo como referente técnico, lo que significa que soy responsable de todo, desde la arquitectura hasta el deploy — por eso desarrollé mi propia metodología (**SDD-GL**) para mantener ese tipo de trabajo disciplinado en lugar de improvisado.

- ⚙️ Construí un **modular monolith de showcase** (Spring Modulith) implementando el **patrón Saga** sobre RabbitMQ, con límites de dominio (DDD) y observabilidad incorporados desde el inicio — no es un clon de tutorial.
- 💳 Trabajando en backend de pagos/fintech: un **motor de verificación 3D Secure**, además de experiencia previa en producción integrando pasarelas de pago para una plataforma de ecommerce.
- 🔧 Actualmente construyendo una **plataforma reactiva de monitoreo de nivel de agua** para ríos argentinos — 5 microservicios, cero código bloqueante, de punta a punta.
- 🧠 Diseñé **SDD-GL**, un framework/plugin de Spec-Driven Development para developers que trabajan solos con agentes de IA.
- 🌱 Expandiéndome hacia **Go**, aprendiéndolo deliberadamente reconstruyendo un dominio conocido (StockGo) en lugar de seguir tutoriales.
- 🇦🇷 Basado en Santa Fe, Argentina — abierto a roles backend / adyacentes a backend.

---

## Stack Tecnológico

**Lenguajes & Runtime**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

**Backend**
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![WebFlux](https://img.shields.io/badge/Spring%20WebFlux-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/R2DBC%20%2F%20JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)

**Datos & Mensajería**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Infra & Herramientas**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

---

## Proyectos Destacados

### ⚙️ Modular Monolith · Patrón Saga · Spring Modulith
Showcase de nivel producción que demuestra arquitectura event-driven con el **patrón Saga** sobre **RabbitMQ**, límites de módulo reforzados vía **Spring Modulith**, **DDD** y observabilidad incorporada desde el inicio — **Java 21**. Construido para demostrar pensamiento de sistemas distribuidos sin el overhead operativo de microservicios completos.

### 💳 AegisGate — Motor de Verificación 3D Secure
Motor de verificación de transacciones que implementa **3D Secure (3DS)** para procesamiento de pagos — trabajo de backend nivel fintech, basado en experiencia real integrando pasarelas de pago (Payway, Cybersource) en ecommerce de producción.

### 🌊 Plataforma Reactiva de Monitoreo de Ríos *(en progreso)*
Sistema totalmente reactivo de monitoreo de nivel de agua para ríos argentinos. **Java 25 · Spring Boot · WebFlux · R2DBC · TimescaleDB · Reactor RabbitMQ**, 5 microservicios (registro de sensores, simulación, ingesta, alertas, API de consultas) con una regla estricta de cero código bloqueante de punta a punta, más un frontend en React/Leaflet.
> Desarrollado activamente con mi propio proceso spec-driven (ver SDD-GL abajo). Los contratos y el progreso son públicos a medida que avanza el proyecto.

### 📐 SDD-GL (Gate/Loop)
Un plugin de Spec-Driven Development para Claude Code que formaliza un flujo Gate → Contrato → Loop para developers que trabajan solos con agentes de IA: contratos estructurados, detección de contradicciones entre requisitos y criterios de aceptación, y checkpoints de aprobación humana antes de escribir código.

### 🔐 Backend Security Starter
Kit reutilizable de Spring Security + JWT — la base de autenticación que no quiero reconstruir desde cero en cada proyecto.

### 📦 Herramientas de Backend para Ecommerce
Gestión de inventario e integración con WooCommerce (Spring Boot + Vaadin) construidas y funcionando en producción para un catálogo de ~1.000 productos — sincronización de stock, facturación e integraciones de pasarelas de pago que hoy representan aproximadamente el 30% de la facturación del negocio.

*(repos fijados abajo — los READMEs incluyen notas de arquitectura y el razonamiento detrás de las decisiones clave, no solo instrucciones de instalación)*

---

<div align="center">

📫 Contactame en **[LinkedIn](https://www.linkedin.com/in/gerardomaidana)**

</div>
