# Exercise 1

## Question 2 
Quand on intègre une constante, on obtient une rampe, et ça se vérifie bien sur la simulation : le signal monte de façon linéaire avec le temps. C’est une courbe droite qui augmente toujours à la même vitesse.
Ensuite, quand on intègre encore une fois, on obtient une parabole. Cette fois, la courbe monte de plus en plus vite. On voit clairement que la croissance n’est plus constante : elle s’accélère avec le temps. Ça confirme que chaque intégration ajoute un “niveau” de variation supplémentaire au signal.

## Question 3 
Le résultat montre que x(t) diminue progressivement pour se rapprocher de zéro. Au début la décroissance est rapide, puis ça ralentit au fur et à mesure. Ce comportement correspond à une décroissance exponentielle.

## Question 4
Les populations oscillent indéfiniment sans amortissement. 
Le pic des lapins précède celui des renards : quand les lapins augmentent, les renards ont plus à manger donc les renards augmentent ensuite mais lapins chutent entrainant la chute des renards et ainsi de suite...C’est un effet de régulation naturelle.
Le plan de phase montre des boucles fermées, ce qui veut dire que le système tourne autour d’un point d’équilibre sans jamais s’y stabiliser complètement. En résumé, le modèle décrit bien un équilibre dynamique entre les deux espèces : ni l’une ni l’autre ne disparaît, mais leurs nombres varient en continu dans le temps.

--- 

# Exercise 2
    
## Question 1
Pour (G=2) et (T=10), la sortie atteint 2 en régime permanent et évolue lentement à cause de la grande constante de temps.

## Question 2
La sortie monte progressivement vers la valeur finale égale à (G). Quand on augmente (G), la courbe garde la même forme mais la valeur finale est plus grande, donc (G) règle simplement l’amplitude du signal de sortie.

## Question 3
Pour (G=5) et (T=8), la sortie atteint 95% au bout d'environ 24 secondes soit environ (3T).
En doublant ou divisant (T), le temps de réponse change dans les mêmes proportions, ce qui montre que (T) contrôle la rapidité du système.

## Question 4
La sortie décroît de façon exponentielle vers zéro. Plus (T) est grand, plus la décroissance est lente. C’est la réponse typique d’un système du premier ordre à une impulsion.

## Question 5
Quand on remplace tout le schéma par un seul bloc (H(s)=\frac{2}{10s+1}), on obtient exactement le même comportement. Les deux montages sont équivalents, seul le niveau de détail change.

