# A phylogenetic model for understanding the effect of-gene duplication on cancer progression

## Abstract

As biotechnology advances rapidly, a tremendous amount of cancer genetic data has become available, providing an unprecedented opportunity for understanding the genetic mechanisms of cancer. To understand the effects of duplications and deletions on cancer progression, two genomes (normal and tumor) were sequenced from each of five stomach cancer patients in different stages (I, II, III and IV). We developed a phylogenetic model for analyzing stomach cancer data. The model assumes that duplication and deletion occur in accordance with a continuous time Markov Chain along the branches of a phylogenetic tree attached with five extended branches leading to the tumor genomes. Moreover, coalescence times of the phylogenetic tree follow a coalescence process. The simulation study suggests that the maximum likelihood approach can accurately estimate parameters in the phylogenetic model. The phylogenetic model was applied to the stomach cancer data. We found that the expected number of changes (duplication and deletion) per gene for the tumor genomes is significantly higher than that for the normal genomes. The goodness-of-fit test suggests that the phylogenetic model with constant duplication and deletion rates can adequately fit the duplication data for the normal genomes. The analysis found nine duplicated genes that are significantly associated with stomach cancer.

**Cite us:** Ma Q, Reeves JH, Liberles DA, Yu L, Chang Z, Zhao J, Cui J, Xu Y, Liu L. A phylogenetic model for understanding the effect of gene duplication on cancer progression. *Nucleic Acids Res.* 2014 Mar;42(5):2870-8. doi: 10.1093/nar/gkt1320.

This program implements the Bayesian phylogenetic model for gene duplication and deletion.

## Environment 
Mac OS system is recommanded. An executable file is also included for windows users.(Tested 5/9/2019)

# Usage

## For Mac OS system users

Simply put "A-phylogenetic-model-for-understanding-the-effect-of-gene-duplication-on-cancer-progression-master.zip" in any directory.

```
unzip A-phylogenetic-model-for-understanding-the-effect-of-gene-duplication-on-cancer-progression-master.zip && rm unzip A-phylogenetic-model-for-understanding-the-effect-of-gene-duplication-on-cancer-progression-master.zip
```

Enter the folder "A-phylogenetic-model-for-understanding-the-effect-of-gene-duplication-on-cancer-progression-master".

```
cd A-phylogenetic-model-for-understanding-the-effect-of-gene-duplication-on-cancer-progression-master
```

Use 'make' to compile the program.

```
make
```

To run the program, type
```
./cancer control
```
 It will generate an output file .out in which the loglikelihood and model parameter m are sampled from the MCMC algorithm. The posterior distribution of the phylogenetic tree is saved in the output file .tre.

## For windows system users
In the Commmand Prompt
Enter the folder containing the unzipped files.
Then type
```
cancer control
```

## Contact

Any questions, problems, bugs are welcome and should be dumped to
Qin Ma <Qin.Ma@osumc.edu>
