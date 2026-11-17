# Documentation Netestim

Netestim est le logiciel de gestion des expertises immobilières de votre agence. Il réunit en un seul endroit vos **projets**, vos **dossiers d'expertise**, les **biens immobiliers** expertisés et leurs **estimations**, ainsi que les tâches, contacts et documents qui les accompagnent.

<div class="grid cards" markdown>

- **Prise en main**

    ---

    Se connecter, se repérer dans l'interface, comprendre ce que votre rôle vous permet de faire.

    [:octicons-arrow-right-24: Commencer](prise-en-main/index.md)

- **Guides**

    ---

    Créer un projet, ouvrir un dossier, décrire un bien, saisir une estimation.

    [:octicons-arrow-right-24: Voir les guides](guides/index.md)

- **Administration**

    ---

    Gérer les utilisateurs, les agences et les modèles (réservé aux administrateurs et managers).

    [:octicons-arrow-right-24: Administrer](administration/index.md)

</div>

## Comment s'organisent les données

Netestim suit une hiérarchie simple, du plus général au plus détaillé :

```
Projet
└── Dossier d'expertise (rapport)
    └── Bien immobilier
        ├── Caractéristiques
        ├── Surfaces
        ├── Photos
        ├── Documents
        ├── Commentaires
        └── Estimations
```

- Un **projet** correspond à une mission confiée par un client (le *donneur d'ordre*). Il a un chef de projet et peut associer plusieurs experts.
- Un **dossier d'expertise** est un rapport rattaché à un projet. Un projet peut en contenir plusieurs.
- Un **bien immobilier** est un bien expertisé dans le cadre d'un dossier. Un dossier peut porter sur plusieurs biens.

## À qui s'adresse cette documentation

| Profil | Pages utiles |
|---|---|
| **Expert** | [Prise en main](prise-en-main/index.md), puis les [guides](guides/index.md) |
| **Manager** | Les guides, plus [Rôles et droits](prise-en-main/roles.md) et l'[administration](administration/index.md) |
| **Administrateur** | Toute la documentation, en particulier l'[administration](administration/index.md) |
