## Bedien de LED's

\--- task \---

Open vanaf het bureaublad het programma EduBlocks.

\---/task\---

\--- task \---

Klik op de **gpiozero** uitklap menu, klik **General** en sleep het `from gpiozero import *` blok naar de werkruimte.

![](images/edublocks1.png)

\--- /task \---

\--- task \---

Klik op de **Outputs** drop-down onder **gpiozero** en klik op **LED**. Sleep een `led = LED (pin)` blok naar de werkruimte onder het importblok. Hernoem de variabele van `led` naar `rood`, and verander `pin` naar `22`.

\--- /task \---

\--- task \---

Sleep een `led.on` blok en plaats het onder het vorige blok. Verander de `on` drop-down naar `blink`. Je codeblokken moeten er nu als volgt uitzien:

![](images/edublocks2.png)

\--- /task \---

\--- task \---

Klik nu op de **Run** knop om je code uit te voeren. Je zou de rode LED moeten zien knipperen.

\--- /task \---

\--- task \---

Voeg nu nog meer LED-blokken toe om de andere twee LED's aan te sturen en laat ze op verschillende snelheden knipperen:

![](images/edublocks3.png)

\--- /task \---

\--- task \---

Voer je code opnieuw uit en je zou de drie lichtjes met verschillende snelheden moeten zien knipperen.

\--- /task \---

\--- task \---

Als een groter getal het lampje langzamer laat knipperen, welk getal zou het dan sneller laten knipperen? Probeer je LED's sneller te laten knipperen.

\--- /task \---