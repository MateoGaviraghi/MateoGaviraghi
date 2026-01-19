# MATEO GAVIRAGHI

**Desarrollador Full Stack**

📍 Santa Fe, Argentina  
📧 mateogaviraghi24@gmail.com  
📱 +54 342 516 2081  
🔗 [LinkedIn](https://www.linkedin.com/in/mateo-gaviraghi-2133482a8/) | [GitHub](https://github.com/MateoGaviraghi)

---

## RESUMEN PROFESIONAL

Ingeniero Full Stack con 2 años de experiencia diseñando y desarrollando soluciones web escalables end-to-end. Especializado en el ecosistema moderno de JavaScript/TypeScript (React, Next.js, Node.js, NestJS) con arquitectura de microservicios y despliegue en cloud (AWS). Experiencia comprobada liderando proyectos desde la concepción hasta producción, logrando reducciones del 60% en costos de infraestructura mediante arquitectura serverless, optimizaciones de performance del 90% en bases de datos, y sistemas de tiempo real procesando ofertas con latencia <200ms. Estudiante de Ingeniería en Inteligencia Artificial con enfoque en integración de LLMs y automatización de procesos.

---

## TECNOLOGÍAS Y HABILIDADES

**Lenguajes:**  
TypeScript, JavaScript (ES6+), Python, SQL, HTML5, CSS3

**Frontend:**  
React, Next.js 15, Redux, Tailwind CSS, Framer Motion, Material-UI, Responsive Design, SSR/SSG

**Backend:**  
Node.js, NestJS, Express, REST API, GraphQL, Microservicios, MQTT (Event-Driven Architecture)

**Bases de Datos:**  
MongoDB, PostgreSQL, MySQL, Mongoose ODM, Redis, Database Optimization

**Cloud & DevOps:**  
AWS (Lambda, S3, EC2, API Gateway, CodeBuild, CodePipeline, SES, ECR), Docker, Docker Compose, CI/CD, Serverless Framework

**Testing & Quality:**  
Jest, Supertest, Unit Testing, E2E Testing, ESLint, Prettier

**Autenticación & Seguridad:**  
JWT, OAuth 2.0 (Google), Passport.js, bcrypt, CORS, Rate Limiting

**Herramientas & Otros:**  
Git, GitHub Actions, Swagger/OpenAPI, Postman, Axios, Nodemailer, ExcelJS, PDFKit, Cloudinary

**IA & Automatización:**  
OpenAI API, Prompt Engineering, LangChain, GitHub Copilot, AI-Assisted Development

---

## EXPERIENCIA PROFESIONAL Y PROYECTOS DESTACADOS

### **Desarrollador Full Stack - 32F Biological Sample Management System**

**Complex Antibodies Inc. (CAI)** | 2024 - 2026 | En Producción

Arquitecté y desarrollé sistema empresarial completo para gestión de muestras biológicas, inventario de freezers y órdenes de compra, reemplazando sistema legacy Freezerworks.

**Logros y Responsabilidades:**

- **Reducción de costos del 60%** migrando de servidores tradicionales a arquitectura serverless AWS Lambda con auto-scaling, eliminando gestión manual de infraestructura
- Diseñé e implementé **API RESTful completa con 30+ endpoints** utilizando NestJS y TypeScript, incluyendo arquitectura modular con 6 módulos independientes (samples, customers, purchase-orders, freezers, audit, default-values)
- Desarrollé **frontend completo en Next.js 15** con TypeScript, implementando dashboard analítico con Chart.js, sistema drag-and-drop para gestión visual de inventario 3D, y generación automatizada de documentos certificados (CoA, Packing Lists) con códigos de barras PDF417
- Integré **autenticación empresarial con Google OAuth 2.0** y JWT, mejorando seguridad y eliminando gestión manual de credenciales
- Implementé **pipeline CI/CD completo** con AWS CodeBuild, CodePipeline y Docker multi-stage builds, reduciendo tiempo de deployment de manual a <5 minutos automático
- Desarrollé **sistema de migración de datos** desde Freezerworks con 0% pérdida de información, incluyendo scripts de validación y rollback
- Alcancé **99.9% uptime** en producción con monitoreo continuo y health checks automatizados

**Stack:** Next.js 15, React 18, TypeScript, NestJS, MongoDB, AWS Lambda, API Gateway, Docker, OAuth 2.0, Chart.js, pdfmake, Tailwind CSS

---

### **Desarrollador Backend Full Stack - Zorrilla Admin System**

**Sistema de Subastas en Tiempo Real** | 2024 - 2026 | En Producción

Diseñé y desarrollé backend robusto para gestión de subastas en tiempo real con procesamiento de ofertas mediante arquitectura event-driven utilizando MQTT.

**Logros y Responsabilidades:**

- Arquitecté **sistema de procesamiento de ofertas en tiempo real** con latencia <200ms medido con timers personalizados, utilizando MQTT para comunicación bidireccional y validación automática de reglas de negocio complejas
- Implementé **arquitectura serverless híbrida en AWS** (Lambda Functions + contenedores Docker) logrando reducción estimada del 60% en costos vs EC2 tradicional con escalabilidad automática
- Desarrollé **20 módulos especializados** con NestJS (auctions, items, lotes, bids, pre-bids, payments, transactions) aplicando arquitectura modular con bajo acoplamiento
- Optimicé **CI/CD inteligente con builds condicionales** que detectan cambios git entre commits, reduciendo tiempo de build hasta 80% en commits pequeños y deployment en 70%
- Creé **sistema de pre-ofertas automáticas** con triggers configurables y auditoría completa, mejorando competitividad y trazabilidad del 100% de transacciones
- Integré **servicios AWS** (S3 para archivos, SES para emails, ECR para containers) con configuración multi-entorno (dev/prod)
- Implementé **sistema de backups automatizado** de MongoDB con cron jobs y scripts de migración con dry-run/rollback

**Stack:** NestJS, TypeScript, Node.js 22, MQTT, MongoDB, AWS Lambda, S3, SES, Docker, Serverless Framework, JWT, ExcelJS, Swagger

---

### **Desarrollador Full Stack - Guzmán Motors**

**Plataforma Web para Concesionaria de Vehículos** | Diciembre 2024 - Enero 2026 | En Producción

Desarrollé plataforma web completa (frontend + backend) para concesionaria automotriz con gestión de inventario, clientes, y multimedia optimizada.

**Logros y Responsabilidades:**

- **Reduje consultas a base de datos en 70%** implementando sistema de caché con TTL de 30 minutos para opciones frecuentes utilizando node-cache
- Desarrollé **API RESTful con NestJS** incluyendo autenticación JWT, guards personalizados (RolesGuard, OwnershipGuard), rate limiting multinivel (10 req/seg, 100 req/min, 1000 req/15min) para protección DDoS
- Implementé **frontend completo en Next.js 15** con más de 40 componentes React reutilizables, búsqueda avanzada con autocompletado inteligente, sistema de filtros dinámicos y panel administrativo completo (CRUD)
- Integré **Cloudinary para gestión de multimedia** con optimización automática y generación de 3 tamaños de thumbnails (small, medium, large), mejorando tiempos de carga significativamente
- Mejoré **seguridad con Helmet, CORS configurado, validación exhaustiva** de DTOs con class-validator reduciendo errores de entrada en 95%
- Diseñé **esquemas MongoDB optimizados** con Mongoose ODM y referencias entre entidades para 6 módulos (clientes, usuarios, vehículos 0km, usados, remolques, novedades)

**Stack:** Next.js 15, React 19, TypeScript, NestJS, MongoDB, Cloudinary, Tailwind CSS, JWT, Docker, React Hook Form, Zod

---

### **Desarrollador Full Stack - BLOODWORK**

**Sistema de Gestión de Laboratorio Clínico y Donaciones** | 2024 - 2026 | En Desarrollo Activo

Backend robusto para gestionar ciclo completo de operaciones en laboratorios clínicos y bancos de sangre (donantes, donaciones, análisis, requisiciones, check-ins).

**Logros y Responsabilidades:**

- Arquitecté **17 módulos especializados** con NestJS aplicando arquitectura modular y separación de responsabilidades (donors, donations, lab, test, check-in, visit, requisition, diagnosis, forms, user, projects, trace)
- Desarrollé **sistema de búsqueda genérica universal** reutilizable con 1000+ líneas de lógica compleja, soportando múltiples tipos de datos (texto, numérico, fecha, ObjectId) con paginación avanzada y filtros dinámicos
- Integré **AWS S3** con generación de URLs pre-firmadas para upload seguro de documentos, gestionando archivos por donante/formulario mediante servicios especializados
- Implementé **arquitectura serverless** lista para deployment en AWS Lambda con handler optimizado (singleton pattern) y body parser configurado para payloads grandes (10MB)
- Creé **sistema de soft delete en cascada** preservando integridad referencial de datos y trazabilidad completa
- Documenté **API completa con Swagger/OpenAPI** accesible en endpoint interactivo

**Stack:** NestJS, TypeScript, Node.js 20, MongoDB, Mongoose, AWS Lambda, AWS S3, JWT, Passport.js, Swagger

---

### **Desarrollador Frontend - Concesionaria Mercedes-Benz (Portfolio Leonardo Guzmán)**

**Catálogo Digital de Vehículos Premium** | Diciembre 2024 - Enero 2025

Plataforma web full-stack para exhibición de catálogo Mercedes-Benz con gestión de contenido personalizada.

**Logros y Responsabilidades:**

- Diseñé **arquitectura de base de datos PostgreSQL en Supabase** con 60+ campos por vehículo utilizando JSONB para especificaciones técnicas flexibles e índices optimizados
- Desarrollé **interfaces responsive en Next.js 16** con React Server Components, carousels de imágenes con Embla Carousel, galerías de colores y navegación por 3 categorías (Autos, SUVs, Eléctricos)
- Implementé **CMS personalizado completo** con formularios dinámicos para gestión de vehículos, especificaciones técnicas, equipamiento y galería multimedia
- Optimicé **imágenes con formatos modernos** (AVIF/WebP) utilizando Next.js Image Optimization para carga rápida
- Creé **animaciones fluidas** con Framer Motion mejorando experiencia de usuario y engagement

**Stack:** Next.js 16, React 19, TypeScript, Supabase (PostgreSQL), Tailwind CSS 4, Framer Motion, Embla Carousel, Vercel

---

## EDUCACIÓN

**Ingeniería en Inteligencia Artificial** | Universidad Nacional del Litoral (UNL)  
En curso (2020 - Presente) | Santa Fe, Argentina

**Bootcamp Full Stack Developer** | Henry Bootcamp  
Remoto | 2023 - 2024

**Secundario Completo** | Colegio de la Inmaculada Concepción  
2020 | Santa Fe, Argentina

---

## IDIOMAS

**Español:** Nativo  
**Inglés:** Intermedio (lectura técnica avanzada, comunicación profesional)

---

## INFORMACIÓN ADICIONAL

- **Disponibilidad:** Trabajo remoto con compatibilidad horaria para equipos internacionales
- **Aprendizaje Continuo:** Actualización constante en tecnologías emergentes (IA, cloud-native architectures, serverless patterns)
- **GitHub:** Portafolio de proyectos open source y contribuciones disponible en perfil público
