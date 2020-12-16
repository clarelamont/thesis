# downloaded FASTQC - A Java based program that performs a range of QC tests onFASTQ sequence data.
# from link provided, unzip the file
# This needs java to run, can be installed via following command -
# sudo apt install default-jre 

# change permissions on fastqc -
# chmod u+x fastq

# add FastQC to you path so that it is permanently added & always excecutable
# nano .bashrc
	# # add local installation of fastqc to PATH
	# PATH="$PATH:/home/ag/sw/FastQC

# fastqc_files.py

# the fastqc_files.py sets up an output directory
# reads in the test_dataset FASTQ files
# for each sequecnce in the files it runs fastqc
# the outputs are put into html & zip files

# to run
# > python fastqc_file.py 

# installing trimmomattic
# conda install -c bioconda trimmomatic

# trimmomatic_script.py is commented to explain the code

# to run trimmomatic
# python trimmomatic_script.py


