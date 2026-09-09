---
title: "Digitisation of the Dixit board game"
description: "University Project : 3D multiplayer adaptation of the famous board game Dixit"
dateString: January - May 2021
draft: false
tags: ["Godot", "Multiplayer", "Networking", "University Project"]
weight: 205
cover:
    image: "/projects/dixit/cover.png"
---

## 🔗 [Ark'Dixit on GitHub](https://github.com/caLsiroL/ARKED-Dixit-GODOT)

## Introduction
As part of my third year of my bachelor's degree, we had a 4–5-month project to complete. Together with four other students, we had the opportunity to produce a proof of concept where we digitalized the board game Dixit. The aim of this project was to test the creation of an application utilising the capabilities of the Ark-Inseec room, a "classroom of the future" equipped with five giant touchscreen walls.

![The Ark-Inseec classroom located on the Inseec Chambéry campus](/projects/dixit/img1.jpg)


Le jeu reprend l'intégralité des règles du Dixit sans compromis. Nous nous sommes même permis d'ajouter quelques fonctionnalités complémentaires comme des effets sur les cartes lorsque les cartes sont dévoilées

## Results
We have produced a peer-to-peer multiplayer game using the open-source Godot game engine, featuring cards taken from the official game. (A big thank you to Dixit for allowing us to use their illustrations for this project)

The game follows all the same rules as the Dixit board game. However, we did take the liberty of adding a few extra features, such as special effects on the cards when they are revealed

![Card with special effects](/projects/dixit/img2.png)

Je me suis personnellement occupé de :
- La partie réseau du jeu & multijoueur du jeu
- Du chat rapide
- De la création du mode plateau 
- De la sélection des personnages et du choix de leur couleur
- De la distribution "aléatoire" des cartes
- Du positionnement des pions lors des votes

Voici une vidéo récapitulative du projet monté et réalisé par mes soins, dont je suis la voix off, dans le cadre de notre rendu

Our game is cross-platform, playable on mobile, PC and even the web. It even features a "board" mode designed to display the board on an external screen. In our case, one of the walls of the Ark-Inseec room, for example.

I personally took charge of:
- The game's networking and multiplayer aspects
- The quick chat feature
- Creating the "board" mode
- Selecting the characters and choosing their colours
- The "random" distribution of cards
- The positioning of tokens during voting

Here is a video summarising the project, which I put together and produced myself, that I the voiced-over (in french), as part of our presentation :

{{< video src="dixit" >}}


## Conclusion

The Ark'Dixit project gave me my first taste of multiplayer game development, which was something I was very interested in and thoroughly enjoyed. It was also my first experience of developing a game as part of a team.
For a student project, it turned out exactly as we'd hoped, and I learnt a great deal about what to do and what not to do. Which, for me, is a success.