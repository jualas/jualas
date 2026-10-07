### Hola, soy Juan Antonio Francés (jualas) 👋

Desarrollador **backend Python** con foco en **IA aplicada**: APIs con FastAPI, bases de datos SQL, integración de LLM y despliegue con Docker. Titulado en **DAM**, en Cartagena, y buscando mi primer puesto como desarrollador (remoto preferiblemente).

Me gusta llevar los proyectos hasta producción: mis aplicaciones corren en un servidor propio con Docker Compose, CI en GitHub Actions, staging y *rollback*.

#### 🚀 Proyectos destacados

**[Electrolineras](https://github.com/jualas/electrolineras)** · [demo en vivo](https://electro.jualas.es)
Mapa de ~22.000 cargadores de vehículo eléctrico en España y Portugal a partir de datos abiertos oficiales (DATEX II).
- FastAPI + React/TypeScript + MapLibre, con OSRM y Nominatim autoalojados.
- Ingestión ETL programada, búsqueda de cargadores en el corredor de una ruta y planificador de paradas de carga.
- Asistente de viaje con IA (Dify) que usa la API como herramientas; zona privada con login TOTP.
- 230+ tests con pytest, Ruff y GitHub Actions; despliegue con Docker Compose.

**[TaskBoard](https://github.com/jualas/taskboard)** · [en producción](https://kanban.jualas.es)
Gestor de proyectos y tareas (Kanban y lista) con **asistente IA**. Nace de mi proyecto fin de ciclo ([proyecto_flutter_supabase](https://github.com/jualas/proyecto_flutter_supabase)) y lo rehíce sobre un backend propio en lugar de Supabase.
- API REST con FastAPI + PostgreSQL (asyncpg, SQL sin ORM) y autenticación JWT; cliente Flutter Web.
- Vincula cada proyecto a su repo: detecta commits y cambios y propone tareas automáticamente.
- Asistente IA para crear tareas a partir de un brief y planificar el backlog por chat, con varios motores (DeepSeek y Ollama con API compatible con OpenAI, y Cursor Agent CLI).
- **Servidor MCP propio** para que agentes de IA (p. ej. Cursor) consulten y gestionen proyectos y tareas a través de la API.
- En uso real: con él planifico y sigo todos mis proyectos. Se arranca en local con `docker compose up`.

#### 📂 Otros proyectos

| Proyecto | Qué es | Stack |
|---|---|---|
| [proyecto_flutter_supabase](https://github.com/jualas/proyecto_flutter_supabase) | Proyecto fin de ciclo DAM (origen de TaskBoard): seguimiento de TFG entre alumnos, tutores y centro | Flutter, Supabase (PostgreSQL) |
| [proyecto-fct-NetJs](https://github.com/jualas/proyecto-fct-NetJs) | Gestión de proyectos FCT con arquitectura limpia | NestJS, TypeScript, Flutter |

*En preparación para publicar:* **Oposiciones** (FastAPI + React, preguntas tipo test generadas con RAG sobre exámenes oficiales).

#### 🛠️ Tecnologías

- **Backend:** Python · FastAPI · Pydantic · SQLAlchemy/Alembic · asyncpg · NestJS
- **Datos:** PostgreSQL · SQLite · SQL · ETL de XML/JSON
- **IA:** integración de LLM (APIs compatibles con OpenAI, Ollama, DeepSeek) · Dify · RAG · MCP
- **Frontend / móvil:** React · TypeScript · Flutter/Dart
- **DevOps:** Docker / Docker Compose · GitHub Actions · nginx · Cloudflare Tunnel · Linux (Debian)

#### 📫 Contacto

[LinkedIn](https://www.linkedin.com/in/jualas/) · [jualas.es](https://jualas.es)
