# Quick TikZ Preview

Quickly preview your TikZ code with TikZJax - a client-side TikZ to SVG converter.

## Description

This tool allows you to preview TikZ code directly in your browser using [TikZJax](https://github.com/artisticat1/tikzjax), which converts LaTeX/TikZ code to SVG using WebAssembly. No server-side processing is required - everything runs locally in your browser.

## Features

- Real-time preview of TikZ diagrams
- Auto-render as you type
- Download generated SVG files
- Mobile-responsive design
- Support for TikZ libraries
- Clean, modern interface

## How to Use

1. Write your TikZ code in the editor
2. Click "Render" or enable "Auto-render" to see the preview
3. Use "Download SVG" to save your diagram

### Using TikZ Libraries

To use TikZ libraries, add `\usetikzlibrary{library-name}` at the beginning of your code:
```latex
\usetikzlibrary{arrows.meta, positioning, shapes.geometric}
\begin{tikzpicture}
  % Your TikZ code here
\end{tikzpicture}
```

Common libraries include:
- `arrows.meta`
- `positioning`
- `shapes.geometric`
- `calc`
- `decorations.pathmorphing`

## Credits

This tool uses [TikZJax](https://github.com/artisticat1/tikzjax) by [artisticat1](https://github.com/artisticat1) for converting TikZ code to SVG.

Created by [alfurka](https://github.com/alfurka).