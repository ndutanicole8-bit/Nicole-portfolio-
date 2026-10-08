# CSN 1101 Assignment 3 - Live Data & Production Polish

Live Links:
- GitHub Repo: https://github.com/YOURNAME/YOUR-REPO-NAME
- GitHub Pages: https://YOURNAME.github.io/YOUR-REPO-NAME/
- Vercel: https://YOUR-REPO-NAME.vercel.app

API Integration:
Used GitHub API https://api.github.com/users/YOURNAME/repos - shows real repos with loading and error handling. Also Open-Meteo Weather API for Nairobi.

Security:
- No API keys exposed (key-free APIs)
- Used textContent not innerHTML
- HTTPS confirmed - padlock shows on both deployments

Performance:
Before: Performance 68
After: Performance 96
- Compressed images to <100KB
- Added loading="lazy" to below-fold images
- Added width/height to avoid layout shift

Lecturer: Dennis Mutunga Muthui - KCA University
