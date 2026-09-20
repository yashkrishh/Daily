---
{"dg-publish":true,"permalink":"/untitled/","dg-note-properties":{}}
---

Your website currently shows the generic fallback page because no note has been designated as your home page yet.

To make your home page look clean and personal, create a dedicated index note in Obsidian and set it as your garden's landing page.

**1.Create a Home Page Note in Obsidian:**

Create a new note titled **Index** (or **Home**) and design your welcome landing page. Here is a clean Markdown template you can copy:

Markdown

```
---
dg-publish: true
---

# Welcome to My Learning Garden 🌱

Hi, I'm Yashwant! This is where I document everything I learn on a daily basis.

---

### 📚 Daily Logs
* [[hi there]]
* [[new]]

### 📌 Topics I Cover
* Software Engineering
* Productivity & Workflows
* Tech & Notes
```

**2.Set as Garden Home Page:**

1. With your **Index** note open in Obsidian, open the Command Palette (`Ctrl + P` or `Cmd + P`).
    
2. Type and select: **Digital Garden: Set as Garden Home Page**.
    
3. Alternatively, right-click the note title in the left sidebar and select **Set as Garden Home Page**.
    

**3.Publish the Home Page:**

1. Open the **Publication Center** (leaf icon).
    
2. Check `Index.md` (or your chosen home note) and click **Publish selected**.
    

**4.Apply a Theme (Optional):**

To make the whole site prettier:

1. Go to **Settings** > **Digital Garden** > **Appearance**.
    
2. Under **Theme**, pick a modern style (like _Catppuccin_, _Dracula_, or _Things_).
    
3. Publish any note again to force the site style to update on Vercel.
    

To verify, refresh `[https://daily-nine-gamma.vercel.app](https://daily-nine-gamma.vercel.app)` after 15–20 seconds—the fallback list will be replaced by your custom welcome page.