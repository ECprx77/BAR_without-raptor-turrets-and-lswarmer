# BAR without brood land swarmers and brood turrets

Fork of [Beyond All Reason](https://github.com/beyond-all-reason/Beyond-All-Reason) where these units no longer appear:

- `raptor_land_swarmer_brood` (T2, T3 and T4)
- `raptor_turret_brood` (T2, T3 and T4 v1/v2)

Brood bombers, brood artillery and healers still spawn. Their shots no longer hatch a brood land swarmer.

There is nothing to compile. The game is Lua, loaded by the official Beyond All Reason launcher.

## Français

### Installer le lanceur

Installe Beyond All Reason depuis [beyondallreason.info/download](https://www.beyondallreason.info/download), puis ouvre le lanceur. Clique sur **Open install directory**.

- Linux : `~/.local/state/Beyond All Reason/`
- Windows : `%LOCALAPPDATA%\Programs\Beyond-All-Reason\data`

### Activer le mode développement

Dans ce dossier d’installation, crée un fichier vide nommé `devmode.txt`.

### Placer cette version

Dans le sous-dossier `games` (crée-le s’il n’existe pas), clone ce dépôt sous le nom `BAR.sdd` :

```bash
mkdir -p "$HOME/.local/state/Beyond All Reason/games"
git clone --recurse-submodules https://github.com/ECprx77/BAR_without-raptor-turrets-and-lswarmer.git "$HOME/.local/state/Beyond All Reason/games/BAR.sdd"
```

Sous Windows, utilise le dossier `games` qui se trouve dans le répertoire ouvert par le lanceur, et nomme aussi le clone `BAR.sdd`.

Le fichier `games/BAR.sdd/modinfo.lua` doit exister.

### Lancer une partie

1. Démarre le jeu depuis le lanceur.
2. Va dans **Settings > Developer > Singleplayer**.
3. Choisis **Beyond All Reason Dev**.
4. Lance une partie normalement. Elle utilise les fichiers de `BAR.sdd`.

Pour prendre en compte un `git pull` ultérieur, relance la partie.

## English

### Install the launcher

Install Beyond All Reason from [beyondallreason.info/download](https://www.beyondallreason.info/download), then open the launcher. Click **Open install directory**.

- Linux: `~/.local/state/Beyond All Reason/`
- Windows: `%LOCALAPPDATA%\Programs\Beyond-All-Reason\data`

### Turn on development mode

In that install directory, create an empty file named `devmode.txt`.

### Install this version

Inside the `games` folder (create it if needed), clone this repository as `BAR.sdd`:

```bash
mkdir -p "$HOME/.local/state/Beyond All Reason/games"
git clone --recurse-submodules https://github.com/ECprx77/BAR_without-raptor-turrets-and-lswarmer.git "$HOME/.local/state/Beyond All Reason/games/BAR.sdd"
```

On Windows, clone into the `games` folder of the directory opened by the launcher, and name the folder `BAR.sdd` as well.

`games/BAR.sdd/modinfo.lua` must exist.

### Start a match

1. Start the game from the launcher.
2. Open **Settings > Developer > Singleplayer**.
3. Select **Beyond All Reason Dev**.
4. Start a match as usual. It loads the files in `BAR.sdd`.

After a later `git pull`, start a new match to pick up the changes.
