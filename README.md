# Hayden Parsons — Creative Portfolio

A responsive editorial portfolio built with React + Vite. Hosting can be free through Cloudflare Pages; a custom domain is optional and typically renews yearly.

## Preview on your computer

1. Install Node.js LTS from https://nodejs.org/ (if needed).
2. Open this folder in Visual Studio Code.
3. Open the terminal in this folder and run:

```bash
npm install
npm run dev
```

4. Open the local URL shown in the terminal (usually http://localhost:5173).

## Edit the website

- `src/projects.js`: all portfolio cards, descriptions, categories, project media and credits. **Review all text and credits before publishing.**
- `src/main.jsx`: homepage, About page, Contact page, navigation, and project templates.
- `src/style.css`: colors, typography, layout and animations.
- `public/`: put images, PDF résumé (after removing private details if desired), and other public assets here.
- To replace a project cover, put a file in `public/images/` and set `image:'/images/filename.jpg'` in `src/projects.js`.
- To add a video link, set `mediaUrl:'https://...'` in the corresponding project.
- Update the email and LinkedIn links in `src/main.jsx` if desired.

## Publish with GitHub and Cloudflare Pages

1. Create a new GitHub repository and upload the contents of this folder (not the outer ZIP file).
2. In Cloudflare Dashboard, go to Workers & Pages → Create → Pages → Connect to Git.
3. Select your repository, choose framework preset **Vite**, build command `npm run build`, and output directory `dist`.
4. Deploy. Cloudflare provides a free `pages.dev` address.
5. Add a custom domain in the project's Custom domains settings when ready.

## Important: Client privacy

The three communications campaigns are intentionally anonymous, and the cover art is illustrative—not actual client creative. Do **not** upload the original spreadsheets or unredacted screenshots. Review descriptions, project credits, client approvals, and any identifiable material before publishing.

## What's still a placeholder?

Existing portfolio media and images are not bundled, because original files/embeds were not supplied. The showreel and short-film cards are ready for your links; no footage or results have been invented. Project roles are deliberately marked for verification where needed. Contact currently uses a working email link rather than a form that requires a third-party backend.
