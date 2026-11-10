# Jouer à cette version de Beyond All Reason

Cette page explique comment installer le jeu, même si vous n’avez jamais installé de programme vous-même.

Cette version est le jeu [Beyond All Reason](https://www.beyondallreason.info/), avec un changement : les petits raptors « brood » qui courent au sol, et les tourelles « brood », n’apparaissent plus. Les bombardiers et l’artillerie brood sont toujours là.

Ce dossier n’est pas un programme à double-cliquer. Il faut d’abord installer le jeu normal. Ensuite, on ajoute cette version à côté.

Prévoyez du temps et de la place sur le disque. Le téléchargement pèse plusieurs gigaoctets.

---

## Français

### 1. Installer le jeu normal

1. Ouvrez cette page dans votre navigateur : [https://www.beyondallreason.info/download](https://www.beyondallreason.info/download)
2. Téléchargez le jeu pour votre ordinateur (Windows ou Linux).
3. Lancez le fichier téléchargé et suivez les boutons jusqu’à la fin.
4. Ouvrez **Beyond All Reason**. Laissez-le finir ses téléchargements s’il en demande.
5. Quand le petit programme d’accueil est ouvert, cliquez sur le bouton **Open install directory**.  
   Une fenêtre de dossiers s’ouvre. C’est le bon endroit. Laissez cette fenêtre ouverte.

Vous n’avez pas besoin de chercher ce dossier à la main.

### 2. Créer un fichier vide nommé devmode.txt

Ce fichier dit au jeu : « j’ai une version spéciale, propose-la-moi ».

**Sur Windows**

1. Dans la fenêtre ouverte à l’étape précédente, cliquez sur **Affichage**.
2. Cochez **Extensions de noms de fichiers**.  
   Sans cette case, Windows cache la fin du nom et le fichier ne marchera pas.
3. Cliquez droit sur un endroit vide de la fenêtre.
4. Choisissez **Nouveau**, puis **Document texte**.
5. Nommez-le exactement :

   `devmode.txt`

6. Validez. Si Windows demande « Voulez-vous changer l’extension ? », cliquez sur **Oui**.
7. Le fichier doit rester vide. S’il s’ouvre, fermez-le sans rien écrire.

Le nom correct est `devmode.txt`.  
`devmode.txt.txt` ne fonctionne pas.

**Sur Linux**

1. Dans la fenêtre de dossiers, cliquez droit sur un endroit vide.
2. Choisissez **Nouveau fichier vide**, ou l’entrée équivalente de votre système.
3. Nommez-le exactement `devmode.txt`.
4. N’écrivez rien dedans.

### 3. Télécharger cette version du jeu

1. Ouvrez cette adresse :  
   [https://github.com/ECprx77/BAR_without-raptor-turrets-and-lswarmer/archive/refs/heads/game.zip](https://github.com/ECprx77/BAR_without-raptor-turrets-and-lswarmer/archive/refs/heads/game.zip)
2. Le navigateur télécharge un gros fichier ZIP. Attendez qu’il soit vraiment terminé.
3. Ouvrez le ZIP et choisissez **Extraire tout** (Windows) ou **Extraire** (Linux).
4. Vous obtenez un dossier au nom long, qui ressemble à `BAR_without-raptor-turrets-and-lswarmer-game`.
5. Renommez ce dossier. Le nouveau nom doit être exactement :

   `BAR.sdd`

   Avec les majuscules `BAR`, un point, puis `sdd` en minuscules.

6. Ouvrez `BAR.sdd`. Vous devez voir un fichier nommé `modinfo.lua`.  
   S’il n’est pas là, vous avez renommé le mauvais dossier : recommencez l’extraction.

### 4. Mettre le dossier au bon endroit

1. Retournez dans la fenêtre ouverte par **Open install directory**.
2. Cherchez un dossier nommé `games`.
3. S’il n’existe pas : clic droit, **Nouveau dossier**, et nommez-le `games`.
4. Déplacez le dossier `BAR.sdd` à l’intérieur de `games`.

À la fin, vous devez avoir ce chemin, en ouvrant les dossiers un par un :

`games`, puis `BAR.sdd`, puis le fichier `modinfo.lua`.

Le fichier `devmode.txt` reste à côté du dossier `games`, pas dedans.

### 5. Lancer une partie

1. Fermez Beyond All Reason s’il était déjà ouvert, puis rouvrez-le depuis son icône.
2. Entrez dans le jeu jusqu’au menu où l’on peut jouer.
3. Ouvrez **Settings** (les paramètres, souvent une roue dentée).
4. Ouvrez **Developer**.
5. Ouvrez **Singleplayer**.
6. Cliquez sur **Beyond All Reason Dev**.
7. Lancez une partie comme d’habitude, contre l’ordinateur.

Si **Developer** n’apparaît pas, le fichier `devmode.txt` n’est pas au bon endroit ou son nom est incorrect. Reprenez l’étape 2, puis rouvrez le jeu.

Cette partie se joue sur votre ordinateur. La file multijoueur habituelle du lanceur continue d’utiliser le jeu officiel, pas ce dossier.

### Si quelque chose bloque

- Le téléchargement ZIP est long : c’est normal, laissez-le finir.
- Le jeu ne propose pas **Beyond All Reason Dev** : vérifiez le nom `devmode.txt` et l’emplacement de `BAR.sdd`.
- Après avoir changé ces dossiers, fermez complètement le jeu et rouvrez-le.

---

## English

### 1. Install the normal game

1. Open this page in your browser: [https://www.beyondallreason.info/download](https://www.beyondallreason.info/download)
2. Download the game for your computer (Windows or Linux).
3. Run the downloaded file and follow the buttons to the end.
4. Open **Beyond All Reason**. Let it finish any downloads it asks for.
5. When the small welcome program is open, click **Open install directory**.  
   A folder window opens. That is the right place. Leave this window open.

You do not need to search for this folder yourself.

### 2. Create an empty file named devmode.txt

This file tells the game: “I have a special version, please offer it to me.”

**On Windows**

1. In the window opened in the previous step, click **View**.
2. Tick **File name extensions**.  
   Without this box, Windows hides the end of the name and the file will not work.
3. Right-click an empty area of the window.
4. Choose **New**, then **Text Document**.
5. Name it exactly:

   `devmode.txt`

6. Confirm. If Windows asks “Do you want to change the file extension?”, click **Yes**.
7. The file must stay empty. If it opens, close it without typing anything.

The correct name is `devmode.txt`.  
`devmode.txt.txt` does not work.

**On Linux**

1. In the folder window, right-click an empty area.
2. Choose **New empty file**, or the equivalent entry on your system.
3. Name it exactly `devmode.txt`.
4. Do not type anything inside it.

### 3. Download this version of the game

1. Open this address:  
   [https://github.com/ECprx77/BAR_without-raptor-turrets-and-lswarmer/archive/refs/heads/game.zip](https://github.com/ECprx77/BAR_without-raptor-turrets-and-lswarmer/archive/refs/heads/game.zip)
2. The browser downloads a large ZIP file. Wait until it has really finished.
3. Open the ZIP and choose **Extract all** (Windows) or **Extract** (Linux).
4. You get a folder with a long name, similar to `BAR_without-raptor-turrets-and-lswarmer-game`.
5. Rename that folder. The new name must be exactly:

   `BAR.sdd`

   Capital `BAR`, a dot, then lowercase `sdd`.

6. Open `BAR.sdd`. You should see a file named `modinfo.lua`.  
   If it is missing, you renamed the wrong folder: extract the ZIP again.

### 4. Put the folder in the right place

1. Go back to the window opened by **Open install directory**.
2. Look for a folder named `games`.
3. If it does not exist: right-click, **New folder**, and name it `games`.
4. Move the `BAR.sdd` folder inside `games`.

When you are done, opening the folders one by one should show:

`games`, then `BAR.sdd`, then the file `modinfo.lua`.

The `devmode.txt` file stays next to the `games` folder, not inside it.

### 5. Start a match

1. Close Beyond All Reason if it was already open, then open it again from its icon.
2. Go into the game until you reach the menu where you can play.
3. Open **Settings** (often a gear icon).
4. Open **Developer**.
5. Open **Singleplayer**.
6. Click **Beyond All Reason Dev**.
7. Start a match as usual, against the computer.

If **Developer** does not appear, `devmode.txt` is in the wrong place or its name is wrong. Repeat step 2, then reopen the game.

This match runs on your computer. The launcher’s usual multiplayer queue still uses the official game, not this folder.

### If something gets stuck

- The ZIP download takes a long time: that is expected, let it finish.
- The game does not offer **Beyond All Reason Dev**: check the name `devmode.txt` and the location of `BAR.sdd`.
- After changing these folders, close the game completely and open it again.
