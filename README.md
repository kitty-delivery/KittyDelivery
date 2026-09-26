<div align="center">
  <img src=".github/assets/banner.png" alt="KittyDelivery banner" width="100%" />

  <h1>KittyDelivery</h1>

  <p>
    A food delivery application split into an independent Node.js microservices architecture, built as a student project.
  </p>

  <p>
    <img src="https://img.shields.io/github/last-commit/kitty-delivery/KittyDelivery" alt="last update" />
    <img src="https://img.shields.io/badge/status-student%20project-lightgrey" alt="status" />
  </p>
</div>

<br />

## :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
- [Architecture](#building_construction-architecture)
- [Related Repositories](#link-related-repositories)
- [Contact](#handshake-contact)

## :star2: About the Project

KittyDelivery is a school project designed as a food delivery application (similar to Uber Eats), split into several independent Node.js / Express microservices, each living in its own GitHub repository. This repository is the entry point and reference for the whole project.

## :building_construction: Architecture

Each microservice is a separate repository, with its own `package.json` and, for some of them, its own `Dockerfile` and `docker-compose.yml`. This organization allows each service to evolve and be deployed independently.

## :link: Related Repositories

| Repository | Role |
| --- | --- |
| [KittyDelivery_core](https://github.com/kitty-delivery/KittyDelivery_core) | Architecture hub: diagram, docker-compose, submodules |
| [KittyDelivery_API](https://github.com/kitty-delivery/KittyDelivery_API) | API gateway |
| [KittyDelivery_mc_user](https://github.com/kitty-delivery/KittyDelivery_mc_user) | User accounts (internally named "Delivery") |
| [KittyDelivery_mc_restaurant](https://github.com/kitty-delivery/KittyDelivery_mc_restaurant) | Restaurant management (Express, MongoDB, Docker) |
| [KittyDelivery_mc_auth](https://github.com/kitty-delivery/KittyDelivery_mc_auth) | Authentication (internally named "General") |
| [KittyDelivery_mc_component](https://github.com/kitty-delivery/KittyDelivery_mc_component) | Shared components (internally named "Developer") |
| [KittyDelivery_mc_notif](https://github.com/kitty-delivery/KittyDelivery_mc_notif) | Notifications (internally named "Client") |
| [KittyDelivery_mc_article](https://github.com/kitty-delivery/KittyDelivery_mc_article) | Products and dishes (internally named "Restaurant") |
| [KittyDelivery_mc_log](https://github.com/kitty-delivery/KittyDelivery_mc_log) | Logs (empty repository) |
| [KittyDelivery_mc_menu](https://github.com/kitty-delivery/KittyDelivery_mc_menu) | Menus (empty repository) |
| [KittyDelivery_mc_order](https://github.com/kitty-delivery/KittyDelivery_mc_order) | Orders (internally named "Commercial") |

## :handshake: Contact

Brieuc Dumortier, [LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/), dumortier.contact@gmail.com
