# Who Are You, Really?

A no-build, mobile-first personality quiz website. It uses plain HTML, CSS and JavaScript, so there are no dependencies, build commands, API keys or paid services.

## Run it locally
1. Download and unzip the project.
2. Open `index.html` in a browser.

## Publish with GitHub + Vercel
1. Create a new **public or private** GitHub repository.
2. Upload `index.html`, `style.css`, `script.js`, and this README to the repository's root.
3. Go to https://vercel.com/ and sign in with GitHub.
4. Select **Add New → Project**, then import your repository.
5. Keep the framework preset as **Other**.
6. Leave Build Command and Output Directory empty (or use `.` as the output directory if prompted).
7. Click **Deploy**.

Vercel will publish the site and provide a URL.

## Customise
- Questions and answer choices: edit the `questions` array in `script.js`.
- Personality descriptions: edit the `profiles` array in `script.js`.
- Colours and layout: edit `style.css`.

## Notes
- This is an entertainment quiz, not a scientific psychological assessment.
- Results and recent history are stored in the visitor's browser using `localStorage`.
- There is no login, server, database, or global leaderboard.
- The Google Fonts import requires an internet connection; system fonts will be used if unavailable.
