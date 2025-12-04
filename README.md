

# 📚 Clubs ESPRIT – README

## 👥 **Membres de l’équipe & Responsabilités**
| Nom                   | Responsabilités                                                                                      |
| --------------------- | ---------------------------------------------------------------------------------------------------- |
| **Hana Harraghi**     | Pages *Club*, *My Club*, *Calendar*, *Home*, *Login*. Intégration Tailwind + design Cosmo Spirit.Navigation et logique JS.    |
| **Houssem Chaouachi** |Pages *Club*, *My Club*, *Calendar*, *Home*, *Login*. Intégration Tailwind + design Cosmo Spirit.Navigation et logique JS. |
| **Ilef Ben Taleb**    | Pages *Competition*, *Profile*, *Events*. UI/UX, interactions JS.                                    |
| **Arwa Ben Amar**     | Pages *Competition*, *Profile*, *Events*. Accessibilité, animations CSS/JS.                          |




---

## 🚀 **Description du Projet**


Le projet Clubs ESPRIT est une plateforme web qui permet aux étudiants d’explorer, rejoindre et suivre les clubs universitaires.
Elle adopte une identité visuelle Cosmo Spirit avec un style moderne, énergique et chaleureux.

Fonctionnalités principales :

🔍 Recherche avancée + filtres par catégories

🏫 Page Clubs avec cartes interactives

📅 Calendrier des activités et événements

🏆 Classement des clubs les plus actifs

💬 Messenger intégré avec mini fenêtre flottante

👤 Profils détaillés des clubs

❤️ Système de favoris & adhésion

🎥 Watch Live → possibilité de suivre certains événements en direct (lives, compétitions, conférences)

📱 Responsive complet (Mobile, Tablet, Desktop)

<img width="1024" height="1024" alt="club" src="https://github.com/user-attachments/assets/47f7c030-9816-4006-8c63-5d774c744a74" />

---


## 🛠️ **Instructions pour exécuter le projet**
Aucune installation nécessaire 👇

### ✔️ **1. Ouvrir le projet

```bash
index.html
t
```

### ✔️**2. Lancer un petit serveur local (optionnel mais recommandé)

Si vous utilisez **npm** :

```bash
npx serve
# ou
live-server

```
Puis accéder à :
👉 http://localhost:3000 (selon l’outil)





### 🧱 **4. Technologies utilisées**

###✔️ Frontend
HTML5

TailwindCSS

JavaScript (Vanilla JS)

###✔️ Design
Palette Cosmo Spirit

Material Design 3 inspiration

Animations CSS & JS (no frameworks)

###✔️ Outils
VS Code

Live Server / Serve

Git & GitHub

---

## 🧩 **Architecture des pages principales**

### 📌 Hana & Houssem

* **Page Home** – Présentation, highlights, CTA
* **Page Clubs** – Recherche, filtres, classement, cartes
* **Page My Club** – Clubs rejoints + interactions
* **Page Calendar** – Événements futurs
* **Page Login** – Authentification

### 📌 Ilef & Arwa

* **Page Profile** – Infos de l’utilisateur / club
* **Page Competition** – Liste + détails
* **Page Events** – Événements à venir / live

---

## 🧠 **Problèmes rencontrés & Solutions apportées**

### 🔹 1. **Organisation des fichiers**

**Solution :**

*  structure /pages, /assets, /js.

---

### 🔹 2. **Responsive complexe avec beaucoup de cartes**

**Solution :**

* Grid Tailwind + breakpoints.

---

### 🔹 3. **odal du profil de club mal centrée**

**Solution :**

* fixed + flex + backdrop blur.

---

### 🔹 4. **Messenger popup**


**Solution:**

*  JS toggle + animation scale.

---

### 🔹 5. **Hover & Glow Cosmo Spirit**

**Solution :**

* Tailwind + transition + shadow + scale.

---

## 🎨 **Palette Cosmo Spirit**


| Rôle           | Couleur                       | HEX                    |
| -------------- | ----------------------------- | ---------------------- |
| **Primary**    | Rouge foncé                   | `#6F1425`              |
| **Secondary**  | Jaune vif                     | `#FECB10`              |
| **Accent**     | Noir                          | `#000000`              |
| **Background** | Rouge foncé (7% transparency) | `#6F1425 (opacity 7%)` |

Note : Pour le background semi-transparent, tu peux utiliser :
en Tailwind → bg-[#6F1425]/[0.07]
```bash

<div class="bg-[#6F1425]/[0.07]">
```


---

## 📱 **Responsive Prototype**

Supports :

* 🖥️ Desktop (1440px)
* 📱 Mobile (375px)
* 📟 Tablet (768px)

---


