
# Science
My Background: PhD, MS Physics, BS Mathematics


## Protein "Physics"
Folding, interfaces, aggregation, electrostatics, statisical mechanics, ...
<br>

&& Not talking about [Ising model topology](http://thoppe.github.io/Presentation_Telluride_2014_WL_Topology/#/), [hacking graph theory](https://github.com/thoppe/Encyclopedia-of-Finite-Graphs), or [other interesting ventures](https://github.com/thoppe/Presentation_Irrelevant_Topics_In_Physics)...

=====*

### Protein Structure
|#### Primary structure    (sequence)
    GSIGAASMEF CFDVFKELKV HHANENIFYC PIAIMSALAM VYLGAKDSTR TQINKVVRFD KLPGFGDEIE AQCGTSVNVH 
    SSLRDILNQI TKPNDVYSFS LASRLYAEER YPILPEYLQC VKELYRGGLE PINFQTAADQ ARELINSWVE SQTNGIIRNV 
    LQPSSVDSQT AMVLVNAIVF KGLWEKAFKD EDTQAMPFRV TEQESKPVQM MYQIGLFRVA SMASEKMKIL ELPFASGTMS 
    MLVLLPDEVS GLEQLESIIN FEKLTEWTSS NVMEERKIKV YLPRMKMEEK YNLTSVLMAM GITDVFSSSA NLSGISSAES 
    LKISQAVHAA HAEINEAGRE VVGGAEAGVD AASVSEEFRA DHPFLFCIKH IATNAVLFFG RCVSP
!(images/1ova/1ova_cartoon.png) <<height:340;transparent>>  Secondary structure<br>helices [red], sheets [blue
!(images/1ova/1ova_spheres.png) <<height:340;transparent>>  Tertiary structure<br>3D structure
!(images/1ova/Ovalbummin_aggregate.gif) <<height:340;transparent>>  Higher-order structure<br>complexes, aggregation


&& Ovalbumin, Egg white protein [PDB:1OVA](http://www.rcsb.org/pdb/explore.do?structureId=1ova), Crystal Structure, Carrell et al., [J. Mol. Biol. (1991)](http://www.ncbi.nlm.nih.gov/pubmed/1942038?dopt=Abstract)<br> SEM Aggregate structure, Zabik et al., [J. Poul. Sci. (1980)](http://ps.oxfordjournals.org/content/60/9/2071.abstract)

====*

## Protein interactions

!(images/biochem/ww_fold.m4v)<<transparent;height:400px>> Folding
!(images/biochem/example_dimer.png)<<transparent;height:400px>> Binding, dimerization 
!(images/biochem/abeta.png)<<transparent;height:400px>> Aggregation, Fibril formation

====* !(images/biochem/zimmer_crowding.jpg)

## <div style="color:white;text-shadow: 2px 2px #000000;"> Protein interactions in a <br>crowded environment</div>

!(images/biochem/ww_fold.m4v)<<transparent;height:350px>>
!(images/biochem/example_dimer.png)<<transparent;height:350px>> 
!(images/biochem/abeta.png)<<transparent;height:400px>>
&& <div style="color:white;text-shadow: 2px 2px #000000;"> Background image from Harvard University, XVIVO Scientific Animation</div>

====

## How do we do it?
Statistical Potentials: Residue-residue interactions

## $U_{a,b} = -kT \ln \frac{p_{\text{obs}}(a,b)}{p_\text{expt}(a,b)} \approx -kT \ln \frac{N_\text{obs}(a,b)}{N_\text{expt}(a,b)}$

!(images/1pcy/1pcy_cartoon.png) <<height:300>>
!(images/1pcy/1pcy_sticks.png) <<height:300>>
!(images/1pcy/1pcy_ultra_sidechain.png) <<height:300>>
!(images/1pcy/1pcy_res_res.png) <<height:300>>

&& Potentials constructed from Top 8000 Protein Database, [Richardson Group](http://kinemage.biochem.duke.edu/databases/top8000.php)


====*<<transition:fade>>

### Residue-residue interaction matrix, MJ
!(images/mj_potential/MJ_matrix.png)  <<transparent; height:700>>

&& Other statistical potentials: [Tanaka and Scheraga](http://pubs.acs.org/doi/abs/10.1021/ma60054a013) (1976), [Spil](http://www.ncbi.nlm.nih.gov/pubmed/2359125) (1990), [Miyazawa and Jernigan](http://www.ncbi.nlm.nih.gov/pubmed/8604144) (1996),<br>[Betancourt and Thirumalai](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2144252/) (1999), [Skolnick, Kolinski and Ortiz](http://onlinelibrary.wiley.com/doi/10.1002/%28SICI%291097-0134%2820000101%2938:1%3C3::AID-PROT2%3E3.0.CO;2-S/abstract) (2000)

====*<<transition:fade>>
### MJ matrix reveals biophysical structure
!(images/mj_potential/MJ_matrix_remapped.png)  <<transparent; height:700>>
&& H (hydrophobic), P (polar), C (charged)
%Analysis of Statistical Potentials by [Li](http://journals.aps.org/prl/abstract/10.1103/PhysRevLett.79.765).
====*

### Higher order structure
Phase separations lead to sudden changes in liquid structure.
!(images/macrocharge/example_phase_sep.jpg) <<height:200px;transparent>> Leibler, [Nature 2004](http://www.nature.com/nature/journal/v430/n6999/abs/nature02758.html)
!(images/macrocharge/phase_sep2.jpg) <<height:200px;transparent>> Tanaka, [Phys. Rev. E 2005](http://journals.aps.org/pre/abstract/10.1103/PhysRevE.72.041509)

How do we model _many_ protein-protein interactions? 
Can we *predict* aggregates from experimental structure? 
!(images/macrocharge/1AO6_cartoon.png) <<height:225px;transparent>> Human serum albumin<br>[PDB:1AO6](http://www.rcsb.org/pdb/explore/explore.do?structureId=1ao6)
!(images/macrocharge/1OVA_cartoon.png) <<height:225px;transparent>> Ovalbumin<br>[PDB:1OVA](http://www.rcsb.org/pdb/explore.do?structureId=1ova)
!(images/macrocharge/1W6Z_cartoon.png) <<height:225px;transparent>> Lysozyme<br>[PDB:1W6Z](http://www.rcsb.org/pdb/explore/explore.do?structureId=1w6z)
!(images/macrocharge/3V03_cartoon.png) <<height:225px;transparent>> Bovine Serum Albumin<br>[PDB:3V03](http://www.rcsb.org/pdb/explore/explore.do?structureId=3v03)

====*<<transition:slide>>

## Where does CS come into play?

1. Be able to say what is possible (and what isn't!)
2. Algorimic design (linear algebra, molecular dynamics...)
3. Prediciting runtime (non-trivial at model stage!)
3. Scaling up! 
