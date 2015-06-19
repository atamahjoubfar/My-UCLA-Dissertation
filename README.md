Where to start!
---------------

This repository is a sample UCLA dissertation in LaTeX. The formatting of this document is based on the great work of many other people; see `Old_README.md` for details of their contributions. I have slightly modified the original formatting files to match the most recent requirements of UCLA. The latest time that a dissertation was approved based on this repository was December 2014 (please let me know if yours was approved after this time). Also, please let me know if you had to change formatting of anything in order to get your dissertation approved. I am looking forward to your pull requests.

I organized my disseration in multiple folders, each cotaining one of my papers, formatted into a chapter. All you need to do is to open `demo.tex` file and modify it for example with TeXworks. In `demo.tex`, many other tex files are imported with `\input` function. This way, your main document remains organized. Use `pdflatex` and `bibtex` for processing `demo.tex` and `demo.aux`, respectively, and you will get your disseration pdf file as the output! Make sure the default page size of your LaTeX distribution is letter size. In case you don't know how to install a LaTeX distribution, look at the instructions below.

Good luck!

How to install a functional LaTeX distribution in Windows
---------------------------------------------------------

1. Uninstall everything related to TeX on your machine
2. Restart
3. Install [TeX Live](https://www.tug.org/texlive/) as admin (you may have to turn off your antivirus based on your operating system). Make sure you will choose custom install.
4. Change the default page size to `letter` and install. It will take a long time.
5. Restart
6. Open `demo.tex` file with TeXworks, and run "pdfLaTeX".
7. To update chapters, open thier seperate TeX files, and use `\input` command to include them in the `demo.tex` file.
8. To update bibliography, edit `DissertationBib.bib` in `FrontBack` folder. You can get bibliography items from "Import into BibTeX" of Google Scholar. You can even make this your default citation format in Google Scholar settings.
9. Everytime you need to update citations run, "pdfLaTeX", then "bibTeX", then "pdfLateX" twice.
10. For figure tiff files doesn't work, but eps, png, and pdf works by default.