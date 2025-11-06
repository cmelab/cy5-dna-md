DNA and DNA + Dye PDBs

-----

cy5_duplex.pdb

FOR COARSE GRAINING DNA-DYE, WE WILL START WITH THIS FILE. IT IS THE MOST STRAIGHTFORWARD.
DNA double helix, with two CY5 dyes. Dyes are incorporated on opposite strands, using a 3-carbon double linker. Each dye is incorporated into the DNA backbone, taking the place of a nucleotide.   This PDB has been energy-minimized, but not fully equilibrated. 

-----

nanotube_long.pdb

Long 6-helix DNA nanotube, seqences taken from (1). DNA only, no dyes are present. This was equilibrated. 

----

nanotube_short.pdb

Short 6-helix DNA nanotube, sequences taken from (1). DNA only, no dyes are present. This was equilibrated.  Some fraying can be seen at the end. 

---

nanotube_long_with_dye.pdb

Long 6-helix nanotube, seqences takes from (1). DNA-portion is the same as nanotube_long.pdb. A 6-dye long chain of bacteriochlorins is inside the nanotube, attached on one end to the DNA via a modified-T linker. This type of linker does not involved the DNA backbone, but rather attaches the dyes to the nucleobase (a slightly modified T). This stucture is equilibrated, and was run in MD for some time. At the one end of the nanotube, harmonic constraints were placed on the end of the DNA strands to prevent the end of the nanotube from fraying. 

---

nanotube_short_with_dye.pdb


Short 6-helix nanotube, seqences takes from (1). DNA-portion is the same as nanotube_short.pdb. A 4-dye long chain of bacteriochlorins is inside the nanotube, attached on one end to the DNA via a modified-T linker. This type of linker does not involved the DNA backbone, but rather attaches the dyes to the nucleobase (a slightly modified T). This stucture is equilibrated, and was run in MD for some time. At the one end of the nanotube, harmonic constraints were placed on the end of the DNA strands to prevent the end of the nanotube from fraying. 

---

dna_holiday_junction_1.pdb  AND dna_holiday_junction_2.pdb

DNA Holiday junction with a single-linked CY5 dye in the center. This linker is district from the double-linker and mod-T linkers. 1 and 2 varientions are slightly different starting positions.  These structures have been lightly equilibrated. 


Works Cited:
(1) Yin, P.; Hariadi, R. F.; Sahu, S.; Choi, H. M. T.; Park, S. H.; LaBean, T. H.; Reif, J. H. Programming DNA Tube Circumferences. Science 2008, 321 (5890), 824–826. https://doi.org/10.1126/science.1157312.
