
### 🛠️ The Terminal Routine (Manual)

Whenever you finish a session in Quito and want to make sure it’s ready for your laptop:

1. **`git add .`** (The "Net" — catches every new file and folder).
    
2. **`git commit -m "Add new Marcia May drafts"`** (The "Label").
    
3. **`git push`** (The "Ship").
### The "Set It and Forget It" Way (Obsidian Git)

Since you have the **Obsidian Git** plugin installed, you can actually automate this so you never have to touch the terminal again.

1. **Go to Settings > Obsidian Git**.
    
2. **Vault backup interval:** Set this to **5** or **10** (This automatically runs the `add`, `commit`, and `push` every 5-10 minutes while you work).
    
3. **Auto pull interval:** Set this to **5** (This ensures your laptop "grabs" the new files automatically when you open it).
    
4. **List new files in commit message:** Toggle this **ON** so you can see exactly what changed in your GitHub history.
    

---

### 🏛️ The "Architect’s" Secret: `.gitignore`

As your vault grows, you’ll find files you **don't** want to sync (like temporary system files or large video drafts for your **Musician Training**).

If you see files you want to "hide" from GitHub, just add their name to your `.gitignore` file. This keeps your sync fast and your GitHub clean.