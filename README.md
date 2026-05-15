# Upptime Figueredo Med · Status Page

Monitoreo de uptime automatizado para [figueredomed.com](https://figueredomed.com) + [Aetheris Med](https://figueredomed.com/aetheris-med).

## Status page

🌐 https://status.figueredomed.com

(También accesible directamente en https://dralexander810121-cpu.github.io/upptime-figueredomed/)

## Sitios monitoreados

| Sistema | URL | Frecuencia |
|---|---|---|
| Figueredo Med Web | figueredomed.com | 5 min |
| Figueredo Med (www) | www.figueredomed.com | 5 min |
| Patologías API | /api/v1/patologias/... | 5 min |
| Stripe Checkout | /api/checkout/pro | 5 min |
| IA Pregúntale Dr. | /api/ia/preguntale-dr | 5 min |
| Supabase REST | xrilfjsamjnyhlvsiiyh.supabase.co | 5 min |
| Supabase Auth | xrilfjsamjnyhlvsiiyh.supabase.co/auth/v1/health | 5 min |
| Cloudflare R2 CDN | pub-...r2.dev/organs/... | 5 min |
| Aetheris Med (B2B) | /aetheris-med | 5 min |
| Tienda | /tienda | 5 min |
| Biblioteca | /biblioteca | 5 min |
| Calculadoras | /calculadoras | 5 min |

## Cómo funciona

- GitHub Actions corre `uptime.yml` cada 5 minutos.
- Ping HTTP a cada URL → verifica status code esperado.
- Si falla 2 veces consecutivas → abre Issue automático en este repo.
- Cuando recupera → cierra Issue.
- Histórico se guarda en `history/` (commit por cada check).
- Status page estática se regenera cada hora desde los datos `history/`.

## SLA objetivo

**99.5% mensual** (4.4 horas downtime max/mes).

## Setup técnico (referencia)

Configuración en `.upptimerc.yml`. Ver [docs Upptime](https://upptime.js.org/docs/configuration).

Editor en Jefe: Dr. Alexander Jesús Figueredo Izaguirre · RP #108356
