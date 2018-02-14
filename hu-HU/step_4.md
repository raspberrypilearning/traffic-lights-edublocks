## Irányítsa a LED-eket

1. Nyissa meg az EduBlock-ot az Asztalról.

2. Kattintson a **gpiozero** gombra legördülő menüből válassza a 123 123_8_2_321 | Általános</strong> és húzza a `-t a gpiozero importból *` blokkolja a munkaterületet.
    
    ![](images/edublocks1.png)

3. Kattintson a **Outputs** gombra legördülő menü alatt **gpiozero** és kattintson a 123_8_4_321 | LED</strong>gombra. Húzás `led = LED (pin)` blokkolja az import blokk alatt lévő munkaterületet. Nevezze át a 123_6_0_321 | led</code> változót 123_6_2_321 | piros</code>, és változtassa meg `pin` 123_6_6_321 | 22</code>.

4. Húzza a `led.on` blokkolja és letegye az előző blokk alá. Módosítsa a `on` -t legördülő menü `villog`. A kódblokknak most így kell kinéznie:
    
    ![](images/edublocks2.png)

5. Most kattintson a **Run** gombra gombot a kód futtatásához. Láthatja a piros LED villogását.

6. Add hozzá még néhány LED-blokkot, hogy bemutassák a másik két lámpát, és különböző sebességgel villogjanak:
    
    ![](images/edublocks3.png)

7. Futtassa újra a kódot, és látni fogja, hogy a három lámpa villog, különböző sebességgel.

8. Ha egy nagyobb szám a lámpa villogását lassítja, akkor mekkora lesz a gyorsabb futás? Próbálja meg villogni a fények gyorsabban.