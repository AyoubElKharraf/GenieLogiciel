# ERP Cloud SaaS Multi-Entreprises

> Projet de Fin d'Études — Master M2I, Ingénierie Informatique, Université Mohammed Premier (Oujda)

## 📋 Description

Conception et développement d'un **ERP Cloud SaaS Multi-Entreprises, Multi-Utilisateur et Multilingue** pour la gestion intégrée et la transformation numérique des activités commerciales, financières, administratives et opérationnelles d'une entreprise.

Le système adopte une architecture **SaaS Multi-Tenant**, permettant à plusieurs entreprises clientes d'utiliser la même plateforme tout en garantissant une séparation stricte de leurs environnements et de leurs données.

## ✨ Fonctionnalités principales

- 🏢 Gestion multi-entreprises (architecture multi-tenant avec isolation des données)
- 👥 Gestion des utilisateurs, rôles et permissions (RBAC)
- 💰 Gestion financière et comptable
- 🧾 Facturation électronique
- 💳 Paiement en ligne sécurisé
- ☁️ Services Cloud et scalabilité
- 📊 Analyse et exploitation des données (BI / dashboards décisionnels)
- 🤖 Assistance et aide à la décision par Intelligence Artificielle
- ⚙️ Automatisation des processus métier
- 🌐 Multilingue
- 📡 Fonctionnalités IoT (optionnel / phase avancée)
- 🔧 Maintenance prédictive et détection intelligente des anomalies (optionnel / phase avancée)

## 🧱 Stack technique

> À finaliser en équipe lors du Sprint 0 — proposition indicative

| Couche | Technologies envisagées |
|---|---|
| Frontend | *(à définir : React / Next.js / Angular...)* |
| Backend | *(à définir : Node.js/Express / Spring Boot / NestJS...)* |
| Base de données | *(à définir : PostgreSQL multi-tenant / MongoDB...)* |
| IA / Décisionnel | *(à définir selon les modules choisis)* |
| Infrastructure | Docker, CI/CD, déploiement Cloud |

## 👥 Équipe

| Membre | Rôle |
|---|---|
| Ayoub El Kharraf | *(rôle à préciser)* |
| ... | ... |

## 🗂️ Méthodologie de gestion de projet

Projet mené en **Scrum** :
- Suivi via **Jira** (Product Backlog, Sprints, Board)
- Sprints de *(durée à définir)*
- Cérémonies : Sprint Planning, Daily Standup, Sprint Review, Sprint Retrospective

## 📁 Structure du repository

```
.
├── frontend/           # Application client
├── backend/            # API et logique métier
├── docs/                # Documentation, diagrammes UML, cahier des charges
│   ├── specs/
│   └── diagrams/
├── docker/              # Fichiers Docker / docker-compose
├── .github/
│   └── workflows/       # Pipelines CI/CD
└── README.md
```

## 🚀 Démarrage du projet

```bash
# Cloner le repository
git clone <url-du-repo>
cd erp-saas-pfe

# Instructions d'installation à compléter après choix de la stack
```

## 🌿 Convention de branches

- `main` — branche stable / production
- `develop` — branche d'intégration
- `feature/<nom-de-la-feature>` — nouvelles fonctionnalités
- `fix/<nom-du-bug>` — corrections de bugs

## 📝 Convention de commits

```
feat: ajout de la gestion multi-tenant
fix: correction du calcul de facturation
docs: mise à jour du README
chore: configuration du pipeline CI
```

## 📄 Licence

Projet académique — Université Mohammed Premier, Oujda.
