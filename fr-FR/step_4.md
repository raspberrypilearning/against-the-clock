\--- challenge \---

## Défi : Compte à rebours

Peux-tu créer un **nouveau** chronomètre , qui compte à rebours jusque 0 ? Voici comment ton nouveau chronomètre devrait fonctionner :

+ Appuyer sur les boutons A et B ensemble devrait réinitialiser ton `chronomètre` à 0
    
    ![capture d'écran](images/clock-challenge-1.png)

+ Appuyer sur le bouton B devrait ajouter 1 à ton chronomètre. Appuie dessus 10 fois pour créer un chronomètre de 10 secondes.
    
    ![captures d'écran](images/clock-challenge-2.png)

+ Appuyer sur le bouton A devrait prendre 1 de ta variable `temps` jusqu'à ce qu'elle atteigne 0. Cela signifie que tu auras besoin d'une boucle `tant que` qui s'exécute aussi longtemps que le `temps` est supérieur à (`>`) 0.
    
    ![capture d'écran](images/clock-challenge-3.png)

## Chronomètre précis

As-tu remarqué que le chronomètre n'est pas très précis ! C'est parce qu'il faut du temps pour afficher et faire défiler les numéros sur le micro:bit.

Essaie d'ajuster la pause pour améliorer le chronométrage. Tu peux utiliser un bloc `si/alors` pour avoir des délais plus courts pour les plus grands nombres qui prennent plus de temps à défiler.

\--- /challenge \---