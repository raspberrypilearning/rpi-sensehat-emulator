यदि आपके पास Sense HAT तक प्रवेश नहीं है, तो आप एमुलेटर का उपयोग कर सकते हैं।

### ऑनलाइन Sense HAT एमुलेटर

एक ऑनलाइन एमुलेटर है जिसे आप Sense HAT के लिए कोड लिखने और परीक्षण करने के लिए अपने ब्राउज़र में उपयोग कर सकते हैं।

![Trinket पर Sense HAT एमुलेटर](images/sense-hat-trinket.png)

+ एक इंटरनेट ब्राउज़र खोलें, [https://trinket.io/sense-hat](https://trinket.io/sense-hat){:target="_blank"} पर जाएं और मौजूदा डेमो कोड को मिटा दें जो संपादक में है।

+ यदि आप अपना काम save करना चाहते हैं, तो आपको एक [मुफ्त खाता बनाना होगा](https://trinket.io/signup){:target="_blank"}, Trinket वेबसाइट पर।

### Raspberry Pi पर Sense HAT एमुलेटर

यदि आप Raspberry Pi का उपयोग कर रहे हैं, तो Raspbian प्रचालन तंत्र में शामिल एक Sense HAT एमुलेटर है।

![Raspbian पर Sense HAT एमुलेटर](images/pi-emulator.png)

+ मुख्य मेन्यू से, **Programming** > **Sense HAT emulator** चुनें एमुलेटर युक्त विंडो खोलने के लिए।

+ यदि आप एमुलेटर के इस संस्करण का उपयोग कर रहे हैं, तो आपके प्रोग्राम को `sense_emu` से आयात करना होगा ` sense_hat ` के बजाय:

```python
from sense_emu import SenseHat
```

यदि आप बाद में अपना कोड एक वास्तविक Sense HAT पर चलाना चाहते हैं, तो नीचे दिखाए अनुसार आयात लाइन को बदल दें। अन्य सारा कोड बिलकुल समान रह सकता हैं।

```python
from sense_hat import SenseHat
```
