## Contrôler les LED

1. Ouvrez EduBlocks à partir du bureau.

2. Cliquez sur le **gpiozero** menu déroulant, cliquez sur **Général** et faites glisser le `depuis gpiozero import *` bloquer dans l'espace de travail.
    
    ![](images/edublocks1.png)

3. Cliquez sur le **Sorties** menu déroulant sous **gpiozero** et cliquez sur **LED**. Faites glisser un `led = LED (pin)` bloquer dans l'espace de travail sous le bloc d'importation. Renommez la variable de `led` à `red`, et changer `pin` à `22`.

4. Faites glisser dans un `led.on` bloquer, et l'ancrer sous le bloc précédent. Changer le `on` menu déroulant à `blink`. Vos blocs de code devraient maintenant ressembler à ceci:
    
    ![](images/edublocks2.png)

5. Maintenant, cliquez sur le **Run** bouton pour exécuter votre code. Vous devriez voir la LED rouge clignoter.

6. Maintenant ajoutez quelques blocs de LED supplémentaires pour introduire les deux autres lumières, et les faire clignoter à des vitesses différentes:
    
    ![](images/edublocks3.png)

7. Exécutez votre code à nouveau et vous devriez voir les trois lumières clignotant à des taux différents.

8. Si un plus grand nombre clignote plus lentement, quel nombre le ferait fonctionner plus vite? Essayez de faire clignoter vos lumières plus rapidement.