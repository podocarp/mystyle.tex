# mystyle.tex

My styles and shortcuts for TeX. Defines some shortcuts and configs to get you goin.

Put these files into `~/texmf/tex/latex/mystyle/`.

## Options

- `beamermode` switches on some beamer-only configs.
- `notes` makes beamer output notes. This makes a handout-like file.
- `varepsilon` `varphi` `varpsi` switches `x` and `varx`.

## Dependencies

If you do not wish to install a 5GB texlive-full package, here is the list of
minimum dependencies:
```
algorithm2e
amsmath bbm
bbm-macros
biber
biblatex
calrsfs
cancel
caption
catchfile
cleveref
enumitem
esint
esint-type1
fancyvrb
float
framed
fvextra
hyperref
ifoddpage
import
latexmk
lineno
mathtools
microtype
minted
multirow
pgf
physics
relsize
rsfs
rsfso
scheme-basic
siunitx
stmaryrd
tikz-cd
upquote
wrapfig
xkeyval
xstring
```
