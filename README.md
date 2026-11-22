# Dawit Dkt — Developer Portfolio

A static, responsive portfolio featuring Fast Menja, a Flutter driving-theory learning app for UK learner drivers.

## Preview locally

Serve the static site from the `site` directory:

```sh
python3 -m http.server 3000 --bind 0.0.0.0 --directory site
```

Then open `http://localhost:3000` in a browser.

## Publish to GitHub Pages

The portfolio is designed for the account-level Pages address `https://dawitdkt.github.io/`. The workflow in `.github/workflows/pages.yml` uploads the `site` directory and deploys it whenever a commit reaches `main`, or when the workflow is run manually.

The repository's Pages publishing source must be set to **GitHub Actions**. The site is plain static HTML, CSS, and JavaScript and needs no package installation or backend.

## Content scope

The Fast Menja details on the page are based on the repository's README, `IMPLEMENTATION_COMPLETE.md`, and `pubspec.yaml`. The feature-map illustration is explicitly identified as a portfolio illustration, not a screenshot. No performance results or personal contact details are invented. GitHub is the listed contact route because no public email or contact page is listed on the profile.

## Image credit

The road photograph is from [Unsplash](https://unsplash.com/photos/winding-road-through-golden-moorland-lCwmiPF8aM4), and is used under the [Unsplash License](https://unsplash.com/license). It is included in `site/assets/fast-menja-road.jpg`.
