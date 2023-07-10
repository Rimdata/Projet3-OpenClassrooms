# Projet3-OpenClassrooms
Concevez une application au service  de la santé publique
# Problématique
L'agence "Santé publique France" a lancé un appel à projets pour trouver des idées innovantes d’applications en lien avec l'alimentation.Mission
Nettoyer et analyser le jeu de données Open Food Facts pour proposer une application au service de la santé publique.

# Idée d'application
Le Reflux GastroOesophagien (RGO): Calcul d'un score_RGO par produit.
Nous avons tous ressenti au moins une fois dans notre vie une remontée de liquide acide de l'estomac dans l’œsophage et parfois dans la bouche surtout après un repas copieux = c’est un reflux gastro-œsophagien (RGO).

En pratique, après avoir pris en photo le code barre du produit, l’application informe l’utilisateur du score_RGO associé, une note entre A et E. L’application recommande également des produits de la même catégorie, et si possible avec un meilleur score_RGO; l’utilisateur peut alors choisir des produits plus adaptés à son régime alimentaire.

Au moins 20 % des adultes ont des symptômes occasionnels de reflux gastro-œsophagien (remontées acides, pyrosis). 10 % ont des symptômes de RGO chaque jour.
Source: https://www.ameli.fr/assure/sante/themes/rgo-adulte/definition-symptomes-causes

Les recommandations pour la gestion du RGO par l’alimentation comprennent :

Favorisent le RGO:

Limiter les aliments gras, p. ex., les aliments frits, les produits de boulangerie élevés en gras, la crème, la crème glacée, les fromages élevés en gras, les saucisses, le bacon, les croustilles, etc. Il a été démontré que les aliments gras retardent la vidange gastrique et réduisent la pression du SOI, prolongeant ainsi la durée d’exposition de l’œsophage à l’acide gastrique et augmentant le volume d’acide qui peut remonter. Pourtant, 45g est une limite qu'il ne faudrait pas dépasser dans le cadre du régime spécial RGO

saturated-fat_100g, trans-fat_100g, cholesterol_100g : augment le RGO. mauvais pour la santé
Les ballonnements peuvent être causés par une fermentation excessive dans l'intestin. Ils aggravent le reflux gastro-œsophagien en augmentant la pression dans l'abdomen. La fermentation est générée par certains types de glucides dits fermentescibles. La consommation de glucides modifie le pH de l’estomac qui devient trop acide.

carbohydrates_100g : augment le RGO.
Autres aliments déconseillés: Produits sucrés

sugars_100g : augment le RGO. mauvais pour la santé
L’excès de sel, c’est bien connu, favorise l’hypertension et les maladies cardiovasculaires. Il diminue aussi la pression du sphincter de l’œsophage et augmente donc le risque de reflux.

salt_100g : augment le RGO. mauvais pour la santé
Diminuent le RGO:

Assurer une consommation adéquate de protéines. Des études préliminaires suggèrent que les protéines augmentent la pression du SOI, ce qui permet ainsi la fermeture du sphincter et réduit le reflux. Même si de plus récentes études n’appuient pas cette suggestion, maintenir une diète qui comprend des protéines faibles en gras peut quand même aider à guérir les muqueuses irritées ou les ulcères.

proteins_100g : diminue le RGO. bon pour la santé
Pour prévenir la constipation et les ballonnements liés à la pression abdominale, il faudrait consommer au minimum 30g de fibres alimentaires par jours.

fiber_100g : diminue le RGO. bon pour la santé
Ce sont des sels (aluminium, calcium, magnésium) qui neutralisent localement l'acidité du contenu de l'estomac.

calcium_100g : diminue le RGO. bon pour la santé
Pensez à consommer suffisamment d'aliments riches en vitamine C

vitamin-c_100g : diminue le RGO. bon pour la santé
Sources:

https://badgut.org/centre-information/sante-et-nutrition/diete-pour-personnes-souffrant-de-rgo/?lang=fr#:~:text=Les%20recommandations%20pour%20la%20gestion,bacon%2C%20les%20croustilles%2C%20etc.
https://www.passeportsante.net/fr/Nutrition/Dietes/Fiche.aspx?doc=reflux_gastro_oesophagien_diete
https://sante.journaldesfemmes.fr/fiches-sante-du-quotidien/2542916-reflux-gastrique-rgo-causes-traitements/
https://www.julienvenesson.fr/reflux-gastrique-aliments/
https://www.thierrysouccar.com/sante/info/5-conseils-pour-renforcer-la-barriere-anti-reflux-2622
Variables pertinentes pour le projet:
Plusieurs variables seront ainsi primordiales dans l'étude de la faisabilité de l'application et le calcul du score_RGO, à savoir:

Favorise le RGO + mauvais pour la santé:
saturated-fat_100g,
trans-fat_100g,
cholesterol_100g,
carbohydrates_100g,
sugars_100g,
salt_100g.
Diminue le RGO + bon pour la santé:
proteins_100g,
fiber_100g,
calcium_100g,
vitamin-c_100g.
