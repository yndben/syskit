## Reponse aux questions 

Q1: Alias est un raccourci qui remplace une commande par une autre tandisqu'une fonction est un veritable bloc de code qui peut contenir une logique et traite des arguments
   exple: Alias ne peut pas cree une commande qui prend un argument, alors qu'une fontion le peut

Q2: source lib/functions.sh : Execute le script dans le shell direct(shell actuel), on utilise soource pour que les fonctions restent chargees et utilisables dans le terminale actuel.
    bash lib/functions.sh  : exécute le script dans un nouveau processus. Une fois le script fini, les fonctions sont oubliées
Q3: On utilise des branches pour isoler de developpement de nouvelles fonctionnalites,il permet de garder le main toujours stables. Si 2 developpeurs travaillent en meme temps sur la branche main il risque d'avoir des conflits de fusion et peuvent bloquer le travail de l'un comme de l'autre

Q4: la ligne set -e arrete immediatement le script si une commande echoue. Il permet d'eviter la continuation du script au cas le script est instable

Q5: la commande git log --oneline --graph --all permet de voir l'historique des commits de facon compacte avec un graphe des branches 
