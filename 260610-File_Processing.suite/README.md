# Notes

[![](https://img.shields.io/badge/YouTube-15m30s-FF0000?logo=youtube)](https://youtu.be/1sldlkGNjPo)

Join Eggplant Research and Developer, Doug Simons, to learn more about Eggplant's English-like language **SenseTalk** and its capabilities.

### Topics
- Treating a file directly as a container with `put … into file` and `put file …`
- File streaming with `open file`, `close file`, `write … to file`, `read … from file`, and `seek in file`
- Opening files in different modes: `for writing`, `for reading`, `for appending`, and `for updating`
- Saving byte-offset bookmarks with `the position in file` and jumping to them with `seek … to`
- Relative seeking: `seek … to N before/after the current position`
- Reading in blocks: `read N chars from file` and `read a line from file`
- Performance comparison: whole-file read vs. streaming in fixed-size blocks
- Overlapping-block buffering to correctly detect matches that span block boundaries

### Helpful Links
- [Sensetalk Travel Guide](https://docs.eggplantsoftware.com/studio/stk-sensetalk-travel-guide/)
- [File and Folder Interaction](https://docs.eggplantsoftware.com/studio/stk-file-folder-interaction/)
- [File and Folder References](https://docs.eggplantsoftware.com/studio/stk-file-folder-references/)
