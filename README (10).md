# ∞ DIGIY HUB

> **L'écosystème vu d'en haut. Vécu d'en bas.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/beauville/digiylyfe)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()

---

## 🌍 VAS CHEZ DIGIY

**DIGIY HUB** est le grand village digital africain - l'écosystème complet **0% commission** qui libère les entrepreneurs africains des plateformes qui prennent 20-30% de leurs revenus.

```
🚗 Tu cherches une voiture ?      → VAS CHEZ DIGIY
🍽️ Tu veux sortir au resto ?       → VAS CHEZ DIGIY
🏠 Tu cherches un logement ?       → VAS CHEZ DIGIY
💇 Besoin d'une belle coupe ?      → VAS CHEZ DIGIY
💼 Les confrères t'attendent ?     → VAS CHEZ DIGIY
```

**Une seule réponse. Pour tout.**

---

## 🎯 La Vision

### L'Afrique enracinée, connectée au monde

DIGIY HUB incarne la **souveraineté digitale africaine** :

- ✅ **Pas d'imitation** : Première main, pas deuxième main
- ✅ **Notre terroir** : Solutions adaptées à notre culture
- ✅ **Économie circulaire** : L'argent reste entre nous
- ✅ **0% commission** : Tu gardes 100% de tes revenus

### Le Grand Village Circulaire

```
Pro africain propose → Client africain achète → 
Argent reste en Afrique → Économie circulaire ♻️
```

**L'argent tourne entre nous, personne ne perd 20-30% !**

---

## 🦅 La Philosophie

> *"L'or était là, sous tes pieds.*  
> *Mais il fallait lever les yeux vers l'horizon*  
> *pour comprendre comment tout s'assemble."*

### L'humilité au sol + La vision d'aigle

- 🙏 **HUMBLE** : Au sol avec les gens, dans leurs galères quotidiennes
- 🦅 **VISIONNAIRE** : Regard sur l'horizon, vue d'ensemble sur l'écosystème
- ∞ **ÉQUILIBRE** : Enraciné dans la terre africaine, connecté au monde

**Ne regarde plus tes pieds. Regarde l'horizon.**

---

## 🏗️ L'Écosystème (11 Modules)

### Modules Actifs

| Module | Description | Status |
|--------|-------------|--------|
| 🚗 **DIGIY DRIVER** | VTC & Transport | ✅ Déployé |
| 🏠 **DIGIY LOC** | Hébergement & Location | ✅ Déployé |
| 🍽️ **DIGIY RESTO** | Restaurants & Livraison | 🚧 En dev |
| 🛒 **DIGIY MARKET** | E-commerce & Marketplace | 🚧 En dev |
| 💼 **DIGIY JOBS** | Emploi & Freelance | 📋 Planifié |
| 💳 **DIGIY PAY** | Paiements & Transactions | 📋 Planifié |
| 🏗️ **DIGIY BUILD** | Artisans & Construction | 📋 Planifié |
| 📅 **DIGIY RÉSA** | Réservations & Événements | 📋 Planifié |
| 🧾 **DIGIY POS** | Point de vente & Caisse | 📋 Planifié |
| 💇 **DIGIY BEAUTY** | Coiffure & Esthétique | 💡 Concept |
| 🏥 **DIGIY HEALTH** | Santé & Bien-être | 💡 Concept |

### Modèle Économique

**0% COMMISSION** - Abonnement mensuel transparent :

| Pack | Prix | Modules inclus |
|------|------|----------------|
| **STARTER** | 19,900 F/mois | 3 modules au choix |
| **PRO** ⭐ | 29,900 F/mois | Tous les 11 modules |
| **BUSINESS** | 49,900 F/mois | + Support prioritaire |

🔥 **Offre Pionniers** : Prix bloqué À VIE pour les 100 premiers !

---

## 🆚 DIGIY vs Plateformes Classiques

| Critère | Google/Uber/Booking | DIGIY HUB |
|---------|---------------------|-----------|
| 🌍 Origine | Occidental | Africain |
| 🎯 Adaptation | Générique | Notre terroir |
| 💰 Commission | 15-30% | 0% |
| 💵 Argent | Part à l'étranger | Reste en Afrique |
| 👤 Relation | Impersonnel | Réseau de confrères |
| 🔧 Solution | Deuxième main | Première main |
| 📊 Données | Exploitées | Tiennes |

---

## 📂 Structure du Projet

```
digiylyfe/
├── apps/
│   ├── driver/           # DIGIY DRIVER (VTC)
│   ├── loc/              # DIGIY LOC (Hébergement)
│   ├── resto/            # DIGIY RESTO (Restaurants)
│   └── market/           # DIGIY MARKET (E-commerce)
├── shared/
│   ├── components/       # Composants React réutilisables
│   ├── utils/            # Utilitaires partagés
│   └── types/            # Types TypeScript
├── backend/
│   ├── api/              # API REST
│   ├── firebase/         # Configuration Firebase
│   └── functions/        # Cloud Functions
├── docs/
│   ├── philosophy/       # Documentation philosophique
│   ├── guides/           # Guides d'utilisation
│   └── marketing/        # Assets marketing
└── assets/
    ├── videos/           # Vidéos promo
    ├── images/           # Images & logos
    └── fonts/            # Typographies (Unbounded, Sora)
```

---

## 🚀 Installation & Démarrage

### Prérequis

```bash
Node.js >= 18.0.0
npm >= 9.0.0
Firebase CLI
```

### Installation

```bash
# Cloner le repo
git clone https://github.com/beauville/digiylyfe.git
cd digiylyfe

# Installer les dépendances
npm install

# Configuration Firebase
firebase login
firebase init

# Variables d'environnement
cp .env.example .env
# Configurer tes clés API dans .env
```

### Développement

```bash
# Lancer tous les modules en dev
npm run dev

# Lancer un module spécifique
npm run dev:driver
npm run dev:loc
npm run dev:resto
npm run dev:market

# Build pour production
npm run build

# Deploy sur Firebase
npm run deploy
```

---

## 🎨 Stack Technique

### Frontend
- **React 18** - Interface utilisateur
- **TypeScript** - Typage fort
- **Tailwind CSS** - Styling (uniquement core utilities)
- **Vite** - Build tool

### Backend
- **Firebase** - Base de données & Auth
- **Cloud Functions** - Serverless backend
- **Firebase Storage** - Stockage fichiers

### Géolocalisation
- **Mapbox GL JS** - Cartes interactives
- **Google Maps API** - Géocodage & directions

### Paiements
- **Wave** - Paiements mobiles Afrique
- **Orange Money** - Paiements mobiles
- **Stripe** - Paiements internationaux (futur)

---

## 📱 Modules Détaillés

### 🚗 DIGIY DRIVER

**VTC & Transport 0% commission**

- GPS temps réel avec Mapbox
- Calcul tarifaire automatique
- Paiement intégré Wave/Orange Money
- Historique courses
- Notation client/chauffeur
- Mode hors-ligne

**vs Uber** : Le chauffeur garde 100% au lieu de perdre 25%

### 🏠 DIGIY LOC

**Hébergement & Location directe**

- Calendrier disponibilités
- Réservation en ligne
- Paiement sécurisé
- Photos & descriptions
- Géolocalisation
- Pricing selon nombre de propriétés

**vs Booking/Airbnb** : L'hôte garde 100% au lieu de perdre 15-18%

### 🍽️ DIGIY RESTO

**Restaurants & Système de caisse**

- POS multi-zones (terrasse, salle, bar)
- Kitchen Display System
- Menu QR code
- Commande en ligne
- Intégration paiements
- Stats en temps réel

**vs Glovo/Deliveroo** : Le resto garde 100% au lieu de perdre 30%

### 🛒 DIGIY MARKET

**Marketplace souveraine**

- Boutique en ligne clé-en-main
- Gestion stock
- Paiement intégré
- Livraison tracking
- Analytics vendeur
- Multi-vendeurs

**vs Jumia** : Le marchand garde 100% au lieu de perdre 20%

---

## 🗺️ Roadmap

### ✅ Q4 2024 (Completed)
- [x] DIGIY DRIVER lancé
- [x] DIGIY LOC lancé
- [x] Système de paiement Wave/Orange
- [x] Dashboard admin
- [x] Offre pionniers 100 places

### 🚧 Q1 2025 (En cours)
- [ ] DIGIY RESTO beta
- [ ] DIGIY MARKET beta
- [ ] Application mobile iOS/Android
- [ ] Système de chat intégré
- [ ] Programme ambassadeurs

### 📋 Q2 2025
- [ ] DIGIY JOBS lancement
- [ ] DIGIY PAY intégration complète
- [ ] DIGIY BUILD lancement
- [ ] Expansion Dakar → Saint-Louis
- [ ] API publique pour développeurs

### 💡 Q3-Q4 2025
- [ ] DIGIY RÉSA & DIGIY POS
- [ ] DIGIY BEAUTY & DIGIY HEALTH
- [ ] Assistant vocal DIGIY IA
- [ ] Expansion régionale (Afrique de l'Ouest)
- [ ] Partenariats stratégiques

### 🔮 Vision 2026+
- [ ] DIGIY Assistant IA conversationnel
- [ ] "VAS CHEZ DIGIY" = Expression quotidienne
- [ ] Expansion panafricaine
- [ ] Écosystème circulaire complet
- [ ] Souveraineté digitale africaine réalisée

---

## 🎥 Assets Marketing

### Vidéos Promotionnelles

Disponibles dans `/assets/videos/` :

- **video-digiy-hub-PHILOSOPHIE.html** - La vision complète (36s)
- **video-VAS-CHEZ-DIGIY.html** - L'expression révolutionnaire (28s)
- **video-digiylyfe-PREMIUM.html** - Version premium institutionnelle
- **video-digiy-driver.html** - Module DRIVER (18s)
- **video-digiy-loc.html** - Module LOC (18s)
- **video-digiy-resto.html** - Module RESTO (18s)
- **video-digiy-market.html** - Module MARKET (18s)

### Page Tarifs

- **tarifs-digiy-monster.html** - Landing page avec calculateur ROI en temps réel

### Guidelines

Consulter `/docs/marketing/` pour :
- Charte graphique (couleurs, typographies)
- Tone of voice
- Stratégie de diffusion
- Scripts réseaux sociaux

---

## 🤝 Contribuer

DIGIY HUB est un projet communautaire ! Voici comment contribuer :

### 1. Fork le projet
```bash
git clone https://github.com/TON-USERNAME/digiylyfe.git
```

### 2. Créer une branche
```bash
git checkout -b feature/nouvelle-fonctionnalite
```

### 3. Commit tes changements
```bash
git commit -m "✨ Ajout fonctionnalité X"
```

### 4. Push et créer une Pull Request
```bash
git push origin feature/nouvelle-fonctionnalite
```

### Convention de commits

Utilise [Conventional Commits](https://www.conventionalcommits.org/) :

- `feat:` Nouvelle fonctionnalité
- `fix:` Correction de bug
- `docs:` Documentation
- `style:` Formatting, CSS
- `refactor:` Refactoring code
- `test:` Ajout de tests
- `chore:` Maintenance

---

## 📞 Contact & Support

### 🏢 DIGIYLYFE
**Fondateur & CEO** : DIGIY

### 📱 Contacts
- **Téléphone** : +221 77 134 28 89
- **Email** : contact@digiylyfe.com
- **Site web** : [digiylyfe.com](https://digiylyfe.com)

### 🌐 Réseaux sociaux
- **Facebook** : [@digiylyfe](https://facebook.com/digiylyfe)
- **Instagram** : [@digiylyfe](https://instagram.com/digiylyfe)
- **LinkedIn** : [DIGIYLYFE](https://linkedin.com/company/digiylyfe)
- **Twitter/X** : [@digiylyfe](https://twitter.com/digiylyfe)

### 💬 Community
- **Discord** : [Rejoindre le village DIGIY](https://discord.gg/digiylyfe)
- **Telegram** : [Groupe DIGIY Sénégal](https://t.me/digiysenegal)

---

## 📄 License

Ce projet est sous licence **MIT** - voir le fichier [LICENSE](LICENSE) pour plus de détails.

```
MIT License

Copyright (c) 2024 DIGIYLYFE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🙏 Remerciements

### Aux Pionniers
Les 100 premiers qui ont cru en la vision et ont rejoint le village.

### À la Communauté
Tous les entrepreneurs africains qui construisent pierre par pierre.

### Aux Confrères
Le réseau qui grandit chaque jour et prouve que l'union fait la force.

---

## 💎 Citations

> *"Lève les yeux vers l'horizon. C'est là que tout change."*  
> — Philosophie DIGIY

> *"L'or était là, sous tes pieds. Mais il fallait la perspective pour le voir."*  
> — Manifeste DIGIY HUB

> *"Ne regarde plus tes pieds. Regarde l'horizon."*  
> — L'écosystème vu d'en haut. Vécu d'en bas.

> *"VAS CHEZ DIGIY"*  
> — La nouvelle expression africaine

---

## 🌍 L'Afrique enracinée, connectée au monde

```
╔═══════════════════════════════════════════╗
║                                           ║
║  DIGIY HUB                                ║
║                                           ║
║  Le grand village qui tourne sur lui-même ║
║  L'argent qui reste entre nous            ║
║  La souveraineté digitale africaine       ║
║                                           ║
║  Notre terroir. Notre village. Notre vie. ║
║                                           ║
║  Pour tout. Par nous. Pour nous.          ║
║                                           ║
║  ∞ VAS CHEZ DIGIY ∞                       ║
║                                           ║
╚═══════════════════════════════════════════╝
```

---

## 🔥 Statistiques du Projet

![GitHub stars](https://img.shields.io/github/stars/beauville/digiylyfe?style=social)
![GitHub forks](https://img.shields.io/github/forks/beauville/digiylyfe?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/beauville/digiylyfe?style=social)

![Contributors](https://img.shields.io/github/contributors/beauville/digiylyfe)
![Last commit](https://img.shields.io/github/last-commit/beauville/digiylyfe)
![Issues](https://img.shields.io/github/issues/beauville/digiylyfe)
![Pull requests](https://img.shields.io/github/issues-pr/beauville/digiylyfe)

---

<div align="center">

### 🦅 Fait avec ❤️ en Afrique

**PIERRE PAR PIERRE, ON CONSTRUIT LE VILLAGE ! 💎**

[⭐ Star ce projet](https://github.com/beauville/digiylyfe) • [🐛 Reporter un bug](https://github.com/beauville/digiylyfe/issues) • [💡 Suggérer une fonctionnalité](https://github.com/beauville/digiylyfe/issues)

---

**∞ DIGIY HUB - L'écosystème vu d'en haut. Vécu d'en bas. ∞**

</div>
