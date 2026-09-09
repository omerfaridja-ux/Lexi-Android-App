# Lexi - תרגום אנגלית ⇄ עברית

![Lexi App Icon](assets/icon.png)

**Lexi** היא אפליקציה מהירה ופשוטה לתרגום מילים בין אנגלית לעברית.

## ✨ תכונות

- ✅ תרגום מיידי אנגלית ↔ עברית
- ✅ חיפוש קולי (Speech Recognition)
- ✅ הגיה טבעית (Text-to-Speech)
- ✅ ממשק RTL/LTR אוטומטי
- ✅ עבודה אופליין (אחרי טעינה ראשונה)
- ✅ ממשק נקי ויפה

## 🚀 התקנה

### דרך 1: APK ישיר (הדרך הקלה ביותר)
1. הורד את ה-APK מ-[Releases](https://github.com/omerfaridja-ux/Lexi-Android-App/releases)
2. התקן על הטלפון שלך (אם קיבלת אזהרה, לחץ "Install anyway")

### דרך 2: בנייה מקומית

#### דרישות מקדימות:
- **Java JDK 11+**
- **Android SDK** (מ-Android Studio)
- **Node.js 16+**
- **Capacitor CLI**

#### צעדים:

```bash
# 1. התקן dependencies
npm install

# 2. הוסף את Android
npm run android

# 3. בנה את ה-APK
npm run build:android
```

ה-APK יהיה ב: `android/app/build/outputs/apk/release/app-release.apk`

## 📱 שימוש

1. **הקלד מילה** בעברית או אנגלית
2. **בחר שפה** (אם רוצה חיפוש קולי)
3. **לחץ על המיקרופון** לחיפוש קולי
4. **לחץ על הרמקול** להגיה

## 🛠️ פיתוח

### מבנה הפרויקט:
```
.
├── www/
│   └── index.html          # האפליקציה הראשית
├── android/                # קובצי Android Studio
├── capacitor.config.json   # הגדרות Capacitor
├── package.json            # Dependencies
└── README.md
```

### שינוי עיצוב:
ערוך את ה-CSS ב-`www/index.html`

### שינוי לוגיקה:
ערוך את ה-JavaScript ב-`www/index.html`

## 🌐 API

Lexiash משתמש ב-2 שרתי תרגום בחינם:
1. **Google Translate** (ראשי)
2. **MyMemory API** (גיבוי)

## 📄 רישיון
MIT License - בחופשיות להשתמש ולשנות

## 👤 יוצר
**@omerfaridja-ux**

---

**שאלות? Issue או דיון!** 💬