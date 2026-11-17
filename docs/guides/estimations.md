# Estimations

Chaque bien est estimé avec une ou plusieurs **méthodes**. Netestim combine ensuite les résultats en une **valeur moyenne pondérée**.

## Méthodes proposées

Les méthodes proposées pour un bien dépendent de deux choses :

- la **catégorie de mission** du dossier : valeur vénale (prix de vente) ou valeur locative (loyer) ;
- la **catégorie du bien**, choisie dans sa typologie.

| Catégorie de bien | Valeur vénale | Valeur locative |
|---|---|---|
| Appartements, lofts, duplex | Comparative, hédoniste, capitalisation | Rendement inversé, hédoniste, comparative par loyers |
| Maisons, villas | Comparative, capitalisation, sol + construction − vétusté | Rendement inversé, comparative par loyers |
| Immeubles | Comparative, capitalisation, hédoniste | Rendement inversé, hédoniste, comparative par loyers |
| Terrains | Comparative | Rendement inversé, comparative par loyers |
| Parties communes | Comparative | Rendement inversé, comparative par loyers |
| Locaux commerciaux, bureaux, entrepôts, immeubles de bureaux et commerces | Comparative, commercialité | Comparative par loyers, commercialité, rendement inversé, valeurs de marché locatif |
| Hôtels | Comparative | Comparative par loyers |

D'autres méthodes apparaissent avec la mention **Méthode bientôt disponible** : bilan promoteur inversé, incidence foncière, capitalisation du revenu, méthode hôtelière, valeur de marché. Elles ne sont pas encore utilisables.

## Créer une estimation

1. Ouvrez le bien, puis la rubrique **Estimations**. Chaque méthode proposée y apparaît sous forme de carte.
2. Sur la carte d'une méthode, cliquez sur **Créer une nouvelle évaluation**.
3. Remplissez le formulaire de la méthode (voir ci-dessous), puis enregistrez.

La **surface du bien** utilisée par les méthodes est sa surface pondérée, calculée à partir de la rubrique **Surfaces**. Saisissez donc les surfaces avant les estimations.

Chaque estimation porte deux réglages, repris dans la synthèse :

- **Inclus** / **Exclus** : prise en compte ou non dans la valeur moyenne pondérée ;
- **Pondération** : poids de la méthode dans cette moyenne.

## Les méthodes

### Méthode comparative

Comparaison avec des ventes de biens similaires.

1. Cliquez sur **Ajouter un bien** pour chaque vente de référence : date ou année de vente, adresse, ville, type de bien, année de construction, surface, surface du terrain et prix. Netestim calcule le prix au m² de chaque référence.
2. Décochez **Inclure dans le calcul** pour écarter une référence sans la supprimer.

Netestim retient un **prix au m² de référence** : la somme des prix des références incluses, divisée par la somme de leurs surfaces. L'estimation vaut ce prix multiplié par la surface du bien.

### Méthode comparative par loyers

Même principe, appliqué aux loyers. Pour chaque bien de référence, saisissez le type de bien, le type de référence, la date d'effet du bail, l'adresse, la surface pondérée et le **loyer réactualisé**.

Le **loyer moyen de comparaison** au m² est la somme des loyers des références incluses, divisée par la somme de leurs surfaces. Le loyer estimé vaut ce montant multiplié par la surface du bien.

### Valeurs de marché locatif

Comparaison avec des **annonces** de location, à titre indicatif. Pour chaque annonce, saisissez l'adresse, l'annonceur, la date, la surface et le prix annuel au m².

Le prix moyen annuel au m² (total des loyers divisé par le total des surfaces) est multiplié par la surface du bien pour donner le **loyer annuel estimé**.

### Méthode par rendement inversé

Pour chaque bien de référence, saisissez la date de l'annonce, l'adresse, la surface et le loyer annuel. Netestim en déduit un loyer moyen au m², puis le **loyer annuel du bien**.

Saisissez ensuite le **taux de rendement** (6,5 % par défaut). Le calcul détaillé s'affiche sous le résultat.

### Méthode hédoniste

La méthode part d'un **prix de référence au m²**, puis l'ajuste selon les caractéristiques du bien.

1. Saisissez le prix de référence au m².
2. Dans **Critères à appliquer**, cochez les critères qui décrivent le bien. Chaque critère porte un poids, positif ou négatif, exprimé en pourcentage. Les critères sont regroupés en catégories : surface, type de construction, étages, environnement, exposition, vue et distribution, isolation thermique (DPE), situation dans l'agglomération, chauffage et énergie, travaux, charges et impôts.
3. Choisissez le mode de calcul :
    - **Méthode linéaire** : chaque catégorie multiplie le prix par (1 + somme de ses poids / 100) ;
    - **Méthode exponentielle** : chaque catégorie multiplie le prix par e^(somme de ses poids / 100).

Le prix au m² ajusté, multiplié par la surface du bien, donne l'évaluation. Le bloc **Formules de calcul** détaille chaque étape.

### Méthode par capitalisation

La valeur découle du loyer que le bien peut produire.

| Paramètre | Rôle |
|---|---|
| **Surface pondérée** | Surface du bien |
| **Loyer mensuel au m²** | Loyer de marché |
| **Taux de vacance**, **Incidences impayées**, **Travaux indispensables** | Abattements, en % du loyer annuel |
| **Taux de capitalisation** | Rendement attendu, en % |

Le calcul se fait en trois temps :

1. **Loyer annuel brut** = loyer mensuel au m² × surface × 12.
2. **Loyer annuel net** = loyer brut, diminué des trois abattements.
3. **Valeur du bien** = loyer net ÷ taux de capitalisation.

La section **Références de marché** permet de noter les sources consultées.

### Méthode sol + construction − vétusté

La valeur se reconstitue en trois blocs.

- **Sol** : pour la surface minimale constructible, la surface d'agrément et la surface inconstructible, saisissez une surface, un coefficient et un prix au m². Leur somme donne la valeur du sol brute, à laquelle s'ajoute un pourcentage pour les **VRD et aménagements**.
- **Construction** : coût de la surface de plancher (surface totale pondérée × prix au m² de construction), plus un **coût d'architecte** en pourcentage de ce coût.
- **Vétusté** : pour chaque élément du bâti (maçonnerie, ravalement, charpente, couverture, menuiseries, revêtements, plomberie, chauffage, électricité), choisissez l'état **Bon**, **Moyen** ou **Mauvais**. Chaque état correspond à un taux. Le cumul des taux, appliqué au coût de la surface de plancher, donne la valeur de vétusté.

La **valeur finale du bien** est la somme du terrain, des aménagements et de la construction, diminuée de la vétusté.

### Méthode par commercialité

Pour les locaux commerciaux et les bureaux.

1. Choisissez le type de tableau : **Bureaux neufs**, **Bureaux anciens** ou **Commerce** (catégories 1 à 3).
2. Pour chaque ligne du tableau (minimum, moyenne, maximum, ou catégorie de commerce), saisissez le loyer annuel au m² ou la valeur au m².
3. Sélectionnez la ligne retenue.

Netestim multiplie le montant de la ligne retenue par la surface pondérée du bien. Le résultat est une valeur vénale ou un loyer, selon la mission.

## Synthèse des évaluations

Le bloc **Synthèse des évaluations** du bien récapitule les méthodes utilisées.

La **valeur moyenne pondérée** se calcule ainsi : chaque estimation incluse est multipliée par sa pondération, puis la somme obtenue est divisée par le total des pondérations. Les pondérations n'ont donc pas besoin de totaliser 100 %. Une méthode exclue ne compte pas.

Cliquez sur **Afficher le détail** pour revoir le calcul d'une méthode.

## Validation

Quand le dossier est **proposé à validation**, ses estimations passent en attente. Elles sont **validées** en même temps que le dossier et ne sont plus modifiables ensuite (voir [Dossiers d'expertise](dossiers.md)).

Deux tâches suivent ces étapes (voir [Tâches](taches.md)) :

- **Évaluations réalisées** est proposée dès qu'une estimation incluse a une valeur et une pondération ;
- **Évaluations validées** se termine seule à la validation.

## Retrouver les estimations

Le menu **Estimations** liste les dernières estimations saisies, tous dossiers confondus, avec leur montant, leur type et leur date.
