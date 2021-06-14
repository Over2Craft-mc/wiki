# Echanger avec les joueurs

## Fonctionnement des panneaux de shops

**Voici un exemple de shop :**

Pour créer un shop, posez un coffre contenant les items que vous souhaitez vendre \(les items placés dans un coffre doivent être les même\). Placez un panneau et remplissez chaque ligne comme expliqué ci dessous :

![](../.gitbook/assets/image%20%287%29.png)

La **première ligne** correspond au nom du shop. Dans le cas d'un shop joueur, elle correspond au **pseudo** du créateur du shop.

La **deuxième ligne** représente la **quantité** vendue par transaction.

La **troisième ligne** représente **le prix** d'une transaction :

* **B** correspond au prix auquel le joueur qui clique **achète** \(clique droit\).
* **S** correspond au prix auquel le joueur qui clique sur le panneau **vend** \(clique gauche\).

La **troisième ligne** peut contenir soit un **prix d'achat** \(B\), soit un **prix de vente** \(S\), soit les deux.

**La quatrième ligne** correspond à **l'identifiant de l'item** vendu. Vous pouvez mettre un `?` sur cette ligne si vous avez mis des items dans votre coffre, cette ligne sera automatiquement complétée.

## Voir les items vendu par d'autres joueurs

Vous pouvez utiliser la commande `/ah` pour voir les items vendu par d'autre joueurs. 

Vous pouvez chercher un item spécifique en faisant par exemple `/ah diamant`

