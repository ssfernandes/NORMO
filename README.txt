NORMO

SOURCE
NORMO: a new heuristic for estimating the number of components in CP tensor decomposition
Sofia Fernandes, Hadi Fanaee-T and João Gama

DESCRIPTION

MATLAB implementation of NORMO, a new method for estimating the number of components in CP tensor decomposition   

This implementation assumes that the tensor is 3 dimensional (but adaptations to other dimensions may be made 
available upon request).

FILES
For illustration purposes we provide a demo file (demo.m) in which we apply our method - NORMO - to one of the
synthetic datasets.

MANUSCRIPT DATASETS
Besisdes the generated synthetic datasets, we also considered the following publicly available datasets:
Amino acids fluorescence:
	Bro, R, PARAFAC: Tutorial and applications, Chemometrics and Intelligent Laboratory Systems, 
	1997, 38, 149-171

	URL: http://www.models.life.ku.dk/Amino_Acid_fluo

dorrit:
	J. Riu, R. Bro, Jack-knife technique for outlier detection and estimation of
	standard errors in parafac models, Chemometrics and Intelligent Laboratory Systems 65 (1)
	(2003) 35-49.

	URL: http://www.models.life.ku.dk/dorrit
wbnmr:
	M. Dyrby, M. Petersen, A. K. Whittaker, L. Lambert, L. Nrgaard, R. Bro,
	S. B. Engelsen, Analysis of lipoproteins using 2d diusion-edited nmr spectroscopy
	and multi-way chemometrics, Analytica Chimica Acta 531 (2)
	(2005) 209-216.

	URL: http://www.models.life.ku.dk/dosylipo

Sugar production: 
	R. Bro, Exploratory study of sugar production using fluorescence spectroscopy
	and multi-way analysis, Chemometrics and Intelligent Laboratory
	Systems 46 (2) (1999) 133-147.

	URL: http://www.models.life.ku.dk/Sugar_Process

Tongue shapes:
	R. Harshman, P. Ladefoged, L. Goldstein, Factor analysis of tongue shapes,
	The Journal of the Acoustical Society of America 62 (3) (1977) 693-707.

	URL: http://www.models.life.ku.dk/tongue

Enron: 
	Priebe, C.E., Conroy, J.M., Marchette, D.J., Park, Y.: Scan statistics on enron graphs.
	Computational & Mathematical Organization Theory 11(3), 229-247 (2005) 

	URL: http://cis.jhu.edu/~parky/Enron/

Friends&Family Call log:
	Aharony, N., Pan, W., Ip, C., Khayal, I., Pentland, A.: Social fMRI: Investigating and
	shaping social mechanisms in the real world. Pervasive and Mobile Computing 7(6), 643-
	659 (2011) 

	URL: http://realitycommons.media.mit.edu/friendsdataset.html

DBLP: 
	Desmier, E., Plantevit, M., Robardet, C., Boulicaut, J.F.: Cohesive co-evolution patterns
	in dynamic attributed graphs. In: Discovery Science, vol. 7569, pp. 110-124. Springer
	(2012)

	URL: http://liris.cnrs.fr/marc.plantevit/doku/doku.php?id=data_sets

Challenge  network:
	S. Rayana, L. Akoglu, An ensemble approach for event detection and characterization in 
	dynamic graphs, in: Proceedings of the 2nd ACM SIGKDD Workshop on Outlier Detection & 
	Description under Data Diversity (ODD), 2014.	

	URL: http://odds.cs.stonybrook.edu/challengenetwork-dataset/

Reality Mining Bluetooth proximity log:
	N. Eagle, A. S. Pentland, Reality mining: sensing complex social systems, Personal and 
	ubiquitous computing 10 (4) (2006) 255-268

	URL: http://realitycommons.media.mit.edu/realitymining.html

	
DEPENDECIES
Our code makes use of the n-way matlab toolbox, which is available at: 
	http://www.models.life.ku.dk/nwaytoolbox/download

CONTACT
To report any bug, comment or suggestion, contact me at sdsf@inesctec.pt.