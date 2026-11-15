# mangoSTEEMS – Website Redesign (Draft)

A static, single-page redesign of mangosteems.asia using the mangoSTEEMS brand kit.
Includes new Student Showcase, Parent Reviews and Events sections.

- No build step, no dependencies. Everything is in `index.html` (logos are embedded).
- Reviews and event dates are **sample placeholders**. Edit the `shows` (student projects) and `evs` (events) arrays at the bottom of `index.html`, and the review cards in the `#reviews` section.

## Deploy on Vercel
1. Push this folder to a GitHub repository.
2. Go to vercel.com, sign in with GitHub, click **Add New → Project**, and import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Click **Deploy**. Vercel gives you a shareable link such as `your-project.vercel.app`.

Every `git push` to the main branch redeploys automatically.
