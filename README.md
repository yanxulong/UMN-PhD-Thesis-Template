# University of Minnesota PhD/Master Thesis Template

This repository contains an updated version of the UMN PhD/Master Thesis Template based on [agude/UMN-PhD-Thesis-Template](https://github.com/agude/UMN-PhD-Thesis-Template).

---------------------------------------------------------------------------------------------------------------------------------------------------------
Most Recently Updated the UMN PhD Thesis Template on 02/27/2025 by:

1. Fixing the issue where the *List of Tables* and *List of Figures* were not appearing in the Table of Contents by modifying `preliminaries/title.tex`.
2. Adding the `geometry` package and setting custom margins in `thesis.tex`:
   ```latex
   \usepackage{geometry}
   \geometry{left=1.5in, right=1.25in, top=1.25in, bottom=1.25in, includehead, includefoot}
   ```
3. Ensuring the *Bibliography* appears in the Table of Contents by updating `thesis.tex`.
---------------------------------------------------------------------------------------------------------------------------------------------------------

You can download the repository to run on VS Code, PyCharm, or Cursor. `thesis.tex` is the master file.
