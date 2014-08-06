
# fences

This will be a version of [transf](http://hackage.haskell.org/package/transf) with a more
modular design.

No code yet, just uploading it to reserve the name.

## Description

Fences combine Markdown and Haskell to include arbitrary data in text documents, and ways to visualize that data.

Fences exenteds *Markdown fenced code blocks* to include arbitrary data, which can be rendered to images, audio, animation or structured text.

Fences brings Haskell EDSLs and Markdown together to be a structured text + data language.

Think of it as a literate programming where the program also generates the content.

### Uses

* Embed images, music or other media described by a Haskell DSL in text
* Extend syntax highligting to visualize structure of the code
* Roll your own markdown extension in Haskell
* Generate markdown (tables, histograms etc) to create "smart" text documents
* As an overkill text preprocessor
* As a meta-programming experiment.
* Document your own DSL with examples *in the documentation*.
* Augment your blog posts with rich generative media.

## Requirements

* [Haskell Platform](http://www.haskell.org/platform)

## Installation

    cabal configure
    cabal install
