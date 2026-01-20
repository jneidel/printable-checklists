# Printable Checklists

> Easily generate a clean printable check list from markdown

Digital checklist are great, but sometimes you just want a easily reusable physical checklist.
The only problem: formatting it is annoying.

This repo provides a dead-simple way to generate A5 (two per A4 pdf) checklists from markdown.
Super easy to change, recompile and print.

## Usage

Install dependencies:
```sh
yay -S ghostscript psutils pdftk wkhtmltopdf-bin
```

Create a markdown file (see [examples](example)) and transform it:
```sh
./transform example/going-to-office
```
