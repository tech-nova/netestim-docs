# Utilisateurs

!!! info "Réservé aux managers et administrateurs"

Ouvrez le menu de votre profil, puis **Utilisateurs admin**. La page réunit quatre formulaires : création d'un compte, modification d'un compte, changement de mot de passe et code de déverrouillage.

## Qui gère quels comptes

| | Manager | Administrateur |
|---|---|---|
| Comptes visibles | Ceux de son agence | Ceux de toutes les agences |
| Rôles qu'il peut attribuer | Expert, Partenaire externe | Tous |
| Modifier le rôle ou désactiver | Experts et partenaires externes | Tous les comptes, sauf le sien |
| Changer un mot de passe | Experts, partenaires externes et son propre compte | Tous les comptes |
| Définir un code de déverrouillage | — | Tous les comptes |

Un manager ne peut ni modifier le rôle ni désactiver un autre manager ou un administrateur.

## Créer un compte

Remplissez le formulaire **Créer un Expert** :

| Champ | Description |
|---|---|
| **Email** | Identifiant de connexion. Il ne pourra plus être modifié. |
| **Mot de passe** et **Confirmer** | 8 caractères minimum. Communiquez-le à l'utilisateur, qui pourra le changer depuis son profil. |
| **Nouveau code (4 chiffres)** | Code de déverrouillage demandé après une période d'inactivité (voir [Se connecter](../prise-en-main/connexion.md)). |
| **Nom** et **Téléphone** | Coordonnées affichées dans l'application. |
| **Nom de l'agence** | Agence de rattachement. Un manager crée les comptes dans sa propre agence uniquement. |
| **Rôle** | Expert par défaut. Voir [Rôles et droits](../prise-en-main/roles.md). |

Cliquez sur **Créer**. Le compte est actif immédiatement.

## Modifier un compte

Dans le formulaire **Mettre à jour l'utilisateur**, sélectionnez le compte. Vous pouvez modifier son nom, son téléphone et son rôle.

L'email et l'agence ne sont pas modifiables. Pour rattacher une personne à une autre agence, créez-lui un nouveau compte.

!!! warning "Dernier administrateur"
    Un administrateur ne peut pas modifier son propre rôle s'il est le seul administrateur actif de son agence. Cette règle évite de se retrouver sans administrateur.

## Désactiver ou réactiver un compte

Les comptes ne se suppriment pas : on les désactive. Un compte **inactif** ne peut plus se connecter, mais son historique (projets, dossiers, tâches) est conservé.

1. Sélectionnez le compte dans **Mettre à jour l'utilisateur**.
2. Cliquez sur **Désactiver**.

Personne ne peut désactiver son propre compte. Les champs d'un compte inactif sont en lecture seule ; cliquez sur **Activer** pour le rétablir.

### Réaffecter les tâches ouvertes

Avant de désactiver un compte, ou de faire passer un expert en partenaire externe, Netestim vérifie ses tâches ouvertes. S'il en a, une fenêtre vous demande de choisir leur nouveau responsable :

- pour les tâches d'un projet, un autre participant actif **de ce projet** ;
- pour les tâches rattachées à aucun projet, un autre utilisateur actif **de la même agence**.

La modification n'est enregistrée qu'une fois chaque tâche réaffectée. Si un projet n'a aucun autre participant actif, ajoutez-en un au projet avant de recommencer (voir [Projets](../guides/projets.md#associer-des-experts-et-ventiler-le-chiffre-daffaires)).

## Changer un mot de passe

Dans **Changer le mot de passe**, sélectionnez le compte, saisissez le nouveau mot de passe (8 caractères minimum) et confirmez-le.

Un utilisateur qui a oublié son mot de passe peut aussi le réinitialiser lui-même depuis l'écran de connexion.

## Définir un code de déverrouillage

!!! info "Réservé aux administrateurs"

Dans **Code de déverrouillage**, sélectionnez le compte, saisissez un code à 4 chiffres, puis cliquez sur **Mettre à jour**.

Le bouton **Tester** affiche l'écran de verrouillage sur votre propre session, pour voir ce que l'utilisateur verra après une période d'inactivité.

Chaque utilisateur peut aussi changer son code depuis son profil.

## Actions avancées

!!! danger "Réservé aux administrateurs, en cas de problème"
    **Synchroniser métadonnées** recopie le nom, le rôle et l'agence d'un compte vers le service d'authentification. N'utilisez cette action que si un utilisateur garde d'anciens droits après une modification de son rôle.
