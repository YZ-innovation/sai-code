<div align="center">

# SAI Code

**תכנות AI מסונן — Claude Code עם סינון התוכן של SAI.**

[⬇️ הורדה ל-Windows](https://github.com/YZ-innovation/sai-code/releases/latest/download/SAI-Code-Setup.exe)
&nbsp;·&nbsp; macOS / Linux: ‎`curl -fsSL https://code.sai-app.com/install.sh | sh`

</div>

---

## מה זה?

SAI Code מאפשר להשתמש ב-Claude Code עם שכבת סינון תוכן חכמה — ממוקד בתכנות,
מותאם למגזר החרדי, ומחובר לחשבון SAI אחד (מאזן מאוחד עם הצ׳אט).

## התקנה

### 🪟 Windows

1. הורידו את המתקין: **[SAI-Code-Setup.exe](https://github.com/YZ-innovation/sai-code/releases/latest/download/SAI-Code-Setup.exe)**.
2. הריצו אותו — האשף מתקין אוטומטית את כל הנדרש (Node.js ו-Claude Code).
3. התחברו עם חשבון SAI ולחצו **"התחבר"**.
4. פתחו טרמינל והריצו `claude`.

**דרישות:** Windows 10/11.

### 🍎 macOS / 🐧 Linux

הגרסה ל-Mac/Linux היא **כלי שורת-פקודה (CLI)** — אין אפליקציה לגרור ל-Applications.
פתחו **Terminal** והריצו:

```sh
# 1) התקנת הכלי (מזהה אוטומטית מערכת + מעבד, כולל Apple Silicon נייטיב)
curl -fsSL https://code.sai-app.com/install.sh | sh

# 2) התקנת Claude Code עצמו (דרך SAI)
sai-code install

# 3) התחברות לחשבון SAI — נפתח דפדפן, מתחברים ומאשרים
sai-code activate

# 4) זהו — עובדים כרגיל, Claude Code כבר עובר דרך SAI:
claude
```

לבדיקה שהכול פעיל: `sai-code status` (אמור להראות **ENABLED**).

**דרישות:** Node.js 18+. אם חסר — התקינו מ-[nodejs.org](https://nodejs.org) או דרך `brew install node`.

**הערות:**
- ההתקנה שמה את `sai-code` ב-`/usr/local/bin` ולכן ייתכן שתתבקשו **סיסמת מנהל (sudo) פעם אחת** — זה תקין.
- ב-macOS הבינארי אינו חתום ב-notarization; ה-installer מטפל בזה אוטומטית. בהורדה ידנית ייתכן שתצטרכו לאשר ב-System Settings → Privacy & Security.

## פקודות שימושיות (Mac/Linux)

| פקודה | מה היא עושה |
|---|---|
| `sai-code activate` | התחברות לחשבון SAI + הפעלת ההפניה ל-Claude Code |
| `sai-code status` | מציג אם ההפניה פעילה |
| `sai-code disable` | כיבוי ההפניה (Claude Code חוזר לברירת המחדל) |
| `sai-code update` | עדכון לגרסה החדשה ביותר |
| `sai-code run -- <args>` | הרצת Claude Code עם ההפניה |

## קישורים

- 🌐 אתר: [code.sai-app.com](https://code.sai-app.com)
- 👤 חשבון ומסלולים: [account.sai-app.com](https://account.sai-app.com)

---

<div align="center"><sub>© SAI · כל הזכויות שמורות</sub></div>
