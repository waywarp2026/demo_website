# WayWarp Demo Website

This directory contains a static demo website for the anonymous CCS 2026 review page.

## Files

- `index.html`: main website page.
- `style.css`: responsive page styling.
- `assets/`: figures and visual material copied or rendered from the paper project.

## GitHub Pages deployment

1. Copy all files in this directory into the target GitHub Pages repository.
2. Ensure `index.html`, `style.css`, and the `assets/` directory are at the repository root.
3. Commit and push the changes.
4. In the repository settings, enable GitHub Pages from the target branch.

## Optional demo video

If a review video becomes available, place it at `assets/demo.mp4` and replace the video-slot notice in `index.html` with a standard HTML `<video>` block.

## Safety scope

The website intentionally does not include optimized physical patches, deployment-ready trigger videos, or instructions for real-world attack execution. The artifact scope is limited to offline scientific review and defensive understanding.
