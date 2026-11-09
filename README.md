# Semantic Letter Search — Theme Tags Demo v3

Static GitHub Pages demo: eight clickable theme tags, mixed direct/semantic concept matches, and one short, highlighted excerpt per result. Each theme is curated to **2–3 pages of 30 results** (at most 72 theme-specific entries). No Reclaim API, database, JavaScript packages or CORS configuration needed.

## Source and cautions

- Derived offline from a user-supplied archived `export-5.csv` snapshot (not queried live).
- Context-refined theme vocabulary v0.2. `ambiguous_without_context` and all other rejected evidence are excluded.
- The demo **selects** results from the larger candidate collection, not an exhaustive search. Featured order interleaves literal theme mentions with semantic concept matches.
- Each item exposes only title, date, sender, recipient, one **short excerpt** (max 185 characters, plus ellipses), one matched term/group, and the real public Item URL. It does not contain full letters, an Omeka export, access keys, private credentials, or the complete thematic inventory.
- The excerpts and metadata in `index.html` remain publicly downloadable once committed to GitHub; **ScholarlyAccess cannot enforce policy on static GitHub assets**. Before publishing, confirm the selected records are still public and that this republication is permitted under the site's access/reuse policy. Do not assert compliance merely because only excerpts are present.
- All theme match labels are algorithmic candidates, not individually human-validated research judgments.

## Selected results (public demo data)

| Theme | Selected | Direct theme mentions | Related-concept matches | Pages | Larger offline candidate set |
|---|---:|---:|---:|---:|---:|
| Music | 72 | 24 | 48 | 3 | 390 |
| Religion & Belief | 72 | 24 | 48 | 3 | 539 |
| Writing & Publishing | 72 | 24 | 48 | 3 | 2206 |
| Health & Illness | 72 | 24 | 48 | 3 | 1304 |
| Women & Education | 58 | 2 | 56 | 2 | 58 |
| Philosophy & Science | 72 | 24 | 48 | 3 | 495 |
| Travel & Places | 72 | 24 | 48 | 3 | 1088 |
| Friendship & Relationships | 72 | 24 | 48 | 3 | 1646 |

## Publish

Upload `index.html` to the root of your public GitHub repository, then Settings → Pages → Deploy from a branch → `main` / (root). Open the Pages URL. The page works as a `file://` local HTML file, too.

**Suggested commit:** `feat(demo): add clickable themes and curated highlighted letter excerpts`
