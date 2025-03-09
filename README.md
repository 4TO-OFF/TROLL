# TROLL
Des petit programme de troll innofencif
# Programme de Fenêtre Fuyante et autres programmes de démonstration 💻⚠️

Ce projet comprend plusieurs programmes en C destinés à simuler des comportements interactifs sur un PC, y compris des fenêtres qui fuient, des curseurs incontrôlables, des sons aléatoires, des effets visuels et des simulations de formatage. Chaque programme est conçu pour créer une expérience unique.

## Fonctionnalités 📂

- **`bsod.c`** : Simule l'affichage d'un écran bleu de la mort (BSOD) pour provoquer une réaction rapide. 🖥️
- **`bureau_movant.c`** : Déplace les icônes du bureau à des positions aléatoires. 📁🔄
- **`chaos.c`** : Lancement de plusieurs effets aléatoires sur le système pour créer un chaos général. 💥
- **`clavier_hante.c`** : Prend le contrôle du clavier et tape des lettres aléatoires. ⌨️🎭
- **`curseur_tp.c`** : Déplace le curseur à des positions aléatoires sur l'écran. 🖱️🔀
- **`fake_format.c`** : Simule un formatage du disque avec des messages progressifs, mais sans réel impact. 💾⚠️
- **`fake_hack.c`** : Affiche des messages d'erreur et crée des pop-ups pour simuler un piratage. 🔓💻
- **`fenetre_fuyante.c`** : Crée une fenêtre qui se déplace à des positions aléatoires lorsque le curseur est dessus. 🏃‍♂️💨
- **`pc_quiz.c`** : Contient une commande potentiellement dangereuse (à utiliser uniquement dans un environnement contrôlé et sécurisé). ⚠️💣

**Important** : Le fichier `pc_quiz.c` contient une commande qui peut entraîner des pertes de données ou d'autres risques. Ce fichier n'a pas été compilé par défaut et **ne doit être exécuté que si vous êtes conscient des risques et que vous avez un environnement de test approprié**. 🔴

## ⚠️ ATTENTION ! ⚠️

### **`pc_quiz.c` est dangereux !** 🔥

Ce programme peut exécuter une commande risquée. Bien qu'elle ne soit pas activée par défaut, **si vous choisissez de compiler et d'exécuter ce fichier, assurez-vous de le faire dans un environnement contrôlé et sécurisé** (comme une machine virtuelle ou un autre environnement de test). 🚨

Si vous avez des doutes sur son utilisation, **il est fortement recommandé de ne pas l'exécuter** ! ⚡

---

## Compilation 📋

Le fichier `pc_quiz.c` peut être compilé de la manière suivante si vous souhaitez l'utiliser.

### Compilation avec MinGW ⚙️

1. Téléchargez et installez MinGW.
2. Ouvrez une fenêtre de terminal et naviguez vers le dossier où vous avez enregistré le fichier source.
3. Compilez le fichier `pc_quiz.c` avec la commande suivante :
   ```bash
   gcc -o pc_quiz pc_quiz.c  # Seulement si vous souhaitez compiler pc_quiz.c
