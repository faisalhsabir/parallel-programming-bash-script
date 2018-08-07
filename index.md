# Command

head -n10000 10K_file_names.txt | parallel -j 4 "python3 testing.py $File"

### -n10000:
pick 10k files from 10_file_names.txt

### -j 4
run on 4 cores.

### python3 testing.py $File
run testing.py on each file.
