# Professor G. Venkat Raman

A static website for Professor G. Venkat Raman, Indian Institute of Management Indore: geopolitics, geoeconomics and China, seen through a realist's lens.

## What's inside

| File | Page |
| --- | --- |
| `index.html` | Home: positioning, the realist's lens, photographs, the globe, leadership, frameworks, latest writing, record and invitation |
| `profile.html` | Full profile: bio, academic leadership, honours, books, scholarship and teaching |
| `writing.html` | Positions and key quotes, plus the searchable writing archive |
| `videos.html` | Recordings, and lectures and keynotes filterable by audience |
| `assets/site.css` | Shared stylesheet (light and dark themes) |
| `photos/` | Photographs used across the site |

No build step and no dependencies to install. Fonts load from Google Fonts and the globe uses d3 from cdnjs.

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `venkat-raman`.
2. Upload everything in this folder to the repository root (drag and drop works on github.com, including the `assets` and `photos` folders).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select the `main` branch and the `/ (root)` folder. Save.
5. After a minute, the site is live at `https://<your-username>.github.io/<repository-name>/`.

To use a custom domain such as `venkatraman.in`, add it under **Settings → Pages → Custom domain** and point your domain's DNS to GitHub Pages.

## Preview locally

Open `index.html` in a browser, or run a small local server from this folder:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Keyboard shortcuts

Press `/` or `Ctrl/⌘ + K` on any page to search all articles, talks, videos and pages.

## Updating content

Articles, talks and videos are written directly into the HTML. To add a new article, copy an existing `<li>` in the archive on `writing.html` and edit its date, title, link, outlet and extract. Add the newest items to the top of the matching month.
