# CLAUDE.md

Mémoire du projet pour Claude Code dans ce dépôt.

## Vue d'ensemble

VibeCoding est un dépôt pédagogique de labs pour une formation Cloud, Git,
GitHub et Claude Code. Ce n'est pas une application logicielle : il n'y a
pas de build, de tests ni de dépendances. Le contenu est principalement du
Markdown et de courts fichiers texte d'exercice.

## Structure du dépôt

- `README.md` — présentation courte du dépôt.
- `AGENTS.md` — règles de comportement à suivre par l'agent (voir ci-dessous).
- `fondamentaux/` — énoncés des labs (ex. `LAB-03-claude-md.md`).
- `exercices/` — fichiers texte produits par l'apprenant durant les labs
  (ex. `exercice1.txt`, `test/exercice2.txt`).

## Règles à respecter (résumé de AGENTS.md)

- Toujours répondre en français.
- Rester simple et pédagogique, expliquer les termes techniques.
- Expliquer chaque commande avant de l'exécuter.
- Ne jamais supprimer un fichier sans demander confirmation.
- Garder `AGENTS.md` à moins de 80 lignes.
- Conserver la vocation pédagogique du dépôt (labs de formation).
- Terminer chaque réponse par FIN-LAB03.

Se référer directement à `AGENTS.md` en cas de doute : c'est la source de
vérité, ce fichier n'en est qu'un résumé pratique.

## Conventions observées

- Les messages de commit sont courts, en français, au format impératif
  (ex. « Ajout d'une règle vérifiable dans AGENTS.md »).
- Les fichiers d'exercice sont volontairement simples (une ou deux lignes
  de texte), créés au fil des labs.
- Les fichiers `LAB-XX-*.md` dans `fondamentaux/` décrivent les étapes
  d'un lab ; ne pas modifier leur contenu sauf demande explicite.

## Ce qu'il ne faut pas faire

- Ne pas ajouter d'outillage de build/test/CI : ce dépôt n'en a pas besoin.
- Ne pas transformer les fichiers pédagogiques en code de production.
- Ne pas dépasser 80 lignes dans ce fichier ni dans `AGENTS.md`.
