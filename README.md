# MODEL1201140001: Keener2001_OscillatoryInsulinSecretionModel

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1201140001.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1201140001.git@20140916`

## Usage

Importing the model package.

`import MODEL1201140001 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Diffusion induced oscillatory insulin secretion.**   
Keener JP. _Bull Math Biol._ 2001 Jul;63(4):625-41.
[11497161](http://www.ncbi.nlm.nih.gov/pubmed/11497161) ,  
**Abstract:**   
Oscillatory secretion of insulin has been observed in many different
experimental preparations. Here we examine a mathematical model for in vitro
insulin secretion from pancreatic beta cells in a flow-through reactor. The
analysis shows that oscillations result because of an important interplay
between flow rate of the reactor and insulin diffusion. In particular, if the
ratio of flow rate to volume of the reaction bed is too large, oscillations
are eliminated, in contradiction to the conclusions of Maki and Keizer (L. W.
Maki and Keizer J. Mathematical analysis of a proposed mechanism for
oscillatory insulin secretion in perifused HIT-15 cells. Bull. Math. Biol.,
57(1995), 569-591). Furthermore, with reasonable numbers for the experimental
parameters and the diffusion of insulin, the model equations do not exhibit
oscillations.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Keener (2001)**
](http://models.cellml.org/exposure/7f1817ef2f2d9365518e25f112a89ed7)  
The original CellML model was created by:  
**Catherine Lloyd**   
c.lloyd@aukland.ac.nz  
The University of Auckland  
The Bioengineering Institute  

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


