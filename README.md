# 🧋 Boba Panic

Une mini-usine kawaii de bubble tea, jouable dans le navigateur sur PC et sur téléphone.

**▶ Jouer : https://nihirii.github.io/boba-panic/**

Un client passe commande, le gobelet avance sur le tapis roulant et tu le prépares poste par poste : base, sirop, toppings, opercule, puis service. Les recettes peuvent être délicieuses… ou franchement dégueu (chocolat-cornichon, lait fraise aux perles wasabi, thé noir à l'ail).

## Modes

- **☁️ Tranquille** : 8 commandes sans chrono, avec un retour immédiat et la possibilité de corriger.
- **⏱️ Rush** : la file s'impatiente, le verdict tombe quand le client reçoit son verre.
- **🧪 Labo** : mélange tout librement. Le client goûte, donne une note et réagit à la recette.

## Commandes

- Souris ou toucher : un appui sur un ingrédient le verse, puis le tapis avance.
- Clavier : touches **1 à 7** pour choisir, **Entrée** pour l'action principale (Sans sirop, Terminer les toppings, Servir), **−** pour retirer une dose de topping.

## Secrets

22 secrets sont cachés dans l'usine : recettes secrètes, réactions de clients et interactions avec le décor. Le carnet 📖 garde la trace des découvertes et propose des indices. La progression et les records sont enregistrés dans le navigateur (`localStorage`).

## Technique

Un seul fichier `index.html` autonome : HTML, CSS et JavaScript, sans dépendance. Les sons sont générés avec la Web Audio API.
