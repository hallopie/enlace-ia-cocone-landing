# Webhook URLs — Kinder Cocone (privado, no compartir con cliente)

## DEV (demo / pruebas)
`REEMPLAZAR_CON_WEBHOOK_DEV`

## PROD (go-live)
`REEMPLAZAR_CON_WEBHOOK_PROD`

## Notas
- El `index.html` actualmente tiene `WEBHOOK_URL = "REEMPLAZAR_CON_WEBHOOK_DE_MAKE"` como placeholder.
- Antes de compartir el demo con el cliente: pegar aquí y en `index.html` el webhook del escenario DEV en Make.
- Antes del go-live: cambiar a PROD en `index.html`, hacer commit "go-live: conectar a PROD [fecha]", y actualizar checklist en README.md.
