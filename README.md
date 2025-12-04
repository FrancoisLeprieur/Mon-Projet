# Site Web sur le Tennis

Ce site a été créé sur le thème du tennis, qui est une passion pour moi.

## Accès au site et Livrables

Le site est hébergé via GitHub Pages et est accessible à l'adresse suivante :
 - https://francoisleprieur.github.io/Mon-Projet/
 
Lien du **Trello** au cas où il serait mal partagé : 
 - https://trello.com/invite/b/690f6c38f258f664e872eeb6/ATTI1ff9be145c75d2681e2ee4f14ec4f45046517C40/projet-sae-104

Les divers autres livrables sont dans le dossier **Gestion-de-projet**.


## Présentation du projet

Ce projet est un site web **multi-pages**.

Il a pour but de présenter **le monde du Tennis**.

### Contenu du site

Le site est divisé en plusieurs sections :

* **Accueil (`index.html`) :** Page de garde avec un menu visuel pour orienter le visiteur.

* **Histoire (`histoire-du-tennis.html`) :** Retrace l'évolution du tennis, du Jeu de Paume à l'ère moderne.

* **Joueurs Emblématiques (`joueurs.html`) :** Présentation détaillée des légendes (Federer, Nadal, Djokovic, Serena Williams, etc.) sous forme de cartes.

* **Règles (`regles.html`) :** Explication des bases du jeu, du système de points et des fautes.

* **À Propos (`a-propos.html`) :** Une page personnelle où je me présente, parle de mon club à Coutances et partage mes anecdotes (comme ma fameuse rencontre avec Benoît Paire).

---

## Technologies utilisées

Ce site a été réalisé avec :

* **HTML5 :** Structure sémantique des pages (`<nav>`, `<main>`, `<section>`, `<footer>`).

* **CSS3 :** Mise en forme avancée incluant :
    
    * **Flexbox :** Pour une mise en page flexible et adaptative.
    * **Variables CSS (`:root`) :** Gestion centralisée des couleurs (Thème "Terre Battue" : `#c94545`).
    * **Animations (@keyframes) :** Effets d'apparition (`fadeIn`, `slideIn`) et transitions fluides.
    * **Responsive Design :** Utilisation de Media Queries pour adapter l'affichage aux mobiles (smartphones).


## Les différentes fonctionnalités

* **Design Responsive :** Le site s'adapte automatiquement aux écrans d'ordinateurs et de téléphones.

* **Micro-interactions :** Effets de zoom au survol des images et des cartes joueurs.

* **Animations d'entrée :** Les éléments de la page apparaissent en cascade lors du chargement pour un rendu dynamique.

* **Navigation intuitive :** Un sommaire réduit est présent sur toutes les pages internes pour faciliter la navigation.


## Structure du projet

```text
/
├── index.html              # Page d'accueil
├── a-propos.html           # Page de présentation
├── histoire-du-tennis.html # Page historique
├── joueurs.html            # Page des joueurs
├── regles.html             # Page des règles
├── Style.css               # Feuille de style unique
└── Images/                 # Dossier contenant les ressources graphiques
    ├── rafael-nadal.jpg
    ├── federer.jpg
    ├── ...

(Schéma de la structure fait avec l'IA)