### The activity of the mammalian DNA transposon piggyBat from Myotis lucifugus is restricted by its own transposon ends
*Alison B. Hickman, Laurie Lannes, Christopher M. Furman, Christina Hong, Lidiya Franklin, Rodolfo Ghirlando, Arpita Ghosh, Wentian Luo, Parthena Konstantinidou, Hernan Lorenzi, Anne Grove, Astrid Haase, Matthew H. Wilson and Fred Dyda*

To process fastq files run `process_forward_reads.sh`.
```
# It is expected that fastq file names have the following format: ${SAMPLE_NAME}.R1.fastq.gz within the subdirectory raw_fastq
# It is also necessary to set the variable ${BOWTIE_GENOME_REF_INDEX} in the process_forward_reads with the path to the bowtie2 index for the reference genome.
bash process_forward_reads.sh ${SAMPLE_NAME}
```

