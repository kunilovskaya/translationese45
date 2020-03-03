## Translationese feature extraction for English, German and Russian

Python3 code to extract 45 translationese indicators for English, German and Russian. 
Most of them were used in the research presented at LREC 2020

Related publication:
- *Kunilovskaya, Maria & Ekaterina Lapshinova-Koltunski (2020). Lexicogrammatic translationese across two targets and competence levels. 
LREC-2020, Marseille, May 11-15, 2020.*
(link and bib to be added)

The detailed description of the features is provided in *lrec20_45featureset_description.pdf*.

To reproduce the extraction of frequencies for the 45 translationese features for the three languages, 
clone the repository to your user's home directory (/home/username/) and unpack the data in the preprocessed folder. 
Change the username in rootdir option in the mega_collector.py and in lists_path in helpfunctions.py module. By default the output (out.tsv) is created in the same folder as the input data.
The archives contain trees of folders for each language pair, including professional and student translations 
with their sources as well as the non-translated reference texts used. The folder names are used as class labels by the script.
Each file contains a preprocessed and UD parsed text in the *.conllu format from the respective subcorpus.

Install the necessary dependencies, specifically python igraph-python 0.7.4 library required to extract mean hierarchical distance.





