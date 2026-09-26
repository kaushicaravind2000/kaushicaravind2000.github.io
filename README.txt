Kaushic Aravind B - static portfolio bundle

Contents:
  portfolio/index.html    Resume-grounded portfolio
  signalscope/index.html  SignalScope interactive demo
  chess-prd/index.html    FIDE player workspace interactive spec

Each folder is a self-contained static site: it includes its own assets/ directory. No Instinct account or service is required. External reference links inside the chess spec still point to their cited public sources.

Recommended GitHub Pages layout: copy all three folders to the root of one Pages repository. Set Pages to deploy from the root of the main branch. Open /portfolio/ for the portfolio. The two project links within it use relative paths to /signalscope/ and /chess-prd/. Do not rename the folders unless you also update the links.

For a repository whose Pages URL ends with /<repo>/, use https://<username>.github.io/<repo>/portfolio/. A user/organization site repository (<username>.github.io) uses https://<username>.github.io/portfolio/. Verify the exact Pages URL and Settings in the GitHub account before sending it to anyone.

These are static demos; there is no live AI provider, backend or sign-in. SignalScope data and sample answers are synthetic. The chess workspace is an interactive concept specification with illustrative screens. The portfolio identifies these separately from production work.
