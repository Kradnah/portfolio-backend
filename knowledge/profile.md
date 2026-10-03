# Julian Camilo Lizcano Rojas

- Rol: Desarrollador Full-Stack (Python · FastAPI · React · Angular · Node.js/NestJS), enfocado en automatización e IA.
- Ubicación: Bogotá, Colombia.
- Idiomas: español (nativo), inglés (fluido).
- Contacto público: email kradnah@gmail.com · LinkedIn linkedin.com/in/julian-lizcano · web julian-lizcano.com
- El CV en PDF se puede descargar desde la sección de contacto de la web.

## Perfil

Desarrollador full-stack con más de 3 años de experiencia construyendo aplicaciones web escalables: backend con Python y FastAPI (también Node.js/NestJS), APIs REST con autenticación JWT/OAuth2, bases de datos relacionales y NoSQL (PostgreSQL, MySQL, MongoDB) y frontend con React y Angular. Experiencia con microservicios, Redis y procesamiento asíncrono, contenedores Docker, CI/CD con GitHub Actions y despliegue en AWS, GCP y Oracle Cloud. Ha llevado soluciones de la idea a producción con impacto medible: una automatización con IA que diseñó ahorra USD 4.000 mensuales y se convirtió en producto comercial. Cuida la seguridad y la calidad del código, participa en diseño técnico y revisión de código, y trabaja en equipos ágiles.

## Experiencia

### Automation Developer — GroupCOS (julio 2023 – presente, Bogotá)
- Diseña, construye y mantiene APIs REST con Python y FastAPI (además de Node.js/NestJS) que integran servicios internos, bases de datos y APIs externas, implementando la lógica de negocio de productos SaaS.
- Desarrolla aplicaciones web full-stack con Angular y React (JavaScript/TypeScript).
- Diseñó e implementó una solución end-to-end de QA y automatización de llamadas: desplegó WhisperX (speech-to-text) en servidores locales y lo integró con ChatGPT para analizar el desempeño de los asesores y dar feedback automático.
- Esa solución ahorra USD 4.000 al mes en consumo de APIs externas (Deepgram) y abrió una nueva línea de ingresos al empaquetarse como producto para nuevos clientes.
- Desarrolló bots de WhatsApp y agentes de IA con APIs de OpenAI integrados a los flujos operativos; implementó modelos preentrenados (HuggingFace, OpenAI) adaptados al negocio.
- Automatizó procesos de datos con Python, Selenium y Pandas.
- Despliega aplicaciones en contenedores Docker sobre GCP y Oracle Cloud; gestiona y optimiza bases de datos MySQL y MongoDB.
- Participa en el ciclo completo de productos SaaS bajo Scrum (diseño técnico, refinamiento, revisión de código, incidencias) con Git (GitHub, GitLab, Azure DevOps).

### Systems Analyst — Net Applications (octubre 2022 – julio 2023, Bogotá)
- Bots de RPA con Automation Anywhere, UiPath y PowerApps para clientes externos.
- Scripts en Python para automatizar flujos operativos.
- Optimización de bases de datos MySQL.

### Administrative Apprentice — Siemens Energy SAS (abril 2022 – octubre 2022, Bogotá)
- Dashboards en Tableau para análisis de KPIs.
- Automatización de procesos internos con Power Platform (Power Apps, Power Automate, Power BI).
- Estructuración y transformación de datos para informes.

## Habilidades técnicas

- Backend y APIs: Python, FastAPI, Node.js, NestJS, APIs REST, GraphQL, webhooks, microservicios.
- Seguridad: autenticación y autorización con JWT y OAuth2.
- Frontend: React, Angular, JavaScript, TypeScript.
- Bases de datos: PostgreSQL, MySQL, MongoDB, Redis.
- Cloud y DevOps: Docker, GitHub Actions (CI/CD), AWS (Lambda, API Gateway, S3), GCP, Oracle Cloud, Terraform.
- IA y automatización: APIs de OpenAI, Claude, HuggingFace, agentes de IA, WhisperX, Pandas, Selenium, Playwright.
- Prácticas: Scrum, diseño técnico, revisión de código, procesamiento asíncrono.

## Educación

- Ingeniería de Sistemas — UNIMINUTO (en curso, 7.º de 9 semestres, homologación).
- Análisis y Desarrollo de Sistemas de Información — SENA (marzo 2022).
- MisiónTIC 2022, desarrollo de software — Universidad Sergio Arboleda (enero 2022).

## Proyectos personales (los construyó solo, apoyándose en herramientas de IA)

### Casa Zhef — casazhef.com (en producción)
- Web de su propio negocio: Julian tiene una cocina oculta ("restaurante") que abre los fines de semana en Girardot, Cundinamarca, y esta es su web real.
- Muestra el menú por categorías, horarios, ubicación y pedidos por WhatsApp.
- Stack: Angular 20 + Tailwind CSS 4 en el frontend; API NestJS para el menú; Docker; desplegado en su propio VPS con Dokploy y Traefik (HTTPS con Let's Encrypt).

### rideapp — app de movilidad tipo Uber (demo funcional)
- Demo de transporte para Girardot, Ricaurte y Flandes (Colombia), con app de pasajero, app de conductor y panel web de administración.
- Apps móviles con React Native (Expo) y Google Maps; las APK de Android se pueden descargar desde la web.
- Backend NestJS (Fastify) con PostgreSQL + PostGIS, Redis (ubicación en vivo, bloqueos de emparejamiento, rate limiting), BullMQ para colas y Socket.IO para tiempo real.
- Emparejamiento de viajes con máquina de estados, tarifas, notificaciones push y recibos por correo.
- Seguridad: Argon2id, JWT ES256 con refresh tokens rotativos, panel con segundo factor (TOTP), cifrado de documentos, escaneo de imágenes con Trivy, tratamiento de datos según la Ley 1581 de Colombia.
- Monorepo pnpm + Turborepo con contratos Zod compartidos entre backend y clientes; tests de integración con Testcontainers.

### Este portfolio y su asistente de IA
- Frontend Angular con diseño brutalista; el asistente es una API en Python (FastAPI) que usa modelos vía OpenRouter, con límites de uso por IP y diarios, respuestas en streaming y presupuesto acotado.

### Infraestructura propia
- Administra su propio VPS con Dokploy y Traefik, donde despliega todos sus proyectos con repos git propios y despliegue automático en cada push.
