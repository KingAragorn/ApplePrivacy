# ApplePrivacy

Public privacy-policy and support pages for games published on the App Store by KingAragorn, an individual Apple developer.

GitHub Pages serves this site from the **root of the `main` branch**.

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
4. If you have a real support email, replace the `support@example.com` placeholder in the new `support.html`.
5. Open a pull request into `main`. After it merges, GitHub Pages publishes the new folder.

Leave `.nojekyll` in place. It tells GitHub Pages to publish the files as they are, without running Jekyll.

Shared layout lives in `styles.css`. Game pages do not need their own stylesheet.

## Support email

`support@example.com` in `jesterdrop/support.html` is a placeholder. It is not a monitored mailbox. Replace it before you rely on email for App Store support. GitHub issues on this repository are the working contact method.
