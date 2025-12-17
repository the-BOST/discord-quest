Voici une proposition pour un **README.md** professionnel, clair et bien structuré pour votre projet GitHub.

---

# 🛠️ Discord Quest DevTools

Ce dépôt explique comment réactiver les outils de développement (Inspecteur Web) dans l'application Discord de bureau pour faciliter le débogage ou l'automatisation liée aux "Quests".

---

## 🚀 Activation des DevTools

Il existe deux méthodes principales pour accéder à la console Discord :

### 1. Utilisation du Navigateur

La solution la plus simple reste d'ouvrir Discord via votre navigateur (Chrome, Firefox, Edge, etc.). Vous pouvez alors utiliser le raccourci classique `F12` ou `Ctrl + Shift + I`.

### 2. Application Bureau (Mode "Dangerous")

Pour activer l'inspecteur directement sur l'application installée sur votre ordinateur, suivez ces étapes :

1. Fermez complètement Discord.
2. Rendez-vous dans le dossier de configuration : `%appdata%/discord/`.
3. Ouvrez le fichier `settings.json` avec un éditeur de texte (Notepad++, VS Code, etc.).
4. Ajoutez la ligne suivante à l'intérieur du bloc JSON :

```json
"DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true

```

5. Enregistrez le fichier et relancez Discord. Vous pouvez maintenant utiliser `Ctrl + Shift + I`.

---

## ⚠️ Avertissements de Sécurité (Disclaimer)

L'accès à la console de développement donne un contrôle total sur votre instance Discord. **Lisez attentivement ce qui suit :**

> [!CAUTION]
> **La prudence est de mise.** Une mauvaise manipulation peut entraîner la perte définitive de votre compte.

* **Ne collez jamais de code inconnu :** Ne copiez/collez jamais de scripts envoyés par d'autres personnes dans votre console. Ces scripts (souvent appelés "Self-bots" ou "Token grabbers") peuvent compromettre votre compte et même infecter votre ordinateur.
* **Confidentialité des captures d'écran :** Ne partagez jamais de captures d'écran de votre inspecteur web, en particulier l'onglet **Réseau (Network)** ou les **Requêtes**.
* **Données Sensibles :** Vos identifiants de session (Tokens) sont visibles dans ces outils. Si quelqu'un obtient ces informations, il peut se connecter à votre compte sans avoir besoin de votre mot de passe ni de votre double authentification (2FA).

---

## ⚖️ Licence

Ce projet est purement éducatif. L'utilisateur est seul responsable de l'utilisation qu'il fait de ces informations.

---

Souhaitez-vous que j'ajoute une section spécifique sur la manière de trouver les requêtes liées aux Quests une fois la console ouverte ?
