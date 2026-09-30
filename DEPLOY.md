# Mettre Koura Music AI en ligne

Le projet est prêt pour un hébergeur Node.js comme Render.

1. Crée un dépôt GitHub et envoie tout le contenu de ce dossier.
2. Sur Render, crée un Web Service depuis le dépôt.
3. Build command : `npm install`
4. Start command : `npm start`
5. Ajoute les variables :
   - `GEMINI_API_KEY` = ta clé Gemini
   - `PUBLIC_BASE_URL` = l'adresse publique du service
   - `PAYMENT_PROVIDER=demo` pour tester sans argent réel.
6. Une fois le site testé, remplace `PAYMENT_PROVIDER=demo` par le connecteur d'un prestataire de paiement marchand et configure ses secrets/webhooks.
7. Pour une vraie base de données et plusieurs utilisateurs, remplace le fichier `data.json` par PostgreSQL/Supabase avant une mise en production importante.

Important : je ne peux pas créer à ta place un compte d'hébergement, une clé API ou un compte marchand, et je ne dois pas inventer ces identifiants.
