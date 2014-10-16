# MODEL0847712949: Kurata2002_SinoatrialNode

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL0847712949.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL0847712949.git@20140916`

## Usage

Importing the model package.

`import MODEL0847712949 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Dynamical description of sinoatrial node pacemaking: improved mathematical model for primary pacemaker cell.**   
Kurata Y, Hisatome I, Imanishi S, Shibamoto T. _Am J Physiol Heart Circ
Physiol_ 2002 Nov;283(5):H2074-101
[12384487](http://www.ncbi.nlm.nih.gov/pubmed/12384487) ,  
**Abstract:**   
We developed an improved mathematical model for a single primary pacemaker
cell of the rabbit sinoatrial node. Original features of our model include 1)
incorporation of the sustained inward current (I(st)) recently identified in
primary pacemaker cells, 2) reformulation of voltage- and Ca(2+)-dependent
inactivation of the L-type Ca(2+) channel current (I(Ca,L)), 3) new
expressions for activation kinetics of the rapidly activating delayed
rectifier K(+) channel current (I(Kr)), and 4) incorporation of the
subsarcolemmal space as a diffusion barrier for Ca(2+). We compared the
simulated dynamics of our model with those of previous models, as well as with
experimental data, and examined whether the models could accurately simulate
the effects of modulating sarcolemmal ionic currents or intracellular Ca(2+)
dynamics on pacemaker activity. Our model represents significant improvements
over the previous models, because it can 1) simulate whole cell voltage-clamp
data for I(Ca,L), I(Kr), and I(st); 2) reproduce the waveshapes of spontaneous
action potentials and ionic currents during action potential clamp recordings;
and 3) mimic the effects of channel blockers or Ca(2+) buffers on pacemaker
activity more accurately than the previous models.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Kurata Y, Hisatome I, Imanishi S, Shibamoto T.
(2002) - version05** ](http://www.cellml.org/models/kurata_hisatome_imanishi_s
hibamoto_2002_version05)  
The original CellML model was created by:  
**Noble, Penny,**   
penny.noble@dpag.ox.ac.uk  
The University of Oxford  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


