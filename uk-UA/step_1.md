Якщо у тебе немає доступу до Sense HAT, ти можеш використовувати емулятор.

### Емулятор Sense HAT онлайн

Існує онлайн-емулятор, у якому ти можеш писати та тестувати код для Sense HAT у браузері.

![Емулятор Sense HAT на Trinket](images/sense-hat-trinket.png)

+ Відкрий браузер, перейди на [https://trinket.io/sense-hat](https://trinket.io/sense-hat){:target="_blank"} і видали наявний демокод, що знаходиться у редакторі.

+ Якщо ти хочеш зберегти свою роботу, тобі потрібно [створити безплатний акаунт](https://trinket.io/signup){:target="_blank"} на сайті Trinket.

### Емулятор Sense HAT на Raspberry Pi

Якщо ти використовуєш компʼютер Raspberry Pi, у його операційній системі існує емулятор Sense HAT.

![Емулятор Sense HAT на операційній системі Raspberry Pi](images/pi-emulator.png)

+ У головному меню вибери **Programming** > **Sense HAT Emulator**, що відкриє вікно з емулятором.

+ Якщо ти використовуєш цю версію емулятора, твоя програма має імпортувати з `sense_emu` замість `sense_hat`:

```python
from sense_emu import SenseHat
```

Якщо пізніше ти захочеш запустити свій код на справжньому Sense HAT, просто заміни рядок з командою import на той, що наведений нижче. Решту коду можна залишити незмінною.

```python
from sense_hat import SenseHat
```
