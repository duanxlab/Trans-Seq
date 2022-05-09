# Trans-Seq

![Asset 1](https://user-images.githubusercontent.com/100653680/160716813-4c17eaba-45c3-4289-9937-1e4bbb36cd05.png)


Trans-Seq is a circuit mapping method that allows for transcriptomically profiling of postsynaptically connected neurons. Trans-Seq combines a fluorescent anterograde transsynaptic tracer, consisting of codon-optimized wheat germ agglutinin  fused  to  mCherry,  with  single-cell  RNA  Sequencing. Connected neurons are recovered via FACS based on mCherry fluorescence. In our study, we  used  Trans-Seq  to  classify neuron types in the superior colliculus innervated by genetically-defined RGC types and predicted a neuronal pair from αRGCs to Nephronectin-positive wide-field neurons (NPWFs). 

This page contains R code and processed data for further data exploration. 

Processed scRNA-Seq superior colliculus data as a Seurat object is available to download [here](https://ucsf.box.com/shared/static/txsu83ydsuxfpbvf8ns9d5x65kq0zl61.rdata).

Processed scRNA-Seq superior colliculus data for excitatory neurons recovered by RGC-Cre line specific tracing is available to download [here](https://ucsf.box.com/shared/static/m3ltqfiofak9ayuj7bb1sbw5eay0qgxq.rdata).


Code for data integration using Seurat is contained within `SC_Combine_PanRGC.Rmd`


Please direct any questions or requests to xin.duan@ucsf.edu.
