# The-importance-of-solvent-adsorption-in-liquid-phase-reaction-kinetics

This repository contains the geometries of Reactants, Products and TSs of each elementary step of the direct Nitrobenzene hydrogenation to Aniline calculated in the work "The importance of solvent adsorption in liquid phase reaction kinetics:  Nitrobenzene hydrogenation in Pd (111) as a case study". Those reactions are:

<ins>*Adsorptions/Desorptions*</ins>
   - ph-NO<sub>2(g)</sub>   -->    ph-NO<sub>2</sub><sup>*</sup>
   - ph-NO<sub>(g)</sub>     -->    ph-NO<sup>*</sup>
   - ph-NHOH<sub>(g)</sub>   -->    ph-NHOH<sup>*</sup>
   - ph-NH<sub>2(g)</sub>    -->    ph-NH<sub>2</sub><sup>*</sup>
   - H<sub>2</sub>O<sub>(g)</sub>       -->    ph-H<sub>2</sub>O<sup>*</sup>

<ins>*Reactions*</ins>
   - H<sub>2</sub><sup>*</sup>                -->    H<sup>*</sup>         +  H<sup>*</sup>
   - ph-NO<sub>2></sub<sup>*</sup>   +  H<sup>*</sup>    -->    ph-NOOH<sup>*</sup>
   - ph-NOOH<sup>*</sup>           -->    ph-NO<sup>*</sup>     +  OH<sup>*</sup>
   - ph-NO<sup>*</sup>    +  H<sup>*</sup>   -->    ph-NOH<sup>*</sup>
   - ph-NOOH<sup>*</sup>  +  H<sup>*</sup>    -->    ph-N(OH)<sub>2</sub><sup>*</sup>
   - ph-N(OH)<sub>2</sub><sup>*</sup>         -->    ph-NOH<sup>*</sup>    +  OH<sup>*</sup>
   - ph-NOH<sup>*</sup>   +  H<sup>*</sup>    -->    ph-NHOH<sup>*</sup>
   - ph-NHOH<sup>*</sup>           -->    ph-NH<sup>*</sup>     +  OH<sup>*</sup>
   - ph-NOH<sup>*</sup>            -->    ph-N<sup>*</sup>      +  H<sup>*</sup>
   - ph-N<sup>*</sup>     +  H<sup>*</sup>    -->    ph-NH<sup>*</sup>
   - ph-NH<sup>*</sup>    +  H<sup>*</sup>     -->    ph-NH<sub>2</sub><sup>*</sup>
   - ph-NO<sup>*</sup>             -->    ph-N<sup>*</sup>      +  ph-O<sup>*</sup>



   
The Pd(111) optimized structure can be found in the root of the "Optimized Geometries" folder and the files for each reaction are located in each "Optimized Geometries/Reaction" folder, where "Reaction" corresponds to each reaction name (*e.g.,* ph-NO2 hydrogenation folder is called **ph-NO2+H->ph-NOOH** ). Each folder contains the VASP CONTCAR files with each independent reactant and product adsorbed into the Pd(111) surface, as well as the coadsorbed species (when applicable) and the TS that connects them. Those are labeled as following (note that Phenile rings were not written for simplicity, so NO2 or NHOH are actually ph-NO2 and ph-NHOH):
   
   - *X-CONTCAR :  The global minimum energy configuration of the X Reactant or Product adsorbed into Pd(111).*
   - *X+Y-CONTCAR: The global minimum energy configuration of the X and Y coadsorbed Reactants or Products adsorbed into Pd(111).*
   - *TS-CONTCAR:  The located structure of the Transition State + Pd(111).*

# Citing this work
Please, if you use any of the optimized CONTCAR files in this repository cite the original work where they were located:
- *J. Herrera, P. Gamallo, C.H. Campos, G. Alonso. The importance of solvent adsorption in liquid phase reaction kinetics:  Nitrobenzene hydrogenation in Pd (111) as a case study. Manuscript under preparation*

``` 
