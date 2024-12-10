# CS582_finalProject_group

## DNA Chisel PART
(REF: https://edinburgh-genome-foundry.github.io/DnaChisel/)  

### what is DNA Chisel?  
    DNA Chisel (complete documentation here) is a Python library for optimizing DNA sequences with respect to a set of constraints and optimization objectives. It can also be used via a command-line interface, or a web application.

    The library comes with over 15 classes of sequence specifications which can be composed to, for instance, codon-optimize genes, meet the constraints of a commercial DNA provider, avoid homologies between sequences, tune GC content, or all of this at once! Users can also define their own specifications using Python, making the library suitable for a large range of automated sequence design applications, and complex custom design projects.


### How to use?
check the website

### Problem
In gene design and optimization, precise DNA sequence generation is critical,  particularly when meeting specific biological constraints and optimization goals. One of the useful tools is called DNA Chisel, which is a Python package for optimizing DNA sequences concerning a set of constraints and optimization objectives (Zulkower & Rosser, 2020). However, this optimization approach may disrupt essential biological motifs or regulatory elements, leading to unintended functional consequences. 


## DNABERT(2)
(REF: https://github.com/jerryji1993/DNABERT  
      https://github.com/MAGICS-LAB/DNABERT_2)

DNABERT is a transformer-based model for DNA, which can identify crucial motifs and regulatory elements that must be preserved (Ji et al., 2021).
And DNABERT2 is the latest version of DNABERT via BPE encoding method.

We hope to use DNABERT2 to detect some region that need to avoid editing.


## File 

### testing1.ipynb
    please only read/use the DNABERT Promoter Detection fine-tune part. For this part, we add a simple network over the output layer of DNABERT2 and freeze all the parameters in DNABERT2.
### BERT-GPT2-fine-tuned.ipynb
    Please refer this code for the implementation of naive BERT and GPT2 for Promoter Detection.
    
