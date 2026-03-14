## Dashboard Streamlit - Sample Project

פרויקט זה הוא **דאשבורד אינטראקטיבי** שנבנה עם `Streamlit`, `Pandas` ו־`Plotly Express`, שמדגים הצגה וניתוח של נתונים בצורה ויזואלית ונוחה.

---

### 🧩 מה יש בפרויקט?

- **`dashboard.py`** – אפליקציית Streamlit המציגה:
  - בחירת מדד מה־Sidebar: `Sales`, `Revenue`, `Users`, `Engagement`
  - כרטיסי מטריקות (KPIs) מסוכמים
  - גרף קווי דינמי לפי המדד הנבחר
  - טבלת נתונים מלאה
- **`test.py`** – סקריפט בדיקה קצר שמדפיס `"Hello world!"`

---

### 🚀 איך להריץ את הפרויקט מקומית

1. **שכפול הריפו**

```bash
git clone <URL-של-המאגר>
cd newproject-github
```

2. **יצירת סביבת עבודה (מומלץ)**

```bash
python -m venv .venv
source .venv/bin/activate  # ב-Windows: .venv\Scripts\activate
```

3. **התקנת חבילות נדרשות**

```bash
pip install streamlit pandas plotly
```

4. **הרצת הדאשבורד**

```bash
streamlit run dashboard.py
```

לאחר מכן הדפדפן ייפתח (או שתראה כתובת מקומית כמו `http://localhost:8501`) ותוכל לראות את הדאשבורד פועל.

---

### 📂 מבנה הפרויקט

```bash
newproject-github/
├─ dashboard.py   # אפליקציית הדאשבורד הראשית
├─ test.py        # סקריפט בדיקה פשוט
└─ README.md      # תיעוד הפרויקט (קובץ זה)
```

---

### 🛠 טכנולוגיות

- **שפה**: Python
- **Frontend / UI**: Streamlit
- **עיבוד נתונים**: Pandas
- **ויזואליזציה**: Plotly Express

---

### 💡 רעיונות להרחבה

- טעינת נתונים מקובץ `CSV` או ממסד נתונים אמיתי
- הוספת פילטרים מתקדמים (טווחי תאריכים, פילוח לפי אזור/מוצר וכו')
- הוספת סוגי גרפים נוספים (Bar, Pie, Area)
- הטמעת עיצוב מותאם אישית (Theme) ב־Streamlit

---

### 👤 קרדיט

פרויקט זה נוצר לצורכי תרגול / דמו וניתן להרחבה חופשית לפי הצורך.

