# Portfolio Site

This is a self-contained static portfolio for Ankit Goila. Open `index.html` in a browser to view it.

## Quick Edits

- Update name, headline, bio, project details, timeline, interests, and links in `index.html`.
- Replace the generated images in `assets/` with screenshots or visuals from your real projects.
- Tune colors and layout in `styles.css`.

## Starter Sections

- Projects: three case-study slots with filters for AI, product, and systems work.
- Timeline: a five-step industry arc from foundations to current direction.
- Interests: four short areas of focus.
- Contact: email, LinkedIn, and GitHub links.

## Deploying on Vercel

This project is ready to deploy as a static site from the project root.

### Option 1: Vercel Dashboard

1. Create a GitHub repository and push these files.
2. In Vercel, choose **Add New > Project**.
3. Import the repository.
4. Leave the framework preset as **Other**.
5. Leave build/output settings empty.
6. Deploy.

### Option 2: Vercel CLI

If the Vercel CLI is installed and you are logged in:

```sh
vercel --prod
```

The `vercel.json` file adds clean URLs and long-lived caching for files in `assets/`.
