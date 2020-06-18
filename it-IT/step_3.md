## Controlla i LED

\--- task \---

Lancia EduBlocks dal desktop.

\--- /task \---

\--- task \---

Apri il menù **gpiozero**, seleziona **General** e trascina il blocco `from gpiozero import *` sullo spazio di lavoro.

![](images/edublocks1.png)

\--- /task \---

\--- task \---

Apri il menù **Outputs** sotto **gpiozero** e seleziona **LED**. Trascina un blocco `led = LED(pin)` nello spazio di lavoro subito sotto il blocco import. Cambia il nome della variabile `led` in `rosso`, e cambia `pin` in `22`.

\--- /task \---

\--- task \---

Trascina un blocco `led.on` e attaccalo sotto al blocco precedente. Cambia il valore mostrato dalla tendina da `on` a `blink`. Il tuo codice dovrebbe apparire così:

![](images/edublocks2.png)

\--- /task \---

\--- task \---

Adesso fai click sul pulsante **Run** per eseguire il tuo codice. Il LED rosso dovrebbe lampeggiare.

\--- /task \---

\--- task \---

Ora aggiungi altri blocchi LED per aggiungere altre due luci, falle lampeggiare a velocità diverse:

![](images/edublocks3.png)

\--- /task \---

\--- task \---

Eseguendo nuovamente il codice dovresti vedere le tre luci lampeggiare a velocità differenti.

\--- /task \---

\--- task \---

Se un numero più alto fa lampeggiare la luce più lentamente, con quale numero andrebbe più veloce? Prova a far lampeggiare i led più velocemente.

\--- /task \---