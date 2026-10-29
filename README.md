# RuniSkills

תשעה סקילים לקורס. כל תיקייה בשורש היא פלאגין נפרד, עם `SKILL.md`, `assets/`, `references/` ו-`scripts/`.

## התקנה מתוך Cursor

1. פתחו **Customize** בסרגל הצד.
2. בחרו **From GitHub Repository**.
3. הדביקו `https://github.com/airunihubteam/RuniSkills`.
4. התקינו רק את הסקיל שאתם צריכים.

אחרי ההתקנה, הקלידו `/` בצ'אט של Agent ובחרו את שם הסקיל. כדי להשאיר אותו פעיל לכל השיחה: Option+Enter ב-Mac, או Alt+Enter ב-Windows.

בארגון עם Cursor Teams אפשר גם לייבא את אותו כתובת כ-Team Marketplace, ואז כל חבר צוות מתקין מהרשימה.

## התקנה מהטרמינל

סקיל אחד, לכל הפרויקטים:

```bash
gh skill install airunihubteam/RuniSkills product-prd-agent/SKILL.md --agent cursor --scope user
```

החליפו את `product-prd-agent` בשם התיקייה. בלי `--scope user` הסקיל מותקן רק בפרויקט הנוכחי.

## הסקילים

| סקיל | מתי להשתמש |
| --- | --- |
| `cursor-skill-foundation` | כתיבה או שיפור של סקיל, כלל, או expertise |
| `product-prd-agent` | הפיכת רעיון למסמך מוצר |
| `ux-user-flow-agent` | מסלולי משתמש ולוגיקת מסכים |
| `ui-design-systems-agent` | תוכנית UI, קומפוננטות וטוקנים |
| `tech-lead-architecture-agent` | החלטות טכניות ופרוסות מימוש |
| `dev-composer-agent` | מימוש פיצ'ר בפרוסות קטנות |
| `debug-fix-agent` | איתור תקלה ותיקון ממוקד |
| `quality-gate-agent` | בדיקת מוכנות למיזוג |
| `security-review-agent` | סקירת סיכוני אבטחה לפני שחרור |
