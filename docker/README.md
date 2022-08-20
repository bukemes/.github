# Docker Configuration
for local development

Nginx Proxy
https://tania.tours
    /auth -> bukemes-auth:9001/auth (Express API)
    /api -> bukemes-api:9002/api (Express API)
    /admin -> bukemes-admin:9003 (React App)
    / -> taniatours:9004 (React App)

