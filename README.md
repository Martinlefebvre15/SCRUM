# Guide des bonnes pratiques de code

## Description
***
Ce guide résume les bonnes pratiques à utilisées pour garder un code maintenable.

## Table des matière
1. [Code en anglais] (#code-en-anglais)
2. [Indentation] (#indentation)
3. [Arborescence] (#arborescence)
4. [Nommage] (#nommage)
5. [Description et commentaires] (#description-et-commentaires)
6. [Documentation] (#documentation)
7. [Test] (#test)

## Les bonnes pratiques

### Code en anglais
***
Ecrire son code en anglais permet de travailler plus facilement de manière mondiale car il s'agit de la langue internationale et tous le monde peut comprendre le code sans avoir à le réécrire. De plus, écrire son code en anglais permet de ne pas provoquer de mauvaise traduction de la part de collaborateurs étrangers.

### Indentation
***
L'indentation de son code est très importante pour que celui-ci sois lisible. En effet, créer des espaces et des retours de ligne permettent à une tierce personne et à nous même, d'avoir une meilleure vue d'ensemble du code car ceux-ci mettent en évidence des blocs de code.

### Arborescence
***
Il s'agit d'organiser des dossiers et fichiers pour s'y retrouver plus facilement. Pour cela, il faut regrouper tout les fichiers appartenant au même groupe (exemple : les fichiers concernant les bases de données seront regrouper ensemble dans un même dossier). Il est également préférable de créer des sous dossiers lorsque le nombre de différents groupe devient trop important (exemple : pour les fichiers de base de données ils seront regroupé dans des sous dossiers en fonction des serveurs à laquelle ils appartiennent).

### Nommage
***
Il est important de bien nommer les fichiers, dossiers, variables, afin de comprendre d'un coup d'oeil à quoi ils correspondent. On peut par exemple nommer une variable en focntion de son utilité dans le code (exemple : pour une variable contenant un bloc de code qui permet de lire un fichier, on pourrait l'appeler read_file).

### Decription et commentaires
***
Cette pratique est essentielle pour décrire ce qu'il se passe dans le code. Pour chaque fonction, boucle, incrémentation, ect... il est nécessaire de le préciser sous forme de commentaire afin de s'y retrouver plus facilement et pour délimiter une fonction. En effet, si un code n'a pas était revu pendant plusieurs semaines, le fait de commenter permet de comprendre immédiatement l'utilité du code et son découpage.

### Documentation
***
Celle-ci permet d'expliquer tout ce qu'il se passe dans un projet ou code. Pour un projet de développement d'application par exemple, la documentation contiendra : une description du projet, son but, les différentes fonctionnalités, les personnes travaillant sur le projet. Il est également conseillé d'écrire une docmentation technique plus ciblée sur le code, les bases de données, ect... Tout ceci a pour but de transmettre une parfaite connaisance du projet à une tierce personne.

### Test
***
Ils servent à vérifier la fiabilité et la qualité d'une application et donc d'anticiper les problèmes liés à celle-ci. Avec des tests unitaires, on peut vérifier le bon focntionnement d'une partie précise de cette application. Ils sont la base sur laquelle les autres processus de tests (tests fonctionnels, d’intégration, de régression, de performance…) doivent être construits pour assurer des fondations solides.


***
## Conclusion
***
Les différents points abordés montrent qu'il est important de fournir le plus d'informations possible pendant l'écriture du code. Il est nécessaire, avant de coder, de bien définir ce que l'on veut, et où on veut aller. De ce fait, il est plus facile d'organiser son code par la suite.

