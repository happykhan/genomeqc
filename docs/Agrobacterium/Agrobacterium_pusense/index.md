# *Agrobacterium pusense*

This is the GenomeQC page for *Agrobacterium pusense*. For detailed methods on how these thresholds were calculated, please see [Methods](../../methods.md).
The suggested thresholds are: 

| metric                 | lower_bounds   | upper_bounds   |
|:-----------------------|:---------------|:---------------|
| N50                    | 177000.0       |                |
| no_of_contigs          |                | 230.0          |
| GC_Content             | 59.0           | 60.0           |
| Completeness           | 99.0           |                |
| Contamination          |                | 6.0            |
| Total_Coding_Sequences | 4600.0         | 6300.0         |
| Genome_Size            | 4900000.0      | 6400000.0      |

[Download metrics CSV](Agrobacterium_pusense_metrics.csv){.md-button}


These thresholds are based on **11** genomes from RefSeq and **119** genomes from ATB / SRA.

These thresholds were applied to all the bacteria dataset, which resulted in removing **12** and retaining **107**.
The list of genomes retained (i.e. high quality) and the list of genomes rejected (filtered) can be downloaded below. These files are in `.xz` format. The rejected genomes file, also includes the reason why.

[Download high quality genomes list](Agrobacterium_pusense_high_quality_genomes.csv.xz)


[Download rejected genomes list](Agrobacterium_pusense_filtered_out_genomes.csv.xz)



## Summary Tables
These tables provide a summary of the distribution of each metric, including SDeviation, Mean, Median, and Percentiles.

[Download full summary tables](summary.csv)

[Download simple summary tables](selected_summary.csv)

## Plots and Visualizations

![Genome Size Histogram](Genome_Size_refseq_histogram_kde.png)

This plot is a histogram comparing genome sizes between the SRA and RefSeq datasets. Each bar represents the density of genomes within a specific size range for both datasets. By comparing the shapes and positions of the bars, you can identify differences in genome size distributions, such as shifts, peaks, or outliers. This visualization helps reveal whether one dataset tends to have larger or smaller genomes, or if there are notable differences in variability or coverage between SRA and RefSeq.

![Genome Size Distribution](Genome_Size_refseq_histogram_kde.png)

This plot is a QQ (quantile-quantile) plot, which compares the distribution of the SRA data with RefSeq. Points falling along the diagonal line indicate that the data follows the expected distribution. Deviations from the line suggest departures from normality, such as skewness or outliers. This helps assess whether the dataset is consistently distributed or if there are systematic differences.

![Genome Size QQ Plot](Genome_Size_refseq_qqplot.png)

### Additional Plots

These plots provide additional insights into the genome characteristics:

- [GC Content Histogram](GC_Content_refseq_histogram_kde.png)
- [GC Content QQ Plot](GC_Content_refseq_qqplot.png)
- [Total Coding Sequences Histogram](Total_Coding_Sequences_refseq_histogram_kde.png)
- [Total Coding Sequences QQ Plot](Total_Coding_Sequences_refseq_qqplot.png)
- [Genome Size Histogram](Genome_Size_refseq_histogram_kde.png)
- [Genome Size QQ Plot](Genome_Size_refseq_qqplot.png)
## Illustrating the filtering process
These plots illustrate the data, pre and post filtering to demostrate what type of outliers have been removed. While this was applied to metric, we will demonstrate using total assembly length and N50.
N50 vs total length for all genomes in the dataset.

![ALL Total Length vs N50](Agrobacterium_pusense_all_total_length_N50.png)

N50 vs total length for genomes in the dataset, coloured according to whether they are an anomaly or not.

![Sampled Total Length vs N50](Agrobacterium_pusense_sample_total_length_N50.png)

N50 vs total length post filtering on the dataset.

![Filtered Total Length vs N50](Agrobacterium_pusense_filt_total_length_N50.png)

### Additional Plots

These plots provide additional insights into the genome characteristics:

- [N50 vs number of contigs, all genomes](Agrobacterium_pusense_all_N50_number.png)
- [N50 vs number of contigs, sampled genomes](Agrobacterium_pusense_sample_N50_number.png)
- [N50 vs number of contigs, filtered genomes](Agrobacterium_pusense_filt_N50_number.png)
- [GC Content vs Total Length, all genomes](Agrobacterium_pusense_all_total_length_GC_Content.png)
- [GC Content vs Total Length, sampled genomes](Agrobacterium_pusense_sample_total_length_GC_Content.png)
- [GC Content vs Total Length, filtered genomes](Agrobacterium_pusense_filt_total_length_GC_Content.png)
- [Longest Contig vs Total Length, all genomes](Agrobacterium_pusense_all_total_length_longest.png)
- [Longest Contig vs Total Length, sampled genomes](Agrobacterium_pusense_sample_total_length_longest.png)
- [Longest Contig vs Total Length, filtered genomes](Agrobacterium_pusense_filt_total_length_longest.png)
