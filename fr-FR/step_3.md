## Contrôle les LEDs

\--- task \---

Ouvre EduBlocks depuis le Bureau.

\--- /task \---

\--- task \---

Clique sur le menu déroulant **gpiozero** puis sur **Général** et glisse le bloc `from gpiozero import *` dans l'espace de travail.

![](images/edublocks1.png)

\--- /task \---

\--- task \---

Clique sur le menu déroulant **Outputs** sous **gpiozero** puis clique sur **LED**. Glisse un bloc `led = LED(pin)` dans l'espace de travail sous le bloc d'import. Renomme la variable `led` en `red` et change `pin` en `22`.

\--- /task \---

\--- task \---

Glisse un bloc `led.on` sous le bloc précédent. Change sa valeur `on` en `blink`. Ton code devrait maintenant ressembler à ça :

![](images/edublocks2.png)

\--- /task \---

\--- task \---

Clique sur le bouton **Run** pour exécuter ton code. Tu devrais voir la LED rouge clignoter.

\--- /task \---

\--- task \---

Ajoute maintenant plusieurs blocs LED pour intégrer les deux autres lumières et les faire clignoter à différentes vitesses :

![](images/edublocks3.png)

\--- /task \---

\--- task \---

Exécute ton code à nouveau. Tu devrais voir les trois lumières clignoter à des fréquences différentes.

\--- /task \---

\--- task \---

Si un grand nombre fait clignoter une lumière lentement, quel nombre la ferait clignoter plus rapidement ? Essaie de faire clignoter tes lumières plus rapidement.

\--- /task \---