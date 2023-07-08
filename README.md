# CIGS-AE

Cuneiform Inscriptions Geographical Site - Assemblage Estimates

### Summary 
The *Cuneiform Inscriptions Geographial Site - Assemblage Estimates* (CIGS-AE) provides basic overall estimates of and bibliographical references for the approximate number of cuneiform inscriptions derived from individual archaeological locations. In use across the wider Middle East from c. 3,400 BCE until 100 CE, cuneiform is one of the earliest and most extensively documented ancient scripts in world history. The CIGS-AE is a component of the [*Cuneiform Inscriptions Geographial Site* (CIGS)](https://doi.org/10.5281/zenodo.4960710) index, a digital geospatial register of archaeological sites with finds of cuneiform inscriptions across Europe, Asia, and Africa.

CIGS-AE provides a first comprehensive quantitative overview of the approximate number of cuneiform inscriptions unearthed from known archaeological locations. It does not provide an overview of the entire corpus of cuneiform inscriptions known, as the index disregards all inscriptions with no verifiable archaeological origin, estimated to be between fifteen and twenty per cent of the overall corpus according to the catalogue of the [Cuneiform Digital Library Initiative](https://cdli.mpiwg-berlin.mpg.de/heatmap). The present resource then offers a lower threshold for the size of the full cuneiform corpus and a fairly reliable overview of its general distribution. The accompanying bibliography offers a basic set of references for all known archaeological sites with finds of cuneiform inscriptions. This information is intended as a starting point for further study, and should not be considered an exhaustive nor authoritative bibliography.

Data for individual sites has been compiled through the following steps:

* Review of primary and most recent publications on unearthing of cuneiform inscriptions at a given location to provide an overview of research and publication history
* Where relevant publications provided no information on the number of inscriptions found at a given location, major digital catalogues within the field, chiefly the [Cuneiform Digital Library Initiative](https://cdli.mpiwg-berlin.mpg.de), have been consulted to generate a minimum number.
* Depending on the scale of cuneiform finds at a given location, estimates given in the index have been compiled by either of the following two approaches:
  1. For smaller assemblages, by counting the number of inscriptions mentioned in individual publications
  2. For larger assemblages, by aggregating estimates provided by relevant specialist surveys of inscriptions from a given location, e.g. Pedersén (1998) *Archives and Libraries in the Ancient Near East, 1500-300 BC*, including figures from all periods.
* In the few cases where no qualified estimate of inscriptions from a given location could be found, the assemblage estimate is derived from the [Cuneiform Digital Library Initiative](https://cdli.mpiwg-berlin.mpg.de).

This resource has been prepared by researchers of the [Department of Linguistics and Philology](lingfil.uu.se) of [Uppsala University](uu.se). The index is intended as a tool for students and researchers in cuneiform studies and related areas and as an aid to cultural heritage managers and educators in communicating and safeguarding this unique body of world written heritage. The index remains under development and is regularly updated. The authors will very much appreciate notices of any omissions, errors, or inaccuracies. For any inquiries, please contact [Rune Rattenborg](https://www.katalog.uu.se/profile/?id=N18-1120) ([rune.rattenborg@lingfil.uu.se](mailto:rune.rattenborg@lingfil.uu.se)).

### Formal
Versions v.1.x and higher are released as *Cuneiform Inscriptions Geographical Site - Assemblage Estimates* (CIGS-AE) and prepared by Gustav Ryberg Smidt with further support from individual authors mentioned below and [Geomapping Landscapes of Writing (GLoW): Large-scale Spatial Analysis of the Cuneiform Corpus (c. 3400 BCE to 100 CE)](https://www.lingfil.uu.se/research/assyriology/glow/), a project funded by [Riksbankens Jubileumsfond](https://rj.se) (grant no. [MXM19-1160:1](https://rj.se/en/grants/2019/geomapping-landscapes-of-writing-glow-large-scale-spatial-analysis-of-the-cuneiform-corpus-c.-3400-bce-to-100-ce)). The data set is released (as of v.1.0) as a .csv with an accompanying bibliography included in a separate .bibtex file. All resources are released under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/) ([https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)). The index and its application is discussed and deployed in [Rattenborg et al. (2023) “The archaeological distribution of the cuneiform corpus: a provisional quantitative and geospatial survey”](INSERT URL). 

Please cite as: Smidt, Gustav Ryberg; Carolin Johansson, Nils Melin-Kronsell, Seraina Nett, Rune Rattenborg. 2023. "Cuneiform Inscriptions Geographical Site Index - Assemblage Estimates (CIGS-AE)". v.1.0 Zenodo, 1 July 2023. 

### Version history

version | date | online release | description
:---|:-----|:---:|:--------------------
**v. 1.0** | July 2023 | 01/07/2023 | 599 entries and 4 fields (see data specification below)

### Index field categories

field | type | description
:----|:----:|:--------------------------------
**site_id** | string | A string of three letters corresponding to the site_id published in the [*Cuneiform Inscriptions Geographial Site* (CIGS)](https://doi.org/10.5281/zenodo.4960710) index
**est** | integer | A whole number representing the estimated amount of texts from a given site
**est_ref** | string | The short title of main references for the estimate provided in **est**, giving a minimum of one and a maximum of three separate sources. Individual references are separated by ";". Individual reference short titles match the short title given for the corresponding reference in the CIGS-AE .bib-file.
**est_size** | integer | An interval category with five classes (1-5), indicating assemblage size of a given location with 1 being the smallest and 5 the largest. The size ranges employed are described in more detail in [Rattenborg et al. (2023) “The archaeological distribution of the cuneiform corpus: a provisional quantitative and geospatial survey”](INSERT URL). 
**notes** | string | Additional notes, typically to clarify counts given in **est** or references in **est_ref**.








