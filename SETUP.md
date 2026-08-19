# How to publish this profile

1. On GitHub, create a **new public repo named exactly `eishi0308`**
   (same as your username — GitHub treats it as your profile README).
   Do NOT add a README when creating it.

2. From this folder:

   ```bash
   cd ~/Desktop/eishi0308-profile
   git init -b main
   git add .
   git commit -m "Profile README"
   git remote add origin https://github.com/eishi0308/eishi0308.git
   git push -u origin main
   ```

3. Go to the repo → **Actions** tab → enable workflows → run
   **"Generate Snake Animation"** once manually (Run workflow button).
   This creates the `output` branch that the snake image is served from.
   Until that runs, the snake section shows a broken image — everything else works immediately.

4. Visit https://github.com/eishi0308 — it's live.

## Things to personalise
- LinkedIn + Portfolio badges near the bottom currently point to `#`. Replace with real URLs.
- The `whoami` code block: trim any stack you don't actually use. An honest short list
  beats a long aspirational one — recruiters check.
- Colours: the gradient is `8E2DE2 → 4A00E0 → 00D4FF` (purple→blue). Search/replace those
  hex codes to re-theme the whole page in one go.
