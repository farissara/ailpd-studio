# AILPD Pre/Post Studio

QRTA Monitoring & Evaluation dashboard for the Advanced Instructional Leadership Diploma pre/post survey:
data check, one-click Copilot marking through Microsoft 365, and an impact dashboard in English and Arabic.

**Live:** https://farissara.github.io/ailpd-studio/

- Survey data is read in the browser and goes only to the signed-in user's OneDrive. Nothing is sent to GitHub.
- The marking rubric is not in this repository. It is loaded from a private `rubric-pack.json` in the user's OneDrive after Microsoft sign-in.
- Sign-in uses Microsoft Entra ID (MSAL.js, MIT licence) with delegated `User.Read` and `Files.ReadWrite` only.

This repository contains only the built page (`index.html`).
