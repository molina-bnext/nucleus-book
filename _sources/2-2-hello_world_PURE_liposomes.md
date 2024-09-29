# “Hello, world” PURE Liposomes

:::{admonition} **Printable Version**
:class: info
[Nucleus Hello World Liposomes Protocol v0.1.1.pdf](https://prod-files-secure.s3.us-west-2.amazonaws.com/21905bfc-36a0-4d06-a531-33b221812f0e/2305c98e-e106-4602-8e68-49704b80bd04/Nucleus_Hello_World_Liposomes_Protocol_v0.1.1.pdf)
:::

## **Overview**

PURE liposomes are the basis of a synthetic cell that can perform the fundamental operations of biology: transcription, and translation.

In this protocol, you will make the necessary precursors to creating liposomes, assemble a PURE cell-free reaction that will express Green Fluorescent Protein (GFP), and encapsulate it within a liposome. For the outer solution, you will use the same simple sugar solution that was used in [Buffer-in-Buffer Liposomes](https://www.notion.so/Buffer-in-Buffer-Liposomes-c15ada1e2f19426fa955d73138249eb9?pvs=21).

Successfully built PURE liposomes will start dark and then increase in green fluorescence over time as GFP is produced.

There are four key stages to making PURE liposomes:

| Step | Process | Hands-on Time | Total Time | Notes |
| --- | --- | --- | --- | --- |
| 1 | [**Prepare stock buffers and lipids**](https://www.notion.so/Hello-world-PURE-Liposomes-412dfbe9ffd941bfab16b69ec866de27?pvs=21) | 1 h | 4 h | Buffers and lipids may be prepared in advance and used for experiments on subsequent days. |
| 2 | [**Assemble PURE reactions**](https://www.notion.so/Hello-world-PURE-Liposomes-412dfbe9ffd941bfab16b69ec866de27?pvs=21) | 1 h | 1 h |  |
| 3 | [**Encapsulate liposomes**](https://www.notion.so/Hello-world-PURE-Liposomes-412dfbe9ffd941bfab16b69ec866de27?pvs=21) | 2 h | 2 h |  |
| 4 | [**Measure and image**](https://www.notion.so/Hello-world-PURE-Liposomes-412dfbe9ffd941bfab16b69ec866de27?pvs=21) | 1 h | 6–12 h | Total time depends on the exact experiment and incubation conditions. GFP expression should be seen over the first 6 hours at 37C.
 |

## **Materials and Equipment**

| **Name** | **Product** | **Manufacturer** | **Part #** | **Price** | **Link** |
| --- | --- | --- | --- | --- | --- |
| ***Buffers*** |  |  |  |  |  |
| **Glucose** | D-(+)-Glucose, 99% | Thermo Scientific | A16828-36 | **$**41.65 | [[link](https://www.thermofisher.com/order/catalog/product/A16828.36)] |
| **Sucrose** | Sucrose, 99% | Thermo Scientific | A15583-36 | $41.65 | [[link](https://www.thermofisher.com/order/catalog/product/A15583.36?SID=srch-srp-A15583.36)] |
|  |  |  |  |  |  |
| ***Lipids*** |  |  |  |  |  |
| **POPC** | 16:0-18:1 PC 25 mg/mL | Avanti Lipids | 850457C-500mg | $435.00 | [[link](https://avantilipids.com/product/850457)] |
| **Liss-Rhod-PE** | 18:0 Liss Rhod PE 1 mg/mL | Avanti Lipids | 810179P-1mg | $273.47 | [[link](https://avantilipids.com/product/810179)] |
| **Mineral Oil** | Mineral oil, mixed weight | Thermo Scientific | AC415080010 | $53.40 | [[link](https://www.sigmaaldrich.com/US/en/product/sigald/496189)] |
| **Glass Syringe 250 uL** |  | Hamilton | 14-815-238 | $150.15 | [[link](https://www.fishersci.com/shop/products/800-microliter-syringes-rn-termination/14815238)] |
|  |  |  |  |  |  |
| ***PURE*** |  |  |  |  |  |
| **PURE** | PURExpress | NEB | E6800S | $295.00 | [[link](https://www.neb.com/en-us/products/e6800-purexpress-invitro-protein-synthesis-kit)] |
| **RNase Inhibitor** | RNase Inhibitor, Murine | NEB | M0314S | $81.00 | [[link](https://www.neb.com/en-us/products/m0314-rnase-inhibitor-murine)] |
| **DNA** | `pT7-plamGFP PURE` | Nucleus v0.1.0-001 DNA | Well E3 |  | [[link](https://nucleus.bnext.bio/dna-distribution/nucleus-v010-001-distribution-plate)] |

## **Step 1: Prepare Stock Buffers and Lipids**

Stock buffers may be prepared ahead of time, and stored for months. Lipids may also be prepared in advance and stored at 4C for at least 1 month. If you are making buffers and lipids at the same time, begin with the lipids so that they can evaporate while the buffers are being prepared.

### **Prepare lipids in mineral oil**

- [ ]  Clean glass syringes.
    - [ ]  Pour a small amount of 95% ethanol into a glass container ****(e.g. a 10 mL beaker).
    - [ ]  Assemble the glass syringe and prime it by drawing ethanol into the glass syringe, then empty into a waste bottle.
- [ ]  Weight 2.67 g (or pipette 3.25mL) mineral oil into a glass test tube or beaker
- [ ]  Add the lipids to the mineral oil using the appropriate glass syringe:
    - [ ]  Add 250 uL 25 mg/mL POPC.
    - [ ]  *Rinse the syringe with ethanol.*
    - [ ]  Add 10 uL 1 mg/mL Liss Rhod PE.
    - [ ]  *Rinse the syringe with ethanol.*
- [ ]  Evaporate the chloroform from the lipid–oil mixture:
    - [ ]  Place lipid beaker in a 55°C dry bath in a fume hood.
    - [ ]  *(optional)* Shield with aluminum foil to protect from light.
    - [ ]  Evaporate uncovered for 3 h.
- [ ]  Clean syringes and store with plunger removed
- [ ]  Let the sample cool to room temperature in the fume hood.
    - [ ]  If lipids settle towards the bottom, stir them using a 10 uL pipette tip.
    - [ ]  Aliquot the lipid–oil mixture into 1.5 mL aliquots, in glass jars.
    - [ ]  The lipid–oil mixture can be stored for a week or more at room temperature, or up to one month at 4C.
    - [ ]  Invert gently 3 times before use. Make sure the solution is not cloudy.

### **Prepare sugar stock stock solutions**

| Buffer | Target Concentration (M) | MW (kDa) | Weight (g) | Final Volume (mL) |
| --- | --- | --- | --- | --- |
| **3M Glucose Stock** | 3.0 | 180.16 | 5.40 | 10.0 |
| **2M Sucrose Stock** | 2.0 | 342.3 | 10.27 | 15.0 |
- [ ]  Make 3M glucose stock solution:
    - [ ]  Combine 5.40 g glucose and 5.0 mL ddH2O in a 50 mL tube.
    - [ ]  Heat for 15 s in a microwave and mix vigorously to dissolve material completely.
    - [ ]  Add additional MilliQ water to achieve a final volume of 10 mL.
    - [ ]  Filter sterilize while warm using a 0.22 um filter and store at -20 C.
- [ ]  Make 2M sucrose stock solution:
    - [ ]  Combine 10.27 g sucrose and 5.0 mL ddH2O in a 50 mL tube.
    - [ ]  Heat and mix vigorously to dissolve material completely.
    - [ ]  Add additional ddH2O to achieve a final volume of 15 mL.
    - [ ]  Filter sterilize using a 0.22 um filter and store at -20 C.

### **Prepare outer buffer**

- [ ]  Make a 800 mM glucose outer solution:
    - [ ]  Add 1.6 mL 3M glucose stock solution to a 15 mL tube.
    - [ ]  Add MilliQ water to a final volume of 6 mL.
    - [ ]  Vortex vigorously to mix.

## **Step 2: Assemble PURE Reactions**


### **PURE reaction setup**

| **Component** | **Volume (per reaction) (uL)** | Notes |
| --- | --- | --- |
| PURE Solution A | 16 | PURE energy solution: small molecules |
| PURE Solution B | 12 | PURE proteins and ribosomes |
| RNAse Inhibitor | 2 | Prevents RNAse activity |
| `pT7-deGFP` (50 fM, ~100 ng/uL) | 4 | DNA encoding green fluorescent protein |
| 2M sucrose | 6 | Adds density for phase-transfer and matches osmolarity |
| **Total** | **40** |  |
- [ ]  Thaw reagents on ice and then keep on ice.
- [ ]  Prepare a PCR strip in a strip holder, on ice, to assemble reactions into.
- [ ]  For each reaction, assemble by adding the reagents from the table in the order listed:
    - [ ]  Vortex and spin down Solution A, pipette mix, and dispense 16 uL into the reaction tube.
    - [ ]  Briefly spin down Solution B, *gently* pipette mix, and dispense 12 uL. **Do not vortex.**
    - [ ]  Vortex and spin RNAse Inhibitor, pipette mix, and dispense 2 uL.
    - [ ]  Vortex and spin `pT7-deGFP` DNA, pipette mix, and dispense 4 uL.
    - [ ]  Dispense 6 uL 2M sucrose and gently pipette mix the assembled reaction.
- [ ]  Close lids on the PCR tubes and briefly spin down to eliminate bubbles.
- [ ]  *(optional)* Transfer 10 uL of each assembled reaction to a 384-well assay plate for plate reader measurement of the reaction.
- [ ]  Hold assembled reactions on ice until ready for encapsulation.
- [ ]  Return reagents to their appropriate storage locations.
    - [ ]  Add a black dot to the lid of each of PURE Solution A and B. The number of dots indicates freeze–thaw cycles, PURExpress functions well up to 4 cycles.

## **Step 3: Encapsulate PURE into Liposomes**

- [ ]  Set up a microfuge tube rack, with three 1.5 mL microfuge tubes per liposome encapsulation:
    - [ ]  Number the tubes per the number of reactions assembled in Step 2.
    - [ ]  For each reaction, label the three tubes:
        - [ ]  **E**—oil emulsion
        - [ ]  **T**—transfer
        - [ ]  **L**—liposomes


::::{margin}
:::{tip}
:class: dropdown
 We have run reactions with as little as 50 uL outer solution, 50 uL oil phase, and 10 uL inner solution.
:::
::::

- [ ]  Add 150 uL of the lipid / oil mixture to tubes labelled **E**.
- [ ]  Add 150 uL of 800 mM glucose outer solution to each of the tubes labelled **T** and **L**.

- [ ]  Emulsify each reaction in its appropriate oil tube:
    - [ ]  Add 30 uL PURE reaction its matching **E** tube.
    - [ ]  Mix the lipid–oil and PURE reaction by running the tube along a row of empty slots on the microfuge tube holder.
    Run along the row 5–10 times, until the solution forms a stable emulsion and is an even milky color.

::::{margin}
:::{note}
:class: dropdown
 Liposome size is related to the speed and intensity of these two mixing steps. If you want smaller liposomes, you can vortex more aggressively; if you want bigger liposomes you should create the emulsion gently and emulsify for less time.
:::
::::
    
::::{margin}
:::{tip}
:class: dropdown
 Imagine that you’re making a [delicious layered cocktail](https://www.seriouseats.com/how-to-make-layered-drinks-cocktail-technique-pousse-cafe).
:::
::::

- [ ]  Immediately layer each emulsion over the transfer solution.
    - [ ]  Pipette 150 uL from tube **E** slowly down the side of the matching tube **T**.
    

- [ ]  Centrifuge **T** tubes at 9000 g for 10 min at room temperature to pellet the liposomes:
    - [ ]  Align the hinges of each microfuge tube towards the outside of the centrifuge rotor, so that the final pellet location will be indicated by the tube hinge.

::::{margin}
:::{tip}
:class: dropdown
Align the hinges of your microfuge tubes towards the outside of the centrifuge. This provides a visual marker of where the pellet will be in each tube if it is difficult or impossible to see.
:::
::::

::::{margin}
:::{note}
:class: dropdown
If you want smaller liposomes, you can try lower spin speeds.
    
We have tried 3000g and 6000g with success, although the pellet formed is not as stable (it streaks the side of the Eppendorf tube, although the liposomes imaged under the microscope seem the same).
    
Alternatively, if you want very small liposomes (less than 1um in diameter), you can also try letting the liposomes settle for a day. The big liposomes will settle to the bottom, leaving small liposomes floating around on top.
:::
::::

- [ ]  Extract the liposomes from each **T** tube:
    - [ ]  Remove the oil layer from the top of each **T** tube by gently pipetting with a 1000 uL pipette set to 150 uL.
    - [ ]  Identify location of the liposome pellet at the corner of the tube where the side wall angles toward the bottom, directly below the hinge.
    - [ ]  Gently extract liposomes by pipetting 50 uL of pellet and outer solution from beside the pellet location.
    - [ ]  Add the 50 uL liposome sample to the matching liposome tube, **L**.
- [ ]  Hold liposomes on ice until you are prepared to begin measurement.

::::{margin}
:::{tip}
:class: dropdown
- Go slowly due to the viscosity of the oil.
- Attempt to pipette from near the surface of the oil, moving the tip down as the oil is removed. If you pull from directly near the oil-water interface you will draw the lipid layer and the aqueous phase into the pipette.
- It is unlikely that you will be able to remove absolutely all of the oil. Leave as little as possible.
:::
::::

::::{margin}
:::{tip}
:class: dropdown
- Make sure to submerge the oil-covered pipette tip as little as possible into the fresh solution: discard the tip from the previous step and use a new one.
- A smaller pipette tip will pick up less oil from the oil-water interface.
- You may dislodge and resuspend the pellet by gently pipette mixing near the pellet.
- If a pellet is not visible, simply remove 50 uL of the aqueous solution from the bottom of the tube. Ideally, target your pipette to where the pellet would be.
- If your yield is low, directly analyse the 50 uL of solution you removed, without diluting it in the fresh outer buffer.
:::
::::

## **Step 4: Measure Liposomes**

- [ ]  Prepare a 18-well imaging slide for microscopy.
- [ ]  Pipette 20 uL of each liposome sample into a well on the slide.
    - [ ]  Remaining liposomes may be stored on ice or at 4C.
- [ ]  Configure microscope:
    - [ ]  Set magnification to 4x.
    - [ ]  Set up imaging conditions for brightfield, GFP fluorescence (480 nm excitation, 520 nm emission), and Rhodamine fluorescence (540 nm excitation, 580 nm emission).
- [ ]  Place the slide on the microscope and prepare for imaging:
    - [ ]  Find focus by focusing on the edge of a single well in brightfield.
    - [ ]  Locate a well containing a sample of interest.
- [ ]  Move to imaging resolution:
    - [ ]  Switch to rhodamine / red fluorescence imaging.
    - [ ]  Find focus on liposomes just above the coverslip:
        - [ ]  Back focus out until an entire field of liposomes appear to lose focus simultaneously (they are all sitting on the coverslip).
        - [ ]  Slowly move back in until these liposomes are in sharp focus.
    - [ ]  Move up to a higher magnification, and find focus again as described.
    - [ ]  Repeat until you are at an imaging magnification of 20x or 40x.
- [ ]  Capture images of liposomes.

## **Background Protocols**

- [ ]  Prepare lipids for use in encapsulation: [Lipid Preparation](https://www.notion.so/Lipid-Preparation-baed10d160fc410a8b1def6154257b54?pvs=21)
- [ ]  Prepare inner and outer buffers: [PURE inner and outer solution](https://www.notion.so/PURE-inner-and-outer-solution-157a348c3f1e44ffb81538c1e953eb9e?pvs=21)
- [ ]  Prepare [Make Energy Mix](https://www.notion.so/Make-Energy-Mix-c21a30ad7dc140a4aa44bdd9c1bea375?pvs=21)

## **Resources and References**

- Other Protocols
    - The Nucleus protocol simplifies this previous work:[The Build a Cell Phase-Transfer Liposome Protocol](https://github.com/BuildACell/liposome-kit/blob/master/txtl-liposome_water-in-oil.md).
    - [Modified protocol from Miyazaki *et al* on OpenWetWare](https://github.com/BuildACell/liposome-kit/blob/master/txtl-liposome_water-in-oil.md).
    - [Miyazaki protocol on Protocol Exchange](https://protocolexchange.researchsquare.com/article/nprot-3815/v1#/related-articles)
- Papers
    - Fujii, S., Matsuura, T., Sunami, T. *et al.* Liposome display for *in vitro* selection and evolution of membrane proteins. *Nat Protoc* **9**, 1578–1591 (2014) [[link](https://www.nature.com/articles/nprot.2014.107#citeas)]
- Resources
    - Comparative Properties and Methods of Preparation of Lipid Vesicles (Liposomes) ****[[link](https://www.annualreviews.org/content/journals/10.1146/annurev.bb.09.060180.002343)]
    - Liposomes: A Practical Approach [[link](https://www.amazon.com/Liposomes-Practical-Approach/dp/0199630771)]
    - Giant Vesicles: Preparations and Applications [[link](https://chemistry-europe.onlinelibrary.wiley.com/doi/abs/10.1002/cbic.201000010)]

## **Credits**

- Developers
    - [Build a Cell Containers Working Group](https://www.buildacell.org/groups)
    - [Murray Lab](https://www.notion.so/Murray-Lab-498206a6c19444f7a1cee90a528f72d4?pvs=21)
- Testers
    - [Freemont Lab](https://www.notion.so/Freemont-Lab-290158f216024a6f862037ebd7d23183?pvs=21)