# Optimizing-Dataframes-and-Processing-in-Chunks

This project uses a dataset of loans approved between 2007-2011 from Lending Club, a marketplace for personal loans that 
matches borrowers with investors. This dataset can be found here: https://www.lendingclub.com/info/download-data.action

The setup is that we want to use Pandas on a medium-sized dataset but we have very limit memory. The goal is to reduce
our memory footprint using chunk processing, as well using optimisations such as converting column dtypes to those that will
consume the least amount of memory.
