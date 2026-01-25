<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=60A5FA&center=true&vCenter=true&width=440&lines=t-+Salut%2C+je+suis+Silver+%F0%9F%91%8B;D%C3%A9veloppeur+Junior;Passionn%C3%A9+de+S%C3%A9curit%C3%A9" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</p>

<div align="center">
  
  ![Status](https://img.shields.io/badge/statut-42_SCHOOL-3B82F6?style=for-the-badge)
  ![Focus](https://img.shields.io/badge/focus-s%C3%A9curit%C3%A9-1E40AF?style=for-the-badge)
  
</div>

---

<img align="right" alt="Coding" width="300" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif">

### À propos

Actuellement en formation pour intégrer l'**École 42** (Piscine en septembre 2025 → Retry Piscine 2026) 

**Mes centres d'intérêt :**
- 🔒 Cybersécurité & Ethical Hacking
- 🐧 Systèmes Linux & Programmation Bas Niveau
- 🔐 Création d'outils sécurisés et respectueux de la vie privée
- 📟 Création de CLI (mini games / outils tout types)


---

### 🛠️ Stack & Outils

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Vim](https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![OSINT](https://img.shields.io/badge/OSINT-FF6B6B?style=for-the-badge&logo=searchengineland&logoColor=white)
![CSINT](https://img.shields.io/badge/CSINT-4ECDC4?style=for-the-badge&logo=hackthebox&logoColor=white)

</div>

---

### 📦 Projets Python

<details>
<summary><b>🔐 PASSWORLD v2</b> - Gestionnaire de Mots de Passe (En développement)</summary>

<br>

**📊 Avancement du projet**

![Progression](https://img.shields.io/badge/Progression-25%25-orange?style=for-the-badge)

```
████████████████████░░░░░░░░░░░░░░░░ 50%
```

**🎯 Objectif**

Créer un gestionnaire de mots de passe sécurisé en ligne de commande, développé en Python. Ce projet est une refonte complète de la v1 pour apprendre à structurer une application avec la POO, comprendre les bases du chiffrement et créer un outil fonctionnel pour gérer mes mots de passe en local.

**✨ Fonctionnalités**

- ✅ Système de connexion avec mot de passe maître
- ✅ Ajouter / modifier / supprimer des mots de passe
- ✅ Recherche par nom
- ✅ Générateur de mots de passe personnalisable
- 🚧 Chiffrement des données (XOR + Base64)
- 🚧 Sauvegarde en JSON
- 📋 Interface CLI améliorée (à venir)

**🏗️ Architecture POO**

| Classe | Rôle |
|--------|------|
| `Password` | Représente un mot de passe (nom, mdp, url, notes, dates) |
| `User` | Représente un utilisateur (pseudo, mot de passe maître) |
| `PasswordManager` | Gère les mots de passe (ajout, modif, suppression, sauvegarde) |
| `Validator` | Vérifie la solidité des mots de passe |
| `Generator` | Génère des mots de passe aléatoires |
| `Crypto` | Chiffre et déchiffre les données |
| `App` | Gère l'interface en ligne de commande |

**🛠️ Technologies**

![Python](https://img.shields.io/badge/Python_3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)
![Chiffrement](https://img.shields.io/badge/XOR_+_Base64-FF6B6B?style=flat-square)

**📂 Lien GitHub** → [PASSWORLD v2](https://github.com/silverfish000/passworld-v2)

---

</details>

<details>
<summary><b>🔓 PASSWORD v1</b> - Version Initiale (Projet de référence)</summary>

<br>

**📊 Statut**

![Statut](https://img.shields.io/badge/Statut-Termin%C3%A9-success?style=for-the-badge)

**🎯 Objectif**

Premier système de gestion de mots de passe en Python avec stockage local. Ce projet correspond à mes débuts en développement et est volontairement laissé imparfait afin de servir de référence pour mesurer mon évolution à travers les versions futures.

**⚠️ Caractéristiques**

- ✅ Système basique d'ajout/suppression de mots de passe
- ❌ Pas de chiffrement (stockage en clair)
- ❌ Pas d'architecture POO
- ❌ Interface CLI minimaliste

**📈 Évolution v1 → v2**

| Aspect | v1 | v2 |
|--------|----|----|
| Architecture | Procédurale | POO (7 classes) |
| Sécurité | ❌ Aucune | ✅ Chiffrement XOR + Base64 |
| Interface | Basique | CLI intuitive |
| Validation | ❌ Non | ✅ Validator |
| Génération | ❌ Non | ✅ Generator personnalisable |

**🛠️ Technologies**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Basique](https://img.shields.io/badge/Projet_Basique-gray?style=flat-square)

**📂 Lien GitHub** → [PASSWORD v1](https://github.com/silverfish000/projet-n1)

---

</details>

<div align="center">
<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYmg1NWhwZDB0aGRueHNvZW93dGpzcWozeGJoaWh5OHVrZTBlc3lqZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3wr2cnwlghNomDeN9W/giphy.gif" width="300">
</div>

---

### 📊 Statistiques GitHub

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=silverfish000&theme=react-dark&hide_border=true&bg_color=0d1117&color=60A5FA&line=3B82F6&point=93C5FD&area=true&area_color=1E40AF"/>
</div>

---

### 🌐 Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-silverfish000-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/silverfish000)
[![Discord](https://img.shields.io/badge/Discord-silver000__0__-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discordapp.com/users/silver000_0_)
[![Dev.to](https://img.shields.io/badge/dev.to-silver__0__-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/silver_0_)
[![CodinGame](https://img.shields.io/badge/CodinGame-Silver000-F2BB13?style=for-the-badge&logo=codingame&logoColor=black)](https://www.codingame.com/profile/58d9710057d474c5fa5b81ac2c2756a83562207)

</div>

---

<div align="center">
  
  ![Profile Views](https://komarev.com/ghpvc/?username=silverfish000&color=3B82F6&style=for-the-badge)
  
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E40AF,50:3B82F6,100:60A5FA&height=100&section=footer"/>
  
</div>
