# Scénario du Workshop

Bonjour,

Vous venez d’être embauché par la société « Coffee Bean ». Cette société souhaite mettre en œuvre un chatbot pour fournir de nouvelles services à ces clients dans sa démarche de digitalisation de sa relation client.

Il voudrait permettre au travers de celui-ci :
1. Lister les différents produits à son catalogue. Il souhaite afficher une image du produit.
2. Répondre aux questions sur le prix des produits
3. Passer commande 
    - un article, 
    - sa quantité,
    - le mode de récupération (livraison / a emporter)
Pour la livraison demander le numéro de téléphone et le stocker
4. Recherche des boutiques par nom de ville. Il a 3 magasins (Paris, Lyon, Bordeaux).

5. (Optionel) Il aimerait aussi pouvoir gérer une carte de fidélité avec des numéros de la forme XXYYYY (X étant une lettre, Y étant un chiffre).

Listes des articles:
1. Café :
- Expresso : 3€
- Latte : 3.5€
- Mocha : 4€
- Cappuccino : 5€

2. Thé :
- Menthe : 2.5€
- Ceylan : 3 €

La livraison est facturé 5€ et 1 euros sur place.

Merci de votre aide pour ce projet.

BONNE CHANCE

# Accélérateurs / Aide

- Regular Expression (REGEX): 
    - Téléphone Mobile:  ^(\\\\+33|0|0033)[0-9]{9}$
    - Regex carte de fidélité : [A-Z]{2}[0-9]{4}

# Fichiers : 
Liste des intentions : [intents_csv](https://github.com/hmatheisen/Watson_Academy/blob/master/Watson_Assistant/data/Intents.csv)  
Liste des entités : [entities_csv](https://github.com/hmatheisen/Watson_Academy/blob/master/Watson_Assistant/data/Entities.csv)

# Tutorial - Solution:

- [Tutorial](https://github.com/hmatheisen/Watson_Academy/blob/master/Watson_Assistant/tutorial.md)
- [Solution](https://github.com/hmatheisen/Watson_Academy/blob/master/Watson_Assistant/data/Coffee_Shop.json)
- [Solution avancée](https://github.com/hmatheisen/Watson_Academy/blob/master/Watson_Assistant/data/Coffee_Shop_avance.json)









