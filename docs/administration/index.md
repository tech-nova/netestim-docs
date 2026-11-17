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

L'import recrée un projet complet à partir de son export : dossiers, biens, surfaces, estimations, commentaires, documents, contacts et ventilation du CA. Il sert à restaurer un projet supprimé définitivement : le projet garde son identifiant d'origine.

L'import est refusé si :

- le projet appartient à une autre agence que la vôtre ;
- un projet avec le même identifiant existe déjà, y compris dans la corbeille.

### Quel fichier importer

Le bouton **Exporter le projet (ZIP)**, sur la page d'un projet, produit une **archive ZIP**. Elle contient les données du projet, dans un fichier `project-<identifiant>.json`, ainsi que les fichiers de ses documents.

| Fichier importé | Données | Fichiers des documents |
|---|:---:|:---:|
| **Archive ZIP** (recommandé) | ✅ | ✅ réimportés |
| **Fichier JSON** extrait de l'archive | ✅ | — |

Avec le fichier JSON seul, les documents sont recréés mais renvoient vers leurs fichiers d'origine : ils ne s'ouvriront que si ces fichiers existent encore. Préférez l'archive ZIP.

### Étapes

1. Dans la liste des projets, cliquez sur **Importer un projet**.
2. Choisissez l'archive ZIP ou le fichier JSON.
3. Vérifiez l'aperçu : Netestim affiche le nombre d'éléments de chaque type et, pour une archive ZIP, signale les documents dont le fichier manque.
4. Cliquez sur **Importer les données**. Un récapitulatif indique ce qui a été créé et, pour une archive ZIP, les fichiers qui n'ont pas pu être repris.

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
