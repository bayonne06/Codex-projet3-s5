# NEON PULSE - Agence Digitale Créative

## 📋 Présentation du Projet

**NEON PULSE** est un site vitrine pour une agence digitale créative spécialisée dans les expériences visuelles futuristes et le gaming. Le projet met en avant les services, le portfolio et l'équipe de l'agence.

**Type** : Site vitrine associatif / ONG  
**Thème** : Agence digitale créative avec focus gaming

---

## 🎯 Fonctionnalités Principales

- **Accueil** - Présentation de l'agence et ses services
- **Portfolio** - Vitrine des projets réalisés
- **Équipe** - Présentation des membres et talents
- **Contact** - Formulaire de contact pour les clients
- **Design Responsive** - Adaptation mobile et tablette
- **Branding Visuel** - Identité NEON PULSE avec palette cyan/futuriste

---

## 🛠️ Stack Technologique

- **HTML5** - Structure sémantique
- **CSS3** - Stylisation avec architecture modulaire
- **JavaScript** - Interactivité (si applicable)
- **Font Awesome 6** - Icônes
- **Google Fonts** - Typographies (Space Grotesk, Hanken Grotesk, JetBrains Mono)

---

## 📁 Structure du Projet

```
projet/
├── index.html          # Page d'accueil
├── home.html           # Alternative page d'accueil
├── portfolio.html      # Portfolio
├── team.html           # Équipe
├── contact.html        # Contact
├── css/
│   ├── main.css        # Imports centralisés
│   ├── variables.css   # Variables CSS
│   ├── reset.css       # Reset CSS
│   ├── components.css  # Composants
│   ├── header.css      # En-tête
│   ├── footer.css      # Pied de page
│   ├── team.css        # Styles équipe
│   ├── responsive.css  # Media queries
│   └── home.css        # Styles spécifiques accueil
├── image/              # Images
└── README.md           # Documentation
```

---

## 👥 Équipe de Développement

**Groupe Name** : The dev

1. **MOUYEDI MBEMBA jzreel Salem** - Lead
2. **Mavoungou Bayonne Précieux** - Repo Admin
3. **Luc Dalland Nkodia De Matsika** - Code Review
4. **Ndongala Dreche** - Collaborateur
5. **Massamba Bouesso Christophe Darly** - Collaborateur

---

## 🚀 Démarrage

### Installation

1. Cloner le repository
```bash
git clone https://github.com/bayonne06/Codex-projet3-s5.git
cd Codex-projet3-s5/projet
```

2. Ouvrir dans un navigateur
```bash
# Option 1 : Ouvrir directement index.html
# Option 2 : Utiliser un serveur local
python -m http.server 8000
# Puis accéder à http://localhost:8000
```

---

## 📝 Architecture CSS

Le projet utilise une architecture CSS modulaire :
- **variables.css** - Variables globales (couleurs, polices)
- **reset.css** - Réinitialisation des styles par défaut
- **components.css** - Composants réutilisables
- **header.css** - Styles de l'en-tête unifié
- **footer.css** - Styles du pied de page
- **team.css** - Styles de la section équipe
- **home.css** - Styles spécifiques à la page d'accueil
- **responsive.css** - Adaptations responsive

---

## 🎨 Design System

**Palette de couleurs** :
- Cyan primaire : `#00ffff`
- Cyan clair : `#14f1ff`
- Fond : `#050505`
- Texte muted : `#bdbdbd`

**Typographies** :
- Headings : Space Grotesk / Orbitron
- Body : Hanken Grotesk / Poppins
- Code : JetBrains Mono

---

## 🔗 Liens

- **Repository GitHub** : https://github.com/bayonne06/Codex-projet3-s5
- **GitHub Pages** : À venir

---

## Gestion des conflits de fusion

Lors de l'intégration des différentes branches de fonctionnalités dans `main`, plusieurs situations ont dû être traitées :

- Divergence de branche (PR #4 — `feature/equipe`) : la branche n'était plus synchronisée avec `main` après de nouveaux commits sur `main`. Nous avons récupéré les changements de `main` localement (`git merge main`) sur la branche, ce qui a permis une fusion automatique sans conflit de code, suivie d'un commit de fusion et d'une Push.

- Historiques divergents (`feat/contact`) : une branche présentait un historique de commits totalement distinct de `main`, probablement introduit par une initialisation locale indépendante. Cette situation nécessite une analyse manuelle et des opérations de réconciliation (rebase/cherry-pick ou intégration via une branche intermédiaire) avant l'intégration.

- Protection de la branche principale : un push direct sur `main` a été refusé par GitHub (règles de protection). Pour résoudre cela, nous avons resynchronisé la branche locale avec la distante (`git reset --hard origin/main`) et conservé les modifications sur une branche dédiée (`fix/home-header`) pour ouvrir une Pull Request propre.

Ces cas montrent l'importance de se synchroniser régulièrement avec la branche distante, d'utiliser des branches dédiées pour chaque fonctionnalité et d'intégrer les changements via des Pull Requests organisées.

---

## 📄 Licence

Licence MIT

Droits d'auteur (c) 2026 The dev - NEON PULSE

Par la présente, toute personne obtenant une copie de ce logiciel et des fichiers de documentation associés (le « Logiciel ») est autorisée à traiter le Logiciel sans restriction, y compris, sans limitation, les droits d'utilisation, de copie, de modification, de fusion, de publication, de distribution, de sous-licence et/ou de vente de copies du Logiciel, et d'autoriser les personnes auxquelles le Logiciel est fourni à le faire, sous réserve des conditions suivantes :

L'avis de droit d'auteur ci-dessus et cet avis de permission doivent être inclus dans toutes les copies ou parties essentielles du Logiciel.

LE LOGICIEL EST FOURNI « TEL QUEL », SANS GARANTIE D'AUCUNE SORTE, EXPRESSE OU IMPLICITE, Y COMPRIS, MAIS SANS S'Y LIMITER, LES GARANTIES DE QUALITÉ MARCHANDE, D'ADÉQUATION À UN USAGE PARTICULIER ET D'ABSENCE DE CONTREFAÇON. EN AUCUN CAS LES AUTEURS OU TITULAIRES DES DROITS D'AUTEUR NE SERONT RESPONSABLES DE TOUTE RÉCLAMATION, DOMMAGE OU AUTRE RESPONSABILITÉ, QUE CE SOIT DANS UN CONTRAT, UN ACTE DÉLICTUEL OU AUTREMENT, DÉCOULANT DE, HORS DE OU EN RAPPORT AVEC LE LOGICIEL OU L'UTILISATION OU D'AUTRES TRAITEMENTS DU LOGICIEL.

---

**Projet scolaire - Codex Projet S5**
