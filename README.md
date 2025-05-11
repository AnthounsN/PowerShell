
| **Commande Unix Bash** | **Commande PowerShell équivalente** | **Description**                             |
| ------------------------ | ----------------------------------- | ------------------------------------------- |
| `cp`                     | `Copy-Item`                         | Copie des fichiers ou des dossiers          |
| `rm`                     | `Remove-Item`                       | Supprime des fichiers ou des dossiers       |
| `cd`                     | `Set-Location`                      | Change le répertoire courant                |
| `mkdir`                  | `New-Item -ItemType Directory`      | Crée un nouveau dossier                     |
| `man`                    | `Get-Help`                          | Affiche l’aide sur une commande             |
| `history`                | `Get-History`                       | Liste l’historique des commandes PowerShell |
| `alias`                  | `Get-Alias` / `Set-Alias`           | Affiche ou définit des alias de commande    |
| `cat`                    | `Get-Content`                       | Affiche le contenu d’un fichier texte       |





# Commandes PowerShell utilisées pour faire les recherches #

## Rechercher les cmdlets pour copier un fichier
Get-Command *copy*

## Rechercher les cmdlets pour supprimer un fichier
Get-Command *remove*

## Rechercher les cmdlets pour changer de répertoire
Get-Command *location*

## Rechercher les cmdlets pour créer un dossier
Get-Command *new*

## Obtenir l’aide sur les commandes (équivalent de man)
Get-Help

## Afficher l’historique des commandes
Get-History

## Afficher les alias disponibles
Get-Alias

## Lire le contenu d’un fichier
Get-Command *content*
