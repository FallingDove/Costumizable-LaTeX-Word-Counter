# LaTeX-Word-Counter
A costumizable LaTeX-Word-Counter. Set up by downloading the file "LaTeX Counter.html" and open it on your browser.

1 Count words from **raw** LaTeX code: Extracts text directly from code while automatically handling markup and syntax.

2 Strip structural document blocks: Optionally skips the preamble or everything before the table of contents (\tableofcontents).

3 Wipe title metadata: Separately excludes \title, \author, \date, \maketitle, or the entire titlepage environment.

4 Filter block equations: Automatically deletes heavy math blocks like equation, align, gather, and matrix variants.

5 Remove display math formats: Recognizes and strips unnumbered math blocks inside \[ ... \] and $$...$$.

6 Apply smart inline math logic: Intelligently checks $ ... $ to remove equation logic (with =, <, >, etc.) while preserving standalone variables.

7 Filter specific text macros: Strips structural strings or notes like sections, captions, cross-references, citations, and footnotes.

8 Nuke floats and diagrams: Entirely deletes figure and tikzpicture graphic environments.

9 Eliminate data metrics: Automatically strips out \qty{}{} and \unit{} SI units macros.

10 Three-way table controller: Gives options to entirely delete, entirely keep, or strip only the configuration/layout brackets for standard tables and Tabularray.

11 Granular parent-child controls: Provides master toggles to control entire categories alongside individual checkboxes for micro-customization.

<img width="863" height="1199" alt="image" src="https://github.com/user-attachments/assets/08b67e7e-d2a9-402f-b4d1-0acd5f96caf8" />
