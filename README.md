![GDevelop logo](https://raw.githubusercontent.com/flathub/io.gdevelop.ide/master/docs/GDevelop%20banner.png "GDevelop logo")

[GDevelop](http://gdevelop.io/) is a full-featured, no-code, [open-source game development software](https://github.com/4ian/GDevelop). You can build games for mobile, desktop and the web. GDevelop is fast and easy to use: the game logic is built up using an intuitive and powerful event-based system.

# Flatpak repository

This is the Flatpak repository for [GDevelop on Flathub](https://flathub.org/apps/details/io.gdevelop.ide).

See [Flathub documentation for more information](https://github.com/flathub/flathub/wiki/App-Maintenance).

You can download GDevelop for other operating system from [the official website](https://gdevelop.io/download) or [try the game engine directly from your browser](https://editor.gdevelop.io/).

## Contributing to the Flatpak

Clone this repository and build locally:

```sh
git clone https://github.com/flathub/io.gdevelop.ide.git && cd io.gdevelop.ide
flatpak-builder --user --install --force-clean build-dir io.gdevelop.ide.yml
flatpak run io.gdevelop.ide
```

Once a Pull Request is merged in this repository, Flathub will automatically rebuild it and publish it.
