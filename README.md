# LocalBBH
My PhD project on study the prospects on detecting binary black holes dynamically formed in globular clusters with space-borne gravitational wave detectors


[Temporary slide show host](http://vpn.domij.info/), rendered by [reveal.js](http://revealjs.com/)

* TOC
	* [Current Updates](#Current)
	* [Extra Projects and Interest](#Extra)
	* [Resume for NLP/Data Science - 03/24/2018 cache](https://www.dropbox.com/s/jjgqut6rgm7md0e/resume2018.pdf?dl=0)


## [Opening Notes]


[Notes]


During my PhD study, I've been questioning about, what is re-search.

It seems to me that research is about 

* looking at something, 
* over and over, 
* in all possible angels.

During these iterations, we may

* narrow assumptions,
* apply different methods,
* collect more data,
* and learn new knowledge.


* Reproducibility => why I present in this transparent way
* so it is informative about what I conclude and how I deliver

-------

Over the past years, I studied about

* Globular Clusters, these are
    * stellar systems that consist of millions of stars, they are also
    * ancient building blocks of galaxies themselves. 

They are extremely interesting environments, in a sense that,

* the timescale of stellar evolution, becomes comparable to 
* the timescale to have stellar encounters.

That is, the stars in these dense star clusters don't die alone,

* they will influence the nearby-stars over dynamical interactions,
* their own stellar evolutions are also altered during such processes.

In a nutshell, 

* smaller systems like open clusters cannot stay gravitationally-binded
    * stars are easily scattered away and they will evaporate before long
    * there are also enough materials to power multiple generation of star formations
* larger systems like galaxies instead, have strong gravitational potentials
    * most of the stars are trapped and move under a quasi-static field
    * the system could be described as statistical equilibrium,

Starting from that, I learned about 

* the larger structure in the local universe and 
* built up the concept of the cosmic web

I will expand on that by populating globular clusters in the local universe, which is the second chapter in my dissertation. 

-----

Then I had this chance to study about numerical simulations.

* I spent the 2013 summer in National Astronomical Observatories, Chinese Academy of Science to study about N-body models with [Rainer Spurzem](http://kiaa.pku.edu.cn/faculty/rainer-spurzem), using Newtonian integrator to solve dynamical interactions.
* I also [met with Jonathon Downing and] picked up the Monte Carlo code from [Mirek Giersz](https://www.camk.edu.pl/en/people/staff/mig/) to evaluate the phase-space evolution in a semi-equilibrium system. 

Both approaches provide great details about stellar dynamics based on theoretical assumptions.

* From the formation mechanism of compact binary systems,
* to the observable global effects of the star clusters, 
different physics and phenomenons are implemented in various scale. 

The adaption of 

* these numerical methods, 
* in together with high performance computing techniques, 
push forward the research greatly so that theoretical prospects become 
* essential to new proposed instrumental projects,
* instructional to reveal discoveries buried in observed data.

I reviewed such aspects in the history of GC studies in chapter 3 and introduced my own simulations to represent the natural assembling of GCs in chapter 4.

* The major effects considered in GCs and 
* the detailed modeling 
are discussed in my dissertation in corresponding sections. I will only briefly demonstrate the key components later. 

-----

From those simulations, I could extract any interesting stellar object with its full dynamical history, especially the compact binary systems that could be potentially the gravitational wave sources in different frequency domain. 

* I spent 2015 summer at Kavli Institute of Astrophysics and Astronomy in Peking University doing data analysis by querying observational databases for variable sources, 
* I visited National Astronomical Observatories, Chinese Academy of Science again to prototype a transient object detection pipeline for 50cm Binocular Network with [Licai Deng](http://sourcedb.naoc.cas.cn/en/enaoexpert/200907/t20090706_2000374.html) and [Richard de Grijs](http://kiaa.pku.edu.cn/faculty/richard-de-grijs).

The mutual benefits supplemented my experience in optical data processing that promoted my understanding on time series data analysis. 

I sketched the work flow to estimate the local abundance of GCs in chapter 2. At the same time, I started to focus on the binary black holes for the resulting GW signals. Matt's code based on Peter's work about general relativity was parallelized to carry out the relativistic evolution for the compact binary systems extracted from GCs. A brief introduction about BBH formation mechanisms and GW astronomy could be found in chapter 5. At the time of the first GW detection, my preliminary result presented on MODEST meeting ruled out GC as the origin of the IMBH merger event. 

-----

In 2016 summer, I started training in the LSST data science program and 

* the systematic coverage of statistical background 
* and conventional data analysis tools 
enhanced my modeling of the GC populations. 

With the super-cluster in Texas Advanced Computing Center, my collection of GC simulations was also enlarged greatly.

* More realizations of the same setup were added to make sure the convergence.
* Finer-grained parameter space was explored to avoid extremity. 
* Selection effect and sampling bias had been made aware as well. 

-----

From all the above, a clear image appeared 

* to derive the detection prospects of BBHs, 
* which are dynamically formed in GCs,
* within 30 Mpc volumetric space
* for space-borne GW detectors


I followed

* the Fixer Informative Matrix analysis from Cutler and 
* configured the BBH database to work with Matt's code

This part of work is included in chapter 6. 


-----

Without further ado, I will walk through the work manuscript-ed in my dissertation in brief and let you question about any part that is particular interesting to your extent.


-----

## <a name="Current"></a>  Ongoing updates

### Publications

1. Co-authored: [The origin of the first neutron star -- neutron star merger](https://arxiv.org/abs/1712.00632)

__In Preparation__

1. Localization of Binary Black Holes in the Local Universe

2. A Data Science Approach Towards the Local Abundance of Globular Clusters

### <a name="NCA"></a> Update localization analysis with Network Coherent Analysis from LIGO - 4/28/2018

1. based on the PhD work from [Dr.
Shihan Weerathunga](https://scholar.google.com/citations?user=qtaTE_oAAAAJ&hl=en)
    1. use PSO optimizer from his PhD advisor [Dr. Soumya D. Mohanty](https://arxiv.org/abs/1506.01526)
    2. need to work on the inverse of ill-conditioned matrix, try [Tikanamov's work]


### Data Management and Release

1. Local Globular Cluster Library

2. Local Binary Black Holes (dynamically formed and ejected from globular clusters) Database



### Collaborations

1. 2013 Summer: Dr. Rainer Spurzem and Dr. Peter Berczik at NAO/CAS 
    * N-body6++ and HPC techniques
    * Simulation on superclusters

2. [2015 Summer](http://kiaa.pku.edu.cn/visitor/dongming-jin): Dr. Licai Deng at NAO/CAS, and Dr. Richard de Grijs at KIAA/Peking University
    * photometry data process pipeline
    * time series data analysis
    * data management and release

3. [MOCCA](https://moccacode.net/): Dr. Mirek Giersz
    * Monte Carlo simulations

4. LOFASM: Dr. Teviet Creighton
    * coherence analysis for radio spectrum

5. Network Coherence Analysis: 
    * Network Coherent Analysis on the Local Binary Black Holes, see [Network Coherrent Analysis](#NCA)



## <a name="Extra"></a> Extra Projects and Interests


### Involvement 

1. LSSTC Data Science Fellowship Program [LSSTC DSFP](http://ciera.northwestern.edu/Education/LSSTC_Students.php)

2. International Conference on Data Intelligence and Security [ICDIS 2018](https://www.icdis.org/)

3. Rockets & Rigs [R&R](http://rocketsandrigs.org/)

<!-- 4. Consulting Board on startup -->



### Interests - 4/30/2018 Cache

1. Quantum Computing, @ [IBM](https://www.research.ibm.com/ibm-q/)

2. Human Genomics sequencing and analysis @ [Human Longevity, INC.](https://www.humanlongevity.com/)

3. Dietary Health and Ingestion Study,  @ [Viome](https://viome.com/)

4. Future Transportations and City Planning, @ [Boring Company](https://www.boringcompany.com/)

5. Security and Privacy, @ [Cloudflare](https://www.cloudflare.com/)

6. various, @ [Google X](https://x.company/)



... To be added



### Side projects

... To be organized and added










