# AI Military Career Navigator

**INSS 780-557 · Group 1 — Student Practicum Prototype**

This repository currently contains the two project pages supplied for this portion of the group project:

- `career-recommendations.html` — displays up to three illustrative civilian career matches.
- `gap-analysis.html` — displays example skills, qualifications, education gaps, certifications, and next steps for a selected career.
- `index.html` — simple project landing page.
- `assets/` — shared CSS, JavaScript, and logo.

## Run locally

Open the folder in Visual Studio Code and use the Live Server extension, or open `index.html` in a browser.

## Publish with GitHub Pages

1. Create a GitHub repository named `military-career-navigator`.
2. Upload all files and folders in this project.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. Open the published URL shown in the Pages settings.

## Important notes

- The career recommendation scores use simple keyword matching; this prototype does not call an AI model.
- The gap-analysis content is illustrative and is not verified O*NET occupational data.
- The pages use browser `localStorage` to pass the selected career and any saved profile information between pages on the same browser and site.
- Use fictional test profiles only. This is not a production account system or verified career-advice service.
- The remaining group pages (profile, education, skills translation, training, and pathway) can be added by teammates as they are completed.