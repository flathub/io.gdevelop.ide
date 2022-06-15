![GDevelop logo](https://raw.githubusercontent.com/flathub/io.gdevelop.ide/master/docs/GDevelop%20banner.png "GDevelop logo")

[GDevelop](http://gdevelop.io/) is a full-featured, no-code, [open-source game development software](https://github.com/4ian/GDevelop). You can build games for mobile, desktop and the web. GDevelop is fast and easy to use: the game logic is built up using an intuitive and powerful event-based system.

# Flatpak repository

This is the Flatpak repository for [GDevelop on Flathub](https://flathub.org/apps/details/io.gdevelop.ide).

See [Flathub documentation for more information](https://github.com/flathub/flathub/wiki/App-Maintenance).

You can download GDevelop for other operating system from [the official website](https://gdevelop.io/download) or [try the game engine directly from your browser](https://editor.gdevelop.io/).

## Contributing to the Flatpak

### Upgrading to a newer GDevelop version

1. Create a commit with:
   - An upgrade the `.deb` file to use in `io.gdevelop.ide.yml` and its checksum.
   - A new `release` in `io.gdevelop.ide.appdata.xml`.
2. Merge in the `master` branch.
3. Follow the build that will be automatically be done on https://buildbot.flathub.org/#/.
4. Open the build page and click on "Publish" when the build is done.
5. Verify [the app is updated on Flathub](https://flathub.org/apps/details/io.gdevelop.ide) a few minutes later.

### Testing locally

Clone this repository and build locally:

```sh
git clone https://github.com/flathub/io.gdevelop.ide.git && cd io.gdevelop.ide
flatpak-builder --user --install --force-clean build-dir io.gdevelop.ide.yml
flatpak run io.gdevelop.ide
```
