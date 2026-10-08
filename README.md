# JinSolata Mono webfonts

WOFF2 files and a mixed Latin and Chinese specimen for 抚今楷 · JinSolata Mono
0.2. The font combines Inconsolata Latin with Tsanger JinKai 04 Chinese
outlines scaled to 95% and lowered by 50 units.

[View the specimen](https://hanlhe.github.io/JinSolata-Mono-Webfonts/).

## Use

```html
<link rel="stylesheet" href="https://hanlhe.github.io/JinSolata-Mono-Webfonts/JinSolataMono.css">
```

```css
body {
  font-family: "JinSolata Mono", monospace;
  font-weight: 400;
}
```

Available weights: Light (300), Regular (400), and Bold (700). Each WOFF2
file includes the full font character coverage and is approximately 8.5 MiB.
Only upright styles are provided. Inconsolata has no designed italic or slant
style, and no synthetic italic is included.

## Updates

The source fonts and build scripts are maintained in a private repository.
This repository contains the generated webfonts, stylesheet, and specimen.
The GitHub Pages workflow publishes these files when they change on `main`.

## Source fonts

- [Inconsolata](https://github.com/cyrealtype/Inconsolata), version 3.100.
- [Tsanger JinKai 04](https://www.tsanger.cn/product/44), W01/W03/W05.

This is a personal font build. Source font licensing notices are retained
inside each font file.
