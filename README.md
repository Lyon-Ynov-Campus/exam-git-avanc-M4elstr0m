[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Bwmh1Xrb)

# Site Web en Go

Ce projet est un site web développé en Go qui affiche une page vide pour le moment. 

## Fonctionnalités

Le site affiche pour le moment une page vide. Deux fonctionnalités seront développées en parallèle, depuis la branche dev déjà existante.

## Installation

```bash
go mod tidy
go run main.go
```

Le serveur sera accessible sur http://localhost:8080

## Exercice 6

### Question 2

Pour effacer le changement (deux nouvelles lignes au README.md) j'ai utilisé :

```git
git revert -m 1 HEAD
git push
```

on aurait aussi pu faire

```git
git reset --hard HEAD^
git push
```

git reset : supprime les changements effectués en supprimant aussi l'historique. Donc très propre visuellement.

git revert : supprime les changements effectués en créant un commit par-dessus. Permet de garder un historique cohérent des changements
