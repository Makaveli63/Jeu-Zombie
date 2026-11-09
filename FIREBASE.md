# Activer le classement en ligne (Firebase, gratuit)

1. Va sur https://console.firebase.google.com et connecte-toi avec ton compte Google.
2. **Créer un projet** → nom : `pont-des-morts` → désactive Google Analytics → **Créer le projet**.
3. Menu **Créer** (Build) → **Authentication** → **Commencer** → onglet *Mode de connexion* → **Anonyme** → active-le → **Enregistrer**.
4. Toujours dans Authentication → onglet **Paramètres** → **Domaines autorisés** → **Ajouter un domaine** → `makaveli63.github.io`.
5. Menu **Créer** → **Firestore Database** → **Créer une base de données** → emplacement `eur3 (europe-west)` → **mode production** → **Créer**.
6. Dans Firestore, onglet **Règles** : efface tout, colle le contenu du fichier `firestore.rules` de ce dépôt, puis **Publier**.
7. Roue dentée (en haut à gauche) → **Paramètres du projet** → en bas *Vos applications* → icône **Web `</>`** → surnom `jeu` → **Enregistrer l'application**.
8. Copie le bloc `const firebaseConfig = { ... }` affiché et envoie-le à Claude (ces valeurs ne sont pas secrètes : elles identifient seulement le projet).
