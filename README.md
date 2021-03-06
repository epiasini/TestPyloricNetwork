Pyloric Pacemaker 
==================

Boris Marin's implementation of the pyloric pacemaker model of the lobster
somatogastric ganglion system in the neuroConstruct folder, from

Prinz, A. A., Thirumalai, V., & Marder, E. (2003). The functional
consequences of changes in the strength and duration of synaptic
inputs to oscillatory neurons. The Journal of neuroscience : the
official journal of the Society for Neuroscience, 23(3), 943–54.
Retrieved from http://www.ncbi.nlm.nih.gov/pubmed/12574423

See http://www.opensourcebrain.org/projects/pyloricnetwork for more
details.

----------------------------------

Aditya Gilra's implementation of the pyloric pacemaker model of the lobster
somatogastric ganglion system in the neuroConstruct_alt folder:

The 3 cell network is for fig 3d from :
Similar network activity from disparate circuit parameters
Astrid A Prinz, Dirk Bucher & Eve Marder
Nature Neuroscience, 2004.

The cell models and channel mechanisms are from:
Alternative to Hand-Tuning Conductance-Based Models: Construction and Analysis of Databases of Model Neurons
Astrid A. Prinz, Cyrus P. Billimoria, and Eve Marder,
J Neurophysiol 90: 3998–4015, 2003.

The same cell is used as the basis for 3 cells AB_PD, LP and PY with different channel densities,
 connected in the pyloric rhythm generator network specified in Fig 3d of Prinz, Bucher and Marder, 2004 above.
Differences from the original model: Synapses are thresholded rather than graded.
