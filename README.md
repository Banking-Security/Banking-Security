[README.md](https://github.com/user-attachments/files/32431056/README.md)
# Payment Protection concept

This folder is ready for GitHub Pages. It is an independent, non-operational presentation prototype and is not an official Zions Bank service.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `app.js`, `styles.css`, and `concept.css` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

## How the saved reference file works

- The prototype displays a six-digit example payment reference.
- Any six-digit sample payment reference is accepted.
- When the demo report is submitted, that sample reference and simulated case result are saved in that browser using local storage.
- Open **Investigation desk** and select **Download CSV** to create `payment-reference-log.csv`.
- **Clear saved log** removes the browser-local records.
- No submission is sent to a server or committed back to GitHub. GitHub Pages is static and cannot safely edit repository files from a visitor's browser.

Do not modify this demonstration to collect passwords, one-time passcodes, account numbers, or real payment references.
