# מחולל ברקודים מאקסל

אפליקציית ווב סטטית בעמוד אחד שמייצרת PDF של ברקודים מקובץ Excel.
כל העיבוד מתבצע בדפדפן — שום קובץ לא עוזב את המחשב.

## מה זה עושה
- העלאת קובץ `.xlsx` / `.xls` / `.csv`
- זיהוי אוטומטי של עמודות (שם פריט וקוד ברקוד)
- הגדרות פריסה: ברקודים בשורה, שורות בעמוד, גובה ברקוד, סוג ברקוד
- שם קובץ חכם להורדה (לפי שם המקור + תאריך)
- יצוא PDF מוכן להדפסה (A4)

## איך מריצים
- מקומית: פותחים את `index.html` בדפדפן.
- ציבורית: כל אחסון סטטי (GitHub Pages / Netlify / Vercel / Cloudflare Pages).

## הטכנולוגיה
- [SheetJS](https://sheetjs.com/) — קריאת Excel
- [JsBarcode](https://github.com/lindell/JsBarcode) — יצירת ברקודים
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) — יצוא PDF

## רישיון
MIT — ראה [LICENSE](LICENSE).
