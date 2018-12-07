i ran the following command:

```
--r1_in
/Users/thomasvangurp/epiGBS/epiGBS_jmounger/R1_IOSField_plate3_headtaillines.fastq.gz
--r2_in
/Users/thomasvangurp/epiGBS/epiGBS_jmounger/R2_IOSField_plate3_headtaillines.fastq.gz
--mode
pe
-b
/Users/thomasvangurp/epiGBS/epiGBS_jmounger/barcodes_IOS_3.txt
--output-dir
/Users/thomasvangurp/epiGBS/epiGBS_jmounger/output_demultiplex
--addRG
-d
--control-nt
--nomatch1
/Users/thomasvangurp/epiGBS/epiGBS_jmounger/output_demultiplex/nomatch.r1.fq.gz
--nomatch2
/Users/thomasvangurp/epiGBS/epiGBS_jmounger/output_demultiplex/nomatch.r2.fq.gz
```
