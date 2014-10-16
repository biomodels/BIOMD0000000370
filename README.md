# BIOMD0000000370: Vinod2011_MitoticExit

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000370.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000370.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000370 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Computational modelling of mitotic exit in budding yeast: the role of separase and Cdc14 endocycles**   
Vinod PK, Freire P, Rattani A, Ciliberto A, Uhlmann F, Novak B. _J R Soc
Interface._ 2011 Aug 7;8(61):1128-41. Epub 2011 Feb 2.
[21288956](http://www.ncbi.nlm.nih.gov/pubmed/21288956) ,  
**Abstract:**   
The operating principles of complex regulatory networks are best understood
with the help of mathematical modelling rather than by intuitive reasoning.
Hereby, we study the dynamics of the mitotic exit (ME) control system in
budding yeast by further developing the Queralt's model. A comprehensive
systems view of the network regulating ME is provided based on classical
experiments in the literature. In this picture, Cdc20-APC is a critical node
controlling both cyclin (Clb2 and Clb5) and phosphatase (Cdc14) branches of
the regulatory network. On the basis of experimental situations ranging from
single to quintuple mutants, the kinetic parameters of the network are
estimated. Numerical analysis of the model quantifies the dependence of ME
control on the proteolytic and non-proteolytic functions of separase. We show
that the requirement of the non-proteolytic function of separase for ME
depends on cyclin-dependent kinase activity. The model is also used for the
systematic analysis of the recently discovered Cdc14 endocycles. The
significance of Cdc14 endocycles in eukaryotic cell cycle control is discussed
as well.

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


