إذا لم تتمكن من الوصول إلى Sense HAT ، يمكنك استخدام المحاكي.

### محاكي Sense HAT المتصل بالإنترنت

هناك محاكي عبر الإنترنت يمكنك استخدامه في متصفحك لكتابة واختبار التعليمات البرمجية لـ Sense HAT.

![محاكي Sense HAT على trinket](images/sense-hat-trinket.png)

+ افتح متصفح إنترنت ، انتقل إلى [ https://trinket.io/sense-hat ](https://trinket.io/sense-hat) {: target = "_ blank"} وقم بحذف التعليمة البرمجية التنفيذية الموجودة في المحرر.

+ إذا كنت تريد حفظ عملك ، فستحتاج إلى [ إنشاء حساب مجاني ](https://trinket.io/signup) {: target = "_ blank"} على موقع Trinket الإلكتروني.

### محاكي Sense HAT على Raspberry Pi

إذا كنت تستخدم Raspberry Pi ، فهناك محاكي Sense HAT متضمن في نظام التشغيل Raspbian.

![محاكي Sense HAT على Raspbian](images/pi-emulator.png)

+ من القائمة الرئيسية ، حدد ** Programming ** > ** محاكي Sense HAT** لفتح نافذة تحتوي على المحاكي.

+ إذا كنت تستخدم هذا الإصدار من المحاكي ، فيجب استيراد برنامجك من ` sense_emu` بدلاً من ` Sense_hat`:

```python
استيراد SenseHat من sense_emu
```

إذا كنت ترغب في وقت لاحق في تشغيل التعليمات البرمجية الخاصة بك على Sense HAT حقيقي ، فما عليك سوى تغيير مسار الاستيراد كما هو موضح أدناه. يمكن أن تبقى كافة التعليمات البرمجية الأخرى كما هي بالضبط.

```python
استيراد SenseHat من sense_emu
```
