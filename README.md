# webR-quarto-demos

This repository houses experiments with generating a standalone [Quarto Document](https://quarto.org/) using [WebR](https://docs.r-wasm.org/webr/latest/).

- [Proof of Concept: Quarto HTML Document with WebR](https://rd.thecoatlessprofessor.com/webR-quarto-demos/webr-quarto-html-demo.html) ([Source](webr-quarto-html-demo.qmd))

You can create WebR-powered Quarto code cells using the [`quarto-webr`](https://github.com/coatless/quarto-webr) extension: 

<https://github.com/coatless/quarto-webr>

## Background

[WebR v0.1.0](https://twitter.com/gwstagg/status/1633821049329537025) was launched on March 9th
by George Stagg ([georgestagg](https://github.com/georgestagg)) and Lionel Henry ([lionel-](https://github.com/lionel-)). The goal of webR is to: 

> run R code in the browser without the need for an R server to execute the code

This is an _amazing_ advancement of _R_ and has major implications with teaching R to the masses in an active learning context!

## Acknowledgements

This repository leans _heavily_ on the webR developers public-facing examples:

- [Source of Tidyverse Blog Post](https://github.com/tidyverse/tidyverse.org/pull/617/files) and [Minor fix](https://github.com/tidyverse/tidyverse.org/commit/72bb2dd7ca0b2f211498a891aa54f55ddcad5014)
- [webR documentation landing page](https://github.com/r-wasm/webr/blob/53acd8861c44f1f167941d0a40f62b0cc23852da/src/docs/index.qmd#L23-L68) ([Live page](https://docs.r-wasm.org/webr/latest/))
