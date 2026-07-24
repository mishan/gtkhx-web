GtkHx is a GTK+ Hotline Client originally based on Hx. Originally written in C, and currently
being rewritten in Rust.

## Features

- Modern GTK+ 4 / libadwaita / libpanel UI with retro look and feel
- Full TLS support, for servers, file transfers, and trackers
- Cross platform -- works on Linux, macOS, and Windows
- Support for extended Hotline protocol features and capabilities
  - Voice chat
  - Inline media
  - Native UTF-8
  - GIF icons
  - Large file transfers
  - Chat history
  - Colored names
  - Blowfish and ChaCha20-Poly1305 cipher support
  - Tracker v3
- File previews
  - Common image types via glycin
  - QuickDraw PICTs via ImageMagick
  - PDFs via libpoppler
  - markdown / source files via libgtksourceview
- Orthogonal file manager
- Customizable UI allows for single window and multi window layouts
- Themable, with support for light and dark themes
- Systray and app notifications

## History

GtkHx was originally created in 2000, with work on it ceasing in 2003. In 2026, the original author, Misha Nasledov, resurrected GtkHx as a modern application with the latest [Hotline](https://en.wikipedia.org/wiki/Hotline_Communications) [protocol extensions](https://github.com/fogWraith/Hotline/tree/main/Docs/Protocol).
