# Introduction to Forensic Speech Science

Slides for *Introduction to Forensic Speech Science* (Dr Massimiliano Canzi, Department of Linguistics, University of Konstanz). The sessions follow the chapters of Leemann, A., Perkins, R., Sullivan Buker, G., & Foulkes, P. (2024), *An Introduction to Forensic Phonetics and Forensic Linguistics*, Routledge: chapters 1 to 7 (forensic phonetics and LAAP), chapters 10 to 12 (language in the legal process and authorship analysis) and chapter 13 (expert witnesses). Sessions 8 and 9 are built from the original studies those chapters cover. The figures use simulated data, except for published results that are labelled as such (for example McGehee, 1937, in session 5).

| | Session | Chapter |
|---|---|---|
| 1 | Course introduction | 1 |
| 2 | Phonetic analysis | 2 |
| 3 | Speaker profiling | 3 |
| 4 | Speaker comparison | 4 |
| 5 | Earwitness evidence | 5 |
| 6 | Authentication, enhancement and speech content | 6 |
| 7 | Linguistic analysis in the asylum procedure | 7 |
| 8 | Language in the legal process | 10 |
| 9 | Authorship analysis | 11, 12 |
| 10 | Expert witnesses | 13 |
| 11 | Praat practical 1: measuring your own voice | 2, 4 |
| 12 | Praat practical 2: casework with the class recordings | 3–5 |

The slides are online at [mcanzi.de/fss](https://mcanzi.de/fss/01_course_introduction.html).

## Rendering the slides

The sessions are [Quarto](https://quarto.org) revealjs decks (`source/*.qmd`). Run `quarto render` in `source` to render every session into `docs`, which GitHub Pages serves; `quarto render 04_speaker_comparison.qmd`, or the Render button in RStudio, renders a single one. The options all sessions share (slide size, transitions, chunk defaults) are in `source/_quarto.yml`; each session's YAML has only its title, subtitle and footer. All sessions use the sunset theme of mcanzi.de (`source/sunset.scss`): the colours of a sunset over Almaty, with oranges drawn in ink in the background; `source/slides_setup.R` sets the plot colours to match it (orange, dusk blue and pink for groups). The fonts are in `source/fonts` (declared in `source/fonts.css`) and are embedded in each HTML file.

Requires [Quarto](https://quarto.org) (bundled with RStudio), `simling` (`remotes::install_github("mcanzi/simling")`) and `tidyverse`; optional: `qrcode` (QR codes), `ragg` and `systemfonts` (Atkinson Hyperlegible in the figures).

## License

Course materials © Massimiliano Canzi, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see `LICENSE.md`). Code is licensed under the MIT License (see `LICENSE-CODE.md`). The fonts used in the slide theme (Atkinson Hyperlegible, Bricolage Grotesque, JetBrains Mono) are licensed under the SIL Open Font License 1.1 (see `source/fonts/OFL-*.txt`).
