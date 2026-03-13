# 💾 FLOPPY_1.44Mo

> *Pas un octet de plus.*

Un jeu de société original de **Valentin HEYNE** — © 2026 Le Cartel du Dé pipé

---

## 🎮 Jouer en ligne

👉 **[Lancer l'application](https://floppy.mechkawaii.com/)**

---

## 🕹️ C'est quoi Floppy ?

Chaque joueur gère sa **disquette personnelle (grille 12×12)**. Le but du jeu est d'y enregistrer **exactement 144 fichiers** en les récupérant dans le Dossier commun.

L'application remplace les disquettes physiques : place tes blocs de fichiers dans ta grille comme un Tetris, gère ton espace, et sois le premier à atteindre 1.44 Mo !

---

## 📦 Contenu du jeu physique

- 1 plateau avec les cases système
- 1 Dossier (boîte ouverte) contenant tous les fichiers
- 1 disquette 12×12 par joueur
- Blocs de fichiers : 1, 5 et 10 unités, de différentes formes
- 1 pion par joueur
- 1 dé

---

## 📋 Règles

### Déroulé d'un tour

À son tour, un joueur choisit **UNE** des deux options :

- **MOVE** — Lance le dé, déplace ton pion, applique l'effet de la case, puis prends 1 fichier dans le Dossier et place-le dans ta disquette.
- **MANAGE** — Ne lance pas le dé. Prends 1 fichier dans le Dossier et place-le dans ta disquette. Aucun effet de case n'est appliqué.

> ⚠️ Un joueur ne peut pas choisir MANAGE deux tours consécutifs.

### Contraintes de placement

- On ne peut pas prendre deux fois de suite un bloc de même forme (sauf les blocs de 1 fichier).
- Si un fichier ne peut pas être placé, il est remis dans le Dossier.
- La réorganisation de la disquette n'est possible que sur une case **TOOLS**.
- Un joueur ne peut jamais s'arrêter sur une case occupée — il avance jusqu'à la prochaine case libre.

### Cases du plateau

| Case | Effet |
|------|-------|
| **DATA +1 / +5 / +10** | Prend immédiatement un bloc correspondant dans le Dossier |
| **TOOLS** | Réarranger sa disquette, ou échanger 5×1 → 1×5, ou 2×5 → 1×10 |
| **BOOT** | Supprime la sauvegarde. Peut supprimer 1 fichier de sa disquette |
| **BACKUP** | Active la sauvegarde. Peut copier un fichier déjà présent |
| **PORT** | Gagne un bloc de 10, ou transforme 1×10 en 2×5 |
| **GLITCH** | Supprime un bloc (1, 5 ou 10) de sa disquette |
| **RESET** | Supprime 5 blocs (1, 5 ou 10) de sa disquette |
| **HACK** | Vole un bloc (1, 5 ou 10) à un adversaire |

### DEFRAG.EXE

Une fois par partie, un joueur peut lancer une défragmentation :
- Réorganiser entièrement sa disquette **et** perdre 5 unités de données
- **ou** passer son prochain tour.

### Victoire

Lorsqu'un joueur possède **144 fichiers** sur sa disquette et se situe **entre les cases BACKUP et BOOT**, il remporte immédiatement la partie.

---

## 💻 L'application

L'app web remplace les disquettes physiques du jeu. Elle permet à chaque joueur de :

- Placer ses blocs de fichiers dans une grille 12×12 interactive
- Voir en temps réel son score (Mo enregistrés)
- Gérer le BACKUP et le DEFRAG
- Jouer jusqu'à 6 joueurs en local (onglets par joueur)

### Contrôles

| Action | Contrôle |
|--------|----------|
| Sélectionner une pièce | Clic sur la pièce |
| Placer une pièce | Clic sur la grille |
| Rotation | Bouton ↻ ou touche R |
| Annuler | Bouton ↩ |
| Changer de joueur | Onglets en haut |

---

## 🛠️ Développement local

Aucune dépendance. Ouvre simplement `index.html` dans ton navigateur.

```bash
git clone https://floppy.mechkawaii.com/
cd floppy
open index.html
```

---

## 📄 Licence

© 2026 **Le Cartel du Dé pipé / Valentin HEYNE**
FLOPPY est un jeu de société original. Tous droits réservés.

---

<p align="center">
  <img src="https://img.shields.io/badge/version-1.44Mo-purple?style=flat-square"/>
  <img src="https://img.shields.io/badge/joueurs-4-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/plateforme-web-green?style=flat-square"/>
</p>
