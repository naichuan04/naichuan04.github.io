# Naichuan Sun · Personal website

A responsive academic homepage for `https://naichuan04.github.io/`. The site uses plain HTML and CSS, with no build step or external font dependencies.

## Preview

Open `index.html` directly, or run `python3 -m http.server 18767 --bind 127.0.0.1` in this directory and visit `http://127.0.0.1:18767/`.

## Edit

- Personal details, research interests, publications, and contact links: `index.html`.
- Typography, spacing, colors, and mobile layouts: `styles.css`.
- Profile photo: `assets/portrait.jpg` (980,128 bytes). CSS displays the lower-left 85% of the original photograph inside a 2:3 frame, preserving the person and original background without stretching.
- Publication image: `assets/micro-positioning-pipeline.png`, extracted from Figure 2 of the author's paper. Click the thumbnail to open the full-size figure.
- Robot project video: `assets/service-robot-demo-0245-0315.mp4`, the 2:45–3:15 excerpt of the supplied demonstration, set to autoplay and loop silently with native playback controls and the same display width as the publication image. The web clip contains no audio track. Its preview frame is `assets/service-robot-poster-0245.jpg`.

## Publish with GitHub Pages

1. Create the public repository `naichuan04/naichuan04.github.io`.
2. Upload the contents of this directory to the repository root, keeping the `assets` folder. Do not upload an extra enclosing directory.
3. In **Settings → Pages**, set the source to **Deploy from a branch**, select **main** and **/(root)**, and save.
4. Wait for the Pages deployment to succeed, then open `https://naichuan04.github.io/`.

The `.nojekyll` file tells GitHub Pages to serve the static files directly. All links use paths that also work when opening the HTML file locally.

The page uses the supplied biography and photo. Its layout and stylesheet were written for this site; no template or source code was copied from the reference website.

Research interests are included in the main biography; the biography and publication/project summaries use justified text. Honors and Awards and Educations follow Selected Publications and Projects.

## Publication source

The Selected Publications entry was checked against the supplied Google Scholar profile (`Nmd-4kYAAAAJ`) on September 27, 2026. The profile currently lists one paper: Naichuan Sun, Yue Lu, Mingzhu Sun, “Precise Positioning of Micro Manipulation Tools Based on Super-Resolution,” 2025 44th Chinese Control Conference (CCC), pages 7424–7429, IEEE. The article link is https://ieeexplore.ieee.org/document/11179587/.

The publication thumbnail is the original pipeline figure (Figure 2) from page 4 of the author's local manuscript, `CCC2025.pdf`. It was rendered at 220 dpi from the figure region; the figure content was not altered. The full manuscript is not included in the website.

The paper summary describes multiple blur scale edge detection, LIIF super-resolution, and localization using the centroid of the tip-edge pixels.

The robot project dates and team role come from the supplied September 2025 résumé. The description follows the owner's wording about the wheeled platform, gripper, LiDAR, YOLO, SLAM, PID control, and the competition result.
