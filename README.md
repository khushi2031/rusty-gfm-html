# rusty-gfm-html
A markdown rendering similar to that of Github Flavored Markdown

This program simply generates an html file, containing the style sheets necessary to render as close to GFM Markdown as possible. Syntax highlighting is not currently supported.

## Installation

Simply extract the downloaded file someplace memorable, like `/opt/rusty`, and optionally add the location to your `$PATH` variable.

## Build From Source

Like any other Rust program, simply clone the repository and run

```bash
cargo build --release
```

Then, copy the executable and styles.css somewhere memorable, like `/opt/rusty`

## Usage

To display the program usage, open a terminal and type

```bash
rusty-gfm-html --help
```