# 👑 تاجی شەترەنج (Crown Chess / Crown Chess 3D)

**تاجی شەترەنج (Crown Chess)** ئەپڵیکەیشنێکی پێشکەوتووی شەترەنجی سێ ڕەهەندییە (3D) لەگەڵ ئەلگۆریتمی **Glicko-2 ELO**، یاری ئۆنلاین بەکاتی ڕاستەقینە، ژیری دەستکردی بیرکەرەوە، و پشتگیری ٤ زمانی جیاواز (کوردی، English، العربية، فارسی).

---

## 🌟 تایبەتمەندییە سەرەکییەکان (Key Features)

- 🎮 **ڕووکاری سێ ڕەهەندی (3D Graphics & Physics):** جوڵاندن و جێگیرکردنی پوولەکان بە ئەنیمەیشنی زۆر خێرا، نەرم و سەرنجڕاکێش.
- 🏆 **سیستەمی ئیلۆی Glicko-2:** هەژمارکردنی ڕاستەقینەی خاڵی یاریزانان بەپێی ئەلگۆریتمی فەرمی FIDE Glicko-2.
- 🌐 **یاری ئۆنلاین (Online Multiplayer):** یاری بەرامبەر ڕکابەران لە سەرجەم جیهان لە ڕێگەی سێرڤەری Supabase Realtime.
- 🤖 **ژیری دەستکرد (AI Engine & Gemini Analysis):** یاری بەرامبەر بایتەکانی ژیری دەستکرد و شیکردنەوەی جوڵەکان بە هۆشی دەستکرد.
- 🌍 **پشتگیری ٤ زمان (Quad-Lingual Localization):** کوردی (Kurdish)، ئینگلیزی (English)، عەرەبی (Arabic)، فارسی (Persian).
- 📜 **تەواوکاری Season Pass & Quests:** ئەرکە ڕۆژانەیییەکان، دەستکەوتەکان (Achievements) و سیزن پاسی تایبەت.
- 🔐 **چوونەژوورەوەی ئاسایش (Supabase Auth & OTP):** تۆماربوون بە ئیمەیڵ لەگەڵ کۆدی پشتڕاستکردنەوەی ٨ ژمارەیی.

---

## 🛠️ تەکنەلۆجیاکانی بەکارهاتوو (Tech Stack)

- **Framework:** Flutter (Dart)
- **Backend & Auth:** Supabase (PostgreSQL, Row-Level Security, Realtime WebSockets)
- **State Management:** Provider
- **Chess Engine:** Custom Stockfish / Minimax Integration
- **AI Analysis:** Google Gemini API

---

## 🚀 ڕێنمایی دروستکردنی فایلی APK (How to Build Release APK)

بۆ دروستکردنی فایلی Release APK بۆ تاقیکردنەوە یان ڕەوانەکردن بۆ مۆبایل:

```bash
# ١. پاککردنەوەی پاشکۆ کۆنەکان
flutter clean

# ٢. وەرگرتنەوەی پەکێجەکان
flutter pub get

# ٣. دروستکردنی فایلی APKی نایاب و کەمکراوە
flutter build apk --release --split-per-abi
```

فایلی APK لەم بەستەرەی خوارەوەدا ئامادە دەبێت:
`build/app/outputs/flutter-apk/app-arm64-v8a-release.apk`

---

## 🔒 مافی کۆپی و پاراستن (License & Security)

© 2026 **Crown Chess Team**. سەرجەم مافەکانی کۆد و دیزاین پارێزراون (All Rights Reserved).
ئەم پڕۆژەیە بە شێوازی **Private Repository** پارێزراوە.
