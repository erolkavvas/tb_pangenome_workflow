# Workflow for statistical and genome-scale modeling of 1595 M. Tuberculosis strains

The study is divided into four sections.

1. **Pan-genome analysis**
    1. Pan-genome partitioning
    2. Heaps Law applied to pan-genome

2. **Statistical determination of antimicrobial genes (Gene-AMR associations)**
    1. Pairwise assocations with Mutual information  
    2. Machine Learning with a Support Vector Machine

3. **iEK1020**
    1. iEK1020.json (new reconstruction of _M. tuberculosis_ H37Rv, iEK1020, in json format)
    2. iEK1020_supplementary.xlsx
        1. Sheet 1-  Reactions in iEK1020 and details of reactions.
        2. Sheet 2- Metabolites in iEK1020 and details of metabolites.
        3. Sheet 3- Gene Essentiality simulation information
        4. Sheet 4- Various _in silico_ media conditions
    3. SUPP_reproducible_modeling.ipynb: an ipython notebook that runs the simulations described in "iEK1020 simulates flux states indicative of physiological conditions"
    4. Escher Maps folder; contains four escher maps of _M. tuberculosis_ metabolic subsystems
    

4. **Game of Allele Coordination (System-AMR assocations)**
    1. SUPP_game_simulations.ipynb: an ipython notebook that sets up and simulates a game.
    2. dfdsa
