# Santé‑Safi — dossier site statique 55

## Contenu
- `index.html`
- `assets/css/styles.css`
- `assets/img/banner-sante-safi.png`

## À personnaliser
Dans `index.html`, remplace :
- `WHATSAPP_PHONE_E164 = "+243XXXXXXXXX"` par le numéro WhatsApp Business au format international
- Les horaires et tarifs si besoin
- Les instructions de paiement Mobile Money (numéro, nom, référence)

## Déploiement Azure Static Web Apps
- `app_location: "/"` (racine)
- Pas de build (skip_app_build: true)
