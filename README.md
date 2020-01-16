Projet : Data scientist de THP

lib/00_journalists.rb
  Une liste de pseudos de journalistes est rentrée dans un tableau. Le programme doit répondre à une série de questions comme :
    Combien y a-t-il de journalistes dans ce array ?
    Combien d'handle contiennent un numéro ?
    Combien d'handle contiennent les 4 lettres du prénom "Aude" à la suite (sans prendre en compte les majuscules) ?
    Combien commencent par une majuscule (première lettre juste après le @) ?
    Combien contiennent une majuscule ?
    Combien y a-t-il de underscore _ dans tous les pseudos confondus ?
    Trie la liste de handle par ordre alphabétique.
    Quels sont les 50 handles les plus courts de ce array ?
    Quelle est la position dans l'array de la personne @epenser ?

lib/01_cryptocurrencies.rb
  Deux tableaux sont données : un sur les cryptomonnaies et l'autre sur leurs valeurs. Le programme doit fusionner ces deux tableaux dans un hashe et doit pouvoir nous renseigner sur :
    La ou les crypto qui ont la plus grosse valeur.
    La ou les crypto qui ont la plus petite valeur.
    Le nombre de crypto contenant le mot "coin".
    Les devises, dont le cours est inférieur à 6000 (Indice : on peut comparer en valeur 2 integers mais pas 2 strings. Pense bien à enlever le $ et éventuellement utiliser .to_i pour faire cet exercice).
    La devise la plus chère parmi celles dont le cours est inférieur à 6000.