# מקורות — הקרחון של ה‑AI בפיננסים (v2)

נבדק בנובמבר 2026. נכללו רק שמות יכולות וטענות אבטחה שאומתו בתיעוד רשמי של הספק. אם יכולת לא אומתה, היא הושמטה.

## מדיניות אימון על נתונים

### OpenAI / ChatGPT
- [Enterprise privacy at OpenAI](https://openai.com/enterprise-privacy/) (עודכן 8 בינואר 2026): כברירת מחדל OpenAI לא מאמנת מודלים על נתוני ChatGPT Business, Enterprise, Edu, Healthcare ופלטפורמת ה‑API.
- [Data controls in ChatGPT](https://help.openai.com/en/articles/7730893-data-controls-in-chatgpt): אותה התחייבות ל‑workspaces מנוהלים; בתוכניות אישיות (Free, Plus, Pro) שיתוף לאימון דלוק כברירת מחדל, וניתן לכבות ב‑Settings > Data controls.
- [How your data is used to improve model performance](https://help.openai.com/en/articles/5722486-how-your-data-is-used-to-improve-model-performance): בתוכניות אישיות, משוב (thumbs up/down) עשוי לאפשר אימון על השיחה גם אחרי opt-out; ב‑Business/Enterprise/Edu משוב אינו מאפשר אימון אלא בהסכם נפרד.
- [Managing data, sharing, and privacy in ChatGPT Business](https://help.openai.com/en/articles/8798634-managing-data-sharing-and-privacy-in-chatgpt-business): נתוני Business מוצאים מאימון כברירת מחדל.

### Anthropic / Claude
- [Is my data used for model training? (commercial)](https://privacy.claude.com/en/articles/7996868-is-my-data-used-for-model-training) (18 באוגוסט 2026): במוצרים מסחריים (Claude for Work, API) הקלט והפלט לא משמשים לאימון כברירת מחדל, אלא אם הארגון בוחר במפורש (למשל Development Partner Program או משוב).
- [Does Anthropic Act as a Data Processor or Controller?](https://privacy.claude.com/en/articles/9267385-does-anthropic-act-as-a-data-processor-or-controller): ב‑Claude for Work (Team/Enterprise) הלקוח הוא Controller ואנתרופיק הוא Processor.
- [Is my data used for model training? (consumer)](https://privacy.claude.com/en/articles/10023580-is-my-data-used-for-model-training) (16 במרץ 2026): ב‑Free, Pro ו‑Max האימון תלוי בהגדרת הפרטיות (opt-in לשיפור המודלים), עם חריגים לשיחות שמסומנות לבטיחות.

### Microsoft / Microsoft 365 Copilot
- [Enterprise data protection in Microsoft Copilot and Microsoft Copilot Chat](https://learn.microsoft.com/en-us/copilot/plan/enterprise-data-protection): prompts, responses ונתוני Microsoft Graph לא משמשים לאימון מודלי יסוד; חל Data Protection Addendum (DPA); Copilot מכבד הרשאות, תוויות רגישות ומדיניות הארגון.
- [Data, Privacy, and Security for Microsoft 365 Copilot](https://learn.microsoft.com/en-us/copilot/microsoft-365-copilot-privacy): אותה התחייבות; עיבוד דרך Azure OpenAI ולא השירות הציבורי של OpenAI.
- [Privacy FAQ for Microsoft Copilot](https://support.microsoft.com/en-us/microsoft-copilot/privacy-faq-for-microsoft-copilot): אימון מודלים חל על חוויית הצרכן; אינו חל על משתמשי Copilot עם חשבון Entra ID ארגוני.

### Google / Gemini ב‑Workspace
- [Generative AI in Google Workspace Privacy Hub](https://knowledge.workspace.google.com/admin/generative-ai/generative-ai-in-google-workspace-privacy-hub) (עודכן 6 באוקטובר 2026): ב‑Workspace מתאים, פרומפטים, תוכן Workspace ותשובות לא משמשים לאימון בלי רשות; חל Cloud Data Processing Addendum (CDPA). כולל Gemini in Workspace, אפליקציית Gemini, ו‑Gemini Notebook (לשעבר NotebookLM).
- [Google Workspace Service Specific Terms](https://workspace.google.com/terms/service-terms-20251007/), סעיף 12.11: Google לא תשתמש בנתוני לקוח לאימון או כיוונון מודלים בלי רשות או הוראה מראש.
- [Gemini Apps Privacy Hub / history](https://support.google.com/gemini/answer/13594961) ו‑[Manage & delete your history in Gemini Apps](https://support.google.com/gemini/answer/13278892): בחשבון אישי, כשההיסטוריה דלוקה (ברירת מחדל מגיל 18), תוכן השיחות עשוי לשמש לאימון; ניתן לכבות בהגדרות.

## יכולות לפי שכבה

### שכבה 1 — שאלה בצ׳אט
זמין בכל ארבעת הכלים כשיחת עזרה כללית: ChatGPT Chat, Claude, Microsoft Copilot Chat, אפליקציית Gemini.

### שכבה 2 — פרויקטים / הקשר שנשמר
- ChatGPT Projects: https://help.openai.com/en/articles/10169521-projects-in-chatgpt
- Claude Projects: https://www.anthropic.com/news/projects
- Copilot Notebooks: https://www.microsoft.com/en/microsoft-365-copilot (מרחב שמאגד קבצים, פגישות, מיילים והערות; הקשר שנשמר לפרויקט)
- Gemini Gems: https://support.google.com/gemini/answer/15146780

### שכבה 3 — סקילים והנחיות
- Claude Skills: https://claude.com/resources/articles/skills ו‑https://claude.com/docs/skills/overview
- הנחיות פרויקט ב‑ChatGPT: https://help.openai.com/en/articles/10169521-projects-in-chatgpt
- Microsoft 365 Copilot Agent Builder / declarative agents: https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder-build-agents
- Gemini Gems: https://support.google.com/gemini/answer/15146780  
  (Skills ב‑Gemini החלו בהשקה ב‑2026 ואמורים להחליף בהדרגה את Gems; במצגת נשמר השם Gems שכבר היה בגרסה הקודמת.)

### שכבה 4 — תוצר מוגמר / יצירת קבצים
- Claude: יצירת Excel, PowerPoint, Word ו‑PDF דרך Skills — https://claude.com/resources/articles/skills
- Gemini: יצירת קבצים באפליקציית Gemini (Docs, Sheets, Slides, PDF, Word, Excel ועוד) — https://blog.google/innovation-and-ai/products/gemini-app/generate-files-in-gemini/ (29 באפריל 2026) ו‑https://workspaceupdates.googleblog.com/2026/10/create-preview-and-edit-files-directly-in-the-Gemini-app.html
- ChatGPT ו‑Copilot צוינו ביצירת קבצים כבר בגרסה הקודמת; לא הורחבו מעבר לכך בלי מקור נקודתי נוסף.

### שכבה 5 — בתוך Excel / PowerPoint / Sheets
- Claude for Excel / PowerPoint: https://claude.com/claude-for-excel
- Copilot in Excel, PowerPoint, Outlook, Teams: https://www.microsoft.com/en-us/copilot/pricing/business ו‑https://learn.microsoft.com/en-us/office365/servicedescriptions/office-365-platform-service-description/microsoft-365-copilot
- Gemini in Docs, Sheets, Slides: https://support.google.com/docs/answer/15123226 ו‑https://knowledge.workspace.google.com/admin/generative-ai/workspace-with-gemini/google-workspace-with-gemini

### שכבה 6 — קונקטורים / ידע ארגוני
- Claude, קונקטור Microsoft 365: https://claude.com/docs/connectors/microsoft/365
- Microsoft 365 Copilot ו‑Microsoft Graph (גישה לפי הרשאות המשתמש; Copilot connectors למערכות חיצוניות): https://learn.microsoft.com/en-us/copilot/plan/enterprise-data-protection ו‑https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/overview-copilot-connector
- Gemini: אפליקציות מחוברות ו‑Gemini ב‑Gmail, Docs, Drive ו‑Workspace — https://knowledge.workspace.google.com/admin/generative-ai/workspace-with-gemini/google-workspace-with-gemini
- ChatGPT Apps / Company knowledge הוזכרו בטבלת ההשוואה על סמך תיעוד OpenAI: https://help.openai.com/en/articles/11487775-connected-apps-in-chatgpt ו‑https://help.openai.com/en/articles/12628342-company-knowledge-in-chatgpt

### שכבה 7 — דשבורד על נתוני החברה
- Claude Data / Dashboards (חיבור ל‑Snowflake, BigQuery, Databricks, Redshift, Salesforce ועוד): https://claude.com/resources/articles/dashboards-and-motion ו‑https://claude.com/resources/articles/sheets-whiteboards-data
- ChatGPT Data agent (ב‑ChatGPT Work, עם Data plugin): https://openai.com/index/put-data-to-work/ ו‑https://help.openai.com/en/articles/20001518-using-the-data-plugin-in-chatgpt-work-and-codex
- Copilot בתוך דוחות Power BI (נדרשת קיבולת Fabric F2+ או Power BI Premium, והגדרת אדמין): https://learn.microsoft.com/en-us/power-bi/create-reports/copilot-introduction
- **הושמט:** מקבילה ישירה ב‑Gemini לדשבורד חי על מחסן נתונים — לא אומתה בתיעוד שנבדק, ולכן לא צוינה בשכבה 7.

## רמות האבטחה במצגת
הרמות (נמוכה / בינונית / גבוהה) הן המלצת עבודה לאנשי כספים, לא תו תקן של הספק:

| שכבה | רמה | למה |
| --- | --- | --- |
| 1 | נמוכה | שאלות כלליות בלי נתוני לקוחות או קבצים |
| 2–3 | בינונית | קבצי עבודה או הנחיות קבועות; תוכנית עסקית בלי אימון כברירת מחדל; בלי פרטים מזהים בלי אישור |
| 4–7 | גבוהה | קבצי חברה, קובץ חי, קונקטורים או מחסן נתונים; תוכנית עסקית/ארגונית, DPA, אישור אדמין לפי הצורך, הרשאות הארגון |

המדיניות המחייבת היא של הארגון ושל הספק, והיא מתעדכנת.
