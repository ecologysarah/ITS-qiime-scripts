This is a set of scripts to analyse ITS metabarcoding data using QIIME2. It starts with raw FASTQs on a remote server and goes through to ASVs with assigned taxonomy and basic QIIME plots. It uses fastp for quality trimming and fastQC and multiqc for quality assessment. The remaining steps are done in QIIME, using DADA2 for denoising. Taxonomy is assigned using a classifer trained on the UNITE database v9.
These scripts were designed to be run on Cardiff School of Biosciences' server iago, which uses a slurm job scheduler and modules for loading software. 
Sarah Christofides, March 2024
