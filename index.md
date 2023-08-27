<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-6KTXKWMYF3"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-6KTXKWMYF3');
</script>

I am an **[Environmental Fellow](https://environment.harvard.edu/environmental-fellows-program)** at Harvard University Center for the Environment (HUCE) working with the **[Materials Intelligence Research](https://mir.g.harvard.edu/)** group since July 2022. Previously, I was a Ph.D. student at University of California, Berkeley with the **[Ceder](https://ceder.berkeley.edu)** group and an AI Resident with **[X](https://x.company/)** (formerly Google X). 

As a **materials scientist working closely with experiments** using computation and machine learning, my research elucidates thermodynamic and kinetic behavior of atoms or molecules to understand and design urgently-needed, sustainable materials for **energy storage and the environment**.

Please see [Google Scholar](https://scholar.google.com/citations?user=GUYnP_cAAAAJ&hl=en) for a full list of publications and my CV [here](CV-JHY-public.pdf). 

___

## Diversity, Equity, Inclusion, and Belonging 

> We are committed to fostering environments that are professionally and personally inclusive, equitable, psychologically safe, and **welcoming to all teammates**. We do this by leading with **kindness, open-mindedness, and empathy**.  
> 
> 1. **Kindness**: We communicate openly and respectfully, remembering that it is okay for others to have different opinions from us. We treat others with the kindness that we want others to treat us. 
> 2. **Open-mindedness**: We leave assumptions behind, and seek first to understand. We are aware of community biases, actively find new ways to reduce them, and encourage our peers to do the same. 
> 3. **Empathy**:  We always remember that we are on the same team, working together on science and engineering challenges that need our solutions. We give ourselves and others the time, space, and patience to grow and learn.
> 
> These are our guiding principles as **ethical scientists and engineers**.
 
___

## Research interests & contributions 
### I. Nano-domain resolution of positive electrode

>We are interested in understanding atomic-level heterogeneities, occurring either as a single-phase, solid solution or as polycrystals. We use computational tools to isolate the systematic,  thermodynamic effects controlling intragranular and intergranular features.

### Previous work:  
>> Using density functional theory (DFT) and random enumeration of large unit-cells (containing ~3000 atoms), we teamed up with an electrochemist and microscopy expert to model the probability of specific, atomic-level interactions of disordered, sodium-ion layered intercalation positive electrodes. Please see our work [here:](https://onlinelibrary.wiley.com/doi/abs/10.1002/aenm.202001151)
![](na-op2.jpg) 

>> However, random enumeration cannot capture experimentally-observed phenomena such as short-range order existing at the nano-domain level. We have also used DFT and lattice cluster expansion models to study a partially-disordered spinel positive electrode with ultrahigh power and energy density. Our cluster expansion model reveals that a newly-activated pathway for Li hops, through 48f-16d sites, explains the origin of high rate. Please see our work [here:](https://onlinelibrary.wiley.com/doi/abs/10.1002/aenm.202202955)    
![](pds.jpg)

### II. Computational methods: understanding and application

> As computational materials scientists, we need to know the utilities and limitations of existing DFT approaches, given that these methods are system-dependent and oftentimes cannot be used "out-of-the-box". In studying complex electrochemical systems and under-explored interfaces, we will need to be sure that our approaches are reliable. 

### Previous work:
>> Given the efficacy of meta-GGA functionals in ground state crystal structure prediction, as observed in our work [here](https://www.nature.com/articles/s41524%E2%80%90018%E2%80%900065%E2%80%90z), we used data-driven methods to find systematic under-coordination in the well-known PBE functional, not observed in SCAN. We trace the origin of this difference to their exchange enhancement factors [here](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.100.035132).
![](scan.jpg)
>
>> Lattice models can be used to disordered systems, but they have rarely been extended to study systems with more than 2 or 3 species. In studying the partially-disordered spinel system, [we constructed one of the most complex lattice models to our knowledge](https://www.nature.com/articles/s41524-022-00818-3), and suggested that model error with CE models should scale with species complexity. We also explained our approaches in a "Behind the Paper" commentary [here](https://materialscommunity.springernature.com/posts/structured-sparsity-for-building-predictive-models-in-chemically-complex-systems).
> ![](npj-pds.jpg)

>> We are also the first to study the DFT corrections needed to model organic solvents. (Preprint coming soon.)

### III. Battery recycling with solvents
> Molecular understanding of metal-solvent interactions are essential to develop new metals recycling methods. We are interested in exploiting the tunability of "designer solvents", such as molten salts, ionic liquids, or deep eutectic solvents, to enable selective metals extraction. 

### Previous work:
>> We have developed a computational workflow, using cheminformatics and Bayesian methods, to navigate reaction conditions for optimizing chemical recycling of waste plastics. Several patents regarding this process have been filed by X Development LLC. See our primary contribution [here](https://patents.google.com/patent/US20230170056A1/en): 

>> We also use large-scale atomistic simulations powered by state-of-the-art machine learning methods to understand molecular structure of neat solvent. (Preprint coming soon.)