# Devs cO'LAB v2

Le sujet en quelques buzzwords : `#twitter`, `#bigdata`, `#elastic`, `#docker`, `#tweetmap`, `#labo`

Tu as tout compris? non? reprenons en français:
Basé sur l'idée de #onemilliontweetmap : [https://onemilliontweetmap.com/](https://onemilliontweetmap.com/),
l'idée est d'afficher les tweets parlant du LAB'O et de ses startups sur une carte 🗺️. Deux parties:
- Extraction des tweets utilisant le `#lavieaulabo`, mentionnant `@le_lab_o`, issus de `@le_lab_o`, mentionnant des startups du LAB'O ... liste non exhaustive. Un point important pour filtrer : la géolocalisation doit être activée sur le tweet. Stockage dans une base de données elastic ([https://www.elastic.co/fr/](https://www.elastic.co/fr/))
- Récupération depuis la base de données et affichage des points sur une carte

[Code source](https://github.com/lab-o/devs-colab-v2)

## Ateliers
### v2.0 - 2018-04-03

7 participant.e.s

- 11h45 - Burgers commandés, début de l'installation
- 12h00 - Le PC portable initialement prévu n'arrive pas à se connecter via le câble HDMI. L'équipe du #devs cO'LAB est sur le coup.
- 12h18 environ - La décision est prise de changer de PC après 2 redémarrages et une mise à jour du pilote graphique... en vain
- 12h22 - Le nouveau PC est démarré, il faut encore transférer quelques fichiers et installer certains outils comme Atom...
- 12h28 - Début du briefing avec l'équipe. Les choses sérieuses vont enfin pouvoir commencer!
- 12h30 - Premier codeur et "C'est qui qui a pris le burger Classik?"

- 15h00 (peut être un peu dépassé) - On lève les mains du clavier! ça ne fonctionne pas mais tant pis, on a quand même bien avancé! Félicitations 👏 aux codeurs et à la codeuse qui ont pu réaliser les tâches suivantes: 

    - Création du projet et "Hello World" en node.js (c'est la base)
    - Empaquetage de l'application dans un container docker
    - Installation de la lib node-twitter
    - Explications du fonctionnement de docker et de docker-compose
    - Récupération des tweets
    - Tentative de lancement d'elastic search (c'est pour l'instant un échec, les deux noeuds d'elastic ne communiquent pas)
