# 🛒 Grocery App - Application de Livraison de Courses

Bienvenue dans **Grocery App**, une application mobile développée en **Flutter** permettant aux utilisateurs de commander des produits d'épicerie en ligne et de les faire livrer à domicile. Cette application est conçue avec une architecture **Clean Architecture + Bloc** pour une meilleure maintenabilité et extensibilité.

---

## 📌 Fonctionnalités Principales

✅ **Authentification** (Inscription, Connexion avec gestion sécurisée des utilisateurs)
✅ **Recherche de produits** par catégories et mots-clés
✅ **Ajout au panier** et gestion des quantités
✅ **Suivi des commandes** en temps réel
✅ **Paiement en ligne sécurisé** (Stripe)
✅ **Notifications push** pour le suivi des commandes
✅ **Intégration de Google Maps** pour la localisation
✅ **Interface utilisateur moderne et fluide**

---

## 📂 Structure du Projet

Le projet suit une architecture **Clean Architecture** bien organisée :

```bash
lib/
│── core/                 # Classes de base (helpers, constantes, etc.)
│── data/                 # Gestion des données (API, repositories, models)
│── domain/               # Cas d'utilisation et logiques métier
│── presentation/         # UI et gestion des états (Bloc, Widgets, Pages)
│── main.dart             # Point d'entrée de l'application
```

---

## 🛠️ Technologies Utilisées

| Technologie      | Description |
|-----------------|-------------|
| Flutter         | Framework de développement mobile |
| Dart            | Langage de programmation |
| REST API        | Communication avec le backend |
| Stripe         | Paiement en ligne sécurisé |
| Bloc           | Gestion d'état avec Bloc |

---

## 🚀 Installation & Configuration

### 📌 Prérequis
Avant d'exécuter l'application, assurez-vous d'avoir installé :
- **Flutter** (dernière version) ➜ [Installation Flutter](https://flutter.dev/docs/get-started/install)
- **Dart SDK** (inclus avec Flutter)

### 🏗 Étapes d'installation

1. **Cloner le projet** :
   ```bash
   git clone https://github.com/ton-repo/grocery-app.git
   cd grocery-app
   ```

2. **Installer les dépendances** :
   ```bash
   flutter pub get
   ```

3. **Configurer les API** :
   - Ajouter les clés API nécessaires dans un fichier de configuration sécurisé (`.env` ou `secrets.dart`)

4. **Lancer l'application** :
   ```bash
   flutter run
   ```

---

## 🎨 Captures d'écran

📌 
<img width="262" alt="image" src="https://github.com/user-attachments/assets/d432bf4c-67b3-4d73-934a-779636736a76" />
<img width="245" alt="image" src="https://github.com/user-attachments/assets/af7e1986-6361-416b-ad28-c012db0ebb55" />
![Screenshot 2025-03-28 111920](https://github.com/user-attachments/assets/a4004c86-8404-4fd1-8f0a-85b853669681)
<img width="245" alt="image" src="https://github.com/user-attachments/assets/b0e6c951-7b70-43b7-ac88-f0c6eb5d4f0e" />
<img width="247" alt="image" src="https://github.com/user-attachments/assets/217f4871-7d18-4361-8d13-1abb58d5ada3" />



---

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :
1. **Fork** le projet 🍴
2. **Crée une branche** (`git checkout -b feature-nom`)
3. **Fais tes modifications** et commit (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`)
4. **Push** la branche (`git push origin feature-nom`)
5. **Ouvre une Pull Request** 🛠

---


📩 **Besoin d'aide ?** Contacte-moi sur [[LinkedIn](https://linkedin.com/in/tonprofil)](https://www.linkedin.com/in/moutawassit-abdelali-98bb95267/) ou crée une issue sur le repo !

🚀 Bon développement ! Happy coding! 🎉

