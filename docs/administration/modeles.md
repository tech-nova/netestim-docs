# Modèles

Les modèles font gagner du temps sur les saisies récurrentes. Netestim en propose deux sortes : les **modèles de commentaires**, que chacun peut créer, et le **catalogue des tâches**, fixe, qui génère les tâches standard.

## Modèles de commentaires

Un modèle de commentaire est un texte type, rattaché à l'un des types de la rubrique **Commentaires** d'un bien. Les modèles sont partagés au sein de l'agence : tout le monde peut les utiliser.

### Qui peut faire quoi

| Action | Expert | Manager, administrateur |
|---|---|---|
| Utiliser un modèle | ✅ | ✅ |
| Créer un modèle | ✅ | ✅ |
| Modifier ou supprimer un modèle | Ceux qu'il a créés | Ceux qu'il a créés |

Un modèle ne se modifie que depuis un commentaire qui l'utilise, et seul son auteur y a accès.

### Utiliser un modèle

1. Dans la rubrique **Commentaires** d'un bien, choisissez le type de commentaire.
2. Cliquez sur **Remplir à partir d'un template**.
3. Recherchez le modèle par son nom, puis sélectionnez-le.

Le texte du modèle est recopié dans le commentaire, qui est alors **lié** au modèle. Vous pouvez ensuite adapter le texte au bien.

Une modification ultérieure du modèle ne change pas les commentaires déjà remplis. Pour détacher un commentaire de son modèle, décochez la case **Le commentaire est lié à un template**.

### Créer un modèle

Rédigez un commentaire, puis cliquez sur **Créer un template depuis ce commentaire**. Donnez un **nom** au modèle, qui servira à le retrouver, vérifiez le **contenu**, puis cliquez sur **Créer**. Le commentaire est aussitôt lié au nouveau modèle.

### Modifier ou supprimer un modèle

Depuis un commentaire lié au modèle, cliquez sur **Modifier le template**. Vous pouvez changer son nom et son contenu, ou le **supprimer** : les commentaires qui l'utilisaient en sont alors détachés, mais gardent leur texte.

## Catalogue des tâches

Netestim crée automatiquement une liste de tâches standard pour chaque **projet**, **dossier d'expertise** et **bien**. Ce catalogue est fixe : il ne se paramètre pas depuis l'application.

Chaque tâche a un **mode** :

- **Automatique** : Netestim la termine seul dès que l'étape est franchie, et la rouvre si ce n'est plus le cas. On ne peut pas la modifier à la main.
- **À confirmer** : la tâche porte sur plusieurs saisies. Quand elles semblent complètes, Netestim la passe au statut **Proposée** ; c'est à vous de confirmer qu'elle est terminée.
- **Manuelle** : Netestim n'a aucun moyen de la vérifier ; marquez-la terminée vous-même. Certaines ont une échéance par défaut.

### Projet

| Tâche | Mode |
|---|---|
| Formulaire d'informations client | À confirmer |
| Équipe assignée et CA réparti | À confirmer |
| Devis créé | Automatique |
| Devis envoyé | Automatique |
| Devis validé | Automatique |
| Acompte client reçu | Manuelle (échéance : 10 jours) |
| Facture envoyée | Automatique |
| Facture payée | Automatique |

### Dossier d'expertise

| Tâche | Mode |
|---|---|
| Mission renseignée | À confirmer |
| Propriétaire renseigné | Automatique |
| Photo de couverture ajoutée | À confirmer |
| Biens rattachés au dossier | À confirmer |
| Rapport généré | À confirmer |
| Dossier validé | Automatique |
| Rapport envoyé au client | Manuelle (échéance : 15 jours) |
| Dossier archivé | Manuelle (échéance : 30 jours) |

### Bien

| Tâche | Mode |
|---|---|
| Adresse renseignée | À confirmer |
| Typologie renseignée | À confirmer |
| Données générales renseignées | À confirmer |
| Surfaces saisies | À confirmer |
| Photos des pièces | Manuelle |
| Photos extérieures | Manuelle |
| Caractéristiques renseignées | À confirmer |
| Commentaires rédigés | À confirmer |
| Rendez-vous client planifié | Manuelle (échéance : 7 jours) |
| Visite du bien effectuée | Automatique |
| Documents requis collectés | À confirmer |
| Évaluations réalisées | À confirmer |
| Évaluations validées | Automatique |

En plus de ce catalogue, les managers et les administrateurs peuvent créer des tâches personnalisées et les assigner (voir [Tâches](../guides/taches.md)).
