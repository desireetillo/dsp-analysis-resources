# Analyzing GeoMX DSP Transcriptome Atlas Data

Collaborative Protein Technology Resource (CPTR)  
CCR Genomics Core

*Last updated: 2022-10-25*


### Raw data processing

Fastq files are converted into digital count (DCC) files using v2.3.3.10 of the [GEOMX NGS pipeline](https://nanostring.com/products/geomx-digital-spatial-profiler/software-updates/v2-4/). We have performed this step for you.

An installation of the GeoMX NGS pipeline is available on the [NIH biowulf cluster ](https://hpc.nih.gov/apps/geomx_ngs_pipeline.html)as a module.


### Data analysis software

DCC files are imported into the interactive secondary analysis on the GeoMX Data Analysis software on the GeoMX DSP instrument. A member of CPTR will contact you when your data have been loaded on the DSP.

Information on analysis using the GeoMX Data Analysis software can be found [here](https://university.nanostring.com/geomx-dsp-data-analysis-user-manual/1163670).

### Off instrument analysis resources
 
* [DSP config files](https://nanostring.com/products/geomx-digital-spatial-profiler/geomx-dsp-configuration-files/):  PKC files for GeoMX RNA assays

* [GeoMXTools bioconductor package](http://www.bioconductor.org/packages/release/bioc/html/GeomxTools.html): Bioconductor package containing tools for NanoString Technologies GeoMx Technology. Package provides functions for reading in DCC and PKC files based on an ExpressionSet derived object. Normalization and QC functions are also included. Helpful vignettes here (including protein assays)

* [GeoMXWorkflows vignette](https://bioconductor.org/packages/release/workflows/vignettes/GeoMxWorkflows/inst/doc/GeomxTools_RNA-NGS_Analysis.html):  Describes basic QC, normalization, and setup of differential expression analyses for CTA/WTA data

* [SpatialDecon](https://bioconductor.org/packages/release/bioc/html/SpatialDecon.html): Bioconductor package for estimation of cell-type abundance in spatial (CTA/WTA) and bulk expression data described in Danaher et al., Nature Communications 2022

* [GeoScript Hub](https://nanostring.com/products/geomx-digital-spatial-profiler/geoscript-hub/):  Nanostring contributed R scripts for data normalization, dimensionality reduction, visualization (e.g. heatmaps, volcano plots), can be used within the GeoMX DSP analysis suite

* [SpatialGE](https://fridleylab.github.io/spatialGE/): An R package for the visualization and analysis of spatially-resolved transcriptomics data

* [GeoDiff](https://github.com/Nanostring-Biostats/GeoDiff):  R package for different normalization strategies for analyzing GeoMX RNA assays

* [DSP Workflow on NIDAP](https://bioinformatics.ccr.cancer.gov/ccbr/education-training/nidap-training/?cid=eb_govdel#:~:text=Digital%20Spatial%20Profiling%20Analysis%20Workflow%3A):  Workflow on the NIH Integrated Data Analysis Platform (NCI only)

### Other resources

* [Nanostring University](https://university.nanostring.com/):  Courses, manuals, and documents for Nanostring assays

* [Spatial Data Analysis Service (sDAS)](https://nanostring.com/products/geomx-digital-spatial-profiler/spatial-data-analysis-service/):  NanoString data analysis service for spatial biology experiments run on the GeoMx DSP


