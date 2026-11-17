# Administration

Cette section s'adresse aux **managers** et aux **administrateurs**. Les outils d'administration s'ouvrent depuis le menu de votre profil (votre avatar, en haut à droite), sauf l'import de projet, qui se trouve dans la liste des projets.

| Outil | Manager | Administrateur |
|---|:---:|:---:|
| [Utilisateurs](utilisateurs.md) : créer les comptes, attribuer les rôles, désactiver | Experts et partenaires de son agence | Tous les comptes |
| [Agences](agences.md) : créer et configurer les agences | — | ✅ |
| [Modèles](modeles.md) : modèles de commentaires, catalogue des tâches | Modèles de son agence | Modèles de son agence |
| [Importer un projet](#importer-un-projet) | ✅ | ✅ |
| [Synchronisation des tâches](#synchronisation-des-taches) | — | ✅ |
| [Traductions](#traductions) | — | ✅ |

Pour le détail des droits de chaque rôle sur les projets, dossiers et biens, voir [Rôles et droits](../prise-en-main/roles.md).

## Importer un projet

L'import recrée un projet complet à partir de l'archive ZIP produite par l'export d'un projet : dossiers, biens, surfaces, estimations, commentaires, documents, contacts et ventilation du CA.

1. Dans la liste des projets, cliquez sur le bouton d'import, à côté de **Nouveau Projet**.
2. Choisissez l'archive ZIP.
3. Vérifiez l'aperçu : Netestim affiche le nombre d'éléments de chaque type et signale les documents absents de l'archive.
4. Confirmez. Un récapitulatif indique ce qui a été créé et les documents qui n'ont pas pu être repris.

Les tâches standard du projet importé sont créées en même temps.

## Synchronisation des tâches

!!! info "Réservé aux administrateurs"

Netestim crée automatiquement les tâches standard de chaque projet, dossier et bien (voir le [catalogue des tâches](modeles.md#catalogue-des-taches)). La page **Synchronisation des tâches** affiche des statistiques sur ces tâches et crée celles qui manqueraient sur des éléments existants, par exemple après l'ajout d'une tâche au catalogue.

Seules les tâches absentes sont créées : l'opération peut être relancée sans créer de doublon.

## Traductions

!!! info "Réservé aux administrateurs"

La page **Traductions** modifie, en français et en anglais, les libellés des listes de référence : types de mission, types de biens, méthodes d'évaluation.

!!! warning "Prise en compte différée"
    Les libellés modifiés n'apparaissent dans l'application qu'après sa prochaine mise à jour.
