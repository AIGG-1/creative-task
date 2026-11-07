# creative-task

Portfolio site for a Creative Lead / Creative Producer.

Single static page: `index.html`. Hosted on GitHub Pages.

## Editing videos

Open `index.html`, find the `VIDEOS` array in the `<script>` block and paste a Google Drive file ID into `id`.
The Drive file must be shared as "Anyone with the link → Viewer".

## Versions

Every change to the site is saved as its own branch `version/vN`. `main` is always the live version.

| Version | What changed |
|---|---|
| `version/v1` | First version of the site |
| `version/v2` | Each section redesigned in its own format, featured $1M+ case |
| `version/v3` | Hero headline no longer splits numbers, new Edge section (own AI system + full funnel), corrected $1M+ case text |

To roll back, the live site is pointed at an older version: `git push --force origin version/v2:main`.
