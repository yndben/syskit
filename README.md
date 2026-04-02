# syskit

 
Collection d'outils système Bash pour Linux. 
 
## Fonctionnalités 
 
disk_usage : Affiche l'utilisation du disque triée par taille.

top_processes [N] : Affiche les N processus les plus gourmands en CPU (10 par défaut).

find_large_files [rép] [taille] : Trouve les fichiers dépassant une certaine taille (Mo).

sys_summary : Résumé du système (OS, Kernel, Uptime, RAM).

Alias

.., ... : Navigation rapide dans les dossiers.

ll, la : Listage amélioré des fichiers.

meminfo, cpuinfo, ports : Informations matérielles et réseau rapides.

rm : Suppression sécurisée (avec confirmation).
 
## Prérequis 
 - Linux (Ubuntu, Debian, Arch...) - Bash >= 4.0 
 
## Installation 
 
```bash 
git clone https://github.com/votre-LOGIN/syskit.git 
cd syskit 
bash install.sh 
source ~/.bashrc 
``` 
 
## Utilisation 
 
# Voir l'espace disque
disk_usage

# Voir les 5 processus les plus lourds
top_processes 5

# Chercher les fichiers de plus de 500Mo dans le dossier courant
find_large_files . 500

# Utiliser un alias de navigation
...
A
 
## Structure du projet 
 
L'arborescence du projet est organisée comme suit :

lib/ : Contient les scripts sources.

	functions.sh : Définition des fonctions système complexes.

	aliases.sh : Raccourcis de commandes simples.

install.sh : Script automatisé pour copier les outils vers ~/syskit et configurer le .bashrc.

README.md : Documentation principale du projet.

ANSWERS.md : Réponses aux questions de compréhension du TP.
 
## Auteur 
 
Votre Nom — yndben
