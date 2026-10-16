## Gustavo Sobrado Aller

Desarrollador backend .NET en Kirey (proyecto Sportian). Trabajo en la identidad digital de los fans: registro, login, consentimientos y migración de usuarios entre proveedores de identidad, con OAuth 2.0 / OpenID Connect y Azure. Termino el Grado en Ingeniería Informática en la Universidad de Oviedo.

Fuera del trabajo construyo backends y sistemas con LLMs de extremo a extremo: diseño, implementación, despliegue, observabilidad y tests. Me interesa cómo se pasa de un prototipo con una API de LLM a algo que se puede dejar abierto a usuarios reales sin que se rompa: retrieval que de verdad recupera, evaluación, latencia, costes, prompt injection, rate limiting.

### En el trabajo

- Microservicio en .NET que une el login con la plataforma de fans: registro, consentimientos, cambio de email y borrado de cuenta, con más de 450 tests unitarios.
- Integración de un proveedor de identidad CIAM con Azure API Management: validación JWT probada con tokens reales.
- Migración just-in-time de usuarios desde Azure AD B2C, con métricas en Application Insights.

*El código es privado del cliente; aquí solo están mis proyectos personales.*

### Proyectos personales

**[LegalDev](https://github.com/gustavintavo8/legaldev)**: API RAG de normativa legal española y europea para developers.
FastAPI + ChromaDB + sentence-transformers + Groq (gpt-oss-120b). Calibración empírica del threshold de retrieval, detección de prompt injection, observabilidad con Prometheus y logs JSON, CI con 290+ tests y 93 % de cobertura. Desplegado con Docker en Hugging Face Spaces.

**[PachagasApp](https://github.com/gustavintavo8/PachagasApp)**: plataforma full-stack para organizar partidos de fútbol, en producción con unos 30 jugadores.
Next.js 16 + Supabase + PostgreSQL. Balanceo de equipos en 3 fases sobre ratings ELO, autorización con Row Level Security y asistente conversacional con 9 herramientas de function calling sobre la base de datos en tiempo real.

**[Bali Flight Tracker](https://github.com/gustavintavo8/bot-vuelos-bali)**: rastreador diario de precios de vuelos.
Python + API de Amadeus. Se ejecuta solo cada mañana con GitHub Actions, avisa por Telegram cuando el precio baja de la media histórica y muestra las tendencias en un dashboard de Streamlit.

### Stack

**Trabajo:** C#, .NET, ASP.NET Core, OAuth 2.0 / OpenID Connect, Azure (API Management, AKS, Key Vault, Application Insights), xUnit.
**Proyectos:** Python, TypeScript, FastAPI, PostgreSQL, ChromaDB, LangChain, Next.js, Docker, GitHub Actions, pytest, Playwright.

### Contacto

[LinkedIn](https://www.linkedin.com/in/gustavosobrado) · gustavintavo1202@gmail.com
