# SecuBot-UdeA

Sistema de gamificación de seguridad para equipos de desarrollo. Detecta alertas de vulnerabilidades desde GitHub Dependabot, OWASP ZAP y Trivy, y convierte su resolución en puntos que se publican en tiempo real en el canal de Discord del equipo.

## Tecnologías

| Capa | Tecnología |
|---|---|
| Lenguaje | Python 3.11+ |
| Framework | FastAPI + Uvicorn |
| Bot Discord | discord.py 2.x |
| Base de datos | MongoDB Atlas (motor async) · Supabase (PostgreSQL) |
| HTTP cliente | httpx async |
| Validación | Pydantic v2 |
| CI | GitHub Actions |
| Despliegue | Vercel · Render · DigitalOcean (Kubernetes) |

## Repositorios

| Servicio | Repositorio | Despliegue | Rol |
|---|---|---|---|
| parser-dependabot | [SecuBotUdea/parser-dependabot](https://github.com/SecuBotUdea/parser-dependabot) | Vercel | Ingesta y normalización de alertas |
| jug-eared | [SecuBotUdea/jug-eared](https://github.com/SecuBotUdea/jug-eared) | Render | Hub de routing y registro de equipos |
| Secubot- | [SecuBotUdea/Secubot-](https://github.com/SecuBotUdea/Secubot-) | DigitalOcean | Motor de gamificación |
| Discord | [SecuBotUdea/Discord](https://github.com/SecuBotUdea/Discord) | DigitalOcean | Bot y notificaciones |

## Demo

> _Enlace a demo / video de presentación_
EOF
