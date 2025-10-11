HR Connect — Project Entry

Overview

HR Connect is a free, open-source Laravel web application built to help Human Resources teams manage applicants efficiently — including invitations, rejections, and approvals — and send professional emails directly through Gmail (using an app password).

This repository is a portfolio site entry describing the project. The portfolio uses a static JSON file (`projects-data.json`) and `project-details.html` to render project pages.

How to preview locally

1. Run a local static server in the `portfolio` folder. From PowerShell you can run:

   python -m http.server 8000

   or if you have Node.js installed:

   npx serve .

2. Open the project details page in your browser:

   http://localhost:8000/project-details.html?id=hr-connect

Files added/modified

- `projects-data.json` — added `hr-connect` project entry
- `index.html` — added a project card for HR Connect to the Projects grid
- `assets/images/hr-connect.svg` — simple thumbnail used by the project card and details page

Notes

- The project entry uses `githubUrl` and `liveUrl` as `#` placeholders. Replace these with real links when available.
- `project-details.html` reads `projects-data.json` and will show the HR Connect details when opened with `?id=hr-connect`.

If you'd like, I can also:
- Add a dedicated `hr-connect.html` detail page with expanded screenshots and README
- Create a small public GitHub repo with starter Laravel boilerplate and instructions
- Add a live demo link (requires hosting)
