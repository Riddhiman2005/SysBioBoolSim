# A Modular Boolean Automata Framework for Multiscale Simulation of Cell Fate, Cycle, Differentiation, and Circadian Dynamics

## Summary 
This repository provides C++ code for simulating Boolean network–based models of cellular decision-making.  
The framework is modular, allowing different biological processes to be represented together in a unified way.  
Rather than studying a single pathway in isolation, the aim here is to capture how various decision processes interact within the cell.  

The project focuses on key cellular fates such as **survival or death, division, differentiation, or maintaining circadian rhythms**.  
To achieve this, we have developed four core modules, each modeled using Boolean automata.

1. **Cell Fate Switch (TNF/FAS driven) :** Decides between survival, apoptosis, or necrosis.  
2. **Cell Cycle (yeast-inspired) :** Captures progression through different cell cycle stages.  
3. **Differentiation Switch (GATA-1/EPO signaling) :** Balances self-renewal vs. differentiation.  
4. **Circadian Oscillator :** A two-state Boolean clock to track timing and synchronization.  

#### Functioning
- The modules are combined into an **agent-based simulation**.  
- Each cell can interact with its neighbors and exchange signals.  
- We run simulations for both **wild-type and mutant cases**.  
- We explore **attractor landscapes** and **synchronization dynamics** across populations.  

## What do we find?

From simple Boolean rules, we observe complex and realistic behaviors:
- Asynchronous cell cycles  
- Mixed fate outcomes in populations  
- Divergence of cell fate under mutations  
- Circadian synchronization across cells

### References

- L. Calzone, L. Tournier, S. Fourquet, D. Thieffry, B. Zhivotovsky, Mathematical modelling of cell-fate decision in response to death receptor engagement, *PLoS Comput Biol* 6 (2010).  
- F. Li, T. Long, Y. Lu, Q. Ouyang, C. Tang, The yeast cell-cycle network is robustly designed, *PNAS* 101 (2004).  
- F. Greil, Boolean networks as modeling framework, *Frontiers* 2, 178 (2012).  
- G. Kroemer, L. Galluzzi, C. Brenner, Mitochondrial membrane permeabilization in cell death, *Physiol Rev* 87 (2007).  
- A. G. Porter, R. U. Jänucke, Emerging roles of caspase-3 in apoptosis, *Stockt. Press* 6 (1999).  
- S. Palani, C. A. Sarkar, Positive receptor feedback lineage commitment can generate ultrasensitivity to ligand and confer robustness to a bistable switch, *Biophys J* 95 (2008).  
- J. S. Takahashi, Transcriptional architecture of the mammalian circadian clock, *Nat Rev Genet* 18, 164–179 (2017).  
- C. L. Partch, C. B. Green, J. S. Takahashi, Molecular architecture of the mammalian circadian clock, *Trends Cell Biol* 24, 90–99 (2014).  
- J. A. Mohawk, C. B. Green, J. S. Takahashi, Central and peripheral circadian clocks in mammals, *Annu Rev Neurosci* 35, 445–462 (2012).  
- A. A. Shafi, K. E. Knudsen, Cancer and the circadian clock, *Cancer Res* 79, 3806–3814 (2019). doi:10.1158/0008-5472.CAN-19-0566.  
- A. Sancar, R. N. Van Gelder, Circadian clock, cancer, and chronochemotherapy, *Science* 350, 1020–1025 (2015).  
- A. Ballesta et al., Systems chronotherapeutics, *Pharmacol Rev* 69, 161–199 (2017).  
- N. Cermakian et al., Circadian clocks and inflammation, *Nat Rev Immunol* 13, 521–528 (2013).  
- C. Rodríguez-Santana et al., Role of melatonin in cancer: Effect on clock genes, *Int J Mol Sci* 24, 1919 (2023). doi:10.3390/ijms24031919.  
- O. E. Akman et al., Digital clocks: simple boolean models can quantitatively describe circadian systems, *J R Soc Interface* 9 (2012).  
- O. E. Akman et al., Isoform switching facilitates period control in the *Neurospora crassa* circadian clock, *Mol Syst Biol* 4 (2008).  
- J.-C. Leloup, D. Gonze, A. Goldbeter, Limit cycle models for circadian rhythms based on transcriptional regulation in *Drosophila* and *Neurospora*, *J Biol Rhythm* 14 (1999).  
- J. C. W. Locke et al., Extension of a genetic network model by iterative experimentation and mathematical analysis, *Mol Syst Biol* 1 (2005).  
- J. C. W. Locke et al., Experimental validation of a predicted feedback loop in the multi-oscillator clock of *Arabidopsis thaliana*, *Mol Syst Biol* 2 (2006).  



