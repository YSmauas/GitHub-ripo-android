# ⚡ GitVault Pro — Web GitHub Manager & Sync

<p align="center">
  <img src="https://img.shields.io/badge/GitHub%20API-v3-2ea043?style=for-the-badge&logo=github" alt="GitHub API">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla%20ES6+-yellow?style=for-the-badge&logo=javascript" alt="JavaScript">
  <img src="https://img.shields.io/badge/UI-Glassmorphism-green?style=for-the-badge" alt="Glassmorphism">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
</p>

**GitVault Pro** הוא כלי דפדפן (Client-side) מתקדם, קל משקל ומעוצב, המאפשר לנהל, לסנכרן, להעלות קבצי ZIP ולהוריד מאגרים מ-**GitHub** ישירות מהדפדפן (מותאם במיוחד לעבודה מהטלפון הנייד או ממחשבים ללא Git מותקן).

---

## ✨ תכונות עיקריות

- 🚀 **העלאת ZIP וקמיט מהיר:** פריקת קבצי ZIP והעלאתם כקומיט יחיד ונקי ישירות לריפו.
- ⚡ **העלאה מקבילית (Concurrent Uploads):** העלאת קבצים מרובים באצוות (Chunks) מבוססות `Promise.all` למהירות מירבית.
- ➕ **יצירת Repository חדש:** פתיחת מאגר פרטי או ציבורי חדש ב-GitHub בלחיצת כפתור ישירות מהממשק.
- ⬇️ **הורדת הריפו הקיים:** הורדת המאגר הנבחר ישירות כקובץ ZIP למכשיר (כולל תמיכה במאגרים פרטיים).
- 🌲 **תצוגת עץ (Tree View):** סייר קבצים היררכי המציג את מבנה התיקיות לפני הביצוע, עם אפשרות לבחירת קבצים ספציפיים.
- 🔍 **סינון קבצים חכם (Ignore Patterns):** הגדרת תבניות להתעלמות מקבצים (כגון `node_modules/`, `*.map`, `.DS_Store`).
- 🔀 **תמיכה ב-Pull Requests:** אפשרות ליצירת קומיט ישיר לברנץ' הבסיס או פתיחת ברנץ' חדש ו-PR אוטומטית.
- 💾 **שמירה מקומית (LocalStorage):** שמירה בטוחה של הטוקן וההגדרות בדפדפן לעבודה שוטפת ונוחה.
- 📊 **מחוון API Rate Limit:** מעקב בזמן אמת אחר מגבלת הקריאות הנותרות ב-Personal Access Token שלך.
- 🎨 **עיצוב Glassmorphism מודרני:** ממשק זכוכית ירוק כהה, רספונסיבי ומותאם באופן מלא למכשירים ניידים.

---

## 🛠️ איך משתמשים?

1. **הזנת הטוקן:** הזינו **Personal Access Token** מ-GitHub עם הרשאת `repo`.
2. **טעינת / יצירת מאגר:**
   - לחצו על **"טען פרויקטים"** ובחרו את המאגר המבוקש.
   - או לחצו על **"＋ חדש"** כדי לפתוח Repository חדש ב-GitHub.
3. **בחירת קבצים:** גלגלו קובץ ZIP או קבצים בודדים לאזור ההעלאה.
4. **ביצוע הקומיט:** הזינו הודעת קומיט ולחצו על **"דחיפה ל-GitHub"**.

---

## 🔒 אבטחה ופרטיות

- **100% Client-Side:** הקוד רץ כולו בדפדפן שלכם. הטוקן האישי אינו נשלח לשום שרת צד-שלישי מלבד ה-API הרשמי של GitHub (`api.github.com`).
- **אחסון מקומי:** הטוקן נשמר ב-`localStorage` של הדפדפן שלכם בלבד.

---

## 📄 רישיון

פרויקט זה מופץ תחת רישיון MIT.