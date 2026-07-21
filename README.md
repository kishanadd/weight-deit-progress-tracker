# Progress Tracker Website

This is a basic static HTML progress tracker designed to be deployed on Cloudflare Pages.

## Files adding edit option for food list 

- `index.html` — main website file
- `progress-tracker.html` — optional backup/edit file

## Deploy to Cloudflare Pages

1. Create or open the GitHub repo: `kishanadd/weigh-deit-progress-tracker`.
2. Add `index.html` (and optionally `progress-tracker.html` and this `README.md`) to the repo root and push to GitHub.
3. In Cloudflare, go to **Workers & Pages** and choose **Create application**.
4. Select **Pages** and then **Import an existing Git repository** [web:228].
5. Choose your `weigh-deit-progress-tracker` repository and begin setup [web:228].
6. For a plain static HTML site:
   - Framework preset: **None**.
   - Build command: leave empty.
   - Output directory: root (`/`) or default for static HTML [web:228][web:235].
7. Deploy the project and Cloudflare Pages will publish the site [web:228].

## Notes

- This starter version stores entries in browser storage, so it is fast to deploy but does not sync between devices.
- A later version can connect to Google Sheets, Supabase, or a Cloudflare database for proper cloud syncing.
- Use the site to log:
  - Current weight
  - Waist
  - Steps
  - Run completed checkbox
  - Lift completed checkbox
  - Daily notes