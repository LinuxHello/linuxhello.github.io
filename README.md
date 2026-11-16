# linuxhello.github.io

The homepage of [Linux Hello](https://github.com/LinuxHello), served by GitHub Pages at <https://linuxhello.github.io/>.

It is one static page with no build step: `index.html`, `style.css` and `assets/`. Open `index.html` in a browser to preview it.

- Colours and font stacks follow [`tokens/tokens.css`](https://github.com/LinuxHello/linux-hello-branding/blob/main/tokens/tokens.css) in the branding repository.
- The logo files in `assets/` are copied from the branding repository's generated files; do not edit them here, regenerate them there and copy again.
- Noto Sans and Noto Sans Mono are self-hosted (Latin subset, SIL OFL 1.1) so the page makes no requests to third-party font services. Headings use Quicksand when it is installed and fall back to the stack in the tokens.
- Status statements on the page must match the [README of linux-hello](https://github.com/LinuxHello/linux-hello#readme). Update both together.

## Publishing

Push to `main` of `LinuxHello/linuxhello.github.io`, then in the repository's Settings, Pages, choose "Deploy from a branch", branch `main`, folder `/ (root)`.

## Licence

LGPL-3.0-or-later, like the rest of the project. The fonts are under the SIL Open Font License 1.1.
