---
layout: default
toc: true
---

# A Software package for fitting small-angle scattering curves

**SASfit** has been written for analyzing and plotting small angle scattering data.
It can calculate integral structural parameters like radius of gyration, scattering invariant,
Porod constant. Furthermore it can fit size distributions together with several form factors
including different structure factors.

Additionally, an algorithm has been implemented, which allows
to simultaneously fit several scattering curves with a common set of (global) parameters. This last
option is especially important in contrast variation experiments or measurements with polarised
neutrons. The global fit helps to determine fit parameters unambiguously which by analysing a single
curve would be otherwise strongly correlated.

![Global fit screenshot](https://github.com/SASfit/SASfit/raw/master/doc/images/sasfit_screenshot_w640.png
"Global fit screenshot")

The program has been written to fulfill the needs at
[the small angle neutron scattering facility at PSI](https://www.psi.ch/en/sinq/sansi).
The numerical routines have
been written in [*C*](https://en.wikipedia.org/wiki/C_(programming_language))
whereas the menu interface has been written in
[*Tcl*](https://en.wikipedia.org/wiki/Tcl)/[*Tk*](https://en.wikipedia.org/wiki/Tk_(software))
and the plotting routine with the [BLT](http://blt.sourceforge.net) extension.

## Author Information

SASfit was developed and is maintained by:

- Joachim Kohlbrecher (joachim.kohlbrecher@psi.ch)
- Ingo Bressler (ingo.bressler@bam.de)

```
Laboratory for Neutron Scattering and Imaging
Paul Scherrer Institut
CH-5232 Villigen PSI
Switzerland
Tel: +41 (0)56 310 3165
Fax: +41 (0)56 310 3131
```

- *SASfit* has been developed at the Paul Scherrer Institute (PSI) and remains copyright of the PSI.
- *SASfit* is available for users analysing data taken at PSI.
- *SASfit* is provided for users of the PSI facilities.
- *SASfit* is provided "as is" and with no warranty.
- *SASfit* is licensed under the GPLv3. For more details see [COPYING.txt](https://github.com/SASfit/SASfit/raw/master/COPYING.txt).

## Publications

Academic papers about SASfit have been published in:

-  [J. Appl. Cryst. (2015). 48, 1587-1598](https://dx.doi.org/10.1107/S1600576715016544)
-  [J. Appl. Cryst. (2017). 50, 1395-1403](https://dx.doi.org/10.1107/S1600576717011979)

If SASfit has been significant in your research, and you would like to acknowledge the project in your academic publication, we suggest citing one of the aforementioned publications.

## Documentation

There is a comprehensive manual included the software package with a jumble of formulas used by SASfit.
It evolves with the program to cover most of the implemented models and functions.
The latest version can also be [viewed online](https://raw.githubusercontent.com/SASfit/SASfit/master/doc/manual/sasfit.pdf).

### Videos

Some tutorial videos can be found [in our channel on YouTube](https://www.youtube.com/user/SASfitTeam).
[An introduction on a simple single curve fit](https://www.youtube.com/watch?v=r_ybV4_K1r0) for example.

## Versions and Changes

The latest changes and versions of the program can be found in the
[Releases section at GitHub](https://github.com/SASfit/SASfit/releases).
