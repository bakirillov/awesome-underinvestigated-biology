# awesome-underinvestigated-biology

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Topics in biology that are not researched as much as they should be. Initial offering is made by the participants of Russian-speaking Biology-related telegram chat Лапкочат GANG.  
Disclaimer: the descriptions are not meant to be comprehensive, I just wanted to provide a starting point for the search.

## Contents

- [Bioinformatics](#bioinformatics)
- [Omics](#omics)
- [Biochemistry](#biochemistry)
- [Prokaryote biology](#prokaryote-biology)
- [Eukaryote biology](#eukaryote-biology)
- [Virology](#virology)
- [Medicine](#medicine)
- [3D bioprinting](#3d-bioprinting)

[Other resources](#other-resources)

### Bioinformatics

[Bioinformatics-aware Neural Network Interpretation](https://www.sciencedirect.com/science/article/pii/S1051200417302385) - it would be very interesting to get pieces of evidence for and against a biological hypothesis from a trained neural network. There are some methods to interpret NNs but most of them are concerned only with vision tasks. Most works here provide LOGO sequences like [DeepMotif](https://arxiv.org/abs/1605.01133) (look for pytorch implementation [here](https://github.com/bakirillov/deepmotif4pytorch)) but something more understandable would be good to have.

[Prediction of response to psychopharma](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5990649/citedby/) - there is some research but pretty recent and not much.     

[Proper visualization of long DNA sequences](http://mate.tue.nl/mate/pdfs/5346.pdf) - it would be nice to have an understandable visualization of long DNA sequences. Some good attempts are available [in this library](https://github.com/Lab41/squiggle).     

[RNN instead of HMMs](https://stats.stackexchange.com/questions/282987/hidden-markov-model-vs-recurrent-neural-network) - there are many applications of [HMMs](https://en.wikipedia.org/wiki/Hidden_Markov_model) in Bioinformatics (classic example is [multiple sequence alignment](https://www.ncbi.nlm.nih.gov/pubmed/20147223)) but [RNNs](https://en.wikipedia.org/wiki/Recurrent_neural_network) have pretty much the same properties while being way stronger as sequence modellers. Don't see much of RNN application in lieu of HMMs in Bioinf though. Maybe [Transformers](https://towardsdatascience.com/the-fall-of-rnn-lstm-2d1594c74ce0) would be helpful as well?     

### Omics

[Functions of genes](https://research.a-star.edu.sg/articles/highlights/a-decline-in-gene-discoveries/) - from about 20k of known human genes we somewhat know a function of about 5k (update: [10k](https://reactome.org/about/news/73-reactome-celebrates-release-of-10-000th-annotated-protein)). Imagine the situation for other species.

[Metagenomics of clouds](https://www.researchgate.net/publication/262932901_Metagenomics_of_Clouds_and_Atmosphere) - metagenomics is a fast growing approach in modern biology. Investigation of microbial community of atmosphere (for example clouds) is very interesting and not fully understood field of microbiology.

### Biochemistry

[Oxygen-resistant nitrogenases](https://www.researchgate.net/post/How_can_we_engineer_nitrogenases_to_be_oxygen-tolerant) anyone? There could be a very promising application in industry since [the current way of nitrogen fixation](https://en.wikipedia.org/wiki/Haber_process) is quite compicated. There was [a paper twenty years ago](https://jb.asm.org/content/174/21/6840.short) with claims of finding such nitrogenase but [current results](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4735515/) contradict it.

### Prokaryote biology

[Light detection in bacteria](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5812497/) - how does it work? 

### Eukaryote biology

[Larvamima](https://scholar.google.com.ua/scholar?cites=7346071014699236931&as_sdt=2005&sciodt=0,5&hl=ru) - ant parasytes that mimic the larvae. After the discovery about 30 years ago only twelve mentions in reviews.

[Mimicry in plants](https://en.wikipedia.org/wiki/Mimicry_in_plants) - quite self-explanatory. There are a number of examples ([rice and Echinochloa crus-galli](https://www.nature.com/articles/s41559-019-0976-1), [fallen leaves and Monotropsis oderata](https://en.wikipedia.org/wiki/Monotropsis)) but it still remains pretty unclear.

[Myrmecophilidae](https://en.wikipedia.org/wiki/Ant_cricket) - live almost everywhere where ants do, [no assembled genomes](https://www.ncbi.nlm.nih.gov/search/all/?term=myrmecophilidae), no research on their ecology and molecular biology.

### Virology

[Archaeal virii](https://www.nature.com/articles/nrmicro1527) - morphology differences from bacteriophages and eukaryote virii. Are there any archaeal virii with hybrid RNA-DNA genome?  

[Fungal virii](https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1005172) - Why they are so often non-pathogenic for their hosts?

### Medicine

[Streptococcus mutans vaccine](https://en.wikipedia.org/wiki/Streptococcus_mutans) - how to evict the stuff that eats your teeth. There is some [research](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3708248/citedby/) but no known solution yet.

### 3D bioprinting

[Reproducibility of directed collagen strand growth](https://www.ncbi.nlm.nih.gov/pubmed/30830351) - it is hard to grow collagen strands with directed linear growth (usually they tend to grow chaotically). Different papers offer different solutions and different results even for similar experiment conditions.

## Other resources

[Original list](https://matthewmcateer.me/blog/under-investigated-fields/) - includes many fields (Math, Physics etc). 

[Open questions: CRISPR biology](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-018-0565-9) - review of open questions in CRISPR by Eugene Koonin     

[Wiki list of unsolved problems in biology](https://en.wikipedia.org/wiki/List_of_unsolved_problems_in_biology) - note that unsolved doesn't imply under-investigated.

[Not yet awesome Rust](https://github.com/not-yet-awesome-rust/not-yet-awesome-rust) - list similar to the current one only about Rust language ecosystem.

[Blog post on under-investigated topics in ecology](https://dynamicecology.wordpress.com/2016/05/09/what-are-the-biggest-understudied-questions-in-ecology/) - on non-stationarity and related stuff.

[Talk on challenges in Synthetic Biology](https://www.ibiology.org/bioengineering/challenges-in-synthetic-biology/) - mostly technical like standardisation, not conceptual ones.

[Fresh review of Deep Learning in Biomed](https://greenelab.github.io/deep-review/) - with focus on obstacles, rather good.

[OpenAI requests for research](https://openai.com/blog/requests-for-research-2/) - a list of requests to research in machine learning by OpenAI.
