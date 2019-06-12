# yolo.pptx
## intro
Sometimes working for a client means you have to hold a presentation.
Often, corporations have a PowerPoint template that they want you to use.
However some of us prefer to write presentations using Markdown
instead of a presentation software. If you are really "unlucky", you might
be expected to hand over a `.pptx` file (maybe for a group project?).

With the markdown converter Pandoc, this can all be solved.
You can use a `.pptx` file as a template. This means you can write your presentation
in Markdown, convert it to `.pptx` and never touch PowerPoint (or similar)!

See example.pptx for an example presentation using the XAL template I created.

## installation
- Install [pandoc](https://pandoc.org/installing.html)
  - macOS: `brew install pandoc`

## use
- Write a presentation in markdown (see pres.md)
- `pandoc pres.md -o out.pptx --reference-doc=res/xal.pptx`
