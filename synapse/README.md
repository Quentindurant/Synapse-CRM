# 🧠 Synapse CRM — Module ADV — V0.0.0 -
> Les **ADV** (Administration des Ventes) gèrent tout le cycle administratif et commercial des prestations
> Elles coordonnent **les partenaires**, **techniciens** et **clients** pour assurer le bon déroulement des installations et interventions.
> Elles garantissent le **suivi**, la **conformité** et la **traçabilité** des dossiers jusqu’à leur clôture.
---

## 🚀 Fonctionnalités principales

### 📄 Informations administratives
 
 - N° dossier / référence interne
 - Nom du client, société, contact, téléphone, email
 - Adresse d’installation
 - Partenaire associé (VIP Telecom, HighCom, etc.)

### ⚙️ Informations techniques

 - Type de prestation (installation, maintenance, migration, portabilité…)
 - Matériel concerné (poste IP, routeur, PABX, etc.)
 - Date d’intervention prévue et durée estimée
 - Technicien assigné
 - Notes internes

### 💬 Suivi / Statut

 - En attente, planifié, en cours, terminé, à facturer, clos
 - Historique des modifications
 - Signature technicien + PV intervention
 - Liens vers les tickets support liés (si besoin)

### 💰 Informations commerciales

 - Partenaire
 - Commande client associée
 - Montant facturé
 - Statut de facturation (non facturé, en cours, payé)

---

## 🏗️ Stack technique

- **Backend :** Nest.js
- **ORM :** Prisma
- **Base de données :** PostgreSQL
- **Auth :** JWT (avec rôles)
- **Tests :** cypress - Postman (et d'autre ?)
- **CI/CD :** GitHub Actions

---

## ⚙️ Installation

```bash
# Cloner le repo github
git clone https://github.com/Quentindurant/Synapse-CRM.git

# Lancer Prisma
npx prisma migrate dev

# Démarrer le serveur
npm run dev