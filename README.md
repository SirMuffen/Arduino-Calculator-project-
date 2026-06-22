# Arduino Calculator

Ce projet a été réalisé dans le cadre du module Électronique Embarquée
à l'EMSI Casablanca, 2ème année IIR, année 2025/2026.
Auteur : Ayoub ABIDA

## Description

Une calculatrice programmée sur Arduino UNO capable d'effectuer les
quatre opérations de base. Le circuit utilise un clavier matriciel 4x4
pour saisir les chiffres et les opérateurs, et un afficheur LCD 16x2
pour afficher l'expression et le résultat en temps réel. Le projet a
été simulé virtuellement sur Wokwi sans matériel physique.

Ce qui rend ce projet un peu plus complet c'est la gestion de la
priorité des opérateurs : les multiplications et divisions sont
calculées avant les additions et soustractions, comme en mathématiques.

## Composants

Arduino UNO, clavier matriciel 4x4, afficheur LCD 16x2 avec module I2C.

## Bibliothèques

LiquidCrystal_I2C, Keypad, Wire.



## Utilisation

Ouvrir le fichier calculator.ino dans Arduino IDE et le téléverser
sur la carte. Pour tester sans matériel, importer le projet sur Wokwi.
