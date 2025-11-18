# 📧 EAFC-SIGN-Gen

**Générateur de Signature Email Professionnel** - 100% Compatible Gmail & Outlook

Un outil moderne et facile à utiliser pour créer des signatures email professionnelles optimisées pour Gmail, Outlook et tous les principaux clients email.

---

## ✨ Fonctionnalités

- **Prévisualisation en temps réel** : Voyez votre signature se construire au fur et à mesure de la saisie
- **100% Compatible** : Testé et optimisé pour Gmail, Outlook, Apple Mail, et autres
- **Styles inline** : Toutes les règles CSS sont inline pour une compatibilité maximale
- **Polices web-safe** : Utilise Arial et autres polices universelles
- **Responsive** : S'adapte à tous les appareils (desktop, mobile, tablette)
- **Réseaux sociaux** : Intégration facile de LinkedIn, Twitter, Facebook
- **Logo personnalisable** : Ajoutez votre logo avec contrôle de la taille
- **Copie en un clic** : Copiez le HTML formaté directement dans votre presse-papiers

---

## 🚀 Utilisation

### 1. Ouvrir le générateur

Ouvrez simplement le fichier `index.html` dans votre navigateur web préféré (Chrome, Firefox, Safari, Edge).

### 2. Remplir vos informations

Remplissez les champs suivants selon vos besoins :

- Nom complet
- Titre / Poste
- Département
- Nom de l'entreprise
- Téléphone
- Email
- Site web
- LinkedIn, Twitter, Facebook (optionnel)
- URL du logo (optionnel)
- Largeur du logo (ajustable)

### 3. Prévisualiser

La signature se génère automatiquement dans la zone de prévisualisation à droite.

### 4. Copier la signature

Cliquez sur le bouton **"Copier la signature HTML"** pour copier le code HTML dans votre presse-papiers.

### 5. Installer dans votre client email

#### Gmail

1. Ouvrez Gmail
2. Cliquez sur l'icône **⚙️ Paramètres** (en haut à droite)
3. Sélectionnez **"Voir tous les paramètres"**
4. Dans l'onglet **"Général"**, descendez jusqu'à la section **"Signature"**
5. Cliquez sur **"Créer"** pour une nouvelle signature
6. Collez le HTML copié (Ctrl+V ou Cmd+V)
7. Faites défiler vers le bas et cliquez sur **"Enregistrer les modifications"**

#### Outlook (Desktop)

1. Ouvrez Outlook
2. Allez dans **Fichier** → **Options** → **Courrier**
3. Dans la section **"Composer des messages"**, cliquez sur **"Signatures..."**
4. Cliquez sur **"Nouveau"** pour créer une nouvelle signature
5. Collez le HTML copié dans la zone d'édition
6. Cliquez sur **"OK"** pour enregistrer

#### Outlook (Web)

1. Ouvrez Outlook sur le web
2. Cliquez sur **⚙️ Paramètres** → **"Afficher tous les paramètres Outlook"**
3. Sélectionnez **"Composer et répondre"** dans le menu de gauche
4. Dans la section **"Signature électronique"**, collez votre HTML
5. Cliquez sur **"Enregistrer"**

---

## 🎨 Bonnes pratiques suivies

Ce générateur respecte toutes les meilleures pratiques pour garantir une compatibilité maximale :

| Pratique | Description | Statut |
|----------|-------------|--------|
| **Styles inline** | Tous les styles CSS sont appliqués directement dans les balises HTML | ✅ |
| **Tables HTML** | Utilise des tables pour le layout (meilleure compatibilité) | ✅ |
| **Polices web-safe** | Arial, Helvetica, sans-serif (supportées partout) | ✅ |
| **Largeur max 600px** | Respecte la norme de l'industrie pour les emails | ✅ |
| **Images optimisées** | Attributs width et height définis pour toutes les images | ✅ |
| **Pas de JavaScript** | Aucun script dans le HTML de la signature | ✅ |
| **Pas de CSS externe** | Aucune feuille de style externe | ✅ |

---

## 📝 Structure des fichiers

```
EAFC-SIGN-Gen/
├── index.html              # Générateur de signature (principal)
├── Signatures eafc.html    # Version alternative (identique)
├── README.md              # Documentation
└── LICENSE                # Licence du projet
```

---

## 🔧 Personnalisation

### Modifier les couleurs

Les couleurs sont définies dans la fonction `generateSignature()` du fichier `index.html`. Vous pouvez modifier :

- Couleur du nom : `color: #1f2937` (ligne 290)
- Couleur des titres : `color: #4b5563` (lignes 294, 298)
- Couleur des liens : `color: #1a73e8` (lignes 308, 311, 313, 324, 330, 336)

### Modifier la police

Pour changer la police, recherchez `Arial, Helvetica, sans-serif` dans le code et remplacez par une autre police web-safe :

- Georgia, serif
- Times New Roman, Times, serif
- Verdana, sans-serif
- Courier New, Courier, monospace

---

## ⚠️ Limitations connues

- Les GIFs animés peuvent ne pas fonctionner dans certains clients email
- Les images SVG ne sont pas supportées (utilisez PNG ou JPG)
- Outlook peut modifier légèrement les espacements
- Les images externes doivent être hébergées sur un serveur accessible publiquement

---

## 🤝 Contribution

Ce projet a été créé pour l'équipe EAFC TIC. N'hésitez pas à proposer des améliorations ou à signaler des bugs.

---

## 📄 Licence

Voir le fichier `LICENSE` pour plus de détails.

---

## 👨‍💻 Auteur

**Pierre de Dobbeleer** - 2025

Créé avec ❤️ pour l'équipe EAFC TIC
