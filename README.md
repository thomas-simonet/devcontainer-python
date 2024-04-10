# Devcontainer Python

Devcontainer pour développer avec python très rapidement sans installer grand chose sur la machine hôte (Pratique pour tester.)

Le premier lancement prend 2-3 minutes.

## Features
* Python + Poetry ;
* Venv automatique à l'ouverture d'un terminal ;
* Oh my zsh (Spaceship prompt + quelques plugins) ;
* Configuration de vscode
* Extensions vscode

## Dépendances minimales sur la machine hôte
* Docker (De préférence sur wsl)
* Visual Studio Code
* Les extensions "Dev containers" et "wsl"

Installer WSL : [lien](https://learn.microsoft.com/fr-fr/windows/wsl/install)
Installer Docker : [Première étape](https://docs.docker.com/engine/install/ubuntu/) - [Deuxième étape](https://docs.docker.com/engine/install/linux-postinstall/)

## Debug
Si Docker engine ne veut pas démarrer sur WSL : [lien](https://github.com/docker/for-linux/issues/1406#issuecomment-1183487816)

## How to
1. git clone the repo
2. open it in vscode
4. Reopen the folder inside a devcontainer
5. Start coding

## todos
* Historique zsh (done)
* Check les powerline font (Doivent être installées sur l'hote ??)
* Remove le dossier .git après le clone (just ??)
* Cache des extensions vscode (?)