# 📚 ESPRIM Virtual Library

> Plateforme web sécurisée de gestion documentaire pour les rapports de **Projet de Fin d'Études (PFE)** de l'École Supérieure Privée d'Ingénieurs de Monastir (ESPRIM).

![Version](https://img.shields.io/badge/version-2.1.0-red)
![Année académique](https://img.shields.io/badge/ann%C3%A9e-2025--2026-blue)

---

## 📖 Présentation

**ESPRIM Virtual Library** centralise tout le cycle de vie d'un rapport de PFE :

- l'**étudiant** soumet son rapport via un formulaire guidé en 3 étapes ;
- l'**enseignant encadrant** le relit, le commente et le valide à l'aide d'une checklist ;
- les rapports validés alimentent une **bibliothèque** consultable par la communauté.

## ✨ Fonctionnalités

### 🔐 Authentification
- Connexion avec l'adresse email institutionnelle
- Création automatique du profil à la première connexion
- **Authentification à deux facteurs (2FA / TOTP)** obligatoire pour les enseignants (Google Authenticator, Microsoft Authenticator, Authy…)
- Gestion multi-rôles (étudiant, enseignant)

### 🎓 Espace étudiant
- Soumission de rapport en 3 étapes : métadonnées → fichier → vérification
- Sauvegarde automatique toutes les 2 minutes, brouillons conservés 30 jours
- Dépôt de fichier PDF par glisser-déposer (50 Mo max)
- Checklist de vérification finale avant soumission
- Choix de la visibilité : consultation publique ou rapport confidentiel

### 👨‍🏫 Espace enseignant
- Tableau de bord avec statistiques (assignés, en attente, validés, rejetés)
- Notifications pour les nouveaux rapports à valider
- Visionneuse PDF intégrée
- Liste de validation détaillée (standards académiques, mise en forme, qualité du contenu)
- Commentaires typés : commentaire, révision requise, approbation, note interne
- Actions : **valider**, **demander une révision** ou **rejeter**, avec notification de l'étudiant par email

### 🏛️ Bibliothèque
- Catalogue des rapports validés
- Recherche par titre, mots-clés, auteur ou résumé
- Filtres avancés et tri
- Favoris, partage, compteurs de vues et de téléchargements

---

## 📸 Aperçu de l'application

### Connexion

![Page de connexion](docs/screenshots/01-connexion.png)

### Authentification à deux facteurs (enseignants)

| Vérification du code | Configuration de l'authentificateur |
|:---:|:---:|
| ![Vérification 2FA](docs/screenshots/02-2fa-verification.png) | ![Configuration 2FA](docs/screenshots/03-2fa-configuration.png) |

### Espace enseignant

**Tableau de bord**

![Tableau de bord enseignant](docs/screenshots/04-dashboard-enseignant.png)

**Notifications et visionneuse PDF**

![Notifications et visionneuse PDF](docs/screenshots/05-notifications-visionneuse-pdf.png)

**Checklist de validation et commentaires**

![Checklist et commentaires](docs/screenshots/06-checklist-commentaires.png)

**Validation d'un rapport**

![Validation d'un rapport](docs/screenshots/07-validation-rapport.png)

### Bibliothèque

![Catalogue de la bibliothèque](docs/screenshots/08-bibliotheque.png)

### Espace étudiant : soumission d'un rapport

**Étape 1 : Métadonnées**

![Soumission - métadonnées](docs/screenshots/09-soumission-metadonnees.png)

**Étape 2 : Fichier**

![Soumission - fichier](docs/screenshots/10-soumission-fichier.png)

**Étape 3 : Vérification**

![Soumission - vérification](docs/screenshots/11-soumission-verification.png)

---

## 🛠️ Technologies

<!-- À COMPLÉTER avec ta stack réelle -->

| Couche | Technologie |
|---|---|
| Frontend | _à compléter_ |
| Backend | _à compléter_ |
| Base de données | _à compléter_ |
| Authentification | JWT + 2FA TOTP _(à confirmer)_ |

## 🚀 Installation

<!-- À ADAPTER à ton projet -->

```bash
# 1. Cloner le dépôt
git clone https://github.com/<ton-utilisateur>/<ton-depot>.git
cd <ton-depot>

# 2. Installer les dépendances
npm install

# 3. Configurer l'environnement
cp .env.example .env

# 4. Lancer l'application
npm run dev
```

## 📁 Structure du projet

```
.
├── docs/
│   └── screenshots/   # Captures d'écran du README
├── src/               # Code source
└── README.md
```

## 👤 Auteur

**<Ton nom>**, ESPRIM, année académique 2025-2026
[GitHub](https://github.com/<ton-utilisateur>) · [LinkedIn](https://linkedin.com/in/<ton-profil>)

## 📄 Licence

À définir (par exemple MIT).
