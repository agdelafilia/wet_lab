# gDNA extraction protocol

## Information
A protocol for high-yield, HMW (>40-50 Kbp) gDNA extraction developed by Andrés G. de la Filia in the Konrad Lohse lab (IEB, The University of Edinburgh). This protocol was adapted from a previous version developed by Dominik Laetsch, the 10x Genomics Sample Preparation Demonstrated Protocol and the MagAttract HMW DNA Kit handbook. It was developed for single butterflies but has been successfully used for insect pools (mealybugs, flies) and mammalian tissue (mouse, toad, fish)

## Reagents and consumables
- LoBind 1.5 ml tubes and filter tips (including low binding 200µl filter tips).
- Autoclaved micropestles for 1.5 ml tubes.
- Qiagen Cell Lysis Buffer.
- Proteinase K (20 mg/ml).
- Qiagen Protein Precipitation Buffer.
- RNAse A (100 mg/ml).
- Isopropanol (molecular biology grade).
- 70% ethanol (freshly made on the day, molecular biology grade).
- H<sub>2</sub>O (molecular biology grade, RNase and DNase free)
- Liquid nitrogen, dry ice, ice, centrifuge, shaking heat block, tweezers, sterile razor blades.

## General advice
-	Always use gloves.
-	Before starting, clean workspace (bench surface, ice bucket) and pipettes with 70% EtOH and DNAZap.
-	To maximise DNA yield and avoid contamination, use LoBind tubes and filter tips only.
-	Micropestles should be handled with care to avoid sample contamination. Do not let micropestle tips touch anything (e.g. ice, surfaces, skin) but the sample. Always use a clean (i.e. autoclaved) micropestle for each sample. Keep micropestles in racks, tip-side up.
-	To minimise DNA shearing, pipette slowly. Follow the 5s rule (5s to load tip, 5s to discharge).
-	Mix by inversion = invert tube at least 10 times (25 for thorough mixing). As a general rule, do not mix by vortexing, as it will shear DNA. Gentle vortexing at low speeds, however, will not adversely affect DNA integrity during sample lysis (but absolutely no vortexing from Part 2 onwards).
-	Always spin down tubes on a microfuge before opening.
-	Heating blocks are not to be trusted. Always confirm that the heat block has actually reached set temperature with a thermometer and adjust accordingly.
-	13,300 rpm = 17,000 g

## Workflow

### Part 1: Sample lysis and protein digestion

1.	Recover sample tubes from the freezer and transfer them to dry ice. Keep samples on dry ice when possible until addition of Cell Lysis Buffer.

2.	Flick sample tubes so that material is not located at the bottom of the tube.
    *	Micropestles may not reach the bottom.
    *	More force can be applied if material is on the side of the tube.
    
3.	Crush material using a micropestle (up to 10 up-and-down pushes). Moderate twisting may be used, but up-and-down pushes are always preferable. Depending on sample material, proceed as follows:
  * 3a. For soft material: open sample tubes and add 500µl of Cell Lysis Buffer. Gently crush submerged tissue.
  * 3b. For harder material: submerge sample tubes in liquid nitrogen and gently crush dry material into smaller pieces until tissue defrosts. If needed, tubes may be closed and submerged in liquid nitrogen again for repeated crushing. Once tissue has been broken into small pieces, add 500µl of Cell Lysis Buffer and proceed as in 3a.
  * 3c. For butterflies (and other big samples): too much starting tissue will adversely affect sample lysis efficiency and eventually result in reduced DNA yield. Therefore, to extract DNA from individual butterflies, it is advisable to cut individuals into smaller pieces and process them separately. To do so, submerge sample tubes in liquid nitrogen, take out the specimen with tweezers, place it on a sterile razor blade and cut it into smaller pieces with a second blade (rule of thumb: divide thorax into 2-4 pieces and abdomen, longitudinally, into 2 pieces. Unless absolutely necessary to maximise DNA yield, heads should be avoided due to their high pigment content). Transfer each piece to a new Eppendorf tube and immediately freeze in liquid nitrogen; then proceed as in 3b. Process all tubes in parallel until Part 3, step 1c.
  
4.	Add >=100µl of Cell Lysis Buffer to wash remains of tissue from the tip of the micropestle. A pipette tip may also be used to manually remaining transfer material from the micropestle tip into the buffer.
    *	Total volume should be at least 600µl. An excess of starting material may result in a highly viscous solution, which will reduce the efficiency of proteinase K digestion. If so, increase volume of Cell Lysis Buffer _(note: in subsequent steps, reagent volumes are given for 600µl of Cell Lysis Buffer. Volumes indicated with an asterisk should be adjusted if more Cell Lysis Buffer is added)._ Recommended maximum volume is 900µl, in order to avoid exceeding maximum volume of 1.5ml tubes after adding subsequent reagents.
    
5.	Add 20µl* of proteinase K and thoroughly mix by inversion. Quickly spin down on microfuge.

6.	Incubate samples @ 56°C overnight (12-16h), shaking at 750-900rpm.
    *	Shaking at these speeds during sample lysis will not affect DNA integrity. Alternatively, if no shaking heat block is available, tubes should be inverted/very gently and briefly vortexed whenever possible to disperse tissue (at least once every 20 min during the first 2h).

## Part 2: RNA digestion and protein precipitation

1.	Add 4µl* of RNase A, mix by inversion and spin down on microfuge.
    *	For more thorough removal of RNA, a RNase mix such as Ambion RNase Cocktail can be used instead at an equivalent concentration.
    
2.	Incubate 1h @ 37°C.

3.	Chill sample on ice for 2-5min. Add 200µl* of Protein Precipitation Solution and mix thoroughly by inversion. Quickly spin down on microfuge.

4.	Incubate at least 10min on ice.

5.	Centrifuge for 8 min @ >13,000 rpm, 4°C
   * After centrifugation, proteins should form a tight pellet at the bottom of the tube. If the pellet is absent or loose, transfer supernatant to a new tube taking as little pellet as possible and centrifuge new tube for an additional 2-5min @ >13,000 rpm, 4°.
    *	An additional floating pellet may appear on the surface of the tube. Avoid transferring it with the supernatant.
    *	Centrifugation can be extended up to 30min, but this can adversely affect DNA yield.
    
6.	Carefully transfer supernatant to a new tube.
    *	If supernatant volume is >700µl, split it in two separate tubes and process in parallel until Part 3, step 1c.
    
7.	Add 1 volume of RT isopropanol and mix thoroughly by inversion. Quickly spin down on microfuge.
    *	At this stage, DNA masses may become visible as white threads. However, do not panic if threads cannot be seen (especially for butterflies)—the DNA is there.
    
8.	Incubate DNA. Longer times and lower temperatures during incubation will maximise yield, as this will facilitate precipitation of smaller DNA fragments; however, as a side effect, co-precipitation of salts will also increase. Depending on the type of sequencing, proceed as follows:
  * 8a. For long-read sequencing (e.g. PacBio): Incubate for exactly 10min at RT and proceed to Part 3.
  * 8b. If DNA size is not a concern and yield should be maximised: Incubate for at least 1h (ideally overnight) @ -20°C and proceed to Part 3. An inert carrier (e.g. glycogen) may be added when yield is expected to be low to increase DNA precipitation; for carrier concentration, follow supplier’s instructions.
  
## Part 3: DNA recovery and resuspension

1.	Recover DNA.
  * 1a. If DNA threads can be seen after adding isopropanol: Invert the tube until DNA threats form a floating mass. Fish the DNA mass with a 200µl low binding tip and transfer to a new tube containing 1ml of freshly made, ice-cold 70% ethanol. Incubate for at least 10min on ice.
  * 1b. If DNA threads cannot be seen after adding isopropanol: Centrifuge for 15 min @ >13,000 rpm, 4°C. DNA will be visible as a pellet at the bottom of the tube. Remove supernatant by decanting carefully (beware of the pellet becoming loose!) and add 1ml of freshly made, ice-cold 70% ethanol.
  * 1c. If starting tissue during sample lysis and/or supernatant after protein precipitation were split into several tubes: DNA pellets from the same sample should be merged at this step. Depending on pellet sizes, this can be done in two ways:
      * For bigger pellets: fish DNA pellets from each separate tube (collected as in 1a or 1b, depending on whether DNA threads are visible) with a 200µl low binding tip and transfer them to a new 1.5 tube containing 70% ethanol.
      * For smaller pellets: add 150-250µl of 70% ethanol to the original tubes, after isopropanol removal, load pellets into a 1000µl tip (avoiding abrupt pipetting) and transfer them a new 1.5ml tube.
      * Both methods can be combined for different pellets from the same sample. After this step, all pellets should have been transferred into a single 1.5 tube containing 1ml of 70% ethanol.
   
2.	Invert tube a few times to wash the pellet(s). For large individual pellets, washing may be aided by gently breaking apart the pellet with a 200µl low binding tip. After washing, incubate for 5-10min on ice.

3.	Centrifuge for 5-10 min @ >13,000 rpm.

4.	Carefully remove ethanol with a 1000µl and/or 200µl pipette, without disturbing the DNA pellet.
    *	If fragments of DNA pellet are accidentally carried into the pipette tip when removing ethanol, discharge and wait until DNA settles again on the bottom of the tube.

5.	_(Optional)_ A second wash may be advisable, especially if DNA was incubated at -20°C. After ethanol removal, add 1ml of ice-cold 70% ethanol and wash the pellet by inverting the tube only (do not break apart pellet this time). A new centrifugation can be avoided by incubating on ice for 10min until the pellet has settled at the bottom of the tube; if pellet is fragmented or too loose, repeat step 3. Carefully remove ethanol by pipetting.

6.	Remove residual ethanol by spinning down the tube and removing remaining drops with a 10µl tip, without disturbing the DNA pellet.

7.	Air dry pellet at RT under a fume hood with tube lid open until pellet becomes transparent.

o	Depending on pellet size, drying may take between 10-30min. Avoid overdrying as it will make DNA very difficult to dissolve. Unless strictly necessary, avoid air drying the pellet for longer than 15min.

8.	Resuspend pellet in at least 20µl of water/elution buffer. Incubate 1h-overnight at RT. For longer incubation times, transfer sample to 4°C.

    * For difficult pellets, resuspension might be facilitated by:
      * Very gently mixing by pipetting using a 200µl tip.
      * Gentle tapping on the sides of the tube.
      * Heating at 37-55°C for <30min.
      
9.	Quantify resuspended DNA (Qubit) and check absorbance ratios (Nanodrop) and DNA integrity (0.8-1% agarose gel).


