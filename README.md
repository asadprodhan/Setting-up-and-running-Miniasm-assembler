# **Setting up and running Miniasm assembler** <br />


Miniasm assembler can be set up and run by using the Pomoxis package. Pomoxis is a bioinformatics tool designed for processing the nanopore sequencing data.


## **Some relevant FAQs**


**Q: How to check if the assembler is already installed in my computer?**


A: Run the executable. If it shows various flags or options, then it is already installed.


**Q: Where is it located or installed in the computer/ What is the path of the assembler’s executable?**


A: Run the following command. If it is installed in your computer, it will show the path.


```
whereis the-name-of-the-executable
```


**Q: Has the executable path been added to the PATH environment variable?**


A: Run the following command and check if the executable path is there.


```
$PATH
```


**Q: Why do you need to add the executable path to the PATH environment variable?**


A: You can run the executable in your terminal without having to specifying its path every time.


**Q: How do you add the executable path to the PATH environment variable?**


A: Run the following command. See https://github.com/asadprodhan/About-the-PATH 


```
export PATH=$PATH:the-path-of-the-executable
```


**Q: How do you install pomoxis?**


A: You can install pomoxis using conda. This will also install all the required binaries (i.e. softwares).


```
conda install -c bioconda pomoxis
```


**Q: Pomoxis usage command?**


A: Run the following command. It will show all the usage options or flags.


```
mini_assemble
```


**Q: What will be an example of the pomoxis usage command?**


```
mini_assemble -i sample.fastq -r reference.fasta -o results -p prefix_output_file -t 18 
```


**The final assembly will be written to results/test_final.fa**



