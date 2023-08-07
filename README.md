# Calculate Average Methylation Workflow
Calculates haplotype-specific average percent modification per region, and additional stats, using modbamtools

## Input considerations
* Sorted and indexed aligned with long reads BAM (.bam file)
* Index for BAM (.bai file)
* BED file defining promoters or regions of interest for average methylation calculation

## Test locally
```
miniwdl run --as-me -i test.inputs.json workflow.wdl
```