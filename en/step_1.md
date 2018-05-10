If you don’t have access to a Sense HAT, you can use the emulator.

### Online Sense HAT emulator

There is an online emulator you can use in your browser to write and test code for the Sense HAT.

![Sense HAT emulator on trinket](images/sense-hat-trinket.png)

+ Open an internet browser, go to [https://trinket.io/sense-hat](https://trinket.io/sense-hat){:target="_blank"} and delete the existing demo code which is in the editor.

+ If you would like to save your work, you will need to [create a free account](https://trinket.io/signup){:target="_blank"} on the Trinket website.

### Sense HAT emulator on the Raspberry Pi

If you are using a Raspberry Pi, there is a Sense HAT emulator included in the Raspbian operating system.

![Sense HAT emulator on Raspbian](images/pi-emulator.png)

+ From the main menu, select **Programming** > **Sense HAT emulator** to open a window containing the emulator.

+ If you are using this version of the emulator, your program must import from `sense_emu` instead of `sense_hat`:

```python
from sense_emu import SenseHat
```

If you later want to run your code on a real Sense HAT, just change the import line as shown below. All other code can remain exactly the same.

```python
from sense_hat import SenseHat
```
