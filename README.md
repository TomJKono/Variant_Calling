# Variant_Calling
Variant calling from high throughput sequence data. These scripts are written to
work on the University of Minnesota Supercomputing Institute's compute clusters.
The scripts in this repository will take advantage of list-based processing
tools to handle batches of samples.

The scripts presented here will call variants for a variety of applications. At
least for now, pipelines to call variants in whole genome or exome resequencing
as well as in GBS data exist. The current workflows use the [GATK](
https://www.broadinstitute.org/gatk/) from the Broad Institute. Other tools,
such as [Platypus](http://www.well.ox.ac.uk/platypus) from the Wellcome Trust
Centre may be used in the future.

Parameters for the stages of variant calling are defined in a central
configuration file.

## Goals
- TBA
