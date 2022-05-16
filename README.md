# doc-bash

Mémo de commandes utilisées régulièrement ou qui devraient l'être

- [doc-bash](#doc-bash)
  - [Commandes](#commandes)
  - [Ressources](#ressources)

## Commandes

- installer proprement un `.deb` téléchargé (aptitude) : `apt install ./mon-deb.deb`
- mettre un script sur le `$PATH` : `export PATH="/path/to/folder/containing/script/:$PATH"`
- revenir au répertoire précédent : `cd -`
- se déplacer dans un répertoire de manière temporaire : `pushd /path`
- revenir au répertoire quand vous avez appelé `pushd` : `popd`
- mettre un programme en arriere plan : `CTR+z`
- ramener un programme au premier plan : `fg` (forground)
- repeating the last command with `sudo` : `sudo !!` 
- historique des commandes : `history`
- relancer une commande de l'historique à partir de son id : `!{id de la commande}`
- améliorer la commande précédente avec un timestamp : `HISTTIMEFORMAT="%Y-%m-%d %T "; history;`
- rendre permanent la commande précédente, la mettre dans le `.bashrc`
- effacer la ligne de commande : `CTR+u`
- aller à la fin de la ligne : `CTR+e`
- aller au début de la ligne : `CTR+a`
- tronquer un fichier (mettre la taille (*s*ize) à 0) : `truncate -s 0 fichier.txt`

## Ressources

- [18 Commands That Will Change The Way You Use Linux Forever](https://www.youtube.com/watch?v=AVXYq8aL47Q&list=PLS3XEhTy6-Ale8Et6pxRR2I3LYNt8-rX3&index=48), vidéo
- [Linux in a nutshell](https://www.pdfdrive.com/linux-in-a-nutshell-6th-editionpdf-e18844861.html), PDF à télécharger gratuitement