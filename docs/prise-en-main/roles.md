# Rôles et droits

Chaque utilisateur appartient à une **agence** et possède un **rôle**. Le rôle détermine ce que l'utilisateur peut voir et modifier. Toutes les données sont cloisonnées par agence : personne ne voit les projets d'une autre agence.

## Les rôles

| Rôle | En résumé |
|---|---|
| **Administrateur** | Tous les droits sur les données de son agence, la gestion de tous les comptes et des agences. |
| **Manager** | Tous les droits sur les données de son agence : projets, dossiers, biens, tâches, contacts, corbeille, comptes des experts. |
| **Expert** | Crée ses propres projets et travaille sur ceux auxquels il est associé. |
| **Partenaire externe** | Aucun accès à l'application pour le moment. |

## Ce que peut faire un expert

Un expert voit et modifie **uniquement les projets sur lesquels il intervient**, c'est-à-dire ceux :

- dont il est **chef de projet** ;
- auxquels il est **associé comme expert** ;
- qu'il a lui-même créés.

Sur ces projets :

| Action | Expert associé | Expert chef de projet |
|---|:---:|:---:|
| Consulter le projet, ses dossiers et ses biens | ✅ | ✅ |
| Modifier le projet | ✅ | ✅ |
| Créer ou modifier un dossier ou un bien | ✅ | ✅ |
| Supprimer le projet, un dossier ou un bien | — | ✅ |

Un expert peut **créer un projet** : il en devient automatiquement le chef de projet. Il garde le droit de modifier et de supprimer les projets qu'il a créés, même si un manager en nomme ensuite un autre chef de projet.

L'expert consulte également l'annuaire de l'agence (contacts, adresses, utilisateurs). Il peut créer des contacts et des adresses, mais ne modifie et ne supprime que ceux qu'il a créés.

## Ce que réservent les rôles Manager et Administrateur

Seuls les managers et les administrateurs peuvent :

- choisir ou changer le **chef de projet** d'un projet ;
- gérer le **chiffre d'affaires** d'un projet et sa ventilation entre experts ;
- **valider** un dossier d'expertise ;
- choisir l'**expert** d'un dossier ;
- consulter le **tableau de bord** de l'agence ;
- gérer la **corbeille** de toute l'agence.

Les managers gèrent aussi les **comptes** des experts et partenaires externes de leur agence ; l'administrateur gère tous les comptes et les agences. Voir [Utilisateurs](../administration/utilisateurs.md).

!!! question "Il vous manque un droit ?"
    Adressez-vous au manager ou à l'administrateur de votre agence : il peut vous associer à un projet ou faire évoluer votre rôle.
