# [ArchiCAD-Objects](https://github.com/runxel/ArchiCAD-Objects)
ArchiCAD Objects made (or modified) by me.

---

### How to use?
Files are uploaded as `.gsm` (ArchiCAD library part / "object") and in the new HSF format introduced in Archicad 23.   
Thus they are easier to maintain and also you can see the source code directly. Converting can be done by using the [LP_XMLConverter](http://gdl.graphisoft.com/tips-and-tricks/how-to-use-the-lp_xmlconverter-tool/).  
The `.gsm` can be used directly and hasslefree. Please have a look at the compatibility down below.

#### Why are you not using the XML exchange format?
I did for a while, but it's plain useless now that we have the HSF format available thru the LP_XMLConverter. If you want to use it right away, there is `.gsm`; if you want to get a grasp of the code, the `.gdl` files are much more legible (And also you can go and edit it in an instant by cloning the repo unto your PC).


---

## Objects:

### [Text auf Polylinie](Objects/Text_auf_Polylinie)  
![Compatibility](https://img.shields.io/badge/compatibility-v20_build_6005_▲-lightgrey?style=flat-square)
![Language](https://img.shields.io/badge/language-GER-lightgrey?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-No-a9dfbf?style=flat-square) 
![Version](https://img.shields.io/badge/version-1.0-2980b9?style=flat-square)

_Description_:  
(DE) Zur Darstellung von Text auf einer Polylinie, auch in 3D. Nutzbar für Höhenlinien, Grenzen, u.ä.  
(EN) Shows text on a polyline, even in 3D. Use cases are elevation lines, boundary curves, etc.  
Credit to Esteban Ramos for his polyline code.

![text on polyline](Objects/Text_auf_Polylinie/Text_auf_Polylinie/images/Picture_0.png)


## [Spannrichtung](Objects/Spannrichtung)  
![Compatibility](https://img.shields.io/badge/compatibility-v19_build_5005_▲-lightgrey?style=flat-square)
![Language](https://img.shields.io/badge/language-GER-lightgrey?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-"Resize__A__B__ZZYZX"_macro-ff7979?style=flat-square)
![Version](https://img.shields.io/badge/version-2.0-2980b9?style=flat-square)

_Description_:  
(DE) Zeigt die Spannrichtung von Deckenplatten im Tragwerksplan an. Sichtbarkeit richtet sich nach der Modelldarstellung. Darstellung gemäß DIN 1356-1 (12.4).  
(EN) Shows the direction of stress in ceiling slabs in the structural plan. Visibility depends on the MVO. Representation according to DIN 1356-1.  

![span direction](Objects/Spannrichtung/Spannrichtung/images/Picture_0.png)


## [Rollstuhlgerecht](Objects/Rollstuhlgerecht)  
![Compatibility](https://img.shields.io/badge/compatibility-v22_▲-lightgrey?style=flat-square)
![Language](https://img.shields.io/badge/language-GER-lightgrey?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-No-a9dfbf?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0-2980b9?style=flat-square)

_Description_:  
(DE) Zur Überprüfung von Bewegungsflächen und des Wendekreises eines Rollstuhlfahrers.  
(EN) For checking of turning circle of wheelchair users.  

![turning circle](Objects/Rollstuhlgerecht/Rollstuhlgerecht/images/Picture_0.png)


## [Faltmarker](Objects/Faltmarker)  
![Compatibility](https://img.shields.io/badge/compatibility-v20_▲-lightgrey?style=flat-square)
![Language](https://img.shields.io/badge/language-GER-lightgrey?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-No-a9dfbf?style=flat-square)
![Version](https://img.shields.io/badge/version-1.2-2980b9?style=flat-square)

_Description_:   
(DE) Faltmarker zur Verwendung im Layout und der anschließenden (physischen) Ablage im A4-Endformat. DIN 824 konform.  
(EN) Folding marker for the use in the layout. DIN 824 compliant.  

![Faltmarker](Objects/Faltmarker/Faltmarker/images/Picture_0.png)  
DIN 824:  
![DIN 824](https://i.imgur.com/G5TzGH7.png)


---

### Compatibility
It is assumed that objects will be upwards compatible. Meaning: the version numbers above are the _lowest_ possible Archicad version where you can use the corresponding object.  
(If for any reason an object is not upwards compatible at some point in the future I will either make a new one, or will clearly state it here.)

---

If not stated otherwise the license is [Public Domain CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).  
Please consider making pull requests if you find and correct bugs and/or introduce new features!

---


**Proudly made with [Sublime Text 3](https://www.sublimetext.com/) and the [GDL-Sublime](https://github.com/runxel/GDL-sublime) plugin.**

_Tautological boilerplate: All trademarks and copyrights on this page are the property of their respective owners._
