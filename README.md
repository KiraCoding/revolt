# Volt

> **Warning**\
> This custom client may violate Discords terms of service, which could result in account suspension or termination. The client may also have limited functionality. Use at your own risk.

## Building

### Linux
Volt uses Wry which depends on gtk-rs and it's related libraries for window creation like WebKitGTK

#### Arch Linux / Manjaro:
```sh
sudo pacman -S webkit2gtk-4.1
```

####  Debian / Ubuntu
```sh
sudo apt install libwebkit2gtk-4.1-dev
```

#### Fedora
```sh
sudo dnf install gtk3-devel webkit2gtk4.1-devel
```

### macOS
WebKit is native on macOS so everything should be fine.

### Windows
WebView2 provided by Microsoft Edge Chromium is used. Volt supports Windows 7, 8, 10 and 11.

## License
Volt is distributed under the terms of both the  MIT and Apache 2.0 license.
- [MIT License][LICENSE_MIT] ─ https://opensource.org/license/mit/
- [Apache License (Version 2.0)][LICENSE_APACHE] ─ http://www.apache.org/licenses/LICENSE-2.0

[LICENSE_MIT]: ./LICENSE-MIT
[LICENSE_APACHE]: ./LICENSE-APACHE