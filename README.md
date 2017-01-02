### Zukitwo-Cinnamon for cinnamon

---

### Installation

Move the `Zukitwo-Cinnamon` folder into your `~/.themes` directory.

---

### Compatibility

The latest version of this theme is on the master branch, and it supports
cinnamon version `3.2`.

For older versions, check the available [releases](../../releases).

---

### Font

The default font is `Roboto` with `Noto Sans` and `Sans-Serif` fallbacks.

To change the font, edit the `cinnamon.css` file at selector `stage`
(beginning of file).

---

### Development

The `watch` script will watch the chosen dirs for changes and
recompile sass and reload the theme when a change occurs.

> **Script dependencies:**

> * inotifywait
> * sassc

> ---  

> **NOTE:**  

> The script creates a link to the `Zukitwo-Cinnamon` dir in `~/.themes`.
