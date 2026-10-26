# MM Trading Hub download

The download page for **MM Trading Hub**, the Market Mavericks trading platform for Mac:
<https://arminparvardegary.github.io/mm-trading-hub-download/>

- `index.html` is the page (GitHub Pages, from `main`).
- The disk images are assets of the [releases](https://github.com/arminparvardegary/mm-trading-hub-download/releases),
  not files in this repository. They are built with `build-app.sh` in the (private) MM Trading Hub repository:
  `./build-app.sh` for Apple Silicon and `TH_RID=osx-x64 TH_OUT=dist/intel ./build-app.sh` for Intel.
- For a new version: upload the new disk images to a new release, then update the links, sizes and SHA-256 checksums
  in `index.html`.

MM Trading Hub is the Market Mavericks edition of [Trading Hub](https://github.com/ralphtradesz/trading-hub) by
ralphtradesz, under the MIT License with the Commons Clause (see [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md)): it may
be shared for free but not sold.
