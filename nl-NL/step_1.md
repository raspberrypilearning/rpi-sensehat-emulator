Als je geen toegang hebt tot een Sense HAT, kun je de emulator gebruiken.

### Online Sense HAT-emulator

Er is een online emulator die je in je browser kunt gebruiken om code voor de Sense HAT te schrijven en te testen.

![Sense HAT-emulator op trinket](images/sense-hat-trinket.png)

+ Open een internetbrowser, ga naar [https://trinket.io/sense-hat](https://trinket.io/sense-hat){:target="_blank"} en verwijder de bestaande democode die zich in de editor bevindt.

+ Als je je werk wilt opslaan, moet je [een gratis account maken](https://trinket.io/signup){:target="_blank"} op de Trinket-website.

### Sense HAT-emulator op de Raspberry Pi

Als je een Raspberry Pi gebruikt, is er een Sense HAT-emulator opgenomen in het Raspbian-besturingssysteem.

![Sense HAT-emulator op Raspbian](images/pi-emulator.png)

+ Selecteer **Programmering** > **Sense HAT-emulator** in het hoofdmenu om een venster met de emulator te openen.

+ Als je deze versie van de emulator gebruikt, moet je programma importeren vanuit `sense_emu` plaats van `sense_hat`:

```python
from sense_emu import SenseHat
```

Als je je code later wilt uitvoeren op een echte Sense HAT, wijzig je gewoon de importregel zoals hieronder wordt weergegeven. Alle andere code kan exact hetzelfde blijven.

```python
from sense_hat import SenseHat
```
