# ⚡ BadUSB - Payload Builder

**BadUSB - Payload Builder** est un environnement de développement web moderne, fluide et ergonomique conçu pour simplifier la conception, l'apprentissage et le déploiement de scripts **DuckyScript**. 

Développé avec une interface graphique immersive inspirée de l'univers de la cybersécurité, cet outil s'adresse aussi bien aux professionnels de la sécurité offensive pour leurs audits de test d'intrusion, qu'aux étudiants souhaitant décortiquer la mécanique des attaques par injection de touches (Keystroke Injection).

---

## ✨ Fonctionnalités Avancées

* 🚀 **Générateur & Éditeur de Script Réel :** Concevez vos payloads à l'aide d'un panneau d'injection rapide ou écrivez directement votre code avec une sauvegarde locale automatique en temps réel (`localStorage`).
* 📚 **Librairie de Scripts & Templates :** Accédez à un catalogue intégré de templates pré-configurés pour vos scénarios d'audit courants (Reconnaissance rapide, ouverture de reverse shell, extraction de données, etc.).
* 🛡️ **Matrice de Compatibilité par Modèle :** Vérifiez en un coup d'œil si vos commandes ou vos scripts sont compatibles avec le matériel à votre disposition :
  * Hak5 USB Rubber Ducky (v1 & v2 et le v3)
  * Flipper Zero
  * M5StickC / M5Stack (avec firmware HID)
  * Digispark ATTiny85
  * Raspberry Pi Pico / Arduino Pro Micro
* 🔍 **Analyseur Pas-à-Pas (Payload Deconstruction) :** Visualisez et comprenez le déroulement exact de chaque payload. L'outil découpe le script ligne par ligne pour expliquer l'impact de chaque commande (`DELAY`, `STRING`, `GUI r`) sur le système cible.
* 💾 **Gestion des Fichiers & Export :** Fonctions intégrées pour **Copier** dans le presse-papiers, **Télécharger** directement le script au format `.txt` standard, ou **Importer** vos propres créations existantes.

---

## 🎨 Design & Ergonomie

Fidèle aux exigences visuelles les plus modernes, l'application intègre :
* Une interface **Dark Mode** profonde avec des auras lumineuses rouge dynamiques (Neon Glow).
* Des composants aux **coins ultra-arrondis** (`border-radius`) pour un rendu "capsule" épuré.
* Un **smoothing de précision** sur les animations de survol, le défilement et le rendu des polices typographiques (`JetBrains Mono`).

---

## 🚀 Installation & Déploiement

Ce projet est entièrement **front-end** (développé en HTML/CSS/JavaScript). Il est autonome et ne nécessite aucune base de données ni serveur lourd.

1. Clonez le dépôt sur votre machine :
   ```bash
   git clone github.com
   ```
2. Ouvrez simplement le fichier `index.html` dans votre navigateur internet moderne préféré.

---

## 🔒 Clause de non-responsabilité (Disclaimer)

Cet outil est développé et mis à disposition **uniquement à des fins d'éducation**, de recherche en sécurité et de tests d'intrusion dûment autorisés par écrit (Ethical Hacking / Pentesting). L'auteur décline toute responsabilité quant à un usage malveillant ou destructeur du logiciel. L'utilisateur est seul responsable du respect des lois en vigueur dans sa juridiction.
