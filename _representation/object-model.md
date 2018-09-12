---
title:  "GA4GH Object Model"
layout: default
permalink: /representation/object-model.html
category: representation
tags:
  - schema
---

# -- DRAFT --

## {{ page.title }}

<div style="display: block; float: right; width: 260px;">
  <img src="/assets/img/ga4gh-object-model.png" />
  <div style="display: block; width: 260px; text-align: justify; font-size: 0.8em; color: #00c; background-color: #eee; padding: 5px;">
A graph showing the basic objects and their relationships. The example attributes represent placeholders for elements defined in the general schema description.
  </div>
</div>

The __GA4GH Object Model__ provides guidance about commonly represented and exchanged higher order data objects and their relationships. The model does not only address objects primarily in the domain of "clinical and phenotypic" data, but aligns with concepts used for genomic data representation, in alignment with the [Genomic Knowledge Standards](https://ga4gh-gks.github.io) working group and driver projects.

### Individual

An individual is a single organism (here typically a human).

### Biosample

In this context, a "biosample" as the source of the material of a molecular analysis (e.g. genomic array, sequencing), represents the main “biological item” against which molecular variants are referenced.

### Callset

The _callset_ object contains information about an experiment performed on material from a single biosample and is a shared identifier for all variants detected in this experiment, attributed to the referenced biosample.

### Variant

A _variant_ is an alteration of the genomic sequence at a specified location, in comparison to a reference genome.

### Additional concepts

While the current model represents a minimal hierarchy, especially for the genomic part, one can foresee the extension by additional grouping categories. In the genomic domain, typical added hierarchy levels could be e.g. _haplotype_ (the sequence status of all alleles at a genomic locus) or _genotype_ (the collection of all variants, for all alleles, i.e. the entire set of _haplotypes_).
