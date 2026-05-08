{\rtf1\ansi\ansicpg1252\cocoartf2867
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Outils & Limites Terry\
\
## Stack technique actuel\
\
### Gestion projets\
- **Google Sheets** : Tracking freelances (nom, sp\'e9cialit\'e9, TJM, dispo, projet attribu\'e9)\
- **Notion** : Base de donn\'e9es clients + archives projets\
\
### Communication\
- **Slack Workspace** : "Terry Studio"\
  - Canal #g\'e9n\'e9ral\
  - Canal #nouveau-projet (notifs agents)\
  - Canaux projets cr\'e9\'e9s \'e0 la vol\'e9e (#projet-nom-client)\
\
### Stockage fichiers\
- **Dropbox Business** (2 To)\
  - Structure : `/Projets/[Nom Client]/[Brief + Assets + Livrables]`\
  - Partage : Liens avec mot de passe\
\
### Outils design\
- Adobe Creative Suite (Photoshop, Illustrator, After Effects, Premiere)\
- Figma\
- Principle (prototypage)\
\
## Limites actuelles\
\
### Pas de CRM\
Terry n'utilise pas de CRM type Pipedrive/HubSpot. Tout est dans Google Sheets + Notion.\
\
### Pas de plateforme freelances\
Il ne passe pas par Malt/Upwork. R\'e9seau direct uniquement.\
\
### Pas de dev interne\
Terry ne code pas. Il fait appel \'e0 des devs freelances pour int\'e9grations web.\
\
## Contraintes agent Phase 1\
\
**Ce qui DOIT marcher** :\
- Lecture fichiers Dropbox\
- Appels API Claude\
- Cr\'e9ation canaux Slack\
- Invitation users Slack\
\
**Ce qui peut attendre Phase 2** :\
- G\'e9n\'e9ration brief automatique (Phase 1 = Terry \'e9crit son brief manuellement)\
- Parsing PDF/images clients\
- G\'e9n\'e9ration r\'e9tro-planning auto\
- Liens Dropbox automatiques\
\
## Budget automation\
Terry est pr\'eat \'e0 investir :\
- **N8N** : 20\'80/mois (plan Starter)\
- **Claude API** : ~50-100\'80/mois (usage pr\'e9vu)\
- **Dropbox API** : Inclus dans son plan Business actuel\
- **Slack API** : Gratuit\
\
**Total** : ~70-120\'80/mois pour automatiser 15-20h/mois \uc0\u8594  **ROI imm\'e9diat**\
\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 ## Limites & S\'e9curit\'e9\
* **Z\'e9ro Suppression** : Interdiction formelle de supprimer ou d'\'e9craser un fichier existant sans demande explicite de ma part.\
* **Confidentialit\'e9** : Ne jamais envoyer de donn\'e9es clients (noms, RIB, montants de transaction) vers des plugins tiers non v\'e9rifi\'e9s.\
* **Validation Humaine** : Tout plan d'action g\'e9n\'e9r\'e9 doit \'eatre soumis \'e0 ma validation avant ex\'e9cution.}