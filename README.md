# ExploringHCACxG

Last modified: 7 July, 2022

This package provides an 'Orchestra' environment for exploring the
[hca][] and [cellxgenedp][] packages for Human Cell Atlas data
access. Please see the vignettes for more information.

### Prerequisites

This workshop assumes familiarity with single-cell RNAseq experiments,
especially the 'count matrix' summary of gene x cell expression
values.

The software in this workshop uses [dplyr][] and 'tidy'
representations for working the R data.frame-like data.

The workshop introduces the [SingleCellExperiment][] data
representation, without emphasizing the mechanical aspects of working
with data in this format.

A portion of the workshop uses the [AnVIL computational
cloud][]. Actual use of the cloud (rather than 'following along'
during the presentation) requires some familiarity with Google cloud
computing concepts related to billing; some familiarity with cloud
concepts such as storage buckets and compute engines will also be
helpful.

### Participation

This vignette forms the basis of the workshop
presentation. Participants can 'follow along' during the presentation,
work through detailed steps after the workshop, and explore avenues
suggested by the material and relevant to their own research at their
leisure.

### Time outline

| Activity                                          | Time |
|---------------------------------------------------|------|
| Accessing Human Cell Atlas data from Bioconductor | 15m  |
| Accessing CellxGene data from  Bioconductor       | 15m  |
| Bioconductor, AnVIL, and the HCA                  | 15m  |

### Additional resources

Presentations on similar material include

- Accessing Human Cell Atlas Data with _R_ / _Bioconductor_ and the
  hca package, 2021-10-06 [slides][hca-1]

- _R_ / _Bioconductor_ for Analysis and Comprehension of the Human
  Cell Atlas, 2022-07-20 [slides][hca-2]

[hca]: https://bioconductor.org/packages/hca
[cellxgenedp]: https://bioconductor.org/packages/cellxgenedp
[dplyr]: https://cran.r-project.org/package=dplyr
[SingleCellExperiment]: https://bioconductor.org/packages/SingleCellExperiment
[AnVIL computational cloud]: https://anvilproject.org

[hca-1]: https://bit.ly/hca2021bioc
[hca-2]: https://bit.ly/3aUAbju
