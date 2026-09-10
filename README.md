# PrintingCPP

A desktop label maker for CUPS-compatible label printers, written in C++ with JUCE.

The app is a tabbed editor. Each tab is a different kind of label, and the
preview pane renders the layout before anything reaches the printer.

| Screen | What it does |
|---|---|
| `NameBadgeComponent` | Name badges. |
| `StorageLabelComponent` | Storage and shelf labels. |
| `GeneralLabelComponent` | Free-form labels. |
| `EditTagComponent` | Edits a tag on an existing label. |
| `TextAggregatorComponent` | Collects the text fields that feed a label. |
| `LabelPreviewComponent` | Renders the composed label. |

`LabelGenerator` does the layout: it takes a font and a set of lines, measures
each glyph run into boxes, and computes the line height from the extremes of
those boxes.

Printing goes through PAPPL and LPrint, which are vendored in the tree, and
libcups underneath them.

## Build

Open `newdir/radger.jucer` in the Projucer and export for your platform, or use
the generated exporters under `newdir/Builds/`. JUCE is a submodule.

```bash
git clone --recurse-submodules https://github.com/godofecht/PrintingCPP.git
```

## Licensing

This project's own code is under [LICENSE](LICENSE). PAPPL and LPrint are
Apache-2.0 and keep their own copyright. See
[THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) before redistributing.
