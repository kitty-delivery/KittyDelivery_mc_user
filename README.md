<div align="center">
  <h1>KittyDelivery_mc_user</h1>
  <p>Microservice Node.js / Express du projet KittyDelivery, déclaré en interne sous le nom "KittyDelivery_Delivery".</p>

<p>
  <img src="https://img.shields.io/badge/stack-Node.js%20%2F%20Express-green" alt="stack" />
</p>
</div>

<br />

## Table des matières

- [A propos](#a-propos)
- [Stack technique](#stack-technique)
- [Installation](#installation)
- [Dépôts liés](#depots-lies)
- [Contact](#contact)

## A propos

Ce dépôt fait partie de l'architecture microservices de [KittyDelivery](https://github.com/BaditSad/KittyDelivery), un projet d'application de livraison de repas réalisé dans le cadre de mes études. Le `package.json` du service le nomme `kittydelivery-delivery` et son README d'origine indique "KittyDelivery_Delivery".

Le service est généré à partir du squelette Express standard (moteur de vue EJS avec layouts) : à ce stade, les routes exposées renvoient encore les réponses par défaut du générateur et n'implémentent pas de logique métier propre.

## Stack technique

<details>
  <summary>Serveur</summary>
  <ul>
    <li><a href="https://expressjs.com/">Express</a></li>
    <li><a href="https://ejs.co/">EJS</a> avec express-ejs-layouts</li>
    <li>cookie-parser, morgan, http-errors</li>
  </ul>
</details>

## Installation

```bash
npm install
npm run devstart
```

Le service démarre via `node ./bin/www` (script `start`), ou avec rechargement automatique via `nodemon` (script `devstart`).

## Dépôts liés

Ce microservice fait partie du projet [KittyDelivery](https://github.com/BaditSad/KittyDelivery), aux côtés de [KittyDelivery_API](https://github.com/BaditSad/KittyDelivery_API), [KittyDelivery_mc_restaurant](https://github.com/BaditSad/KittyDelivery_mc_restaurant), [KittyDelivery_mc_auth](https://github.com/BaditSad/KittyDelivery_mc_auth), [KittyDelivery_mc_component](https://github.com/BaditSad/KittyDelivery_mc_component), [KittyDelivery_mc_notif](https://github.com/BaditSad/KittyDelivery_mc_notif), [KittyDelivery_mc_article](https://github.com/BaditSad/KittyDelivery_mc_article), [KittyDelivery_mc_log](https://github.com/BaditSad/KittyDelivery_mc_log), [KittyDelivery_mc_menu](https://github.com/BaditSad/KittyDelivery_mc_menu) et [KittyDelivery_mc_order](https://github.com/BaditSad/KittyDelivery_mc_order).

## Contact

Brieuc Dumortier, [LinkedIn](https://www.linkedin.com/in/dumortier-brieuc/), dumortier.contact@gmail.com
