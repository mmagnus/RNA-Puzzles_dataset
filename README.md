# RNA-Puzzles dataset
This repository includes all the submitted RNA structures in RNA-Puzzles. 

Raw dataset contains structures submitted to the organizers without any correction.

Normalize dataset contains  structures processed using PDBnormalizer, which only use the aligned segments and drop the missing atoms. This is used for prediction evaluation.

We also provide https://github.com/RNA-Puzzles/RNA-Puzzles-Normalized-submissions which is normalized with rna-tools, which unmodify the nucleotides, add missing atoms. This is used for training scoring functions.

The RNA Puzzles:  

* Puzzle 1: RNA dimer of a regulatory element from human thymidylate synthase mRNA
* Puzzle 2: Self-assembling RNA square
* Puzzle 3: Glycine riboswitch
* Puzzle 4: SAM-I riboswitch aptamer
* Puzzle 5: Lariat capping ribozyme.
* Puzzle 6: Adenosylcobalamin riboswitch
* Puzzle 7: Varkud satellite ribozyme
* Puzzle 8: SAM riboswitch
* Puzzle 9: TBA
* Puzzle 10: T-box riboswitch and tRNA
* Puzzle 11: TBA
* Puzzle 12: YdaO riboswitch
* Puzzle 13: ZMP riboswitch
* Puzzle 14: L-glutamine riboswitch (Free)
* Puzzle 14: L-glutamine riboswitch (Bound)
* Puzzle 15: Hammerhead
* Puzzle 16: TBA
* Puzzle 17: Pistol ribozyme
* Puzzle 18: Zika virus
* Puzzle 19: Twister sister

# Citation

```
Miao, Zhichao, et al. 
"RNA-Puzzles Round III: 3D RNA structure prediction of five riboswitches and one ribozyme." 
RNA 23.5 (2017): 655-672.

Miao, Zhichao, et al. 
"RNA-Puzzles Round II: assessment of RNA structure prediction programs applied to three large RNA structures." 
Rna (2015).

Cruz, José Almeida, et al. 
"RNA-Puzzles: a CASP-like evaluation of RNA three-dimensional structure prediction." 
Rna 18.4 (2012): 610-625.
```
