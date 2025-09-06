# 📬 Application de messagerie (Prototype Qt6)

## 📖 Présentation
Cette application est un **prototype d’interface de messagerie** développé en **C++ avec Qt6**.  
L’objectif est de fournir un client bien réfléchi à la base avec :
- les **interfaces graphiques** (Qt Widgets),
- la **gestion d’événements** (signaux/slots),
- et une architecture de qualité pour un client de messagerie.

⚠️ **Note** : il s’agit pour l’instant d’une application de démonstration, sans backend réseau ni authentification.

---

## 🛠️ Technologies utilisées
- **C++23** → langage principal.
- **Qt 6 (QtCore, QtGui, QtWidgets)** → gestion de l’interface utilisateur.
- **CMake** → système de build (intégré à CLion).
- **CLion** → IDE recommandé, mais tout IDE compatible CMake peut être utilisé.

---

## 👩‍💻 Pré-requis pour les développeurs

### 1. Compilateur
- Un compilateur C++ **compatible C++23**
- La version 6.9.2 au minimum d'installé et informée dans le CMake PREFIX_PATH