# Convergent mutations – Experimental validations - References

__In this document, we summarize the information on convergence mutations (potential or validated) that we have used to compare ConDor, FADE, and PCOC. The aim is to facilitate reuse of our datasets for future studies and interpretation of the results. We highlight mutations for which we have only predictions and those for which we have experimental validations. We also discuss unvalidated mutations discovered in our study for which there are strong and consistent predictions. For more information, please refer to the manuscript describing ConDor and our analyses and comparisons, as well as the references cited here and in the main text.__

## Sedge PEPC dataset
The A780S mutation (i.e., a change from A to S on reference position 780) has been experimentally demonstrated to be a major determinant of C4-specific characteristics (Bläsing et al. 2000). Mutations at positions 780 and 665 were confirmed experimentally to have an impact on the catalytic activity and folding of PEPC (Svensson et al. 2003; Christin et al. 2007). 

Besnard et al. (2009)  found 16 positions (including the aforementioned two positions) under positive selection that carry parallel amino-acid mutations in genes associated with C4 metabolism. These 16 positions are 505, 540, 572, 573, 623, 665, 731, 733, 749, 751, 761, 770, 780, 810, 839 and 906.

Although most of these positions have not been confirmed experimentally (unlike HIV DRMs and convergent mutations in fish rhodopsin, see below), Rey et al. (2018) used these potentially convergent positions to evaluate the application of PCOC (and other approaches) on this dataset. Among them, PCOC classifies 8 positions as convergent (540, 572, 573, 623, 665, 731, 751, 780). For the other 8 positions, Rey et al. (2018) state: "there are eight positions classified only by Besnard et al. (2009) as convergent and not predicted as convergent by PCOC, because they each underwent substitutions only in a subset of the C4 clades out of five: four for position 505, three for position 761, 839, two for positions 749, 770, 810, and 906, and one for position 733. For all those sites, there is no support for OC and at best weak support for PC, because those sites do not fit PCOC's definition of a convergent site."

Moreover, for 2 positions (584 and 620) not found by Besnard et al. (2009), Rey et al. (2019) state: "Further, manual inspection of the two new sites with the best posterior probabilities (positions 584, 620) suggests that they have undergone substitutions inside each of the C4 clades, possibly on the branch ancestral to those clades, and toward amino acids that are seldom found in the gene sequences from C3 species." Analyses with ConDor (Fig. 3) confirm position 620, while position 584 receives relatively high scores. These two positions are not found by FADE.

Four (five with phenotypic annotation) positions predicted to be convergent by Besnard et al. (2009) were not tested in our comparisons because they showed less than 3 EEMs. These positions (733, 770, 810, 906, and 839 for the "phenotypic" annotation) have not been experimentally confirmed and are not found by PCOC due to their rare emergence in convergent clades (see above).

The two experimentally confirmed mutations 780 and 665 are highly scored by ConDor as well as by FADE and PCOC (Fig. 3).

## Drug resistance mutations (DRMs) in HIV :

Mutations must meet certain criteria to be identified as DRMs, including experimental validation (Wensing et al. 2019). DRMs are primarily found in proteins targeted by antiretroviral therapies: protease, reverse transcriptase, and integrase. The list of known DRMs affecting these proteins is publicly available at https://hivdb.stanford.edu/ and is updated regularly.

We studied mutations on the reverse transcriptase, where DRMs are numerous, diverse, and have been experimentally confirmed.

The mutation M184V, which is the most frequent, is observed in 378 and 5 sequences with treated and naive status, respectively, corresponding to relative frequencies of 66% and 0.4%. It is expected that such a DRM will be found by any reasonable convergence detection method. In contrast, rare DRMs are much more difficult to detect. For example, DRM Y188L is found in only 21 sequences (all from treated patients), which corresponds to 3.7% of treated sequences and 1% of all sequences.

In our dataset, all DRMs present in at least 10 sequences emerged frequently (between 9 and 225 times, Sup. Tab. S7).

Our dataset contains several examples of DRMs involving highly exchangeable amino acids (some of which are TP detected by ConDor: K70R, M41L and, almost, V90I) demonstrating that convergent mutations with effects on phenotype can occur even between amino acids sharing highly similar biochemical properties. Moreover, detailed results show that DRMs occur in both fast and slowly evolving positions (e.g., M184V and V90I with evolutionary rates of 3.27 and 0.17, respectively, meaning that M184V evolves ~20 times faster than V90I; Sup. Tab. S7).

L228R (detected by ConDor, PC and FADE, Fig. 4), is not listed as a DRM in  https://hivdb.stanford.edu/, but has previously been described as an accessory mutation occurring in response to certain HIV treatments (Rhee 2003; Blassel et al. 2021).

E138A (a DRM with negative log BF, but 46 EEMs and a corrected p-value of 0.001) is a polymorphic mutation found naturally in naive patients and particularly in subtype C. This subtype happens to be the main subtype sampled in our dataset and mainly from naive patients (Villabona-Arenas et al. 2016). E138A is therefore prevalent in our dataset, with many EEMs, but no significant difference between treated and naïve patients, which explains our results with Correlation.
 
## Rhodopsin data:

Mutagenesis experiments of engineered pigments revealed that the difference of λmaxs between most rhodopsins could be explained by 9 amino-acid mutations (Yokoyama 2008). In particular D83N, E122Q, F261Y and A292S occurred several times independently and resulted into functional changes.

The dataset we used comes from a study in which the authors characterized substitution F261Y as convergent in fish rhodopsin, as a possible result of a transition from marine to brackish or fresh water environments (Hill et al. 2019).

E122I and Y102F mutations have emerged several times in our dataset (Hill et al. 2019), and have also been shown experimentally to affect absorption wavelength (Yokoyama 2008).

In total, we thus have 6 "direct" mutations with experimental validation : D83N, Y102F, E122Q, E122I, F261Y and A292S. 

In the case of successive changes in the environment, we can consider the reversion to the ancestral amino acid as convergent if it has emerged multiple times independently, that is, N83D, Y261F, S292A, and Q122E and I122E, which were counted together as they both revert to the same ancestral amino acid E. The F102Y mutation shows zero emergence in the data set and was not tested. 

All this allowed us to study 10 (6 direct, 4 revertant) mutations as truly convergent.

Convergent candidate mutation A166S is detected by the three methods (Fig. 5). This mutation is found by ACR to have 48 EEMs whereas on simulations it emerged at most 38 times. Following previous results from (Malinsky et al. 2015; O'Reilly et al. 2016), it might be associated with a blue-shifting absorption wavelength.
