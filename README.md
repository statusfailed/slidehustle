# Slide Hustle 📟

Minimalist terminal markdown slide decks

# What is this?

**Slide Hustle** is a single-file shell script that presents a Markdown file as a slide deck,
right in your terminal.

- One `# Header` per slide
- No GUI, no browser, no dependencies except [`bat`](https://github.com/sharkdp/bat)
- Great for lightning talks, live coding demos, and [asciinema](https://asciinema.org/) casts.

Example:

    ./slideh README.md

![slide hustle README example cast](./propaganda/slideh-readme-cast.svg)

# Usage

```bash
slideh talk.md
```

Navigate with:

* `n` – next
* `p` – previous
* `q` – quit

Each top-level `#` starts a new slide.

# Installation and Dependencies

Install [`bat`](https://github.com/sharkdp/bat), then run slideh:

```bash
curl -o slideh https://raw.githubusercontent.com/statusfailed/slidehustle/refs/heads/master/slideh
chmod +x slideh
./slideh README.md
```
