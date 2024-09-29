# Make protein mix

## **Getting started**

You want to make PURE. You’re going to have to make Protein Mix, which contains the thirty-six (36) proteins in the PURE system. To make Protein Mix, you will need to:

1. Prepare all the materials that you will need,
2. express each protein in an *E. coli* expression strain,
3. purify each protein (by Ni-His affinity columns),
4. quantify their concentration and purity, and
5. combine proteins into a final Protein Mix.

This protocol shows you how to do each of these five (5) steps.

*For more details, or if you want to look at specific subprotocols, see [**Subprotocols**](https://www.notion.so/Subprotocols-13bf76e5a7114bd1aa9356d217f316e1?pvs=21).*

## **Materials and equipment**

| **Name** | **Product** | **Manufacturer** | **Part #** | **Price** | **Storage Conditions** | **Link** |
| --- | --- | --- | --- | --- | --- | --- |
| ***Columns*** |  |  |  |  |  |  |
| Gravity columns | Empty Disposable PD-10 Columns | Cytiva | 17043501 | $258.30 | 4C to 30C | [[link](https://www.cytivalifesciences.com/en/us/shop/chromatography/columns/empty-columns-for-lab-scale/empty-disposable-pd-10-columns-p-06217)] |
| Ni-His Resin | NEBExpress Ni Resin | New England Biolabs |  S1428S | $358.00 | 1C to 4C | [[link](https://www.neb.com/en-us/products/s1428--nebexpress-ni-resin)] |
|  |  |  |  |  |  |  |
| ***Salts (for Buffers)*** |  |  |  |  |  |  |
| Potassium Hydroxide  | Potassium hydroxide - ACS reagent, ≥85%, pellets | Sigma-Aldrich | 221473-1KG | $99.90 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sigald/221473)] |
| Hydrochloric acid (1M) | Hydrochloric acid 1 N, Reagent Grade, Packaging=Amber Bottle, Size=500 mL | VWR | E447-500L | $72.46 | 4C to 30C | [[link](https://us.vwr.com/store/catalog/static_catalog.jsp?catalog_number=97064-756)] |
| HEPES | HEPES, Crystalline Powder, ≥99.5% (titration), Poly bottle | Sigma-Aldrich | H3375-500G | $431 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sigma/h3375)] |
| Imidazole | ReagentPlus® Imidazole, Crystalline, 99% | Sigma-Aldrich | I202-500G | $120 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/aldrich/i202)] |
| Ammonium Chloride | Ammonium chloride,ACS reagent, ≥99.5% | Sigma-Aldrich | 213330-500G | $73.50 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sigald/213330)] |
| Sodium Chloride | Sodium Chloride, Redi-Dri™, anhydrous, free-flowing, ACS, ≥99% | Sigma-Aldrich | 746398-1KG | $133.00 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sigald/746398)] |
| Potassium Chloride | Potassium Chloride, ACS reagent, 99.0-100.5% | Sigma-Aldrich | P3911-1KG | $146.00 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sigald/p3911)] |
| Magnesium Chloride hexahydrate | BioXtra Magnesium chloride, Hexahydrate, Powder or Crystals, ≥99.0% | Sigma-Aldrich | M2670-100G | $50.50 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sial/m2670)] |
|  |  |  |  |  |  |  |
| ***Supplements (for Buffers)*** |  |  |  |  |  |  |
| Glycerol | Glycerol, Molecular Biology Grade, Liquid, ≥99.0% | Sigma-Aldrich | G5516-1L | $157.00 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sigma/g5516)] |
| Lysozyme | Lysozyme from chicken egg white, protein ≥90%, ≥40,000 units/mg protein, lyophilized powder | Sigma-Aldrich | L6876-1G | $76.90 | -25C to -15C | [[link](https://www.sigmaaldrich.com/US/en/product/sigma/l6876)] |
| TCEP-HCl (0.5M; presuspended) | Thermo Scientific, Bond-Breaker® Tris[2-Carboxyethyl]phosphine Neutral Solution (TCEP), Application=Water-Soluble Reducing Agent, Molecular Weight=286.65, Size=5 mL | Thermo Scientific | 77720 | $175.65 | 4C to 30C | [[link](https://www.thermofisher.com/order/catalog/product/77720)] |
| cOmplete Protease Inhibitor | cOmplete™ Protease Inhibitor Cocktail, EDTA-Free, Tablets | Roche | 11873580001 | $472 | 1C to 4C | [[link](https://www.sigmaaldrich.com/US/en/product/roche/coedtafro)] |
|  |  |  |  |  |  |  |
| ***Media*** |  |  |  |  |  |  |
| LB | Luria Broth (Miller's LB Broth), Non-Sterile, 6.8 - 7.2, Molecular Biology Grade, suitable for regular E.coli culture, Powder | Sigma-Aldrich | L3522-1KG | $221 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sigma/l3522)] |
| IPTG | Isopropyl β-D-thiogalactoside (IPTG), Powder, ≥99% (TLC), ≤0.1% Dioxane | Sigma-Aldrich | I6758-1G | $89.90 | -25C to -15C | [[link](https://www.sigmaaldrich.com/US/en/product/sial/i6758)] |
| Kanamycin | BioReagent Kanamycin sulfate, 
≥750 ug/mg, From Streptomyces kanamyceticus, Suitable for cell culture, 
Suitable for plant cell culture, Powder | Sigma-Aldrich | K1377-1G | $47.70 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/sigma/k1377)] |
| ***Misc. Reagents*** |  |  |  |  |  |  |
| Pierce660 Reagent | Pierce™ 660nm Protein Assay Reagent | Thermo Scientific | 22660 | $176.65 | 4C to 30C | [[link](https://www.thermofisher.com/order/catalog/product/22660)] |
| BSA Protein Standard | Pierce™ Bovine Serum Albumin Standard Ampules, 2 mg/mL | Thermo Scientific | 23209 | $81.65 | 4C to 30C  | [[link](https://www.thermofisher.com/order/catalog/product/23209)] |
|  |  |  |  |  |  |  |
| ***Consumables*** |  |  |  |  |  |  |
| Culture tubes | Culture Tube, PS, 14mL, 18x95mm, Sterile, TC Treated, w/ Snap (Vent) Cap | Greiner Bio-One | 191160 | $258.15 | 4C to 30C | [link] |
| 15 mL centrifuge tubes | Corning® 15 mL PP Centrifuge Tubes, Rack Packed with CentriStar™ Cap, Sterile, 50/Rack, 500/Case | Corning | 430790 | $230.44 | 4C to 30C | [[link](https://ecatalog.corning.com/life-sciences/b2b/UK/en/Liquid-Handling/Tubes%2C-Liquid-Handling/Centrifuge-Tubes/Corning%C2%AE-15mL-Centrifuge-Tubes/p/430790)] |
| 10 mL Luer lock syringes | Syringes with BD Luer-Lok® Tip, BD Medical, Syringe with Luer-Lok® Tip, Volume=10 mL | BD Industrial/Difco | 550-80620-PK | $102.40 | 4C to 30C | [[link](https://www.spectrumchemical.com/bd-8482-sterile-luer-lok-8482-tip-general-purpose-syringes-320054)] |
| 0.22 um syringe filters | PES Syringe Filter, 0.22μm, 30mm, Sterile | CELLTREAT Scientific Products | 229747 | $84 | 4C to 30C | [[link](https://www.celltreat.com/product/229747/)] |
| 0.22 um vacuum filters | Corning® 500 mL Vacuum Filter/Storage Bottle System, 0.22 µm Pore 33.2cm² PES Membrane, Sterile, 12/Case | Corning | 431097 | $187.14 | 4C to 30C | [[link](https://ecatalog.corning.com/life-sciences/b2c/US/en/Cell-Culture/Filtration/Vacuum-Filters/Vacuum-Filtration-Systems/p/431097)] |
| 0.45 um syringe filters | PES Syringe Filter, 0.45μm, 30mm, Sterile | CELLTREAT Scientific Products | 229749 | $84 | 4C to 30C | [[link](https://www.celltreat.com/product/229749/)] |
| 15 mL spin filters (3 kDa cutoff) | Amicon® Ultra Centrifugal Filter, 3 kDa MWCO | Millipore Sigma | UFC9003 | $125 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/mm/ufc9003)] |
| 0.5 mL spin filters (3 kDa cutoff) | Amicon® Ultra Centrifugal Filter, 3 kDa MWCO | Millipore Sigma | UFC5003 | $63 | 4C to 30C | [[link](https://www.sigmaaldrich.com/US/en/product/mm/ufc5003)] |
| Tris-Glycine 10—20% gels | Novex™ Tris-Glycine Mini Protein Gels, 10–20%, 1.0 mm, WedgeWell™ format | Invitrogen | XP10205BOX | $120.65 | 1C to 4C | [[link](https://www.thermofisher.com/order/catalog/product/XP10205BOX)] |
| 96-well optical plate | Microplate, 96 well, PS, U-bottom, clear | Greiner | 650101 | $156.14 | 4C to 30C  | [[link](https://shop.gbo.com/en/usa/products/bioscience/microplates/96-well-microplates/96-well-microplates-clear/650101.html)] |
|  |  |  |  |  |  |  |
| ***Glassware*** |  |  |  |  |  |  |
| 250 mL baffled flasks | PYREX® 250 mL Delong Shaker Erlenmeyer Flask with Baffles | Pyrex | 4444-250 | $188.26 | 4C to 30C | [[link](https://ecatalog.corning.com/life-sciences/b2c/US/en/Bioprocess-and-Scale-up/Erlenmeyer-Flasks/Erlenmeyer-Flasks,-Glass/PYREX%C2%AE-Flask-with-Baffles/p/4444-250)] |
| flask closures | Chemglass Life Sciences Closure, 38mm, Stainless Steel | Chemglass Life Sciences | Chemglass Life Sciences Closure, 38mm, Stainless Steel | $100.75 | 4C to 30C | [[link](https://www.fishersci.com/shop/products/sst-closure-38mm-lanced-1/501215156)] |
|  |  |  |  |  |  |  |
| ***Equipment*** |  |  |  |  |  |  |
| Sonicator | Q700 Sonicator | QSonica | Q700A-110 | $5500 | 4C to 30C | [[link](https://www.sonicator.com/products/q700-sonicator?variant=36028875408)] |
| Sonicator Probe | Standard Probe, Replaceable Tip, 1/2” (12.7mm) diameter | QSonica | 4220 | $670 | 4C to 30C | [[link](https://www.sonicator.com/collections/q700-probe-options/products/standard-probes-for-q700-and-q500?variant=36022579984)] |
| Sound Enclosure | Sound Enclosure | QSonica | 432B2 | $995 | 4C to 30C | [[link](https://www.sonicator.com/collections/q700-sound-enclosure/products/sound-enclosure-for-q700-and-q500)] |
| Lab Jack | Fisherbrand™ Lab Jacks (15cmx15cm) | Fisher Scientific | 14-673-51 | $484 | 4C to 30C | [[link](https://www.fishersci.com/shop/products/fisherbrand-lab-jacks-11/1467351)] |
| Gel Tank | Mini Gel Tank | Thermo Fisher | A25977 | $664.65 | 4C to 30C | [[link](https://www.thermofisher.com/order/catalog/product/A25977)] |
| Gel Power Supply | PowerEase™ Touch Power Supply | Invitrogen | PS0120 | $861.65 | 4C to 30C | [[link](https://www.thermofisher.com/order/catalog/product/PS0120)] |
| Plate Reader | BioTek Cytation 5 Cell Imaging Multimode Reader | Agilent | CYT5MFAWSN | Must request quote | 4C to 30C | [[link](https://www.fishersci.com/shop/products/cytation-5-cell-imaging-multi-mode-reader-28/BTCYT5MFAW)] |

## **Step 1: Prepare Materials for Purification**

- [ ]  Make (or buy) the following stock solutions. Use deionized water (e.g., milliQ).
    
    
    | **Reagent** | **MW [g/mol]** | **Amount [g]** | **Final Volume [mL]** | **Storage** | **Needs pH adjustment?** | **Needs Sterilization?** |
    | --- | --- | --- | --- | --- | --- | --- |
    | ***Stock Solutions*** |  |  |  |  |  |  |
    | Potassium Hydroxide (1M) | 56.11 | 14.0 | 250 | 4C to 30C | no | no |
    | HEPES-KOH (pH=7.6; 1M) | 238.3 | 59.5 | 250 | 4C to 30C; dark | yes | no |
    | Imidazole-HCl (pH=7.6; 1M) | 68.08 | 34.0 | 500 | 4C to 30C; dark | yes | no |
    | Ammonium Chloride (1M) | 53.49 | 13.4 | 250 | 4C to 30C | no | no |
    | Sodium Chloride (5M) | 58.44 | 73.1 | 250 | 4C to 30C | no | no |
    | Potassium Chloride (1M) | 74.55 | 18.6 | 250 | 4C to 30C | no | no |
    | Magnesium Chloride (1M) | 203.3 | 20.3 | 100 | 4C to 30C | no | no |
    | Lysozyme (30 mg/mL) | 14320 | 1 | 33 | -25C to -15C | no | no |
    |  |  |  |  |  |  |  |
    | ***Media*** |  |  |  |  |  |  |
    | LB | n/a | 25 | 1000 | 4C to 30C |  | autoclave OR filter (0.22 um) |
    | IPTG (0.5 M) | 238.3 | 1 | 4.2 | -25C to -15C | no | filter (0.22 um) |
    | Kanamycin (50 mg / mL) | 484.5 | 2.5 | 50 | -25C to -15C | no | filter (0.22 um) |
    - **Notes: use hydrated salts when able to and avoid explosions!**
        
        Anhydrous Magnesium Chloride releases a *lot* of energy when dissolved in water, rapidly heating up the solution and causing violent bubbling and sputtering, which can burn you through gloves. 
        
        Magnesium Chloride hydrates (as in, the Magnesium Chloride crystals incorporate water molecules into the crystal structure) do not release as much energy when dissolved and are much safer to work with. 
        
        When calculating how much hydrated salt to use, don’t use the molecular weight of the anhydrous salt. You must consider the water weight as well. Hydrates generally have their adjusted molecular weights labelled on the bottle, but can be calculated by adding 18.02 g/mol for each water molecule.
        
    - **Notes: adjust pH *then* volume.**
        
        HEPES-KOH and Imidazole-HCl must be buffered (pH=7.6) using KOH and HCl, respectively.
        
        First, resuspend HEPES or Imidazole in half the required volume of water. Next, using a pH meter and stirplate, measure pH while stirring. Slowly add KOH or HCl as appropriate to adjust pH to 7.6. Finally, transfer pH adjusted buffers to graduated cylinders and add water to target volume.
        
    - **Notes: store HEPES and Imidazole in the dark.**
        
        HEPES and Imidazole are light sensitive compounds! Keep stock solutions in the dark. Either wrap bottles in aluminum foil OR store bottles in a cabinet.
        
- [ ]  Make the following buffers *in advance* and store at 4C:
    - [ ]  **P1 Wash Buffer** - used to equilibrate all columns and wash samples. P1 Wash Buffer contains a small amount of imidazole (20 mM) to reduce nonspecific protein binding to columns.
        
        
        | Reagent | Final Concentration [mM] | Stock Concentration [mM] | Volume to Add [mL] |
        | --- | --- | --- | --- |
        | HEPES-KOH | 50 | 1000 | 100 |
        | Ammonium Chloride | 100 | 1000 | 200 |
        | Sodium Chloride | 500 | 5000 | 200 |
        | Magnesium Chloride | 10 | 1000 | 20 |
        | Imidazole-HCl | 20 | 1000 | 40 |
        | TCEP | 1 | 500 | 4 |
        | water (milliQ) |  |  | 1436 |
        | **Total** |  |  | 2000 |
    
    - [ ]  **P2 Elution Buffer** - used to elute proteins from Ni-His columns. P2 Elution Buffer contains a large amount of imidazole (500 mM) to displace 6xHis tagged proteins from Ni-His columns.
        
        
        | Reagent | Final Concentration [mM] | Stock Concentration [mM] | Volume to Add [mL] |
        | --- | --- | --- | --- |
        | HEPES-KOH | 50 | 1000 | 12.5 |
        | Ammonium Chloride | 100 | 1000 | 25 |
        | Sodium Chloride | 500 | 5000 | 25 |
        | Magnesium Chloride | 10 | 1000 | 2.5 |
        | Imidazole-HCl | 500 | 1000 | 125 |
        | water (milliQ) |  |  | 59.5 |
        | TCEP | 1 | 500 | 0.5 |
        | **Total** |  |  | 250 |
    - [ ]  **4x P3 Concentrate** - used to prepare P3 Exchange and P3 Storage buffers later.
        
        
        | Reagent | Volume to Add [mL] | Final Concentration [mM] | Stock Concentration [mM] |
        | --- | --- | --- | --- |
        | ***4x P3 Concentrate*** |  |  |  |
        | HEPES-KOH | 100 | 200 | 1000 |
        | Potassium Chloride | 200 | 400 | 1000 |
        | Magnesium Chloride | 20 | 40 | 1000 |
        | water (milliQ) | 180 |  |  |
        | **Total** | 500 |  |  |
        - **Notes: P3 Buffers are compatible with PURE reactions**
            
            The functions of PURE system are sensitive to the types and concentrations of the salts included in the reaction (e.g., [Mg++] can control how much transcription vs translation the PURE reaction will do). Proteins in P1 and P2 Buffer (high [NaCl] and [Imidazole]) cannot be used directly PURE reactions because Na+ and Imidazole affect the function of PURE. 
            
            P3 Buffers replace Na+ with K+ and remove Imidazole. Protein samples are taken out of P2 Elution buffer and put into P3 Exchange buffer, and can then be immediately used. Store proteins at -80C in P3 Storage Buffer, which has 30% glycerol (v/v) added as a cryoprotectant.
            
- [ ]  Make the following buffers *on the same day as use:*
    - [ ]  **Lysis Buffer** - used to resuspend bacterial pellets for mechanical lysis by sonication. Also chemically lyses cells with lysozyme (*G. gallus*). Contains protease inhibitor (cOmplete) to slow proteolysis.
        
        
        | Reagent | Final Concentration [mM] | Stock Concentration [mM] | Volume to Add [mL] |
        | --- | --- | --- | --- |
        | HEPES-KOH | 50 | 1000 | 5 |
        | Ammonium Chloride | 100 | 1000 | 10 |
        | Sodium Chloride | 500 | 5000 | 10 |
        | Magnesium Chloride | 10 | 1000 | 1 |
        | Lysozyme | 0.3 mg/mL | 30 mg/mL | 1 |
        | TCEP | 1 | 500 | 0.2 |
        | cOmplete Protease Inhibitor | 1 tablet / 50 mL | n/a | 2 tablets |
        | water (milliQ) |  |  | 72.8 |
        | **Total** |  |  | 100 |
        - **Notes: Lysis Buffer is unstable at 4C**
            
            We observe that Lysis Buffer stored at 4C will become cloudy over the span of about a week. We believe that this is due to lysozyme aggregating in solution. Lysis buffer should be prepared fresh for use the same day.
            
        
    - [ ]  **P3 Exchange Buffer** - used to remove Na+ and Imidazole from proteins. Filter with a 0.22 um vacuum filter.
    
    | Reagent | Final Concentration [mM] |
    | --- | --- |
    | HEPES-KOH | 50 |
    | Potassium Chloride | 100 |
    | Magnesium Chloride | 10 |
    | TCEP | 1 |
    
    | Reagent | Volume to Add [mL] |
    | --- | --- |
    | 4x P3 Concentrate | 125 |
    | TCEP | 1 |
    | water (milliQ) | 374 |
    | **Total** | 500 |
    - [ ]  **P3 Storage Supplement** - used to protect samples in P3 Exchange buffer from damage by freezing during storage at -80C. Add an equal volume of P3 Storage Supplement to samples in P3 Exchange Buffer (1:1). Filter P3 Storage Supplement with a 0.22 um syringe filter.
    
    | Reagent | Final Concentration [mM] |
    | --- | --- |
    | HEPES-KOH | 50 |
    | Potassium Chloride | 100 |
    | Magnesium Chloride | 10 |
    | TCEP | 1 |
    | Glycerol | 60% (v/v) |
    
    | Reagent | Volume to Add [mL] |
    | --- | --- |
    | 4x P3 Concentrate | 2.5 |
    | Glycerol | 6.0 |
    | TCEP (0.5 M) | 0.020 |
    | water (milliQ) | 1.48 |
    | **Total** | 10 |
    - [ ]  Store all buffer concentrates at 4C until ready to use (up to one month).
- [ ]  Prepare Columns.
    - [ ]  Pack columns.
        - [ ]  We used PD-10 gravity columns, which came with ~ 12 mL gravity columns, plastic filters (to hold the resin bed), plastic bungs (caps for column tips) and plastic lids (caps for column openings).
        - [ ]  Cut column tips off using scissors or a razor blade.
        - [ ]  Pack a filter into the bottom of the column using the back end of a cell spreader.
        - **Notes: the columns have ridges!**
            
            The filter needs to be pushed across two circular ridges on the inside of the column, one ~ 2 cm from the opening of the column and another ~ 5 cm further down the column
            
    - [ ]  Wash empty columns.
        - [ ]  Attach columns to a lab stand by clamp above a beaker (≥ 500 mL) to capture waste flowthrough.
        - [ ]  Wash columns and filters with 5 CV of milliQ water; allow water to flow through.
        - **Notes: “CV” = Column Volume**
            
            One “Column Volume” is equal to the volume of Ni-His resin used in a given column.
            
            e.g., “Wash with 5 CV of P1” ⇒ pour 10 mL of P1 buffer over 2 mL of resin.
            
            Specifying buffer volumes by CVs allows the user to increase or decrease the scale of the purification and still use the same protocol. 
            
    - [ ]  Load and Equilibrate Ni-His Resin into Ni-His columns.
        - [ ]  Resuspend Ni-His resin (50% v/v suspension) by shaking bottle.
        - [ ]  Add 2 mL resin by pipette to each column.
        - [ ]  Equilibrate columns with 10 CV (20 mL) of cold P1 Wash Buffer (4C); allow buffer to flow through.
    - [ ]  Store Columns
        - [ ]  Seal each column with a cap and bung.
        - [ ]  Store columns at 4C until ready for use.

## **Step 2: Express Proteins in *E. coli***

- [ ]  Prep overnight cultures.
    - [ ]  Add 5 mL LB + kanamycin (50 ug / mL) to 15 mL culture tubes. Label each tube.
    - [ ]  Poke your expression strain working stock with a pipette tip.
    - [ ]  Eject the whole tip into each culture tube.
    - [ ]  Incubate cultures overnight at 37C / 250 rpm for between 10 hrs and 16 hrs.
    - **Notes - you can work from glycerol stocks OR fresh colonies.**
        
        We first need to prepare bacterial cultures to induce. We will work from 5 mL overnight cultures of our expression strains and backdilute them the next day. In order to prepare these overnight cultures, we need stocks of bacteria.
        
        We work from 100 uL aliquots of our glycerol stocks, frozen in PCR strip tubes. When seeding our overnights with bacteria, we poked each glycerol stock with a pipette tip and ejected the tip into culture tubes.
        
        Optionally, you can work from individual colonies by streaking out your bacterial stocks onto selective plates (here: Kanamycin at 50 ug / mL). Working from colonies assures that your bulk outgrowth will have come from a single colony forming unit (CFU), which may improve plasmid stability over the course of protein expression.
        
- [ ]  Perform bulk outgrowth.
    - [ ]  Back dilute overnights 1:1000 into fresh media (e.g., add 100 uL of overnight and 100 mL LB with Kanamycin to 250 mL Erlenmeyer flasks).
    - [ ]  Incubate back diluted cultures at 37C / 250 rpm / to mid-log phase (OD600 between 0.4 and 0.6 ~ 3.5 hrs.)
    - **Notes: leave ≥ 2.5x culture volume in headroom!**
        
        Bacteria need breathing room! Oxygenation matters, plus shaking can spill overfilled flasks. Make sure to leave at 2.5 culture volumes worth of headroom. E.g., 
        
        100 mL culture in a 250 mL flask
        
        500 mL culture in a 2 L flask
        
- [ ]  Induce protein expression.
    - [ ]  Once bacterial cultures reach midlog phase (OD600 between 0.4 and 0.6) add IPTG to 500 uM. To do this, we added IPTG from 0.5M aliquots (1000x) at 1:1000.
    
    E.g., for 100 mL of culture, we add 100 uL of IPTG at 0.5M.
    - [ ]  Incubate induced cultures at 37C / 250 rpm / 4 hr to allow cells to express proteins.
- [ ]  Centrifuge cells and freeze pellets.
    - [ ]  While induced cultures are incubating, pre-chill centrifuge and rotor to 4C
    - [ ]  Pour 50 mL of each culture into 50 mL centrifuge tubes and label each (2x50 mL tubes per 100 mL culture).
    - [ ]  Centrifuge cultures at 3200 rcf / 4C / 30 min.
    - [ ]  Decant supernatant and reserve pellets.
    - [ ]  Store pellets at -80C and allow to freeze (at least overnight)
    - **Notes: freezing pellets may help lyse cells.**
        
        Freezing bacterial pellets partially disrupts cell walls and membranes. Anecdotally, freezing bacterial pellets improves lysis at later stages of purification. We have not thoroughly tested this claim, but it makes sense to us.
        
    

## **Step 3: Purify Proteins from *E. coli***

- [ ]  Lyse cells by sonication.
    - [ ]  Prepare centrifuge and lysis buffer.
        - [ ]  Prechill centrifuge and lysis buffer to 4C.
        - [ ]  Finish lysis buffer with TCEP (500x, or 1 mL TCEP per 2 L buffer).
        - **Notes - keep lysate cold to prevent proteolysis!**
            
            Lysis releases any proteases on the cell walls of the bacteria and can degrade the sample. These proteases are less active at colder temperatures; keep samples between 1C and 4C. 
            
            Don’t vortex samples too long without returning them to ice. You want to keep samples as cold as possible to prevent proteases in the bacterial pellet from digesting your proteins!
            
            To check that your sample is fully suspended, vortex the pellet briefly, then hold the tube above your head and look up at the bottom of the tube. You may see either chunks or flecks of the pellet slowly float down to the bottom of the tube, or pellet gunk stuck to the bottom of the tube.
            
            cOmplete and other protease inhibitors reduce the activity of those proteases, and certain expression strains are deficient in endogenous proteases. 
            
            We also have a hunch (that can readily be looked up) that some protein sequences are more sensitive to these proteases than others (I’m looking at you, T7 RNA Polymerase 👀), possibly due to protease recognition sites in the proteins.
            
            All to say, try to reduce proteolysis, or clean up proteolyzed peptides later
            
    - [ ]  Resuspend pellets in cold lysis buffer.
        - [ ]  Thaw bacterial pellets on ice.
        - [ ]  Add 10 mL lysis buffer to each pellet. Resuspend pellets completely by vortexing.
        - [ ]  Transfer resuspended pellets to 15 mL centrifuge tubes
    - [ ]  Lyse cells by sonication.
        - [ ]  Set sonicator to appropriate setting. We lysed cells to a final energy of 12 000J / 40 mL total lysate (50% amplitude, 20s on / 20s s off).
        - [ ]  Put resuspended pellets in an ice bucket. Place samples on a lab jack beneath the sonicator tip(s).
        - [ ]  Adjust sample height using the lab jack such that the sonicator tip(s) are submerged about one quarter (1/4) of the way into the sample (e.g., 2.5 mL into a 10 mL sample).
        - [ ]  Lyse cells by sonication.
        - **Notes - always use a Sound Enclosure during sonication.**
            
            Sonicators produce an intense, high pitched noise during operation. This sound can be dangerous if standing next to the sonicator during operation, and at the very least obnoxious to anyone in the same room.
            
            Always use a soundproof enclosure during sonication to reduce the amplitude of this noise.
            
        - **Notes - avoid foaming during sonication.**
            
            Lysing your cells too aggressively can form a foam at the top of your sample. That foam is presumably lipid and protein coagulating and trapping air as the sonicator blows cells apart. Try to avoid foaming!
            
    - [ ]  Clarify lysates by centrifugation and filtration.
        - [ ]  Centrifuge lysates at 4 krcf / 4C / 45 min.
        - [ ]  (Meanwhile) for each lysate, assemble 10 mL Luer lock syringes and filters (we used 0.45 um for lysates). Pull the plunger out of the syringe, screw on the filter, and leave the plunger outside of the syringe.
        - [ ]  For each lysate, decant the supernatant into syringe and put in the plunger. Plunge lysate through filter into a collection tube (we used 15 mL centrifuge tubes).
- [ ]  Purify proteins by Ni-His affinity column.
    - [ ]  Wash each column with 5 column volumes (”CVs”) of DI water (i.e., 5x 2mL resin bed = 10 mL DI water).
    - [ ]  Equilibrate each column with ≥ 5 CVs (10 mL) cold P1 buffer.
    - [ ]  Load up to 5 CVs (10 mL) clarified lysate per column and allow to flow through. (Optionally) capture flowthrough for later analysis; see  [Pierce660 Assay](https://www.notion.so/Pierce660-Assay-d2328927b1484016805b7fc6692fcdbc?pvs=21)  and [Protein Gel](https://www.notion.so/Protein-Gel-614dc8319e184d66adc578b3fd193121?pvs=21).
        - **Notes: you can load more than 10 mL lysate in tranches.**
            
            If you have more than 10 mL of clarified lysate, you can load tranches of 10 mL at a time, allowing each tranche to flow through before topping off each column. Past a certain point, the resin bed will saturate and you will stop binding more protein. 
            
            You can determine the saturation point of your resin bed by collecting the flowthrough of each tranche and measuring protein concentration by BCA assay or protein gel. You can also increase your saturation point by using a larger resin bed (go to 2 mL).
            
    - [ ]  Wash column with ≥ 5 CVs (10 mL) cold P1 buffer. Allow buffer to flow through. (Optionally) capture flowthrough for later analysis; see [Pierce660 Assay](https://www.notion.so/Pierce660-Assay-d2328927b1484016805b7fc6692fcdbc?pvs=21) and [Protein Gel](https://www.notion.so/Protein-Gel-614dc8319e184d66adc578b3fd193121?pvs=21).
    - [ ]  Elute sample in 2.5 mL cold P2 buffer. Capture flow through in 15 mL centrifuge tube.
        - **Notes: the first 500 uL fraction has little protein.**
            
            We find that our proteins don’t come out in the first 500 uL of our elution. We believe this first fraction is mostly P1 buffer being ejected from the column before P2 + protein can move across the resin bed. There’s nothing wrong with the first 500 uL fraction, it’s just diluting your sample is all.
            
- [ ]  Exchange proteins from P2 Elution Buffer to P3 Exchange Buffer.
    - [ ]  Dilute sample ~ 10x with the final buffer(e.g., 5 mL protein in P2 elution buffer + 45 mL P3 Exchange Buffer).
    - [ ]  Load sample onto the spin column.
    - [ ]  Centrifuge samples at 4000 rcf for 10 min at 4C.
    - [ ]  Repeat loading and spinning until all the sample has been processed.
    - [ ]  Dilute sample ≥ 10x further with the final buffer and repeat loading and spinning until all the sample has been processed.
- [ ]  Store proteins until ready for use.
    - [ ]  Add an equal volume of P3 Storage Supplement to each protein sample (e.g., 100 uL P3 Storage Supplement to 100 uL EF-Tu in P3 Exchange Buffer)
    - [ ]  Mix *gently* by pipetting.
    - [ ]  Store frozen at -80C until ready for use.

## **Step 4: Quantify Protein Yield and Purity**

- [ ]  Assess protein concentration by Pierce660 Assay
    - [ ]  Prepare a standard curve within the assay’s working range (125 ug / mL to 2000 ug / mL). Remember to dilute the BSA stock in the same buffer used for your sample.
        
        
        | Concentration | Volume of BSA Stock (2 mg/mL) | Volume of Buffer |
        | --- | --- | --- |
        | 2 mg/mL | 200 uL | 0 uL |
        | 1.5 mg/mL | 150 uL | 50 uL |
        | 1 mg/mL | 100 uL | 100 uL |
        | 0.75 mg/mL | 75 uL  | 125 uL |
        | 0.50 mg/mL | 50 uL | 150 uL  |
        | 0.25 mg/mL  | 25 uL | 175 uL |
        | 0.125 mg/mL | 12.5 uL | 187.5 uL |
        | 0 mg/mL | 0 | 200 uL |
    - [ ]  Prepare a dilution series of your samples in the same buffer.
        - **Notes: we do 2x serial dilutions**
            
            We like to prepare eight (8) dilutions of our samples in a twofold (2x) dilution series (1x, 2x, …, 128x) by diluting 15 uL of each sample + 15 uL of diluent. 
            
            This range of dilutions (~ 100x) fits on a 96-well plate (one column per sample) and tends to give at least one well in the linear range of the assay for each sample.
            
    - [ ]  Mix Pierce660 Reagent well before use by inversion.
    - [ ]  Array 150 uL of Pierce660 Reagent on a 96 well optical plate.
    - [ ]  Add 10 uL of each sample (BSA standard series and sample concentration series) column-wise (e.g., BSA standard in Column 12, Sample 1 in column 1, …) to the optical plate.
    - [ ]  Cover plate with aluminum foil and mix on a plate shaker at medium speed for 1 minute.
    - [ ]  Incubate plate at 25C for 5 minutes. Samples should turn green.
    - [ ]  Using a plate reader, measure the absorbance of the samples at 660 nm.
    - [ ]  Analyze results.
        - [ ]  Subtract the absorbance of blank samples (e.g., BSA standard = 0 mg/uL) from all other samples (”background subtracted absorbance”).
        - [ ]  Prepare the standard curve by plotting the background subtracted absorbance vs. concentration for each BSA sample.
        - [ ]  Fit the standard curve by linear regression.
        - [ ]  For each dilution series of each sample, choose a dilution in the range of the standard curve.
        - [ ]  Using the linear fit of your standard curve, calculate the concentration of the sample.
- [ ]  Assess protein purity by protein gel.
    - [ ]  Denature samples.
        - [ ]  Label one tube per sample.
        - [ ]  Add 7 uL of 4x sample buffer to each tube.
        - [ ]  Add 21 uL of each sample to its tube. Mix by pipetting.
        - [ ]  Incubate samples at 90C / 10 min.
    - [ ]  Set up gel box.
        - [ ]  Open an individually wrapped protein gel (we use 10% - 20% Tris Gly gels). Throw out the bag that the gel came with.
        - [ ]  Remove plastic tape at bottom of gel. This exposes a strip of gel to buffer, allowing current to flow through the gel and out the bottom.
        - [ ]  Place gel in gel box and seal tightly.
        - [ ]  Pour running buffer (we use Tris Gly) into the front half of the gel box reservoir. Check to make sure that the gel is tightly sealed (i.e., no buffer can run from the front to the back of the gel box).
        - [ ]  Pour running buffer into the back half of the gel box reservoir.
        - [ ]  Remove comb from top of gel.
    - [ ]  Load between 10 uL and 20 uL of sample onto each lane of the gel. Remember to include a protein ladder!
    - [ ]  Run the gel. We use 150 V / 60 min.
    - [ ]  Stain and destain the gel.
        - [ ]  Using a gel knife (looks like a paint can opener), pop open the plastic cassette holding the gel.
        - [ ]  Poke the gel out of the plastic box by pushing the gel knife through the exposed strip of gel on the back of the plastic cassette. This step is easier if the gel knife is wet.
        - [ ]  Briefly rinse the gel in milliQ water.
        - [ ]  Submerge gel in a rapid staining protein stain in a waterproof container. Incubate gel at room temperature with rocking for up to 1 hr.
        - [ ]  Decant staining solution, rinse gel at least once, then submerge gel in milliQ water. Incubate gel at room temperature with rocking for 15 min.
        - [ ]  Repeat above step until bands are clearly visible (we do three destaining steps).
    - [ ]  Observe gel.
    - **Note: use an imager to semi-quantitate!**
        
        You can see protein bands with the naked eye at this point of the protocol. If all you want is a qualitative measurement of protein concentration and quality, that can be done right now. That said, using a nice gel imager will allow you to take high resolution photos of your gel, allowing you to semi-quantitate band intensities (and thus protein concentrations) as well as migration distance (and thus protein molecular weights).
        
    

## **Step 5: Assemble Protein Mix**

- [ ]  Calculate how much volume of each protein stock is needed for a given final volume of Protein Mix (here: 100 uL)
    
    
    | **#** | **Protein** | **Protein Mix Concentration [ng/uL]** | **Stock Concentration [ng/uL]** | **Volume to Add per 100 uL Protein Mix [uL]** |
    | --- | --- | --- | --- | --- |
    | 1 | AlaRS | 538 |  |  |
    | 2 | ArgRS | 15 |  |  |
    | 3 | AsnRS | 169 |  |  |
    | 4 | AspRS | 62 |  |  |
    | 5 | CysRS | 9 |  |  |
    | 6 | GlnRS | 29 |  |  |
    | 7 | GluRS | 97 |  |  |
    | 8 | GlyRS | 74 |  |  |
    | 9 | HisRS | 6 |  |  |
    | 10 | IleRS | 308 |  |  |
    | 11 | LeuRS | 31 |  |  |
    | 12 | LysRS | 49 |  |  |
    | 13 | MetRS | 18 |  |  |
    | 14 | PheRS | 131 |  |  |
    | 15 | ProRS | 77 |  |  |
    | 16 | SerRS | 15 |  |  |
    | 17 | ThrRS | 48 |  |  |
    | 18 | TrpRS | 48 |  |  |
    | 19 | TyrRS | 5 |  |  |
    | 20 | ValRS | 14 |  |  |
    | 21 | IF1 | 77 |  |  |
    | 22 | IF2 | 308 |  |  |
    | 23 | IF3 | 77 |  |  |
    | 24 | EF-G | 385 |  |  |
    | 25 | EF-Tu | 3846 |  |  |
    | 26 | EF-Ts | 385 |  |  |
    | 27 | RF1 | 77 |  |  |
    | 28 | RF2 | 77 |  |  |
    | 29 | RF3 | 77 |  |  |
    | 30 | RRF | 77 |  |  |
    | 31 | MTF | 154 |  |  |
    | 32 | CK | 31 |  |  |
    | 33 | MK | 23 |  |  |
    | 34 | NDK | 8 |  |  |
    | 35 | PPiase | 8 |  |  |
    | 36 | T7RNAP | 77 |  |  |
    |  | **Total** | **7430** |  |  |
    - **Notes: if your Protein Mix is dilute, you can concentrate it**
        
        If your protein stocks are dilute, you may be required to add more volume of each stock than you’d like. This results in a Protein Mix with the right ratios of each protein, but that is more dilute than designed.
        Don’t worry! You can always concentrate your final Protein Mix to your target volume. See [Exchange Buffers and Concentrate by Spin Filtration](https://www.notion.so/Exchange-Buffers-and-Concentrate-by-Spin-Filtration-1b5fcf32943144c4a7a436a9efb173ce?pvs=21) for details. We routinely design and build our Protein Mix assemblies at low concentrations, then bring them to the desired concentration later.
        
- [ ]  Aliquot Protein Mix (e.g., eight (8) PCR tubes of 12.5 uL each) and store at -80C until ready for use.

## **Subprotocols**

- [ ]  Prepare buffers, media, and columns for purification: [Prepare Columns](https://www.notion.so/Prepare-Columns-a2ac52c22832487aafca3a8aa167db00?pvs=21) and[Make Protein Purification Buffers and Media](https://www.notion.so/Make-Protein-Purification-Buffers-and-Media-9d2ac519c37e4300b7e2c01bf74515a6?pvs=21)
- [ ]  Express proteins for purification: [Grow and Induce Expression Strains](https://www.notion.so/Grow-and-Induce-Expression-Strains-71ab2becdb564b16ab31907e065569f8?pvs=21)
- [ ]  Prepare cell lysate for purification from frozen cell pellets: [Lyse Bacteria by Sonication](https://www.notion.so/Lyse-Bacteria-by-Sonication-9612afcc01604625ba199ad3a089b607?pvs=21)
- [ ]  Purify proteins from cell lysate: [Purify Proteins by Ni-His Gravity Column](https://www.notion.so/Purify-Proteins-by-Ni-His-Gravity-Column-251b00fd8a8948d1a48de02350ea08ae?pvs=21)
- [ ]  Get your purified proteins in the right buffer at the right concentration: [Exchange Buffers and Concentrate by Spin Filtration](https://www.notion.so/Exchange-Buffers-and-Concentrate-by-Spin-Filtration-1b5fcf32943144c4a7a436a9efb173ce?pvs=21)
- [ ]  Measure the yield and purity of your proteins: [Protein Gel](https://www.notion.so/Protein-Gel-614dc8319e184d66adc578b3fd193121?pvs=21) and [Pierce660 Assay](https://www.notion.so/Pierce660-Assay-d2328927b1484016805b7fc6692fcdbc?pvs=21)
- [ ]  Assemble protein mix from purified proteins:[Assemble Protein Mix](https://www.notion.so/Assemble-Protein-Mix-f9c91a6cf1b54ab99b9f1dbd4aab1de0?pvs=21)

## **Resources and References**

- Papers
    - Original PURE paper
    
    [Cell-free translation reconstituted with purified components](https://doi.org/10.1038/90802)
    
    - OnePot PURE
    
    [A Simple, Robust, and Low-Cost Method To Produce the PURE Cell-Free System](https://doi.org/10.1021/acssynbio.8b00427)
    
    [OnePot PURE Cell-Free System | Text Page](https://dx.doi.org/10.3791/62625)
    

## **Credits**

Yan Zhang, Zoila Jurado, and Miki Yun (Richard Murray Lab, Caltech)

- Developers
    - [Murray Lab](https://www.notion.so/Murray-Lab-498206a6c19444f7a1cee90a528f72d4?pvs=21)
    - [Freemont Lab](https://www.notion.so/Freemont-Lab-290158f216024a6f862037ebd7d23183?pvs=21)
    - [Shimizu lab](https://www.notion.so/Shimizu-lab-501c98e185a048c988f8a9ee0a5cb38a?pvs=21)