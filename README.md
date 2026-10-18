# H2 Physics Flashcards

A responsive, static H2 Physics revision website themed with `#FCBACB`.

## Run locally
1. Download and unzip `physics-flashcards-website.zip`.
2. Open `index.html` in a modern browser. The site is static and does not need a server for normal use.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, e.g. `h2-physics-flashcards`.
2. Upload the contents of this folder to the repository root. Make sure `index.html` and `cards.js` are at the top level, not inside another nested folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then click **Save**.
6. Wait a minute or two. The Pages screen will show a URL like `https://YOUR-USERNAME.github.io/h2-physics-flashcards/`.
7. Open that URL on your phone, tablet, or computer. You can add it to your home screen for quick access.

## Revision behaviour
- Choose one chapter or the full syllabus.
- Each cycle is randomised.
- Reveal the answer before rating yourself.
- Correct cards leave the current session; missed cards return in a later cycle.
- Progress is stored in that browser/device using local storage. It does not automatically synchronise between devices.

## Important note about the current question bank
The included cards are an initial, editable set derived from the uploaded lecture notes' chapter topics and learning outcomes. Review them against your full notes before relying on them as a complete list of every definition and formula. To add/edit cards, edit `cards.js` and redeploy the repository.
