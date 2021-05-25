# Family Resemblance in Genre Stylistics
[![DOI](https://zenodo.org/badge/370617664.svg)](https://doi.org/10.5281/zenodo.4785348)

Data and scripts accompanying the paper "Family Resemblance in Genre Stylistics: A Case Study with 19th Century Spanish American Novels" authored by Ulrike Henny-Krahmer.

Family resemblance is a concept that has been introduced into genre theory as an analogy to describe partial and overlapping similarities between different works of the same genre. It has often been referred to in the description of historical changes of genres. Here, the concept of family resemblance is taken up to analyze a corpus of 19th century Spanish American novels with computational methods. A formal implementation of the concept is developed and applied to historical and sentimental novels. For this, networks of nearest neighbors are built on topic features, first for historical and sentimental novels alone and then for the two subgenres together. Subgroups in the networks are identified with community detection.

To generate the topic model, the tool [_tmw_](https://github.com/cligs/tmw/) was used. Because the tmw files were customized, a copy of the topic modeling workflow is included [here](tmw).

The scripts and data in this repository are licensed under the GNU General Public License v3.0.
