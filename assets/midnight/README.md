# Blue Hour

A restrained navy and steel-blue theme for Sudeep's GitHub profile. The cover reuses the landscape embedded in the previous profile banner, with a blue-hour grade and the neon portal removed. No new external image provider is required.

- `hero.svg` is shared across themes. Its JPEG is embedded so GitHub's image sandbox does not need to load nested remote resources.
- `cloudshield-*.svg`, `interests-*.svg`, and `footer-*.svg` have matching light and dark variants. Edit their SVG text directly; use the same viewBox and update both variants.
- Body copy and the toolkit use ordinary Markdown so they wrap naturally on phones and remain selectable.
- Motion is limited to the cover stars, circuit marker and football. The SVGs hide those moving elements when reduced motion is requested; the rest of each composition remains visible.
- `.github/workflows/snake.yml` regenerates the contribution calendar from real GitHub activity every 12 hours. Its output is published to the existing `output` branch. There are no hard-coded personal contribution counts or third-party statistics cards.

Palette: dark background `#0d1117`, dark text `#e6edf3`, steel accent `#99bdd9`; light background `#ffffff`, light text `#172b3e`, blue accent `#315f85`.

The CloudShield figures describe the project's documented capabilities, not live production metrics. Existing legacy assets remain in the repository for reference and are no longer used by the profile README.
