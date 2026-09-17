# Bruno Martins personal site support repo

This repository is a small support/configuration repo for the personal website of Bruno Martins.

It mainly contains the domain and email-related configuration used alongside the main website in the `www.bmartins.pt` project, including:

- the `CNAME` record for the site
- an MTA-STS policy file under `.well-known/mta-sts.txt` for email security
- general domain-level support configuration for the personal web presence

The actual content site lives in the separate `www.bmartins.pt` repository and is a static personal website with:

- a home page linking to social and professional profiles
- an about page describing Bruno's career, skills, certifications, and interests
- a contact page with a form for reaching out
- lightweight serverless backend handling form submission via Netlify Functions
- dark mode and bilingual content support

In short, this repo complements the public site by handling domain and email posture, while the website repo contains the actual user-facing content and contact functionality.
