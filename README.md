# Markdown to lecture slides

The `slides` directory contains slides for my course "General Biology".

Check [example.md](slides/example.md) for basic syntax. Then generate PDF slides with 

```bash
make example.slides.pdf
```

[slides/example.slides.pdf](slides/example.slides.pdf) is the result on my iMac.

To generate PDF handouts, with

```bash
make example.notes.pdf
```

[slides/example.notes.pdf](slides/example.notes.pdf) is the result on my iMac.

To make slide and note PDFs at once.

```bash
make example
```

`make clean` to delete all intermediate files.

**Modified from [agoldst's repo](https://github.com/agoldst/tex/tree/master/lecture-slides).**
