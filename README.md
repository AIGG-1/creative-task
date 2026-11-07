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
| `version/v4` | Hero split into 3 lines + $1M+ total spend badge, Mobile app / Web2Web funnel switch, favicon |
| `version/v5` | Niches: AI Photo & Video editors, AI Assistants, Language learning |
| `version/v6` | 14+ niches, updated toolkit (AI video, AI image & sound) |
| `version/v7` | Free audit of 3 creatives offer, sticky mobile CTA, fix mobile page width |
| `version/v8` | Link preview (OG tags + og.png cover), new Background section, page title without placeholder name |
| `version/v9` | Full-cycle advantage: one specialist does script, generation and editing (Edge panel + Work note) |
| `version/v10` | "3–4 people" → "a team" in the full-cycle comparison |
| `version/v11` | A/B-test hero (A killed / B winner), REC · RESULTS label above stats, subtle film grain |
| `version/v12` | Role moved into the header logo, A/B test bar without the role tag |
| `version/v13` | Sharp 4px corners everywhere, viewfinder frames on key blocks (winner B, stats, main case, full-cycle panel, free audit) |
| `version/v14` | Removed REC label; added $10–25 avg purchase CPA by geo and niche (hero badge, stats tile, main case) |
| `version/v15` | Emerald accent (#2FD48A), less accent area, warm white text; favicon and link cover recolored |
| `version/v16` | Pistachio accent (#B5E07A) with full accent fills, as in the palette preview; favicon and link cover recolored |
| `version/v17` | Hand-drawn notes: arrow into the winner card, sad face on A, underline, circled stat, star on $1M+, "that's me", "start here"; sketch icons beside Paid / Organic / Content |

To roll back, the live site is pointed at an older version: `git push --force origin version/v2:main`.

## Reserve variants

| Branch | What it is |
|---|---|
| `variant/pistachio` | v14 with a pistachio accent (#B5E07A) instead of acid lime, kept in reserve |
