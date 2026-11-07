# Publishing this portfolio to GitHub

1. Create a new public repository on GitHub named `edwards-tech-portfolio` (or any name you prefer).
2. From the folder that contains this file, run:

   ```bash
   git init
   git add .
   git commit -m "Initial portfolio import from Google Sites"
   git branch -M main
   git remote add origin https://github.com/<username>/edwards-tech-portfolio.git
   git push -u origin main
   ```

3. Optional: copy `PROFILE-README.md` into a repository named exactly after your GitHub username
   (`<username>/<username>`) as `README.md`, and replace every `<username>` placeholder with your handle.
   GitHub shows that file at the top of your profile page.

4. Optional: enable GitHub Pages (Settings, then Pages, then Deploy from branch, `main` / root) to serve
   the Markdown pages as a simple website.

## Before you publish

- Review the screenshots under `assets/` for names, email addresses, or other details you do not want public.
  The Microsoft Bookings and Microsoft Teams screenshots in particular show staff names and contact details.
- Replace `<username>` in `PROFILE-README.md` and in this file.

## Maintaining

- Each section lives in its own folder with a `README.md` and matching images under `assets/<section>/`.
- Every solution entry follows the same four-part structure: Overview, Techniques, Challenge addressed, Intended use.
- Add new work by appending a numbered entry to the relevant section page and updating the counts in the root `README.md`.
