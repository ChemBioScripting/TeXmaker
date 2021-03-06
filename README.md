# TeXmaker
Fork of the [Official TeXmaker Source Code](http://www.xm1math.net/texmaker/download.html).
-------------------------------------------------------------------------------------------

The _Qt toolkit_ (**version >= 5.7**) is required to compile the **version 5.0.3** of _TeXmaker_, together with other packages.

On  [Fedora Linux](https://getfedora.org/) distribution, for example, you will need to install the following packages, as described in the [videotutorial](https://youtu.be/955l78bDlFA) uploaded on [ChemBioScripting | YITA YouTube channel](https://www.youtube.com/channel/UCezPdWWrwIexD96fYNgO4pA):

* `gcc`
* `gcc-c++`
* `qt5`
* `qt5-devel`
* `poppler`
* `poppler-qt5`
* `poppler-qt5-devel`
* `ghostscript`

[![IMAGE ALT TEXT HERE](https://raw.githubusercontent.com/ChemBioScripting/TeXmaker/master/YouTube/copertina.png)](https://www.youtube.com/watch?v=955l78bDlFA)

The source-code can be compiled with `gcc`, `clang` and `msvc`.

> **Warnings** : all new code must have been tested before being proposed. Untested patches will be automatically rejected and all new features must follow the guide lines of the TeXmaker project :
>
> * Keep Texmaker easy to use with a clean and uncluttered interface;
> * Keep Texmaker being really and fully unicode;
> * Keep Texmaker being cross-platform.
