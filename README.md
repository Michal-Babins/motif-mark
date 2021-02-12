# motif-mark

Motif Mark is a code meant to visualize protien motifs around intron-exon regions in a given gene sequence. Motif Mark uses random color generation as a form of marking your motifs. If the color palatte is not to your liking at first, it may be fun to run multiple times until desired aesthetic is reached. 

Motifs must be input by the user in the form of a text file: ```-m motif.txt```


Required packages include: Pycairo.
Pycairo can be installed by running ```conda install -c conda-forge cairo``` or if on local you can run ```pip install cairo```


Once you have the script in your environment, and pycairo intalled, you will need to feed your fasta and motif file from your working directory:

```python motif-mark.py -i ./file.fasta -m ./motif.txt```

Here is the output (reminder that colors are randomly generated and subject to change): 





