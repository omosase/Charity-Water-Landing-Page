
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Help Hope Flow — Nonprofit Landing Page</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
  <style>
    /* ========= Brand Identity ========= */
    :root{
      --yellow:#FFC907; /* Primary accent */
      --blue:#2E9DF7;   /* Primary brand blue */
      --ink:#111827;    /* Dark text */
      --bg:#FFFFFF;     /* Background */
      --muted:#6B7280;  /* Secondary text */
    }

    /* ========= Base Reset ========= */
    *,*::before,*::after{ box-sizing:border-box; }
    html,body{ margin:0; height:100%; }
    body{
      font-family:"Inter",system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;
      line-height:1.6;
      color:var(--ink);
      background:var(--bg);
    }
    img{ max-width:100%; display:block; height:auto; }
    # Charity Water Landing Page

    A small static landing page prototype for a clean-water nonprofit. Includes a responsive header, hero, impact story section, and donation CTA. Images used for the hero/story are stored locally in `assets/images/` to avoid signed-URL expiry.

    Files of interest

    - `index.html` — main landing page markup (open in a browser or serve with a static server).
    - `styles.css` — page styles extracted from the original inline CSS.
    - `assets/images/` — local image assets (hero and impact images).

    How to preview locally

    Open a terminal in the project root and run:

    ```bash
    python3 -m http.server 8000
    ```

    Then open http://localhost:8000 in your browser. The page will be served from `index.html`.

    Notes

    - I moved the site HTML into `index.html` and cleaned up CSS into `styles.css` for easier editing.
    - If you want an automated screenshot, I can install a headless browser tool (requires network access and permission).
    - To save changes to the remote repository, stage, commit, and push with git. Example commands:

    ```bash
    git add -A
    git commit -m "Describe your change"
    git push origin main
    ```
<title>Help Hope Flow — Preview</title>
