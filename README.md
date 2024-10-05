Trhacknon Console Webshell

Console-Webshell est un outil modifié à partir d'une base solide que j'utilise depuis longtemps. Ce webshell vous permet d'exécuter des commandes directement via une interface web et de contourner plusieurs couches de sécurité. Deux versions sont incluses dans ce dépôt :

tw.php : Version sans authentification.

twl.php : Version avec login protégé par mot de passe.


Fonctionnalités

Bypass de sécurité : Conçu pour contourner certaines protections courantes.

Interface console : Permet d'exécuter des commandes dans une interface web minimaliste.

Deux modes :

tw.php : Pas de login requis, accès direct à la console.

twl.php : Requiert un login et un mot de passe (protégé par MD5).



Détails des versions

tw.php : Webshell sans authentification. Idéal pour des environnements de test rapides.

twl.php : Webshell avec authentification. Le login et le mot de passe sont chiffrés avec l'algorithme MD5. Les identifiants sont :

Login : guest

Mot de passe : trknshell (chiffré en MD5)



Installation

1. Clonez ce dépôt :

git clone https://github.com/tucommenceapousser/console-webshell.git


2. Placez les fichiers sur votre serveur web.


3. Accédez à l'URL de votre serveur pour utiliser le webshell :

Pour tw.php : votre-serveur/tw.php

Pour twl.php : votre-serveur/twl.php (authentification requise)




Notes de sécurité

Usage réservé à des fins légales : Ce webshell est uniquement destiné à des tests en environnement contrôlé. Toute utilisation malveillante est strictement interdite.

Mot de passe MD5 : Le mot de passe est chiffré avec MD5, une méthode considérée comme faible. Utilisez-le uniquement dans un contexte de test.


Avertissement

Je décline toute responsabilité en cas d'utilisation illégale ou non éthique de cet outil. Utilisez-le uniquement à des fins éducatives ou dans des environnements où vous avez l'autorisation.
