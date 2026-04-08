# Politique de confidentialité de GardiePro

Dernière mise à jour : avril 2026

GardiePro respecte votre vie privée. Cette politique explique quelles informations sont collectées, où elles sont stockées et comment elles sont utilisées.

---

## 1. Données stockées dans le nuage (Appwrite)

GardiePro utilise Appwrite (appwrite.io) comme plateforme de stockage infonuagique. Vos données (profil du service de garde, dépenses, articles de dépenses, catégories et photos de factures) sont enregistrées sur les serveurs d'Appwrite situés à Toronto, Canada (région tor.cloud.appwrite.io).

Appwrite agit à titre de sous-traitant de GardiePro pour l'hébergement de vos données. Ces données sont chiffrées en transit (HTTPS) et au repos. Appwrite ne vend pas vos données et ne les utilise pas à des fins commerciales. La politique de confidentialité d'Appwrite est accessible à : appwrite.io/privacy

Les données suivantes sont également conservées localement sur votre appareil (base de données chiffrée) : règles de catégorisation apprises, préférences locales.

---

## 2. Analyse des photos de factures (Anthropic / Cloudflare)

Lorsque vous utilisez la fonction de numérisation de factures, la photo est transmise via un serveur mandataire (proxy) hébergé sur Cloudflare Workers à l'API Claude d'Anthropic (anthropic.com), un service d'intelligence artificielle, afin d'en extraire automatiquement les informations (articles, montants, fournisseur, date). Cette transmission est chiffrée (HTTPS).

Aucune photo d'enfant ni aucun renseignement personnel sur les enfants n'est jamais transmis à ces services.

Conformément à la politique d'Anthropic, les données soumises via l'API ne sont pas utilisées pour entraîner leurs modèles. Anthropic peut conserver les données transmises jusqu'à 30 jours à des fins de sécurité et de détection d'abus.

Cette fonctionnalité est optionnelle et peut être désactivée dans Paramètres → Analyse des factures.

Politiques applicables :
- Anthropic : anthropic.com/legal/privacy
- Cloudflare : cloudflare.com/privacypolicy/

---

## 3. Autocomplétion d'adresses et calcul de kilométrage (Google)

GardiePro utilise les services Google Maps Platform (Google LLC) pour deux fonctionnalités :

- **Autocomplétion d'adresses** : lorsque vous saisissez l'adresse d'un fournisseur, le texte partiel est envoyé à l'API Places de Google afin de vous proposer des suggestions. Cette transmission est chiffrée (HTTPS).

- **Calcul du kilométrage** : lorsque vous activez l'option « Calcul du km » sur une dépense, les coordonnées géographiques de votre garderie et du fournisseur sont envoyées à l'API Distance Matrix de Google afin de calculer la distance parcourue.

Ces données sont traitées par Google conformément à sa politique de confidentialité accessible à : policies.google.com/privacy

Ces fonctionnalités sont optionnelles. Vous pouvez ne pas saisir d'adresse et ne pas activer le calcul de km.

---

## 4. Photos de factures

Les photos prises ou importées sont copiées dans le dossier de support de l'app sur votre appareil, puis téléversées sur les serveurs d'Appwrite (Toronto) liées à votre compte. Elles ne sont accessibles qu'à vous via votre compte GardiePro.

---

## 5. Authentification

La gestion des comptes utilisateurs (création de compte, connexion, réinitialisation de mot de passe) est assurée par Appwrite. Votre adresse courriel et votre mot de passe (haché) sont stockés sur les serveurs d'Appwrite à Toronto.

---

## 6. Aucune collecte de données analytiques

GardiePro ne collecte aucune donnée analytique, aucun identifiant publicitaire et n'utilise aucun outil de suivi (traceur). Aucune information sur votre comportement dans l'application n'est envoyée à des tiers à des fins publicitaires ou statistiques.

---

## 7. Sauvegarde (iCloud / iTunes)

Si la sauvegarde iCloud ou iTunes est activée sur votre appareil, les données locales de GardiePro peuvent être incluses dans ces sauvegardes. Ces sauvegardes sont gérées entièrement par Apple et sont soumises à la politique de confidentialité d'Apple.

---

## 8. Vos droits (Loi 25)

Conformément à la Loi modernisant des dispositions législatives en matière de protection des renseignements personnels (Loi 25), vous avez le droit d'accéder à vos données personnelles, de les corriger et de demander leur suppression. Pour exercer ces droits ou pour toute question relative à la confidentialité, contactez-nous à l'adresse indiquée sur la page de l'application dans l'App Store.
