
# Mac-Theobio Lab Meetings

- Tuesdays, 11:30AM (Toronto time)
- LSB-216 or [Google hangout](http://tinyurl.com/theobio-lab-meeting)

## Current Meeting (Feb 14)

- agenda item 1: What is the plan for Feb 28?
- Informal/long reports


## Upcoming Meetings

### Feb 21

- Learn the basics of PCoA. Can anyone suggest a reading?
    - This isn't a full solution: it doesn't help with the inference/why we would do one or the other, but it does explain the geometry pretty nicely ... [PCA and PCoA explained](http://occamstypewriter.org/boboh/2012/01/17/pca_and_pcoa_explained/), from Bob Carpenter
	- Mike suggests we cover all the variants: (PCA, PCoA, CPC (common principal components), Factor analysis, CVA (canonical variate analysis), Non-negative matrix factorization) (the [CANOCO](http://www.canoco5.com/index.php/canoco5-overview) web page lists: DCA, CA, CCA, DCCA, PCA, and RDA ...)
	- There's also [NMDS](https://jonlefcheck.net/2012/10/24/nmds-tutorial-in-r/), which is very popular among microbiome people. (JCSz) That link says something I don't understand about NMDS: 
		- "NMDS requires a distance matrix, or a matrix of dissimilarities. Raw Euclidean distances are not ideal for this purpose: they’re sensitive to total abundances, so may treat sites with a similar number of species as more similar, even though the identities of the species are different." This shouldn't be true, should it? If each species gets its own axis...
	- [GUSTA ME](https://sites.google.com/site/mb3gustame/constrained-analyses/rda) has an overview of a number of techniques.
- BB proposed inviting Steve Walking to talk to us if he has time.

### Feb 28

- topic/paper needed

## Meeting Topics

- Estimating scale of effects
    - q. BMB has had for a long time, re-inspired by Rob Ness's biology seminar 5 Jan 2017
	- cf. abstract p. 169 (PDF page 188) of [ISEC 2016 abstracts](http://depts.washington.edu/uwconf/isec/ISEC2016_ABSRACT_BOOKLET.pdf)
    - cf. Gadenne, H., Cornulier, T., Eraud, C. et al. Popul Ecol (2014) 56: 493. doi:10.1007/s10144-014-0435-4
	- pp. 28-29 of http://www.slideshare.net/bbolker/montpellier-36611460
	
- FDR
	- It might be worth more of us (any of us?) understanding how the various FDR methods work.
	

		
## Proposed Readings

- [A transmission-virulence evolutionary trade-off explains attenuation of HIV-1 in Uganda](https://elifesciences.org/content/5/e20492)

## Short Agenda Items

## Past readings and agenda items

- Feb 7: [Mandal et al., Analysis of Composition of Microbes: A novel method for studying microbial composition](http://www.microbecolhealthdis.net/index.php/mehd/article/view/27663)
	- [The supp is apparently more relevant than the article](http://www.microbecolhealthdis.net/index.php/mehd/rt/suppFiles/27663/0)

- Jan 24:  [Phillips et al., _JID_, 2016: Identifying Key Drivers of the Impact of an HIV Cure Intervention in Sub-Saharan Africa](http://jid.oxfordjournals.org/content/214/1/73)

- Jan 9: How to construct R-packages [BB's slides](https://github.com/bbolker/compstatsR/blob/master/session4.rmd)

- Nov 14: [Probert *et al* (2016): Decision-making for foot-and-mouth disease control: objectives matter.  Epidemics 15: 10-19](http://dx.doi.org/10.1016/j.epidem.2015.11.002)
    - from Katriona Shea's lab: "Results illustrate how control actions change across both the base metric used to measure management success and across the statistic used to rank control actions according to said metric. This work represents a first step towards reconciling the extensive modelling work on disease control problems with frameworks for structured decision making. This work represents a first step towards reconciling the extensive modelling work on disease control problems with frameworks for structured decision making."

- _All Hallows' Eve_ [Retention of Adult Patients on Antiretroviral Therapy in Low- and Middle-Income Countries: Systematic Review and Meta-analysis 2008-2013](https://www.ncbi.nlm.nih.gov/pubmed/25942461)

- Oct 24: [Callahan *et al.* (2016): DADA2: High-resolution sample inference
from Illumina amplicon data](http://www.nature.com/nmeth/journal/v13/n7/full/nmeth.3869.html)
    - JCSz: stuff with McMurdie's name on it can sometimes be sloppy, so I'm interested in people's opinions on this method.
	- So what did you-all think of this one anyway?

- Oct 17: [Wilson *et al* (2016 arxiv):  Good Enough Practices in Scientific Computing](http://arxiv.org/pdf/1609.00037v1.pdf)
- Oct 3: [Trapman *et al* (2016): Inferring R0 in emerging epidemics—the effect of common population structure is small](http://rsif.royalsocietypublishing.org/content/13/121/20160288)
	- [The bus waiting-time paradox and multiplying by 1+C^2](http://science.sciencemag.org/content/304/5671/684.3.full?_ga=1.101519745.1672006810.1453387049)

- Sep 26: [Delva *et al* (2016): Connecting the dots: network data and models in HIV epidemiology.](http://www.ncbi.nlm.nih.gov/pubmed/27314176)
- (22 Sep) [Ye and Sugihara (2016): Information leverage in interconnected ecosystems: Overcoming the curse of dimensionality](http://science.sciencemag.org/content/353/6302/922)
	- for what it's worth these methods are available in an [R package](https://github.com/ha0ye/rEDM) ...
- Sep 15: Skyline plots
	- [Pybus et al Genetics 155: 1429–1437](http://www.genetics.org/content/155/3/1429.short) (Original paper, July 2000) 
	- [Drummond et al 2005doi:10.1093/molbev/msi103](http://mbe.oxfordjournals.org/content/22/5/1185.short) (Cool Bayesian stuff)
