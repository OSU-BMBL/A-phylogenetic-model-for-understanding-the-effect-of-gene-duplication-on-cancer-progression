## Usage

#### Introduction
This program implements the Bayesian phylogenetic model for gene duplication and deletion.

#### Environment 
OS system is recommanded. An executable file is also included for windows users.

#### Installation and usage

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

#### For windows system users
In the Commmand Prompt
Enter the folder containing the unzipped files.
Then type
```
cancer control
```

#### Contact

Any questions, problems, bugs are welcome and should be dumped to
Qin Ma <Qin.Ma@osumc.edu>
