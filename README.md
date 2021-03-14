# Alternative LaTeX Beamer Template in TU Berlin Style

This is an alternative LaTeX beamer theme for presentations in the style of TU Berlin.

## Usage

To use it just place the `.sty` files where LaTeX can find them (e.g. your project folder) and include `\usetheme{Berlin}` in the preamble of your `.tex` file. For a title slide at the start of each section use `\usetheme[sectionslides]{Berlin}`.

You can also use the colour theme `beamercolorthemeBerlin.sty` separately with other themes via `\usecolortheme{Berlin}`.

These colour aliases are available for use with `\textcolor{tub-blue}{example text}`. 

You may also find it convenient to start with the ready-to-use `example.tex` file which includes a few additional design tweaks. 
