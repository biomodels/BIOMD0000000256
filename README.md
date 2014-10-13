

This is the _standard_ model described in the article:  
**Systems analysis of effector caspase activation and its control by X-linked inhibitor of apoptosis protein.**   
Rehm M, Huber HJ, Dussmann H, Prehn JH. _EMBO J._ 2006 Sep 20;25(18):4338-49.
Epub 2006 Aug 24. PMID:
[16932741](http://www.ncbi.nlm.nih.gov/pubmed/16932741) , doi:
[10.1038/sj.emboj.7601295](http://dx.doi.org/10.1038/sj.emboj.7601295) ;  
**Abstract:**   
Activation of effector caspases is a final step during apoptosis. Single-cell
imaging studies have demonstrated that this process may occur as a rapid, all-
or-none response, triggering a complete substrate cleavage within 15 min.
Based on biochemical data from HeLa cells, we have developed a computational
model of apoptosome-dependent caspase activation that was sufficient to
remodel the rapid kinetics of effector caspase activation observed in vivo.
Sensitivity analyses predicted a critical role for caspase-3-dependent
feedback signalling and the X-linked-inhibitor-of-apoptosis-protein (XIAP),
but a less prominent role for the XIAP antagonist Smac. Single-cell
experiments employing a caspase fluorescence resonance energy transfer
substrate verified these model predictions qualitatively and quantitatively.
XIAP was predicted to control this all-or-none response, with concentrations
as high as 0.15 microM enabling, but concentrations >0.30 microM significantly
blocking substrate cleavage. Overexpression of XIAP within these threshold
concentrations produced cells showing slow effector caspase activation and
submaximal substrate cleavage. Our study supports the hypothesis that high
levels of XIAP control caspase activation and substrate cleavage, and may
promote apoptosis resistance and sublethal caspase activation in vivo.

This model is slightly altered from the description in the article. Cytochrome
C and SMAC release from the mitochondrion is modelled as simple first order
kinetics, giving the same form as the (integrated) equations in the supplement
of the article. The apoptosome formation is modelled equally - and independent
of the Cytochrome C release. The speed is either limited by the Apaf1 or
ProCaspase9 concentration, whichever is higher, symbolised via the parameter
with the ID _apolim_ .  
Also, once the substrate concentration falls below 1 percent, the event
_Production_Breakdown_ is triggered, leading to a breakdown of XIAP and
procaspase3 production and turning off of the enhanced/proteosomal degradation
(degradation rate for reactions 38,39,40,43,44,46,48,50,51 changes from 0.0347
to 0.0058).

Originally created by libAntimony v1.3 (using libSBML 3.4.1)

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2012 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

