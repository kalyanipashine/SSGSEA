SSGSEA
Single-sample GSEA (ssGSEA), an extension of Gene Set Enrichment Analysis (GSEA), 
calculates separate enrichment scores for each pairing of a sample and gene set.
Each ssGSEA enrichment score represents the degree to which the genes in a particular gene 
set are coordinately up- or down-regulated within a sample.

Dataset : 
previous DEG file was converted into log values matrix file which we used.

Interpretation:
The score derived from ssGSEA reflects the degree to which the input gene signature is coordinately up- or downregulated within a sample.

HeatMap:

![image](https://user-images.githubusercontent.com/112052476/199164851-8ba4511a-abcf-40cf-8bf7-ed6f6e6bf3bf.png)

The heatmap shows 0 to 2 up-regulated genes(in orange color) and 0 to -2 down-regulated genes(in green color)
