# UMN-PhD-Thesis-Template

Updated the UMN PhD Thesis Template by:

1. Fixing the issue where the *List of Tables* and *List of Figures* were not appearing in the Table of Contents by modifying `preliminaries/title.tex`.
   
3. Adding the `geometry` package and setting custom margins in `thesis.tex`:
   ```latex
   \usepackage{geometry}
   \geometry{left=1.5in, right=1.25in, top=1.25in, bottom=1.25in, includehead, includefoot}
   ```
   
4. Ensuring the *Bibliography* appears in the Table of Contents by updating `thesis.tex`.

