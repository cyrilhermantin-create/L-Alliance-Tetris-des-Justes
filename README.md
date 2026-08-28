# 🎮 L'Alliance — Tetris des Justes

![License](https://img.shields.io/badge/licence-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-e34f26.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-f7df1e.svg)
![Statut](https://img.shields.io/badge/statut-en%20développement-orange.svg)

**L'Alliance — Tetris des Justes** est un jeu de réflexion et d'adresse sur navigateur web qui revisite le gameplay intemporel du *Tetris* à travers un prisme historique et spirituel, de l'Exode aux Évangiles.

Empilez les pièces thématiques (Cultuel, Juridique, Moral, Social), complétez des rangées pour accomplir les commandements de la Torah et des Évangiles, et faites reculer les adversaires historiques qui barrent la route des Justes.

---

## 🌐 Démo en ligne

👉 **[Jouer à L'Alliance](https://cyrilhermantin-create.github.io/L-Alliance-Tetris-des-Justes/)**
*(actif une fois GitHub Pages activé sur le dépôt — voir la section Installation ci-dessous)*

---

## 🧠 Démarche pédagogique & développement

Ce projet **open source et entièrement gratuit** a été réalisé dans un but purement **pédagogique**. Il vise à rendre l'apprentissage et la mémorisation des textes anciens ludiques, interactifs et accessibles à tous à travers des mécaniques de jeu vidéo éprouvées.

L'ensemble du code HTML, CSS et JavaScript a été développé en collaboration avec l'assistant d'intelligence artificielle **Claude (Anthropic)**, sur la base des mécaniques de jeu, de la recherche exégétique et de la direction artistique conçues par l'auteur.

---

## 📜 Travail d'exégèse & sources textuelles

Les idées originales et la structure des commandements intégrés au gameplay sont le fruit d'un travail d'exégèse mené par l'auteur. Le codex du jeu s'appuie sur les sources suivantes :
*   **La Bible Zadok Kahn** (référence principale pour le texte de la Torah)
*   **La Bible Crampon** (référence pour les récits du Nouveau Testament et la nomenclature des dix plaies d'Égypte)
*   Recherches complémentaires de l'auteur sur les enseignements attribués à Yeshoua

> Le décompte des commandements suit une méthodologie propre à l'auteur (regroupement macro-sémantique par blocs), distincte de l'énumération classique des 613 mitsvot du traité Makkot 23b, et unifiant volontairement corpus de la Torah et enseignements des Évangiles. C'est un choix explicite, assumé comme tel — pas une prétention à l'exhaustivité consensuelle entre traditions.

---

## ✍️ Auteur & crédits

*   **Concepteur-auteur et donneur d'ordre :** Cyril HERMANTIN.
*   **Conception des mécaniques de jeu et recherche exégétique :** Cyril HERMANTIN.
*   **Assistance au développement et à la programmation :** Claude (Anthropic)

---

## 🎯 Concept & gameplay

Le jeu fusionne la tension mécanique du puzzle-game et la progression narrative d'un mode campagne en 6 chapitres.

*   **Mécanique centrale :** chaque ligne complétée accomplit un commandement (affiché avec sa référence) et inflige des dégâts à l'adversaire du chapitre. Si la pile déborde, la partie est perdue — sauf si une vie de secours est disponible.
*   **Couleur = catégorie :** chaque pièce est colorée selon la vraie catégorie du commandement qu'elle porte (Cultuel, Juridique, Moral, Social), affichée en légende à l'écran.
*   **Les 6 épreuves (chapitres) :** chacune oppose une figure biblique à son adversaire, avec des étapes nommées et sourcées, et des répliques du boss propres à l'histoire.

    | # | Chapitre | Le Juste | L'adversaire |
    |---|----------|----------|---------------|
    | 1 | L'Exode | Moshé | Pharaon (10 plaies d'Égypte) |
    | 2 | 1 Samuel 17 | David | Goliath |
    | 3 | Pourim | Esther & Mardochée | Haman |
    | 4 | Hanouka | Les Maccabées | Antiochus Épiphane |
    | 5 | Le Jourdain | Yohanan le Baptiseur | Hérode |
    | 6 | La Passion | Yeshoua | Pilate |

*   **Interventions divines (bonus) :** des pièces dorées apparaissent occasionnellement. Complétées, elles déclenchent un miracle inspiré des récits bibliques — l'ouverture de la Mer (efface les rangées adverses), le Rocher (vie de secours), la Manne (bonus de points).
*   **Vies de secours :** jusqu'à 3, gagnées via les miracles. Elles dégagent la pile in extremis plutôt que de mettre fin à la partie sèchement.
*   **Duel local (2 joueurs) :** deux joueurs peuvent affronter le même adversaire à tour de rôle, sur le même appareil, avec un score individuel suivi en plus du score commun.
*   **Codex :** un écran recense les commandements croisés, groupés par catégorie, avec suivi de progression.
*   **Inclusivité & respect :** affichage du Nom divin personnalisable (`YHWH` ou `L'Éternel`) selon la confession et la sensibilité du joueur.
*   **Interface en 14 langues :** français, anglais, espagnol, allemand, néerlandais, portugais, italien, mandarin, russe, arabe, hébreu, créole haïtien, créole mauricien, créole seychellois.

> **Portée linguistique :** seule l'interface (menus, boutons, catégories) est traduite dans les 14 langues. Les textes bibliques du jeu (récits des chapitres, versets, corpus des commandements) restent en français, par souci d'exactitude — une traduction fidèle de contenu scripturaire demande une relecture humaine spécialisée, langue par langue, qui n'a pas encore été menée. Le jeu l'indique lui-même à l'écran.

> **Portée multijoueur :** le mode « duel » est local (même appareil, deux joueurs qui alternent). Il n'y a pas de multijoueur en ligne à ce stade — cela demanderait une infrastructure serveur qui n'existe pas encore pour ce projet.

---

## 🕹️ Commandes du jeu

### 💻 Sur ordinateur
*   `←` / `→` : déplacer la pièce
*   `↑` : tourner la pièce
*   `↓` : descente rapide (soft drop)
*   `Espace` : chute instantanée (hard drop)
*   `P` : pause / reprendre

### 📱 Sur smartphone
*   Cinq boutons tactiles dédiés en bas de l'écran (gauche, tourner, droite, descendre, chute rapide)
*   Glisser le doigt sur le plateau fonctionne aussi (balayage latéral, vers le bas ou vers le haut)

---

## 🛠️ Stack technique

Projet volontairement minimaliste, sans dépendance ni framework, pour une compatibilité maximale :
*   **Structure :** un seul fichier HTML autonome (HTML + CSS + JavaScript)
*   **Rendu du plateau :** grille CSS (`display:grid`), pas de `<canvas>`
*   **Logique de jeu :** JavaScript (Vanilla JS) — moteur Tetris (collision, rotation, gravité), machine à états des chapitres, système de bonus, minuteur d'attaque du boss
*   **Son :** synthétisé en direct via la Web Audio API (aucun fichier audio externe, aucune mélodie existante reproduite)
*   **Données :** objets JavaScript pour le corpus de commandements et le dictionnaire de traduction
*   **Aucune dépendance externe**, à l'exception des polices Google Fonts (Cinzel, Alegreya, Frank Ruhl Libre)

---

## 🚀 Installation et lancement local

Le projet tient dans **un seul fichier HTML**. Aucun outil de build n'est nécessaire.

### Lancer en local
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/cyrilhermantin-create/L-Alliance-Tetris-des-Justes.git
   cd L-Alliance-Tetris-des-Justes
   ```
   — ou téléchargez simplement le fichier `alliance-tetris.html` seul.
2. Double-cliquez dessus, ou ouvrez-le depuis votre navigateur (`Fichier → Ouvrir`).

### Publier sur GitHub Pages
1. Dans le dépôt, renommez `alliance-tetris.html` en `index.html` (ou configurez Pages pour servir ce fichier précisément).
2. Dans **Settings → Pages** du dépôt, activez GitHub Pages sur la branche principale (dossier racine `/`).
3. Le jeu devient accessible à l'adresse ci-dessus, installable en "app" sur mobile via *Ajouter à l'écran d'accueil*.

---

## 🤝 Contribution

Les contributions pour enrichir le codex, traduire les textes bibliques (voir la note sur la portée linguistique ci-dessus), optimiser le gameplay ou améliorer l'interface sont les bienvenues.

1. Forkez le projet.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/ma-fonctionnalite`).
3. Commitez vos changements (`git commit -m "Ajout de ma fonctionnalité"`).
4. Poussez la branche (`git push origin feature/ma-fonctionnalite`).
5. Ouvrez une **Pull Request**.

Une relecture par un locuteur natif est particulièrement bienvenue pour les traductions en créole haïtien, mauricien et seychellois, réalisées de bonne foi mais sans validation par un locuteur natif.

---

## 📄 Licence

Ce projet est distribué sous licence **MIT** — voir le fichier `LICENSE`. Cela signifie concrètement que vous êtes libre d'utiliser, modifier et redistribuer ce code, y compris à des fins commerciales, à condition de conserver la mention de copyright et le texte de la licence.

Un crédit visible vers ce projet original en cas de réutilisation ou d'adaptation est apprécié, sans être une obligation légale distincte de la licence MIT.
