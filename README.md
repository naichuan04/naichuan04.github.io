# Naichuan Sun · Academic Homepage

🌐 [Personal website](https://naichuan04.github.io/) · 🎓 [Google Scholar](https://scholar.google.com/citations?user=Nmd-4kYAAAAJ) · ✉️ [Email](mailto:sun_naichuan@outlook.com) · [ORCID](https://orcid.org/0009-0000-6410-4237)

- 🎓 Ph.D. student at the School of Artificial Intelligence, Shanghai Jiao Tong University (SJTU), advised by [Prof. Yuanbo Xiangli](https://kam1107.github.io/).
- 🎓 Previously a visiting student at Westlake University, working with [Prof. Peidong Liu](https://ethliup.github.io/), and an undergraduate in Automation at Nankai University.
- 🌱 Research interests: robot learning, loco-manipulation, and world models for humanoid robots and robotic arms.

## Website content

- Selected publications and projects, including DexWeave, micropipette localization, and a mobile household service robot.
- Honors and awards.
- Education and contact information.

## Maintenance

The website uses plain HTML and CSS, with no build step or external dependencies.

| File | Content |
| --- | --- |
| `index.html` | Biography, publications, projects, awards, and education |
| `styles.css` | Typography, layout, and responsive styles |
| `assets/` | Portrait, publication figure, robot demonstration video, and icons |

The DexWeave entry links to the [project page](https://dexweave.github.io/) and the [Paper](https://arxiv.org/abs/2609.34724).

To preview locally, run this command from the repository root:

```sh
python3 -m http.server 18767 --bind 127.0.0.1
```

Then open [the local preview](http://127.0.0.1:18767/).

GitHub Pages publishes the website from the root of the `main` branch. Updates committed to `main` are deployed automatically. The `.nojekyll` file enables direct serving of the static files.
