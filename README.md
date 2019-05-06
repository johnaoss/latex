# latex

This repo includes my (very small) changes to Calvin Kent's LaTeX files.

Description of .sty files.

- CKcrowdmark.sty: For assignments submitted by Crowdmark.
- CKlecture: For lectures.
- CKpreamble: Preamble for every document.
- CKprintedassignment: For printed assignments.
- JAOCode: For code formatting using the FiraCode typeface.

Description of .tex files.

- Crowdmark: Template for assignments submitted by Crowdmark.
- Lecture: Template for lectures.
- PrintedAssignment: Template for printed assignments.

Description of .pdf files.

- Crowdmark: An example of the crowdmark assignment template, without any user-added content.

## Usage

All of these .sty files have been able to be compiled with the latest version of pdflatex, with the exception of `JAOCode.sty`. Due to how the older editions of LaTeX handle fonts, it is most likely that LuaTex or XeTex will be needed. `JAOCode.sty` has been tested with LuaTeX and found to compile fine on a macOS system.

## Copyright

The majority of this project is a direct fork of [Calvin Kent's LaTeX files](https://github.com/CalvinKent/My-LaTeX). Every file who's name begins with a "CK" is either a direct mirror, or small changes to his files.

More information can be found in [LICENSE.md](https://github.com/johnaoss/latex/blob/master/LICENSE).

The University of Waterloo logo `mlogo.png` is taken from [University of Waterloo's Official Branding Page](https://uwaterloo.ca/brand/visual-expression/logos-and-marks/official-logos), and used **ONLY** for non-commercial, personal academic use.
