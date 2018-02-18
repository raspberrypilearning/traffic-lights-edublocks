## Contrôlez les DELs

1. Lancez EduBlocks à partir du Bureau.

2. Cliquez le menu déroulant **gpiozero**, cliquez **General** et glissez le bloc `from gpiozero import *` dans l'espace de travail.
    
    ![](images/edublocks1.png)

3. Cliquez le menu dérounalt **Outputs** sous **gpiozero** et cliquez sur **LED**. Glissez un bloc `led = LED(pin)` dans l'espace de travail sous le bloc import. Renommez la variable de `led` à `rouge` et changez `pin` pour `22`.

4. Glissez un bloc `led.on` et imbriquez le sous le bloc précédent. Changez la valeur du menu déroulant de `on` à `blink`. Votre code devrait maintenant avoir l'air de ceci:
    
    ![](images/edublocks2.png)

5. Maintenant cliquez le bouton **Run** pour exécuter votre code. Vous devriez voir la DEL rouge clignoter.

6. Maintenant, ajoutez des blocs LED de plus pour introduire les deux autres feux et les faire clignoter à différentes vitesses:
    
    ![](images/edublocks3.png)

7. Exécutez votre code à nouveau et vous devriez voir les trois feux clignoter à des vitesses différentes.

8. Si un nombre plus élevé fait clignoter un feux plus lentement, quel nombre le ferait clignoter plus rapidement? Essayez de faire clignoter vos feux plus rapidement.