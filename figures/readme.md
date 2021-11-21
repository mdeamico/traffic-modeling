# Figures Folder
Contains images, html, and other figure formats that are referenced within Rmd documents.

## File Organization
- Use one figure subfolder corresponding to one Rmd file.
- The figure subfolder and Rmd file have the same name.
- Within the figure subfolder, create a "src" folder that contains any source material needed to create the figure, for example, Inkscape/Illustrator files, R code that generates graphs, etc.
Use subfolders under src to if a figure has a lot of source material.
- The final figure output created by the source material is saved up one level, in its parent figure subfolder.

The following example shows how figures for a hypothetical "01_chapter_1.Rmd" file would be organized. The example also shows how source material for Figure 1 is saved. Figure 2 did not have any corresponding source material in this example. Another figure subfolder is shown for another "02_chapter_2.Rmd" file.

```
figures/
├─ 01_chapter_1/
│  ├─ src/
│  │  ├─ figure_1.svg
│  ├─ figure_1.png
│  ├─ figure_2.png
├─ 02_chapter_2/
│  ├─ src/
```






