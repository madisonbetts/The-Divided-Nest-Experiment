# The Divided Nest Experiment
## *Embryonic selfish-herding blurs the line between brood parasitism and mutualism for communal-breeding stream fishes*

The following repository contains data, code, and information related to a study conducted by the Frimpong Lab at Virginia Tech, which investigated the distribution of Leuciscid embryos within bluehead chub nests in Toms Creek, near Blacksburg, VA, USA from 2021-2023. As of October, 2025, the full study has been accepted for publication at *Ecology*.

### Primary Contacts: Maddie Betts (mmbetts03@gmail.com), Emmanuel Frimpong (frimp@vt.edu)

## Background

Bluehead chub (*Nocomis leptocephalus*) is a minnow species (family: Leuciscidae) common across the southeast United States. They are known for the large, mounded nests they construct out of streambed pebbles that attract other species of leuciscids as "nest associates," which spawn with bluehead chub. The relationship between bluehead chub and nest associates is thought to be mutualistic, however, mutualisms are inherently selfish interactions, with all participating parties attempting to benefit without cost. We investigated the distribution of different species' embyros on nests of bluehead chub to determine if the chub is disproportionately benefiting from the relationship by positioning its embryos such that those of its nest associates are forced to the less-desirable nest periphery. 

![bluehead chub tending its nest](chubpic.JPG)

*A bluehead chub sets a stone on its nest, amidst a swarm of nest associates.*

## Objective

The objective of this study was to determine whether certain species in the heterospecific spawning aggregation on a bluehead chub nest predominantly benefit from the protection of the nest as opposed to a random mix of embryo that would afford every participant an equal benefit. 

## Methods
1) We collected embryos from 20 bluehead chub nests using a systematic nest-dismantling protocol that defined six separate nest compartments
2) After subsampling the embryos, we identified each embryo to species using DNA barcoding
3) Embryo distributions for each species were analyzed using an information theoretic approach and model-based inference; we developed three model sets: Model Set A (overall total embryo distributions), Model Set B (host vs. associate distribution comparisons), and Model Set C (manipulator vs. non-manipulator distribution comparisons). 

## Results

In this study, we show that adult *Nocomis* have a reason to accept spawning nest associates onto their nests - they can selfishly manipulate embryo placement to ensure a higher chance of survival for their own young. Substrate-manipulating associates similarly benefit from nest association to a greater degree than non-manipulators, an effect worthy of additional study. Our results highlight the complexity of leuciscid reproduction, introduce the existence of embryonic selfish-herds into discussion of mutualisms, and may offer support for re-examining some interspecific interactions among vertebrates currently labelled as brood parasitism.

## Navigation of Repository

| File | Contents |
| --- | --- |
| embryo_distribution.xlsx | Raw data and preliminary statistics associated with genetics sequencing, nest division field sampling, and larval proportions, see readme tab for details  |
| embryo_distribution.Rmd | Finished R markdown file with all code used for anlaysis of embryonic distribution, and larval distribution within nests |

## Funding and Acknowledgments

This study was supported by the National Science Foundation (grant #2039692). All methods were conducted with approval from the Virginia Tech Institutional Animal Care and Use Committee (IACUC) under permit number 20-213. The participation of coauthor E.M.H. was supported in part by the Virginia Agricultural Experiment Station under the U.S. Department of Agriculture’s National Institute of Food and Agriculture program. We would like to thank S. Brooks, M. Burgess, T. Bustamante, N. Ferguson, S. Floyd, H. Greenway, M. Harris, K. Mowry, T. Pham, B. Peoples, E. Shawish, T. Stephenson, K. Tanner, and S. Wolf for their help in the field and lab. Special thanks to G. Anane-Taabeah, C. Carey, S. Harris, and K. Ortiz for their help troubleshooting in the genetics laboratory, and to T. Pusser for his photography.  

[![DOI](https://zenodo.org/badge/1024537475.svg)](https://doi.org/10.5281/zenodo.16955721)
