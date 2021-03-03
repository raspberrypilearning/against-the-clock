## Démarrer et arrêter ton chronomètre

Utilisons le bouton A pour démarrer ton chronomètre, et le bouton B pour l'arrêter.

+ Ton chronomètre devrait démarrer lorsque le bouton A est pressé. Ajoute un nouveau bloc `lorsque le bouton A pressé` à ton script :
    
    ![capture d'écran](images/clock-a-pressed.png)

+ Le chronomètre doit compter aussi longtemps que le bouton B **n'a pas été pressé**. Pour faire cela, glisse un bloc `tant que` dans ton nouvel événement `lorsque le bouton A est pressé` .
    
    ![capture d'écran](images/clock-while.png)

+ Fais glisser un bloc `non` , de « Logique » à ton bloc `tant que` :
    
    ![capture d'écran](images/clock-not.png)

+ Tu peux ensuite faire glisser un bloc `bouton B est pressé` après le bloc `non`.
    
    ![capture d'écran](images/clock-b-pressed.png)
    
    Tout code à l'intérieur de cette boucle `tant que` sera répété, **aussi longtemps que le bouton B n'a pas été pressé**.

+ Ensuite, tu veux ajouter 1 à ta variable `temps` à chaque seconde (1 seconde = 1000 ms). Ajoute un bloc `pause` pour que ton chronomètre attende 1 seconde.
    
    ![capture d'écran](images/clock-pause.png)

+ Pour augmenter ta variable `temps`
    
    ![capture d'écran](images/clock-change-time.png)

+ Enfin, tu devras afficher la variable `temps` mise à jour. Voici à quoi ton code devrait ressembler :
    
    ![capture d'écran](images/clock-update.png)

+ Clique « lancer » pour tester ton code.
    
    + Appuie sur les boutons A et B ensemble pour régler ton chronomètre à 0
    + Appuie sur le bouton A pour démarrer ton chronomètre
    + Appuie (et maintiens) sur le bouton B pour arrêter ton chronomètre
    
    ![capture d'écran](images/clock-test.png)

## Défie tes amis !

Utilise le chronomètre pour défier tes amis. Par exemple, tu pourrais voir combien de temps il leur faut pour réciter l'alphabet en arrière, ou nommer 10 capitales.