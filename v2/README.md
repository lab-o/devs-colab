# Devs cO'LAB v2

Le sujet en quelques buzzwords : `#twitter`, `#bigdata`, `#elastic`, `#docker`, `#tweetmap`, `#labo`

Tu as tout compris? non? reprenons en français:
Basé sur l'idée de #onemilliontweetmap : [https://onemilliontweetmap.com/](https://onemilliontweetmap.com/),
l'idée est d'afficher les tweets parlant du LAB'O et de ses startups sur une carte 🗺️. Deux parties:
- Extraction des tweets utilisant le `#lavieaulabo`, mentionnant `@le_lab_o`, issus de `@le_lab_o`, mentionnant des startups du LAB'O ... liste non exhaustive. Un point important pour filtrer : la géolocalisation doit être activée sur le tweet. Stockage dans une base de données elastic ([https://www.elastic.co/fr/](https://www.elastic.co/fr/))
- Récupération depuis la base de données et affichage des points sur une carte

[Code source](https://github.com/lab-o/devs-colab-v2)
