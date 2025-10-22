# Reproducible datasets and code for:

## Sex-role-reversal and the Bateman gradient in coucals – females benefit from mating with multiple partners

### Guadalupe Lopez-Nava<sup>1,2</sup>, Ignas Safari<sup>3</sup>, Clemens Küpper<sup>4</sup>, Wolfgang Goymann<sup>1,2,5</sup>*
\* corresponding author

1)  *Max Planck Institute for Biological Intelligence (MPI-BI), Department Behavioural Neurobiology, Eberhard-Gwinner-Str., 82319 Seewiesen, Germany.*
2)  *Ludwig Maximilians University Munich, Department Biology II, Großhaderner Str. 2, 82152 Martinsried, Germany.*
3)  *Department of Biology, College of Natural and Mathematical Sciences, University of Dodoma, P.O. Box 338, Dodoma, Tanzania.*
4)  *Max Planck Institute for Biological Intelligence (MPI-BI), Behavioural Genetics and Evolutionary Ecology, Eberhard-Gwinner-Str., 82319 Seewiesen, Germany.*
5)  *Coucal Project, P.O. Box 26, Chimala, Tanzania.*

✉ For correspondence regarding the code and statistical analyses, please
contact: Guadalupe (<a href= "mailto:lopez-nava.guadalupe@bi.mpg.de">lopez-nava.guadalupe[at]bi.mpg.de</a>)

✉ For correspondence regarding the data collection , statistical analyses and study systems please
contact: Wolfgang (<a href= "mailto:wgoymann@bi.mpg.de">w.goymann[at]bi.mpg.de</a>)

In this repository you can find all the data and code needed to reproduce our study on 
Bateman Gradients in Black coucals (*Centropus grillii*) and White-browed coucals
(*Centropus superciliosus*) inhabiting the Usangu wetlands of Tanzania.
Our study is based on data collected over **15 breeding seasons** for Black coucals and **13 breeding** seasons
for White-browed coucals. 

| Female Black Coucal | White-browed Coucals |
|--------------|-------------------|
| ![](images/Blackcoucal.jpeg)| ![](images/WBcoucals.jpeg) |


#### Repository Contents

- [`BatemangradientsCoucals.Rproj`](https://github.com/lguadal/Batemangradients_coucals/blob/main/BatemangradientsCoucals.Rproj)
    RStudio project to run and reproduce results.

*Notes*: 
1) All analyses in Rmarkdown scripts are referenced according to their number in the manuscript.
2) Tables were created using the R package [gt v.0.2.2](https://cran.r-project.org/web/packages/gt/index.html).
3) Figures were created using  R package [ggplot2 v.3.3.3](https://cran.r-project.org/web/packages/ggplot2/index.html).

##### Black coucals 
- [`GradientsBC.Rmd`](https://github.com/lguadal/Batemangradients_coucals/blob/main/GradientsBC.Rmd)
    R Markdown script containing the statistical analyses. Outputs of estimates of 1) bateman gradients, 2) differences between sex classes, 3) opportunities for selection and sexual selection and 4) Path Selection analyses for age. 
- [`PathsSelection_BC.Rmd`](https://github.com/lguadal/Batemangradients_coucals/blob/main/PathsSelection_BC.Rmd)
    R Markdown script containing the path selection analyses of morphological traits. 

##### White-browed coucals
- [`GradientsWB.Rmd`](https://github.com/lguadal/Batemangradients_coucals/blob/main/GradientsWB.Rmd)
    R Markdown script containing the statistical analyses. Outputs of estimates of 1) bateman gradients, 2) differences between sex classes and  3) opportunities for selection and sexual selection.
- [`PathsSelection_BC.Rmd`](https://github.com/lguadal/Batemangradients_coucals/blob/main/PathsSelection_WB.Rmd)
    R Markdown script containing the path selection analyses of morphological traits.

[**`figures`**](https://github.com/lguadal/Batemangradients_coucals/tree/main/figures) 

-   [`/black coucals/ Fig1`](https://github.com/lguadal/Batemangradients_coucals/blob/main/figures/black%20coucals/Fig1_gradients_BC.png) 
-   [`/whitebrowed coucals/Fig2`](https://github.com/lguadal/Batemangradients_coucals/blob/main/figures/whitebrowed%20coucals/Fig2_gradients_WC.png) 
-   [`Fig3`](https://github.com/lguadal/Batemangradients_coucals/tree/main/figures/fig3) All figures associated to the panel saved individually.

[**`images`**](https://github.com/lguadal/Batemangradients_coucals/tree/main/images) folder containing the images in the README file.
-   [`WBcoucals.jpeg`](https://github.com/lguadal/Batemangradients_coucals/blob/main/images/WBcoucals.jpeg) 
-   [`Blackcoucal.jpeg`](https://github.com/lguadal/Batemangradients_coucals/blob/main/images/Blackcoucal.jpeg)

[**`supl`**](https://github.com/lguadal/Batemangradients_coucals/tree/main/supl) folder containing figures and tables of the supplementary information.

-   [`FigS1.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/supl/FigS1.png) 
-   [`TabS1a.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/supl/TableS1a_BC.pdf)
-   [`TabS1b_females.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/supl/TableS1b_females_BC.pdf) 
-   [`TabS1b_males.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/supl/TableS1b_males_BC.pdf)
-   [`TabS2a.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/supl/TableS2a_WBC.pdf)
-   [`TabS2b.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/supl/TableS2b_WBC.pdf)

[**`tables`**](https://github.com/lguadal/Batemangradients_coucals/tree/main/tables) 
-   [`Table1_BC_I.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/tables/Table1_BC_OppSel.pdf) Estimates Opportunity for Selection in Black coucals.
-   [`Table1_BC_Is.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/tables/Table1_BC_OppSexSel.pdf) Estimates Opportunity for Sexual Selection in Black coucals.
-   [`Table1_WB_I.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/tables/Table1_WB_OppSel.pdf) Estimates Opportunity for Selection in White-browed coucals.
-   [`Table1_WB_Is.pdf`](https://github.com/lguadal/Batemangradients_coucals/blob/main/tables/Table1_WB_OppSexSel.pdf) Estimates Opportunity for Sexual Selection in White-browed coucals.

[**`tables/estimatediff/`**](https://github.com/lguadal/Batemangradients_coucals/tree/main/tables/estimatediff) outputs of estimated differences in slopes and selection opportunities in both coucal species.

### Datasets description: 
- For each provided data set, we include details on the variables presented. Each row the associated information of an individual bird.
- Standardized values of mating and reproductive success are generated directly through the analysis in the Rmarkdown scripts.

[**`data`**](https://github.com/lguadal/Batemangradients_coucals/tree/main/data) CSV files associated to the statistical analyses in the study.

###### Black coucals 
-   [`blackcoucal_gradients.csv`](https://github.com/lguadal/Batemangradients_coucals/blob/main/data/blackcoucal_gradients.csv)
-   [`data_morpho_BC.csv`](https://github.com/lguadal/Batemangradients_coucals/blob/main/data/data_morpho_BC.csv)

###### White-browed coucals
-   [`whitebrowedcoucal_gradients.csv`](https://github.com/lguadal/Batemangradients_coucals/blob/main/data/whitebrowedcoucal_gradients.csv)
-   [`data_morpho_WB.csv`](https://github.com/lguadal/Batemangradients_coucals/blob/main/data/data_morpho_WB.csv)


---
#### [`blackcoucal_gradients.csv`](https://github.com/lguadal/Batemangradients_coucals/blob/main/data/blackcoucal_gradients.csv)

| Column name       | Type   | Units / Scale                        | Description |
|------------------|--------|--------------------------------------|-------------|
| `ring_no_lab`     | factor | categorical (299 levels)             | An anonymized identifier for each individual bird obtained from sibship analyses. |
| `year`            | factor | categorical (2001–2015)              | Year when the bird was sampled. |
| `ring_no`         | factor | categorical (166 levels)             | Ring number identifying each bird. |
| `sex`             | factor | categorical (`female`, `male`)       | Sex of the individual. |
| `age`             | factor | categorical (1, 2, 3)               | Age class of the individual (in years) |
| `totaloff`        | numeric| count                                | Total number of offspring sired by the individual. |
| `totalmates`      | numeric| count                                | Total number of genetic mates for the individual. |
| `epy`             | factor | categorical (0, 1)                   | Extra-pair offspring indicator (1 = extra-pair offspring present, 0 = none). |
| `category`        | factor | categorical ("1females", "2males"", "3malesENO"")| Classification category of the individual (2males == males without extra nest offspring (ENO); 3malesENO == males with ENO). |
| `totalnest_sum`   | numeric| count                                | Total number of nests where an individual sired offspring.|

---

---
#### [`data_morpho_BC.csv`](https://github.com/lguadal/Batemangradients_coucals/blob/main/data/data_morpho_BC.csv)

| Column name           | Type    | Units / Scale                        | Description |
|----------------------|---------|--------------------------------------|-------------|
| `ring_no`             | factor  | categorical (163 levels)             | Ring number identifying each bird. |
| `sex`                 | factor  | categorical (`female`, `male`)       | Sex of the individual. |
| `year`                | factor  | categorical (2001–2014)              | Year when the bird was sampled. |
| `parent`              | factor  | categorical (163 levels)             | An anonymized identifier for each individual bird obtained from sibship analyses.  |
| `totaloff`            | integer | count                                | Total number of offspring produced by the individual. |
| `totalmates`          | integer | count                                | Total number of genetic mates of the individual. |
| `epy`                 | integer | count (0/1)                          | Number of extra-pair young produced. |
| `category`            | factor  | categorical (1females, 2males, etc.)|  Classification category of the individual (2males == males without extra nest offspring (ENO); 3malesENO == males with ENO). |
| `species`             | factor  | categorical (1 level: black coucal)  | Species of the bird. |
| `body_mass`           | integer | g                                     | Body mass of the individual. Some entries missing. |
| `right_tarsus`        | numeric | mm                                    | Length of the right tarsus. |
| `tarsus_mean_SMI`     | numeric | mm                                    | Mean tarsus length used for scaled mass index calculations. |
| `scaled_mass_index`   | numeric | g                                     | Scaled mass index for body condition. |
| `tail_body`           | integer | mm                                    | Tail-to-body length measurement. |

---
---
#### [`whitebrowedcoucal_gradients.csv`](https://github.com/lguadal/Batemangradients_coucals/blob/main/data/whitebrowedcoucal_gradients.csv)

| Column name       | Type   | Units / Scale                        | Description |
|------------------|--------|--------------------------------------|-------------|
| `lab_id`          | factor | categorical (162 levels)             | Laboratory ID for each individual bird. |
| `year`            | factor | categorical (2005–2017)             | Year when the bird was sampled. |
| `no_off`          | numeric| count                                | Total number of offspring sired by the individual. |
| `no_mates`        | numeric| count                                | Total number of genetic mates of the individual. |
| `sex`             | factor | categorical (`female`, `male`)       | Sex of the individual. |
| `ring_no`         | character | text                              | Ring number identifying each bird. |

---
---
#### [`data_morpho_WB.csv`](https://github.com/lguadal/Batemangradients_coucals/blob/main/data/data_morpho_WB.csv)

| Column name           | Type    | Units / Scale                        | Description |
|----------------------|---------|--------------------------------------|-------------|
| `ring_no`             | factor  | categorical (96 levels)              | Ring number identifying each individual bird. |
| `sex`                 | factor  | categorical (`female`, `male`)       | Sex of the individual. |
| `year`                | factor  | categorical (2005–2017)             | Year when the bird was sampled. |
| `lab_id`              | factor  | categorical (96 levels)             |  An anonymized identifier for each individual bird obtained from sibship analyses. |
| `no_off`              | integer | count                                | Total number of offspring produced by the individual.  |
| `no_mates`            | integer | count                                | Total number of genetic mates of the individual. |
| `species`             | factor  | categorical (1 level: white-browed coucal) | Species of the bird. |
| `body_mass`           | integer | g                                     | Body mass of the individual. |
| `right_tarsus`        | numeric | mm                                    | Length of the right tarsus. |
| `tarsus_mean_SMI`     | numeric | mm                                    | Mean tarsus length used for scaled mass index calculations. |
| `scaled_mass_index`   | numeric | g                                     | Scaled mass index for body condition;.|
| `tail_body`           | integer | mm                                    | Tail-to-body length measurement. |

---

#### Usage Policy

You are welcome to view and download the materials in this repository.  
However:
- **Do not** use, modify, or share any code or data without **written permission** by Wolfgang Goymann (<a href= "mailto:w.goymann@bi.mpg.de">w.goymann[at]bi.mpg.de</a>) 

© 2025 Guadalupe Lopez-Nava – All rights reserved.
