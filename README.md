# ACheatSheetForTheTransparentCHIPaper
Repo for the cheat sheet for the transparent CHI paper

To compile locally, you will need a LaTeX installation. One idea is to use TinyTex, a minimal LaTeX distribution which is integrated well with R and RStudio. In R, you can run

```
install.packages("tinytex")
tinytex::install_tinytex()
```

to install a minimal TeX installation. If you are not an R user, you can [install TinyTex from the commandline](https://yihui.org/tinytex/#for-other-users), or use a LaTeX distribution that allows you to install via point and click. For example, [TexShop](https://yihui.org/tinytex/#for-other-users) for Mac or [MikTex](https://miktex.org/), which works on many systems.  

If you go the TinyTex direction, you may also need to install a few additional packages. This can also be done from within R,

```
library(tinytex)
tlmgr_install(c("beamerposter", "type1cm", "fontawesome5", "ccicons", "babel-english"))
```

If you are using a less lightweight LaTeX installation, some of these packages may come with your installation, or you will need to learn to use a package manager.

