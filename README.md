# WhatsApp Rust Bot — Linux x86_64

نسخة تشغيل جاهزة للبوت لمعمارية **Linux x86_64**.

## التشغيل

1. حمّل الملف `whatsapp-rust-bot-linux-x86_64.zip` وفك ضغطه.
2. انسخ `.env.example` إلى `.env`.
3. ضع رقم WhatsApp الدولي في `WHATSAPP_PHONE_NUMBER`.
4. ضع ملف `cookies.txt` بصيغة Netscape بجانب الملف التنفيذي؛ سيكتشفه البوت تلقائيًا. أو حدّد مسارًا مخصصًا عبر:

```env
YTDLP_COOKIES_PATH=/path/to/cookies.txt
```

5. شغّل:

```bash
./run.sh
```

الحزمة مخصصة لـ Linux x86_64 فقط. يمكن تشغيلها عبر `./run.sh` أو `./start.sh`. ملف الكوكيز غير مضمن في المستودع لحماية جلسة الحساب، ولا توجد ملفات Release؛ الحزمة مرفوعة كملف عادي داخل المستودع.
