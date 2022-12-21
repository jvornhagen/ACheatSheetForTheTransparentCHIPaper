# A Cheat Sheet For The Transparent CHI Paper
Repo for the "Cheat Sheet for the Transparent CHI Paper"

## Credits
This work was started during the Dagstuhl Seminar 22392 by Lahari Goswami, Amelia McNamara, Viktorija Paneva, Jan Benjamin Vornhagen, and Erich Weichselgartner. For full credit, please refer to the CREDIT_List.csv.

Please cite as:
Lahari Goswami, Amelia McNamara, Viktorija Paneva, Jan B Vornhagen, and Erich Weichselgartner. 2022. A Cheat Sheet for a Transparent CHI paper. https://doi.org/10.17605/OSF.IO/YHWUQ


## Instructions
To compile locally, you will need a LaTeX installation. One idea is to use TinyTex, a minimal LaTeX distribution which is integrated well with R and RStudio. In R, you can run

```
install.packages("tinytex")
tinytex::install_tinytex()
```

to install a minimal TeX installation. If you are not an R user, you can [install TinyTex from the commandline](https://yihui.org/tinytex/#for-other-users), or use a LaTeX distribution that allows you to install via point and click. For example, [TexShop](https://yihui.org/tinytex/#for-other-users) for Mac or [MikTex](https://miktex.org/), which works on many systems.  

If you go the TinyTex direction, you may also need to install a few additional packages. This can also be done from within R,

```
library(tinytex)
tlmgr_install(c("beamer", "beamerposter", "type1cm", "fontawesome5", "ccicons", "babel-english", "caption", "grfext"))
```

If you are using a less lightweight LaTeX installation, some of these packages may come with your installation, or you will need to learn to use a package manager.

## Acknowledgements

We want to thank the following people for their input and recommendations:

* Chat Wacharamanotham for organising the Dagstuhl seminar, bringing us all together, and giving valuable input to for this cheat sheet.

* Mikke Tavast for providing early feedback.
