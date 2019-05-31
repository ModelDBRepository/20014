Model program for the paper: 

Sergey M. Korogod, Irina B. Kulagina, and Suzanne Tyc-Dumont

Transfer Properties of Neuronal Dendrites with Tonically Activated Conductances

Neirofiziologiya/Neurophysiology
Vol.30, Nos.4/5, pp.259-264, July-October, 1998
(Kluwer Academic/ Plenum Publishers English version: Neurophysiology 
30(4/5):203-207, 1999)


Running the mosinit.hoc program recreates Figures 2 and 3 of the paper. 
To compute and display a figure click on the corresponding item, e.g. 
"Fig.2. A-D" or "Fig.3. C", of the "Article Results" menu window 
operating similar to "NEURON Main Menu". Then click on "Init & Run" 
in "RunControl" window.
Click on "Quiet" in "RunControl" window to get the results quicker.
To see 3D shape of simulated dendrites click on "Graph" and "Shape plot" 
in "NEURON Main Menu" when the corresponding Fig.2 or 3 is activated. 
For details of the individual dendrite geometry see also Figure 1 of the 
paper (Fig1.gif file).
This presentation was programmed by Valery I. Kukushka.

The models extend those described in

Korogod SM and Kulagina IB (1998) Biol Cybern 79: 231-242

by using geometry of digitally reconstructed dendritic arborization of 
rat abducens motoneuron. 
Models 1 and 2 include, respectively, a moderately complex single dendrite 
and the whole arborization. They show how the membrane properties and 
stochastic geometry define the somatopetal current transfer from tonic 
excitatory synaptic inputs distributed over the dendrites. Introducing 
uniform steady synaptic conductivity in the dendritic membrane simulates 
such input. The extrasynaptic dendritic conductances were either passive or 
active, Hodgkin-Huxley type Na and K conductances. 
The simpler model 1 (Fig.2) shows effects of random branching and diameter 
variation on the contribution from each dendritic site to the total current 
reaching the soma. For that the NEURON programs compute and display the 
path profiles of the membrane voltage (A, E), total and partial 
conductivities (B, F), total current per unit membrane area (C, G) and the 
core current increment per unit path length (D, H). The latter is the 
estimate of the current transfer effectiveness. 
The heterogeneous depolarization increases with path distance from the soma 
with unequal rates (gradients) along different dendritic paths. The voltage 
path profiles diverge according to the branching asymmetry due to greater 
depolarization of longer sister paths. More depolarized dendritic sites 
generate inward membrane current of smaller density. Path profiles of the 
core current increment that is the product of the membrane current density 
and perimeter are modulated by randomly varying diameter (cf. Fig.2. D, H 
and Fig.1).
The complex model 2 (Fig.3) shows that, in the whole reconstructed 
arborization receiving distributed input, whatever are membrane properties, 
passive or Hodgkin-Huxley type active (B or C, respectively), the path 
profiles of depolarization form bundles, which correspond to those of the 
passive transfer effectiveness from single site inputs (A). The bundles 
indicate the groups of dendritic paths, which although hardly 
distinguishable, morphologically are functionally distinct due to 
between-group difference and within-group similarity of their electrical 
behavior. Random diameter variations perturb bundling of the path profiles 
of the current transfer from distributed sources (D).

Membrane mechanisms:


PasD.mod  - passive extrasynaptic and synaptic currents (models with passive 
	  dendrites)
PasS.mod  - passive synaptic current (models with active dendrites)
Hh1.mod  - sodium, potassium and leak currents of Hodgkin-Huxley type (models 
	   with active dendrites)
PasSA.mod: passive membrane current of the soma and axon (all models)

For further details see the above-mentioned papers or contact the authors at:
Laboratory of Biophysics and Bioelectronics, 
Dniepropetrovsk National University, 
49050 Dniepropetrovsk, Ukraine
Phone/FAX: +38056 776 91 24
E-mails: korogod@ff.dsu.dp.ua;  kulagina@ff.dsu.dp.ua;  valery@ff.dsu.dp.ua
