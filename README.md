# RF-Supertrees
This program takes as input a collection of rooted trees and heuristically searches for a binary supertree that minimizes the total (rooted) Robinson-Foulds distance between the supertree and the input trees.

# Download

* RFS v2.0 executables for: [Linux](https://iastate.box.com/s/jyp9y29az90s6ocyicfh6jyf021mn5ni), [Mac (Intel)](https://iastate.box.com/s/3em6amcscmaggwyx42mkvch05wrc9agr), [Windows](https://iastate.box.com/s/7x6q0kte10juneb0m5gt16unfvds2gd7)
* [Manual](https://iastate.box.com/s/d6xheaix7g2e9zkol7q1pinhy3hjkqaf)
* Sample dataset: [seabirds.newick](https://iastate.box.com/s/9x2qd4svlaorux3u2wr9p91p5b7889zc)

This program takes as input a collection of rooted trees and heuristically searches for a binary supertree that minimizes the total (rooted) Robinson-Foulds distance between the supertree and the input trees. The intuition behind seeking a binary supertree, even though the input trees may be non-binary (unresolved), is that, under this setting, minimizing the RF distance is equivalent to maximizing the number of shared clades (or clusters) between the input trees and the supertree. Thus, an RF supertree is a supertree that is consistent with the largest number of clusters from the input trees. The program can quickly compute accurate supertrees for even large datasets containing thousands of input trees with many hundreds of taxa.

The new version of RFS (v2.0) implements several enhancements that make the software much faster and even more accurate.

The software can be cited as follows:

[Robinson-Foulds Supertrees](https://almob.biomedcentral.com/articles/10.1186/1748-7188-5-18)
   Mukul S. Bansal, J. G. Burleigh, Oliver Eulenstein, David Fernandez-Baca.
   Algorithms for Molecular Biology 2010, 5:18.

This work was supported in part by NSF grants DEB-0334832 and DEB-0829674.

Contact: Please feel free to contact Mukul Bansal (mukul@engr.uconn.edu) if you have any questions, concerns, or suggestions.
