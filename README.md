# 🛠️ Discord Quest DevTools

**English:** This repository provides a guide to re-enable Discord's Inspector (DevTools) and includes a script to automate Discord Quests. The documentation below is in French.

**Français :** Ce dépôt explique comment réactiver l'inspecteur Discord et automatiser vos quêtes via un script.

---

## 🚀 Activation des DevTools

Pour utiliser le script, vous devez d'abord pouvoir ouvrir la console Discord.

### Via l'application Bureau (obligatoire !)

1. Fermez Discord.
2. Allez dans `%appdata%/discord/settings.json`. (vous pouver coller l'URL dans la barre de recherche fichier)
3. Ajoutez cette ligne au fichier (en rajoutant une virgule a la ligne d'avent):
```json
"DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true

```


4. Relancez Discord et utilisez `Ctrl + Shift + I`.

---

## 📜 Script d'automatisation (quest-script.js)

Ce script détecte automatiquement votre quête en cours et simule l'activité nécessaire (Stream, Jeu, Vidéo) pour la valider sans avoir à installer ou lancer le jeu réel.

### Comment l'utiliser ?

1. Copiez l'intégralité du code ci-dessous.
2. Ouvrez la **Console** dans l'inspecteur Discord.
3. Si Discord affiche un avertissement, tapez `allow pasting` et appuyez sur Entrée.
4. Collez le script et appuyez sur **Entrée**.

<b>le script (quest-script.js)</b>

```javascript

aller voir le code ici
https://gist.github.com/aamiaa/204cd9d42013ded9faf646fae7f89fbb

```

---

## ⚠️ Sécurité & Responsabilité

> [!CAUTION]
> **AUTO-HACK (SELF-XSS) :** Ne collez jamais de code dont vous ne comprenez pas le fonctionnement. Des personnes malveillantes peuvent voler votre **Discord Token** et accéder à vos messages, serveurs et informations de paiement.

* **Confidentialité :** Ne partagez jamais de captures d'écran de l'onglet `Network` (Réseau).
* **Bannissement :** Bien que ce script soit discret, l'utilisation de méthodes d'automatisation est techniquement contre les ToS de Discord. Utilisez-le à vos propres risques.

---

Voici la section à ajouter à ton fichier pour respecter la source originale et remercier l'auteur. Tu peux l'insérer juste après la section **Script d'automatisation** ou avant la **Licence**.

---

## 🔗 Crédits & Source originale

Le script utilisé dans ce dépôt n'est pas de moi. Il provient du travail de **aamiaa** et est disponible sur ce Gist :

📌 **Source :** [Gist GitHub - aamiaa/discord-quest.js](https://gist.github.com/aamiaa/204cd9d42013ded9faf646fae7f89fbb)

Un grand merci à l'auteur original pour la maintenance et la mise à jour régulière des méthodes d'injection Webpack.


PS: 
il est juste mieux expliqué et Synthétiser en francais.
---

## ⚖️ Licence

Ce projet est distribué à des fins éducatives uniquement.
