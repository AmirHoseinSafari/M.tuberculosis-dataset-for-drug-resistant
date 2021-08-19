# M.tuberculosis dataset for drug resistant

The SNP and gene datasets of M. Tuberculosis for drug resistance prediction.
Here is a brief description of each file:

- `AllLabels.csv` contains the susceptibility/resistance status (susceptibility:0 and resistance:1) for each sample isolate to 12 different drugs.
- `SNPList.csv` contains the list of all loci on the MTB genome where a mutation was detected using the variant calling tools, based on the reference genome provided [here](https://github.com/Sadegh-Saberian/LRCN-drug-resistance/blob/master/Data/EPFL_Data/Mycobacterium_tuberculosis_H37Rv_allGenes.csv).
- `SNP_data_part*.zip` contains csv files with the binary SNPs. The csv files are concatenated using **loading_data** package (refer to this [repo].(https://github.com/Sadegh-Saberian/LRCN-drug-resistance))
- `gene_data.csv.zip` contians a csv file that summarizes the SNPs based on the gene that they fall into to form a matrix that contains a single feature for each gene of each sample isolate.
- `iso_list.csv` a list of all isolates IDs used in the training data.
- `sparsetableFeb27.npz` The binary SNP file in npz format for ease of use.

For understanding how to load and use this data please visit the [LRCN-drug-resistance](https://github.com/AmirHoseinSafari/LRCN-drug-resistance#loading_data-package) repository, especially the loading_data section.

--- 

## Citation
If you found the content of this repository useful, please cite us:

https://www.biorxiv.org/content/10.1101/2020.11.07.372136v1?rss=1

---
