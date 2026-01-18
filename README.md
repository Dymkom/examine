<div align="center">
  <br>
  <img src="res/icons/hicolor/scalable/apps/io.github.cosmic_utils.Examine.svg" width="150" />
  <h1>Examine</h1>

  <p>A system information viewer for the COSMIC™ Desktop</p>

  <img src="res/screenshots/distribution.png"/>
</div>

## Install

To install Examine, you will need [just](https://github.com/casey/just) and headers for libxkbcommon.

If you're on Pop!\_OS, you can install them with the following command:

```sh
sudo apt install just libxkbcommon-dev
```

For Fedora (or derivatives):
```sh
sudo dnf install just libxkbcommon-devel
```

Once the dependencies are installed, you can run the following commands to build and install the application:

```sh
just build-release
sudo just install
```

To uninstall simply run

```sh
sudo just uninstall
```
