# ApplePrivacy

Public privacy-policy and support pages for games published on the App Store by KingAragorn, an individual Apple developer.

GitHub Pages serves this site from the **root of the `main` branch**.

## Enable GitHub Pages

In the repository on GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**. Choose branch `main` and folder `/` (root), then save.

The site is published at https://kingaragorn.github.io/ApplePrivacy/ after `main` contains these files.

| App | Privacy | Support |
| --- | --- | --- |
| JesterDrop | [`jesterdrop/privacy.html`](jesterdrop/privacy.html) | [`jesterdrop/support.html`](jesterdrop/support.html) |

Published URLs, once `main` contains these files and Pages is enabled:

- https://kingaragorn.github.io/ApplePrivacy/jesterdrop/privacy.html
- https://kingaragorn.github.io/ApplePrivacy/jesterdrop/support.html

The home page is https://kingaragorn.github.io/ApplePrivacy/.

## Add a new game

Copy a folder. `jesterdrop/` is the template.

1. Copy `jesterdrop/` and rename the copy to a short lowercase name, for example `mygame/`.
2. Edit `privacy.html` and `support.html` in the new folder. Keep the stylesheet link as `../styles.css`.
3. Add the game to the list in `index.html`, with links to its privacy and support pages.
4. On the new privacy and support pages, link the contact email as [brad@arthedain.net](mailto:brad@arthedain.net). Keep GitHub issues as a secondary option.
5. Open a pull request into `main`. After it merges, GitHub Pages publishes the new folder.

Leave `.nojekyll` in place. It tells GitHub Pages to publish the files as they are, without running Jekyll.

Shared layout lives in `styles.css`. Game pages do not need their own stylesheet.

## Contact

The monitored contact email is [brad@arthedain.net](mailto:brad@arthedain.net). Use it on each game’s privacy and support pages. GitHub issues on this repository are a secondary way to get help.
