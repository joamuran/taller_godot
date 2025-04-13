# taller_godot


1. Introducció a Godot i preparació del projecte
    * Instal·lació i entorn de treball
    * Configuració inicial del projecte i resolució
    * Estructura bàsica: Escenes, Nodes i Scripts
    * POO en Godot: Nodes com a objectes

2. Creació del personatge principal
    * CharacterBody2D i estructura bàsica del node
    * Assignació de sprites i animacions (idle, run, jump, fall, doble bot)
    * Tractament del píxel art (filtrat)

3. Programació del moviment
    * Control de moviment horitzontal i salts
    * Separació del codi en funcions modulars (_move_x, _jump, etc.)
    * Gestió d’inputs personalitzats
    * Reproducció d’animacions segons estat
    * Doble bot i animació associada

4. Creació de l'escena principal
    * Muntatge de l’escena de joc (Node2D)
    * Afegir el personatge
    * TileMaps i TileMapLayers (Godot 4.3)
    * Assignació de TileSets, col·lisions i decoració

5. Plataformes i col·lisions
    * Crear plataformes amb Sprite2D + CollisionShape2D
    * Ús de col·lisions unidireccionals

6. Càmera i seguiment del jugador
    * Camera2D i sistema de drag margins
    * Activació de smooth follow
    * Limitació de moviments amb límits

7. Fons amb efecte Parallax
    * ParallaxBackground i ParallaxLayer
    * Velocitats diferenciades i motion_mirroring
    * Sincronització amb la càmera

8. Exercicis i millores
    * Afegir nous estats al personatge
    * Provar nous tiles i redissenyar l’escenari
    * Crear objectes interactius bàsics
    * Reforç de conceptes de POO aplicats