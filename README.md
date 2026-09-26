<div align="center">
  <h1>KittyDelivery</h1>
  <p>Projet d'application de livraison de repas, découpé en architecture microservices Node.js.</p>

<p>
  <img src="https://img.shields.io/badge/status-projet_scolaire-lightgrey" alt="status" />
</p>
</div>

<br />

## Table des matières

- [A propos](#a-propos)
- [Architecture](#architecture)
- [Dépôts du projet](#depots-du-projet)
- [Contact](#contact)

## A propos

KittyDelivery est un projet réalisé dans le cadre de mes études, pensé comme une application de livraison de repas découpée en plusieurs microservices indépendants (Node.js / Express), chacun dans son propre dépôt GitHub. Ce dépôt sert de point d'entrée et de référence pour l'ensemble du projet.

## Architecture

Chaque microservice est un dépôt à part, avec son propre `package.json` et, pour certains, son propre `Dockerfile` et `docker-compose.yml`. Cette organisation permet de faire évoluer et déployer chaque service indépendamment.

## Dépôts du projet

| Dépôt | Rôle |
| --- | --- |
| [KittyDelivery_API](https://github.com/BaditSad/KittyDelivery_API) | Point d'entrée API du projet |
| [KittyDelivery_mc_user](https://github.com/BaditSad/KittyDelivery_mc_user) | Microservice déclaré en interne comme "Delivery" |
| [KittyDelivery_mc_restaurant](https://github.com/BaditSad/KittyDelivery_mc_restaurant) | Microservice restaurants (Express, MongoDB, Docker) |
| [KittyDelivery_mc_auth](https://github.com/BaditSad/KittyDelivery_mc_auth) | Microservice déclaré en interne comme "General" |
| [KittyDelivery_mc_component](https://github.com/BaditSad/KittyDelivery_mc_component) | Microservice composants |
| [KittyDelivery_mc_notif](https://github.com/BaditSad/KittyDelivery_mc_notif) | Microservice notifications |
| [KittyDelivery_mc_article](https://github.com/BaditSad/KittyDelivery_mc_article) | Microservice articles |
| [KittyDelivery_mc_log](https://github.com/BaditSad/KittyDelivery_mc_log) | Microservice logs |
| [KittyDelivery_mc_menu](https://github.com/BaditSad/KittyDelivery_mc_menu) | Microservice menus |
| [KittyDelivery_mc_order](https://github.com/BaditSad/KittyDelivery_mc_order) | Microservice commandes |

## Contact

Brieuc Dumortier, [LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/), dumortier.contact@gmail.com
