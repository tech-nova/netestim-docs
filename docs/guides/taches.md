# Tâches

Les tâches suivent ce qu'il reste à faire sur les projets, les dossiers et les biens. La plupart sont créées automatiquement ; les managers et administrateurs peuvent en ajouter.

## D'où viennent les tâches

À la création d'un projet, d'un dossier ou d'un bien, Netestim crée ses **tâches standard** : devis, facturation, mission, photos, surfaces, estimations, etc. La liste complète figure dans le [catalogue des tâches](../administration/modeles.md#catalogue-des-taches).

Elles sont assignées automatiquement :

- les tâches d'un projet, au **chef de projet** ;
- les tâches d'un dossier et de ses biens, à l'**expert du dossier**.

Chaque tâche standard a un **mode**, qui détermine qui la fait avancer :

| Mode | Fonctionnement | Ce que vous faites |
|---|---|---|
| **Automatique** | Netestim la termine dès que l'étape est franchie (devis créé, dossier validé…), et la rouvre si ce n'est plus le cas. | Rien : elle ne se modifie pas à la main. |
| **Semi-automatique** | Quand les saisies semblent complètes, Netestim la passe au statut **Proposée**. | Vérifiez, puis confirmez en la marquant **Terminée**. |
| **Manuelle** | Netestim ne peut pas la vérifier (rendez-vous, envoi du rapport…). | Changez son statut vous-même. |

Les tâches ajoutées par un manager ou un administrateur sont dites **personnalisées**.

## Statuts

| Statut | Signification |
|---|---|
| **En attente** | Pas encore commencée |
| **En cours** | Commencée |
| **Proposée** | Netestim estime qu'elle est faite et attend votre confirmation (tâches semi-automatiques) |
| **Terminée** | Faite |
| **Annulée** | Sans objet pour ce projet, ce dossier ou ce bien |

Le statut **Proposée** est réservé à Netestim : une tâche proposée ne peut qu'être confirmée.

## La liste des tâches

Le menu **Tâches** affiche les tâches avec leur titre, leur contexte (projet, dossier ou bien concerné), leur priorité, leur statut, la personne assignée et leur échéance.

Les filtres permettent de restreindre la liste :

- par **statut** ;
- par **priorité** ;
- par **entité** : projet, dossier, bien ;
- par **personne assignée** ;
- par **mode** : automatique, semi-automatique, manuelle ou personnalisée.

**Mes tâches** n'affiche que les tâches qui vous sont assignées.

En haut de la page, des indicateurs signalent les **tâches en retard**, les **propositions à confirmer** et les dossiers peu avancés. Cliquez sur un indicateur pour filtrer la liste.

Les tâches apparaissent aussi sur la page de chaque projet, dossier et bien, limitées à leur contexte.

## Faire avancer une tâche

Ouvrez la tâche pour changer son statut. Pour une tâche manuelle, semi-automatique ou personnalisée, vous pouvez aussi modifier sa priorité et son échéance.

Quand vous terminez une tâche, le chef de projet en est notifié, sauf si c'est lui qui l'a terminée. Les tâches automatiques, terminées par Netestim, ne donnent pas lieu à notification.

## Avancement d'un dossier

L'**avancement** d'un dossier se calcule à partir des tâches du dossier et de ses biens :

- une tâche terminée compte entièrement ;
- une tâche en cours ou proposée compte pour moitié ;
- une tâche annulée n'est pas prise en compte.

Un dossier ne peut être **proposé à validation** qu'à partir de **75 %** d'avancement (voir [Dossiers d'expertise](dossiers.md)).

## Ajouter une tâche

!!! info "Réservé aux managers et administrateurs"

Depuis le menu **Tâches**, ou depuis la liste des tâches d'un projet, d'un dossier ou d'un bien, cliquez sur **Ajouter une tâche**. Renseignez le titre, la description, la priorité, l'échéance et la personne assignée, puis cliquez sur **Ajouter la tâche**.

La personne assignée reçoit une notification, et à nouveau si la tâche lui est réattribuée.

## Réaffectation

Quand un compte est désactivé, ou qu'un expert devient partenaire externe, ses tâches ouvertes doivent être confiées à quelqu'un d'autre (voir [Utilisateurs](../administration/utilisateurs.md#reaffecter-les-taches-ouvertes)).

Lors d'un changement de chef de projet, Netestim propose de transférer ses tâches ouvertes au nouveau chef (voir [Projets](projets.md#changer-de-chef-de-projet)).
