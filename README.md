[README.md](https://github.com/user-attachments/files/27262789/README.md)
# 🛒 بوت علي إكسبرس للترويج بالعمولة

بوت تليجرام للترويج لمنتجات علي إكسبرس عالية العمولة.

## ✨ المميزات

- 🔍 البحث عن أحدث الترندات من علي إكسبرس
- 📈 فلترة المنتجات (عمولة ≥ 8%)
- 📢 إنشاء إعلانات ترويجية (عربية + إنجليزية)
- ⏰ جدولة الإرسال (كل ساعة)
- 🖼️ صور المنتجات بدون أشخاص أو حيوانات
- 📁 تصنيفات متعددة (منزلية، إلكترونيات، اكسسوارات، تجميل، مطبخ)

## 📋 الأوامر المتاحة

| الأمر | الوصف |
|------|-------|
| `/start` | رسالة الترحيب |
| `/trends` | عرض أحدث الترندات |
| `/categories` | عرض التصنيفات |
| `/search [اسم]` | البحث عن منتج |
| `/subscribe` | اشتراك للإشعارات |
| `/next` | المنتج القادم |
| `/settings` | الإعدادات |
| `/help` | المساعدة |

## 🚀 التشغيل

### 1. التثبيت

```bash
pip install python-telegram-bot
```

### 2. التشغيل

```bash
python aliexpress_final.py
```

## 📁 هيكل الملفات

```
telegram-research-bot/
├── aliexpress_final.py    # الكود الرئيسي
├── products_data.json     # قاعدة بيانات المنتجات
├── requirements.txt       # المكتبات المطلوبة
└── README.md             # هذا الملف
```

## ⚙️ الإعدادات

### متغيرات البيئة

| المتغير | الوصف | الافتراضي |
|---------|-------|-----------|
| `TELEGRAM_BOT_TOKEN` | توكن بوت تليجرام | مطلوب |

### طريقة التعيين

```bash
export TELEGRAM_BOT_TOKEN="your_bot_token_here"
python aliexpress_final.py
```

## 🔗 رابط المنتج

للحصول على روابط الأفلييت، استخدم:
- [AliExpress Affiliate Platform](https://alitools.io/)
- [Admitad](https://admitad.com/)
- [CJ Affiliate](https://www.cj.com/)

## 📊 هيكل بيانات المنتج

```json
{
  "id": 1,
  "title_ar": "اسم المنتج بالعربية",
  "title_en": "Product name in English",
  "description_ar": "وصف المنتج بالعربية",
  "description_en": "Product description in English",
  "price_usd": 12.99,
  "original_price_usd": 24.99,
  "commission_rate": 12.0,
  "rating": 4.8,
  "orders_count": 2580,
  "category": "home",
  "aliexpress_url": "https://www.aliexpress.com/item/...",
  "affiliate_link": "https://s.click.aliexpress.com/e/..."
}
```

## 🎨 شكل الإعلان

```
🛒 اسم المنتج

📦 الوصف...

━━━━━━━━━━━━━━━━━━━━

💰 السعر الآن: $12.99
❌ كان: $24.99
🏷️ خصم: 50%

📈 العمولة: 12%
💵 ربحك: $1.56

━━━━━━━━━━━━━━━━━━━━

⭐ التقييم: 4.8/5
📦 الطلبات: 2580+

🔗 اطلب الآن:
[الرابط]

━━━━━━━━━━━━━━━━━━━━
⏰ العرض لفترة محدودة!
```

## 🌐 النشر على الخادم

### Render.com (مجاني)

1. أنشئ حساب على [Render](https://render.com/)
2. أنشئ Web Service جديد
3. اربط مستودع GitHub
4. أضف متغير البيئة `TELEGRAM_BOT_TOKEN`
5. اضغط Deploy

### Railway.app (مجاني)

1. أنشئ حساب على [Railway](https://railway.app/)
2. أنشئ مشروع جديد
3. اربط GitHub
4. أضف متغير البيئة `TELEGRAM_BOT_TOKEN`

## 📝 ملاحظات

- ⚠️ لا تستخدم صور تحتوي على أشخاص أو حيوانات
- ⏰ الإرسال المجدول كل ساعة
- 💰 الحد الأدنى للعمولة 8%
- 🔄 يتم تكرار المنتجات بعد انتهاء القائمة

## 🔒 الأمان

- لا تخزن التوكن في الكود مباشرة
- استخدم متغيرات البيئة
- لا تشارك روابط الأفلييت العامة

## 📞 الدعم

للمساعدة أو الاستفسارات، تواصل مع مطور البوت.
