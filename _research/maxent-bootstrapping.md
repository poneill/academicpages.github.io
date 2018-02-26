---
title: "MaxEnt Bootstrapping for Biological Sequence Motifs"

excerpt: "MaxEnt bootstrapping provides a general framework for assessing the significance of arbitrary statistics of sequence motifs.<br/><img src='/images/maxent_schematic-500x300.png'>"

collection: research
---

<img src='/images/maxent_schematic-800x600.png'>

Much work in bioinformatics comes down to determining
whether a given property of a sequence motif is "interesting" or
"unusual".  To help answer such questions in a principled manner, we
can define a probability distribution over all motifs subject to a
constraint on mean information content.  We can then sample this
distribution (exactly and efficiently) in order to estimate the null
distribution of said property.