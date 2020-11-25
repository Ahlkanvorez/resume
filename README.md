# Resume

My resume in LaTeX.

## Compiling to PDF

The `pdflatex` command is required to compile the `.tex` file to
`.pdf`.

On Linux distributions using apt, this can be installed via
```
sudo apt install texlive-latex-base -y
```

Once installed, the PDF can be generated with
```
pdflatex resume.tex -output-format=pdf
```