# Oligo Pool Plasmid Library Cloning Protocol

**Protocol typed up by Evan Hass**  
**Last modified 2020-05-07**  

**_NOTE: The scale required for cloning the plasmid library (i.e., in order to get good pool coverage in your plasmid library) will depend on how big your oligo pool is. The scale of the protocol below worked well for a pool containing ~35,000 oligos. When re-scaling this protocol for smaller or larger pools, the number of transformations and maxipreps performed are the most important things to adjust (i.e., to get adequate coverage for larger pools or to save reagents with smaller pools)._** 

## A: Digesting and purifying ePCR and vector DNA
1. Digest 200 ng of cleaned-up ePCR DNA, and digest and dephosphorylate 3 ug of your vector of choice. Here's an example protocol:  

- **ePCR digest**  
  200 ng cleaned-up ePCR DNA  
  5 uL 10x NEB CutSmart Buffer  
  1 uL AgeI-HF  
  1 uL Not1-HF  
  Fill to 50 uL with nuclease-free water  
  
- **Vector digest**  
  3 ug plasmid DNA  
  10 uL 10x NEB CutSmart Buffer  
  1.5 uL AgeI-HF  
  1.5 uL NotI-HF  
  Fill to 100 uL with nuclease-free water  
  
- Incubate digests at 37°C for 15 minutes  
- Add extra enzyme to each reaction:  
  For the ePCR digest, add 0.5 uL more of each enzyme  
  For the vector digest, add 1 uL more of each enzyme  
- Incubate digests at 37°C for 15 more minutes  
- Add 4 uL of NEB Quick CIP (NEB M0525) to the vector digest  
- Incubate vector digest at 37°C for 15 more minutes

- *NOTE: Because you'll be scraping all your colonies off your transformation plates instead of picking single clones, your ligation should have as little empty vector as possible, which also means your purified vector DNA should have as little uncut or single-cut vector as possible. One good way to ensure this is to also set up a smaller-scale digest of your vector that only includes one of your two enzymes. Then, when you get to the gel-extraction step, you can run uncut and single-cut vector on the same gel as your double-digest, allowing you to see where the uncut and single-cut species are running and avoid them when excising the double-cut band from the gel.*

2. Clean up the ePCR digest using the Qiagen MinElute PCR Purification Kit (Qiagen 28204) with the following protocol modifications:  
- Repeat the PE wash step one extra time.  
- Elute the DNA with 10 uL of Buffer EB. Then, load the eluate back onto the column and elute again to maximize DNA recovery.  
3. Run the vector digest and associated controls on an agarose gel (*NOTE: You'll likely have to run the gel longer than usual in order to see separation between your double-cut and single-cut bands.*), and excise the double-cut vector band. Isolate DNA from the gel slice using the QIAquick Gel Extraction Kit (Qiagen 28706) with the following protocol modifications:  
- Include the optional QG wash step.  
- Repeat the PE wash step one extra time.  
- Elute the DNA with 30 uL of Buffer EB. Then, load the eluate back onto the column and elute again to miximize DNA recovery.  
4. Measure the concentration of your cleaned-up ePCR and vector DNAs.

## B: Ligation
In these ligations you will be using 100 ng of cut and dephosphorylated vector DNA and a 4-fold molar excess of ePCR DNA. Calculate what volume that is for your cleaned-up ePCR DNA. Then set up three ligation reactions as follows:

- **Reaction 1** (+insert ligation)  
  100 ng of cut-dephosphorylated vector DNA  
  X uL (4-fold molar excess) of cleaned-up ePCR DNA  
  15 uL 2x NEB Quick Ligase Buffer  
  1.1 uL NEB T4 Quick Ligase (NEB 2200)  
  Fill to 30 uL with nuclease-free water

- **Reaction 2** (vector only control)  
  100 ng of cut-dephosphorylated vector DNA  
  3 uL 2x NEB Quick Ligase Buffer  
  0.22 uL NEB T4 Quick Ligase  
  Fill to 6 uL with nuclease-free water

- **Reaction 3** (vector only, no ligase control)  
  100 ng of cut-dephosphorylated vector DNA  
  3 uL 2x NEB Quick Ligase Buffer  
  Fill to 6 uL with nuclease-free water

Incubate reactions at room temp for ~15 minutes  

## C: Transformation
Before starting this protocol, place 62 plates of the appropriate plating medium (usually LB+amp) and ~9 mL of liquid SOC medium at 37°C to pre-warm. Then:  

1. Thaw 32 tubes of Invitrogen One Shot TOP10 Chemically Competent *E. coli* (Invitrogen C404003) on ice for 10 minutes.  
2. Add 1 uL of DNA to each tube as follows:  

- Tubes 1-30: 1 uL of ligation reaction 1 (+insert ligation)  
- Tube 31: 1 uL of ligation reaction 2 (vector only control)  
- Tube 32: 1 uL of ligation reaction 3 (vector only, no ligase control)  

3. Vortex tubes to mix, and incubate on ice for 30 minutes  
4. Heat shock tubes at 42°C for 45 seconds  
5. Immediately return tubes to ice, and incubate for ~2 minutes  
6. Add 250 uL of pre-warmed SOC media to each tube  
7. Incubate at 37°C for 1 hour  
8. Plate transformations as follows:  

- Tubes 1-30: plate each tube to 2 plates each (~150 uL of transformation mix per plate)  
- Tubes 31 and 32: plate 150 uL of transformation mix to one plate and discard the rest  

- *NOTE: If you're plating your transformations using glass beads, you can re-use the same beads to plate all 30 +insert transformations. You'll be pooling all those colonies for the maxiprep anyway, so it doesn't matter if there's cross-contamination between those transformations.*  

9. Incubate plates at 37°C overnight  

## D: Harvesting Colonies and Maxiprepping DNA
Remove plates from 37°C. Count colonies on your +insert and control plates to calculate (a) how many +insert colonies you have per oligo in your pool, and (b) what percentage of your colonies from your +insert transformations are empty vector. To approximate how many colonies you got from your +insert transformations, it is easiest to pick a plate with representative colony density, count colonies in a sector of the plate (e.g., 1/12 of the plate), and then calculate back approximately how many +insert colonies you have in total.

After counting, harvest all colonies from all +insert transformation plates as follows (discard both control plates):  

1. Add 5 mL of appropriate liquid media (usually LB+amp) to a plate  
2. Gently scrape cells off the agar and into the liquid media with a cell lifter (e.g., VWR 29442-200)  
3. Transfer the liquid media to a centrifuge bottle on ice  
4. Add 5 mL more liquid media to the plate  
5. Gently scrape any remaining cells off the plate and into the liquid media  
6. Transfer the liquid media to the centrifuge bottle on ice, and discard the scraped plate  

**TIPS FOR HARVESTING COLONIES**  

- This works best when done by a 2-person team, with one person doing the pipetting and the other doing the scraping. Harvesting 60 plates takes an hour or two with a two-person team, and it'll take even longer if you do it by yourself. Relatedly, if you're feeling like you need a break after an hour or two of scraping colonies, I've not had any downstream issues if I let the cells sit on ice for an hour before starting the maxiprep.  
- It works best to process the plates in groups of ~4 plates at a time.  
- Try to avoid scraping off chunks of agar. A little agar is fine, but too much will clog some of the filters used in the maxiprep protocol.  
- After scraping a plate, the bacteria will stick to the agar again if left to sit for too long. Swirling the liquid after scraping the bacteria off can help prevent this.  
- Split the liquid between a few different centrifuge bottles with ~15-20 plates of bacteria per bottle.  

Spin down the harvested bacteria at 6000 x g for 15 minutes at 4°C. Isolate plasmid DNA from each bacterial pellet using the Qiagen Plasmid Plus Maxi Kit (Qiagen 12963), using the high-yield volumes with the following protocol modifications:  

- In step 10, wash columns twice with Buffer ETR.  
- In step 11, wash columns three times with Buffer PE.  
- For the final elution step, add 300 uL of Buffer EB to the column, and allow it to sit for 5 minutes before eluting. Then, add the eluate to the column again, allow it to sit for another 5 minutes, and re-elute it to maximize DNA recovery.  

Pool all maxipreps, and measure DNA concentration. Proceed to amplicon library generation to check representation in the plasmid library.  
