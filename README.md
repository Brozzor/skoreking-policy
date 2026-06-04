# SkoreKing — Privacy Policy

The privacy policy page for the **SkoreKing** app (a score counter for the *Skull King* card game),
hosted on GitHub Pages.

🔗 **Live URL (once Pages is enabled):** https://brozzor.github.io/skoreking-policy/

## Files

| File          | Purpose                                              |
| ------------- | ---------------------------------------------------- |
| `index.html`  | The privacy policy page (self-contained HTML + CSS). |
| `icon.png`    | App icon, used as the page logo + Apple touch icon.  |
| `favicon.png` | Browser tab favicon.                                 |
| `.nojekyll`   | Tells GitHub Pages to serve files as-is (no Jekyll). |

## ⚠️ Before publishing

Open `index.html` and replace the placeholder contact email **`your-email@example.com`**
(it appears in an HTML comment and in the Contact section) with your real address.

## Deploy on GitHub Pages

1. Create a public repo named `skoreking-policy` on the `Brozzor` account and push these files:
   ```bash
   cd skoreking-policy
   git init
   git add .
   git commit -m "Add SkoreKing privacy policy page"
   git branch -M main
   git remote add origin https://github.com/Brozzor/skoreking-policy.git
   git push -u origin main
   ```
2. On GitHub: **Settings → Pages → Build and deployment**
   - **Source:** *Deploy from a branch*
   - **Branch:** `main` / `/ (root)` → **Save**
3. Wait ~1 minute. Your policy is live at:
   **https://brozzor.github.io/skoreking-policy/**

## Use the URL in the stores

Paste that URL into the **Privacy Policy URL** field of your App Store Connect and
Google Play Console listings.
