# Best practices and checklist for the set-up and molecular dynamics simulation of solid-fluid interfacial systems

Jacob Monroe, Andrew Summers, Kristen Fichthorn

## Scope

In this contribution to the LiveCoMS journal, we recommend specific methods for setting up interfacial systems, as well as parameters and techniques that should be used when simulating solid-fluid interfaces.
We believe the procedures detailed here to constituted the current "best practices" in the field, and encourage readers to make comments and suggestions at the GitHub repository in order to keep this document consistent with the state of the art.
This document DOES NOT specifically cover fluid-fluid interfaces or lipid membranes, which are, or will be, addressed in other contributions to the journal.
However, many of the concepts presented here will also be useful in working with such systems.
The first part of this document provides a very brief introduction to interfacial science, and a (inexhaustive) list of other resources that the reader should carefully study before attempting to run any simulations.
The checklists provided after should not be viewed as complete, but, if followed, should help the reader to avoid \textit{most} mistakes involved in performing interfacial simulations.
Although this document recommends performing common analyses and computation of specific properties for simulation verification, these procedures WILL NOT be covered here.
Supplements are provided for specific, relatively popular systems of interests.
Though not every interfacial system may be covered in depth, we hope the selected systems serve as concrete examples that help the reader to better understand the considerations involved in simulating interfacial systems with molecular dynamics.

## A brief introduction to interfacial science

### Brief overview of molecular interactions in the context of interfaces
* Electrostatic interactions
  * Considerations at short range
  * Considerations at long range
    * Distinct from short range if have something like a net dipole moment in the surface or a double-layer at the surface, or longer range surface-surface interactions
* Dispersion interactions
  * Considerations at short range
  * Considerations at long range 
    * Again distinct from short-range, with potentials such as an effective 9-3, etc.
* Adsorption at interfaces
* Surface reactivity and covalent bonding

### Brief overview of thermodynamics of interfaces
* Introduction of thermodynamic ensembles involving surface area, surface tension, and interfacial free energy
* Definition of an interface 
* Interfacial tension and interfacial free energy - not the same for solid interfaces
* General resources  
  “Molecular Theory of Capillarity,” Rowlinson and Widom  
  “Intermolecular and Surface Forces,” Israelachvili

### Commonly used terminology and abbreviations
 * It was decided that every document should have such a section, which is likely a very good idea

### Background on specific interfaces of interest/case studies
* Self-assembled monolayers (SAMs)
  * May be of general interest, not sure
* Metallic Interfaces
  * If there are any specific background
