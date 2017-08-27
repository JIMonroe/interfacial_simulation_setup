# Best practices and checklist for the set-up and molecular dynamics simulation of solid-fluid interfacial systems
2
​
## A brief introduction to Interfacial Science  
4
​### Brief overview of molecular interactions in the context of interfaces  
7
*​ Electrostatic interactions  
9
  * Considerations at short range  
11
​  * Considerations at long range  
    * Distinct from short range if have something like a net dipole moment in the surface or a double-layer at the surface, or longer range surface-surface interactions  
* Dispersion interactions  
  * Considerations at short range  
  * Considerations at long range  
    * Again distinct from short-range, with potentials such as an effective 9-3, etc.  
* Adsorption at interfaces  
25
​* Surface reactivity and covalent bonding  
27
​
28
### Brief overview of thermodynamics of interfaces  
30
​* Introduction of thermodynamic ensembles involving surface area, surface tension, and interfacial free energy  
32
  * Definition of an interface 
  * Interfacial tension and interfacial free energy - not the same for solid interfaces  
  * General resources  
    * “Molecular Theory of Capillarity,” Rowlinson and Widom  
    * “Intermolecular and Surface Forces,” Israelachvili  
42
​
### Background on specific interfaces of interest/case studies  
45
​* Self-assembled monolayers (SAMs)
  * May be of general interest, not surfaces 
* Metallic Interfaces  
  * If there are any specific background  
*  Lipid Membranes
  Lipid bilayer membranes (planar and vesicular) have applications in soft matter physics, pharmacology, consumer products, etc., and are first approximants to biological membranes. Lipid bilayers consist of two molecularly-thick layers, or leaflets, in aqueous solvent, where the lipids are oriented with their polar head groups outward and their nonpolar tail groups inward. The dominant driving forces in their formation and stability include hydrophobic and dispersion interactions, wherein the lipid tail groups maximize their contacts with each other and minimize their contacts with water, decreasing area per lipid; and head group electrostatic repulsion and tail group conformational entropy, which work to increase the area per lipid. “Fluid” (liquid crystalline) lipid membranes are normally modeled as liquid-like laterally (no in-plane shear modulus), and solid-like transversally (out of plane). In lipid membrane simulations, the canonical system is DPPC (dipalmitoylphosphatidylcholine) in water. This is typically the system for which new force fields are first tested. DPPC is sometimes not preferred in experiments, however, due to its high melting point (from the gel to liquid-crystalline state). In any event, the main goal for a lipid membrane model study should be to correctly capture the correct structural, mechanical, thermodynamic, and/or dynamic properties (whatever is relevant) at the relevant length and timescales and the correct equilibrium (thermodynamic, temperature, pressure, etc.) and/or nonequilibrium (thermal/mechanical/chemical/other gradients) conditions. Transferability is ideal, but not necessarily a priority.  

  Some good papers/textbooks for statistical mechanical/thermodynamic background on membranes  
    Safran, Samuel A. “Statistical Thermodynamics of Surfaces, Interfaces, and Membranes.” 2003: Westview Press.  
    Nelson, D.; Piran, T.; and Weinberg, T. “Statistical Mechanics of Membranes and Surfaces.” 2004: World Scientific Publishing Company.  
    Boal, David. “Mechanics of the Cell.” 2012: Cambridge University Press, New York.  

  Good papers/textbooks for computational/simulation guidance on membranes  
    Sundararajan, V. “Computational Modeling of Membrane Bilayers, Volume 60 (Current Topics in Membranes).” 2008: Academic Press.  
    Tieleman, Marrink, and Berendsen. Biochimica et Biophysica Acta, 1997.
