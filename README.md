Voici un **README complet, clair et propre**, adapté à ton projet *Clubs ESPRIT* et conforme aux points demandés.
Tu peux le copier directement dans ton fichier `README.md`.

---

# 📚 Clubs ESPRIT – README

## 👥 **Membres de l’équipe & Responsabilités**

| Nom                   | Responsabilités                                                                                                                              |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| **Hana Harraghi**     | Développement des pages *Club*, *My Club*, *Calendar*, *Home*, *Login*. Intégration responsive et cohérence du design Cosmo Spirit.          |
| **Houssem Chaouachi** | Co-développement des pages *Club*, *My Club*, *Calendar*, *Home*, *Login*. Mise en place de la logique de navigation et de state management. |
| **Ilef Ben Taleb**    | Développement des pages *Competition*, *Profile*, *Events*. Intégration des interactions et composants UI/UX.                                |
| **Arwa Ben Amar**     | Développement des pages *Competition*, *Profile*, *Events*. Amélioration de l’accessibilité et animations UI.                                |

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

### ✔️ **1. Cloner le projet**

```bash
git clone https://github.com/username/club-esprit.git
cd club-esprit
```

### ✔️ **2. Installer les dépendances**

Si vous utilisez **npm** :

```bash
npm install
```

Ou **yarn** :

```bash
yarn install
```

### ✔️ **3. Lancer le serveur de développement**

```bash
npm run dev
```



### ✔️ **4. Technologies utilisées**

* Framework : **React / Next.js** (ou autre selon ton projet)
* Style : **TailwindCSS**, Material Design 3
* Icons : **Lucide / Material Icons**
* State management : **Context / Redux / Zustand**
* UI animations : CSS transitions / Framer Motion

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

### 🔹 1. **Manque de cohérence visuelle entre les pages**

**Solution :**

* Mise en place du *Cosmo Spirit Design System*
* Palette définie
* Composants réutilisables (Card, Button, Badge, Input, etc.)

---

### 🔹 2. **Problèmes de responsive sur mobile et tablette**

**Solution :**

* Mise en place de breakpoints Tailwind
* Utilisation d’un layout en grilles responsive
* Tests sur plusieurs tailles d’écran

---

### 🔹 3. **Filtrage des clubs non fonctionnel**

**Solution :**

* Optimisation de la logique des filtres
* Implémentation d’un tri server-side ou client-side efficace

---

### 🔹 4. **Intégration du chat (Messenger intégré)**

**Problème:** Fenêtre de chat qui s’affichait mal sur mobile
**Solution:**

* Création d’un composant modal glissant verticalement
* Animation "slide-up" + repositionnement fixe en bas
* Optimisation de l’UI minimaliste

---

### 🔹 5. **Performance du rendu de la grille de clubs**

**Solution :**

* Pagination ou lazy loading
* Optimisation des images (logos)
* Memorisation des composants (React.memo)

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



---

## 📱 **Responsive Prototype**

Supports :

* 🖥️ Desktop (1440px)
* 📱 Mobile (375px)
* 📟 Tablet (768px)

---


