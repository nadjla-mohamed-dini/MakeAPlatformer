# MakeAPlatformer

# Composition du groupe:
Fathima Nadjla Nelson
# Nom du jeu : 
World Eater
# Description du projet: 
World eater est un jeu platformer dans lequel le joueur contrôle un slime qui a 
pour objectif de tout manger. Le joueur devra donc parcourir les différents 
niveaux en franchissant les divers obstacles et ennemis qui se dressent sur 
sa route.
# Mode d'emploi pour démarrer le jeu: 
Télécharger le bluid et le lancer
# Journal des écarts du GDD

| Section du GDD | Ce que dit le GDD | Problème | Décision prise | Justification |
| -------- | -------- | -------- | -------- | -------- |
| Condition victoire/défaite   | Pour réussir le niveau, il suffit que le joueur atteigne l'objectif situé tout à la fin celui-ci. Le joueur n'a pas de réel moyen de défait  | Comment gérer l'échec du joueur sans créer de frustration ?   |    | Cellule 1   |
| Personnage   | Le personnage possède une barre de vie qui diminue lorsqu'il subit des dégâts.   | Aucun nombre de points de vie n'est défini dans le GDD.   | Fixer la barre de vie à 3 HP.   | Trois points de vie offrent un bon équilibre entre difficulté et accessibilité   |
| Mécanique principal   | Chaque pouvoir est soumis à une limitation de temps ou de nombre d'utilisation, sans valeur précise.   | Le GDD ne précise ni la durée des pouvoirs ni leur nombre d'utilisations.   | Limiter chaque pouvoir à 20 secondes ou 3 utilisations, selon sa nature.  |  Ces valeurs permettent au joueur d'utiliser ses pouvoirs de manière significative sans déséquilibrer le gameplay.  |
| Mécanique secondaire   | Lorsque le joueur est dans les airs, il peut utiliser la touche correspondante pour accélérer sa chute  | La vitesse d'accélération de la chute n'est pas définie dans le GDD.   | Augmenter la vitesse de chute à 1,5× la vitesse verticale normale lorsque le joueur utilise la commande dédiée.   | Elle améliore la réactivité du gameplay et facilite l'esquive des attaques ainsi que les déplacements précis.   |
| Checkpoint   | Le joueur peut placer un checkpoint en divisant son slime. Le nombre de checkpoints est limité selon le niveau.   | Le GDD ne précise pas les emplacements autorisés pour les checkpoints, ce qui peut créer des situations de soft lock.  | Autoriser le placement des checkpoints uniquement dans des zones prédéfinies et sécurisées du niveau.   | Cette restriction empêche les soft locks, évite que le joueur bloque sa progression par erreur.  |
| Cellule 1   | Cellule 2   | Cellule 1   | Cellule 2   | Cellule 1   |
| Cellule 1   | Cellule 2   | Cellule 1   | Cellule 2   | Cellule 1   |
| Cellule 1   | Cellule 2   | Cellule 1   | Cellule 2   | Cellule 1   |
| Cellule 1   | Cellule 2   | Cellule 1   | Cellule 2   | Cellule 1   |
