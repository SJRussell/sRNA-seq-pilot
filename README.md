# sRNA-seq-pilot
2017-01-29
Merge and Trim with BBtools:
Trimming of the adapters using basespace was not straight forward for either library prep kit, however I was able to get the adapters perfectly (at least for the NEXTflex kit) after merging with BBmerge using the command:

$ bash bbmerge.sh in1=sRNAtrim/ECM-Day6_S1_L001_R1_001.fastq in2=sRNAtrim/ECM-Day6_S1_L001_R2_001.fastq out=sRNAtrim/ECM-Day6_merged outadapter=sRNAtrim/NEXT_adapter.txt ihist=sRNAtrim/NEXT_insert_hist.txt
