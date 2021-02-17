# Oligo Pool Amplification Protocol

**Protocol typed up by Evan Hass, edits by Erika Lasda**  
**Last modified 2020-05-07**  

## A: ePCR  
1. Combine emulsion components 1, 2, and 3 from the Chimerx Micellula Emulsion & Purification (ePCR) Kit (FisherSci NC1117239) as follows:  

Component | for 1x 300 uL reaction | For 10 reactions
--- | --- | ---
Emulsion Component 1 (~73%) | 220 uL | 2.2 mL
Emulsion Component 2 (~20%) | 60 uL | 600 uL
Emulsion Component 3 (~7%) | 20 uL | 200uL

2. Mix thoroughly by vortexing, then keep on ice until step 4.  
3. Make PCR water phase mix on ice:  

Component | for 1x 50 uL reaction | For 9 reactions
--- | --- | ---
Nuclease-free water  | 30 uL | 270 uL
NEB 5x Q5 Buffer (NEB M0491) | 10 uL | 90 uL
10 mM dNTP mix | 1 uL | 9 uL
10 uM primer mix | 2.5 uL | 22.5 uL
Acetylated BSA (0.1 ug/uL, Fisher AM2614) | 5 uL | 45 uL
Oligo pool DNA (1 ng/uL) | 1 uL | 9 uL
Q5 High-Fidelity DNA Polymerase (NEB M0491) | 0.5 uL | 4.5 uL

**_Primer Design_**  
As of the writing of this protocol as a markdown file (2020-05-01), all of our lab's oligo pools are designed such that the following primer sequences will fit the purpose of this PCR:  

**Fwd Primer:** TAGTA[restriction site]ACTGGCCGCTTCACTG (JR1 in our primer database is of this design with an AgeI cut site)  
**Rev Primer:** TAGTA[restriction site]CGACGCTCTTCCGATCT (JR2 in our primer database is of this design with a NotI cut site)  

4. Add 300 uL of emulsion mix to each of 8 1.5-mL low-binding tubes  
5. Add 50 uL of the PCR water phase mix to each low-binding tube (keep the remaining 50 uL for a control reaction), and mix by inverting a few times  
6. Vortex tubes for 5 minutes at 4°C using Vortex Genie with Horizontal Microtube Holder (FisherSci 50728070)
7. Split the contents of each 1.5-mL tube into 3 tubes of a PCR strip  
8. Transfer the remaining 50 uL of PCR water phase mix to a separate PCR tube for the control reaction  
9. Run the following program in the thermal cycler:  

- 94°C for 0:30  
--- --- --- --- ---
- 94°C for 0:10 |  
- 57°C for 0:10 | **30 cycles**  
- 72°C for 0:10 |  
--- --- --- --- ---
- 72°C for 2:00  
- Hold at 4°C  

## B: ePCR DNA recovery

1. Add 1 mL butanol to 8 2-mL low-binding tubes  
2. With a p200 set at 150 uL, transfer the contents of all 3 PCR tubes for a given reaction into 1 butanol-containing tube (**_DON'T DISCARD THE PCR TUBES YET_**)  
3. For each reaction, transfer 150 uL of butanol from the 2-mL tube back to the first PCR tube, then to the second and third, mixing by pipetting each time to disolve all remaining emulsion in each PCR tube. Then transfer from the third PCR tube back into the 2-mL tube.  
4. Vortex all 2-mL tubes until the solution becomes transparent  
5. Add 400 uL of Orange-DX buffer (from the Chimerx ePCR Kit) and mix by gentle agitation (by hand or on a rotator for 2 minutes)  
6. Spin down at 16,000 x g for 2 minutes  
7. Remove the upper organic phase (it should be approximately 1.2-1.3 mL), leaving a small volume on top of the interphase (to avoid getting any of the bottom water phase), and transfer it to a clean tube to store at 4°C until completion of the purification  
8. Add 40 uL of activation Buffer DX onto the spin column (both from the Chimerx kit) and keep it at room temperature (do not spin)  
9. Transfer all of the aqueous phase and interphase (max 600 uL) into a spin column/receiver tube assembly, and spin at 12,000 RPM for 1 minute. Discard flowthru, and if more sample needs to be loaded, repeat until all sample has been loaded onto the column.  
10. Add 500 uL of Wash-DX1 buffer (from the Chimerx kit) and spin at 12,000 RPM for 1 minute. Discard flowthru.  
11. Add 650 uL of Wash-DX2 buffer (from the Chimerx kit) and spin at 12,000 RPM for 1 minute. Discard flowthru.  
12. Spin again at 12,000 RPM for 2 minutes to remove excess Wash-DX buffer  
13. Place spin column into new 1.5-mL low-binding tube and add 50 uL of Elution-DX buffer (from the Chimerx kit) to the column  
14. Incubate for 2 minutes at room temp, then spin at 12,000 RPM for 1 minute  
15. Discard spin columns, and pool all eluted ePCR DNA into a single tube. Store at -20°C.  

## C: 1.6X SPRI bead clean up (to remove DNAs <100 bp in size)
Before starting, warm AMPure XP beads (Beckman Coulter A63881) to room temp for 30 minutes, and make fresh 80% ethanol.  

1. Determine exact sample DNA volume for each sample (probably 40 uL – 400 uL) and calculate 1.6X volume beads to use (64 uL – 640 uL). Record volumes. Add 1.6X volume of vortexed AMPure beads (640 uL beads to 400 uL of eluted DNA from the ePCR DNA recovery), and mix by pipetting (gently to minimize foaming)  
2. Incubate for 10 minutes at room temp  
3. Pull down beads on magnet for 2 minutes (or longer until supernatant is clear)  
4. Discard supernatant, and keep tube on magnet  
5. Add 200 uL 80% ethanol, incubate for 30 seconds, keeping on magnet, and discard ethanol (use p200 to aspirate)  
6. Repeat step 5, and discard all ethanol (use p200, then p20 or p10 to aspirate)  
7. Dry beads at room temp for 5 minutes (or longer based on the beads volume)  
8. Add 32 uL nuclease-free water to beads, and mix by pipetting (gently to minimize foaming)
<br> *(optional) For increased concentration, add 22 uL instead*
9. Incubate for 2 minutes at room temp  
10. Pull down beads on magnet for 2 minutes (or longer until supernatant is clear)  
11. Transfer 30 uL of supernatant to a new pre-labeled low-binding tube
<br> *(optional) transfer 20 uL instead* 
12. Repeat steps 8-10 to recover all of the cleaned pool  
13. Transfer 30 uL of the supernatant to the tube from step 11 
<br> *(optional) tilt plate to recover all elution without transferring any beads*

Use 1 uL of cleaned-up ePCR to measure DNA concentration on the Qubit using the dsDNA HS Kit (Thermo Fisher Q32854). Then, dilute to ~0.5 ng/uL and run 1 uL on the Bioanalyzer (HS DNA Kit, Agilent 5067-4626) to check for a product of the expected size. Proceed to amplicon library generation to check oligo pool representation.  
