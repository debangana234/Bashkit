Bioinformatics often involves working with massive sequencing datasets (e.g., FASTQ, BAM, VCF) and requires chaining together dozens of command-line tools. Knowing Bash allows you to:

- Automate analysis pipelines
-  Filter, clean, and transform large datasets on the fly
-  Manage files, permissions, and job scripts in HPC environments
-  Work smoothly on remote servers and cloud platforms via SSH

The tutorial1  (`tutorial1.ipynb`) covers the fundametal concepts:

-  File system navigation (`cd`, `ls`, `pwd`)
-  Permissions & ownership (`chmod`, `chown`)
-  Script creation and execution
-  Finding files and managing users (`find`, `id`, `dscl`)
-  Practical Bash commands relevant to bioinformatics 

## Requirements

- macOS or Linux environment (or WSL on Windows)
- Jupyter Notebook or VS Code

## Coming Next
-  `awk` for data extraction from gene expression files
-  `grep`/`cut` in combination with genome annotations
-  A section on integrating Bash with bioinformatics tools (e.g., `samtools`, `fastqc`, `bedtools`)
