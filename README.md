# Learning on Graphs — redesigned group homepage

A static website prepared from the public Learning on Graphs group website at <https://log-rwth.github.io/> on 25 September 2026. It uses the classic beige and maroon style of Christopher Morris's academic homepage.

## Files

- `index.html` contains the page content.
- `styles.css` controls the layout and colors.
- `images/` contains the original group photo, portraits, favicon, and retained RWTH logo.
- `assets/fonts/eb-garamond/` contains the local font files, their source information, and the required `OFL.txt` license. Keep these files together.
- `NAR_position_paper.pdf` preserves the existing downloadable paper at the same path.

The working delivery stores these website files inside `dist/`. The ZIP places them directly inside its `log-rwth.github.io/` folder, alongside this README.

## Preview and publish

No build or package installation is needed. Open `index.html` in a browser to preview the page.

To use the redesign with the existing GitHub Pages repository:

1. Extract `log-rwth.github.io-redesigned.zip`.
2. Copy the contents of its `log-rwth.github.io/` folder into the existing repository's publishing folder, replacing the matching website files. Keep the repository's existing GitHub Pages configuration and any unrelated files.
3. Commit and push the changes using the repository's normal publishing process.
4. After GitHub Pages finishes publishing, check the live homepage and the existing `/NAR_position_paper.pdf` address.

No live deployment is included in this delivery.

## Content and maintenance

The page lists eight current group members, including two student assistants, and one alumnus. Darius Weber's card and unused portrait are removed at the user's request; he is not listed as an alumnus. Luis Müller appears in the Alumni section after the student assistants with the user-provided role “Now at Google Research.” His former research description is replaced with the user-provided text “PhD student from 2022 to 2026.” The remaining member information comes from the supplied group website.

The header has no subtitle and includes Group Members, Publications, Teaching, and Thesis navigation. The original link destinations are unchanged: publications open Christopher Morris's Google Scholar profile, and teaching opens his academic homepage.

At the user's request, the Research box follows the personal homepage's research wording and numbered format. It opens with “Our research brings together machine learning, theoretical computer science, and discrete mathematics. We focus on the following:” and retains the personal homepage's three research questions. A fourth item adds “Applying principled learning on graphs to real-world problems.” This replaces the group page's previous research text.

The thesis guidelines start expanded and can be collapsed. Repeated student-assistant biographies are condensed to the displayed role. Student-assistant cards use the same portrait sizing and typography as the other member cards. Gia Chi Dang is represented by initials because the source website supplied no portrait.

Edit the text and links in `index.html` to update the page. Retain the section IDs `welcome`, `group-members`, and `thesis` so existing direct links continue to work, and keep `top` as the target for the Back to top link. Apart from Luis Müller's user-provided alumni status, affiliation, and PhD dates, member details reflect the supplied group website as retrieved on 25 September 2026 and have not been independently reverified.
