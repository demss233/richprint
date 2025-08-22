# RichPrint

RichPrint is a tiny wrapper around Rich that gives you a chainable, fluent way to print styled text. You keep writing `show()`, then chain styles.

## Features
- Chainable API: `RichPrint.bold().green().underline().show("Hello")`
- Drop-in feel for `print()`, but actually readable
- Minimal surface area, built on Rich

## Installation

```bash
pip install richprint
