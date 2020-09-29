---
title: "Hugo"
date: 2020-09-29T20:02:24+02:00
draft: false
---
# Site static HUGO

## Installation sur windows 10
choco install hugo 

## Création d'un site 
hugo new site sisr4 

## Initialiser votre dépôt git 
git init


## Choisi un thème 
https://themes.gohugo.io/tags/responsive/

## Ajouter le thème à votre dépôt 
git submodule add https://github.com/xoxys/hugo-geekdoc.git themes\hugo-geekdoc


## Ajout du themes au fichier de config
echo 'theme =  "geekdoc"' >> config.toml

# Ajout de contenu 
hugo new post/hugo.md
