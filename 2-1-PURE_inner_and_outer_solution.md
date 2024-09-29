# PURE inner and outer solution

<aside>
<img src="/icons/light-bulb_gray.svg" alt="/icons/light-bulb_gray.svg" width="40px" /> **Getting Started**

</aside>

Go through this page before entering the lab to guide the design of a prototypical PURE inner solution to be used in liposomes. 

---

<aside>
<img src="/icons/merge_gray.svg" alt="/icons/merge_gray.svg" width="40px" /> **Prerequisite Protocols**

</aside>

- [ ]  Outer solution
    - [ ]  Make energy mix (2.5x): [Make Energy Mix](https://www.notion.so/Make-Energy-Mix-c21a30ad7dc140a4aa44bdd9c1bea375?pvs=21)
    - [ ]  Make glucose stock solution (3M): [Inner and Outer Solutions](https://www.notion.so/Inner-and-Outer-Solutions-34b49e957050422e980002052dd72b80?pvs=21)
- [ ]  Inner solution
    - [ ]  Know how to make assemble a standard PURE reaction: [Assemble PURE Reactions](https://www.notion.so/Assemble-PURE-Reactions-c7ef412d064d4c469313cf77ed81ecb8?pvs=21)
    - [ ]  Make sucrose stock solution (2M): [Inner and Outer Solutions](https://www.notion.so/Inner-and-Outer-Solutions-34b49e957050422e980002052dd72b80?pvs=21)
    - [ ]  Obtain template DNA: [DNA Distribution](https://www.notion.so/DNA-Distribution-6d3e45ae88b84a038828b815ed54e8bc?pvs=21)

## Outer solution for PURE reactions

<aside>
<img src="/icons/iterate_gray.svg" alt="/icons/iterate_gray.svg" width="40px" /> **Protocol**

</aside>

- [ ]  b.next energy solution: contains all small molecules need for performing transcription and translation (no tRNAs)
    - [ ]  200 uL 2.5x energy solution
    - [ ]  227 uL nuclease free water
    - [ ]  73 uL 3M glucose
- [ ]  We recommend storing at -80 C.

---

## Inner solution for PURE reactions

- [ ]  Plan experiment using the following worksheet. The first table describes the master mix the second table describes the reaction conditions for an experiment containing DNA templates encoding for green fluorescent protein and alpha hemolysin.
- [ ]  NOTES: the only difference between a PURE in vitro experiment and PURE in synthetic cells is the inclusion of sucrose such that the density of the inner solution is significantly greater than the outer solution AND such that the osmolarity is approximately 800 mM (500 mM from NEB PURExpress-Sol A+B and 300 mM sucrose). Remember: *PURE reactions in liposomes are Sweet!*
- [ ]  NOTES: in general, PURE reactions should be 10 uL but can be run with an additional 20% volume (i.e., 12 uL). Construct your reaction by adding components in the order in which they’re listed in the table below.

| **Component** | **Reaction Volume (ul)** | **Total Volume (ul)** |
| --- | --- | --- |
| *Master Mix* |  | (5x reactions) |
| NEB-Sol A | 4 | 20 |
| NEB-Sol B | 3 | 15 |
| RNAse Inb. | 0.5 | 2.5 |
| Sucrose (2 M) | 1.5 | 7.5 |
| **Total** | 9 | 45 |

When specifying specific experimental conditions we use the following notation OS-T1T2...-IS, where OS = outer solution; T1, T2,… = DNA template 1, DNA template 2, …; and IS = inner solution. Here is an example where the DNA templates used contain sequences encoding for GFP and aHly:

|  | OS-T1T2-IS | OS-T2-IS | notes |
| --- | --- | --- | --- |
| Master Mix | 9 | 9 |  |
| DNA-aHly | 0.5 | 0.5 | 10 fmol/uL |
| DNA-eGFP | 0.0 | 0.5 | 10 fmol/uL |
| nuc Free H20 | 0.5 | 0.0 |  |
| **Total** | 10 | 10 |  |

<aside>
<img src="/icons/checklist_gray.svg" alt="/icons/checklist_gray.svg" width="40px" /> In progress

</aside>

- Improved osmolarity matching for outer and inner solutions. We have not empirically determined the osmolarity of the outer solution. We have validated that the matching is sufficient to obtain a significant fraction of stable cells.

<aside>
💡 **Credits**

</aside>

<aside>
<img src="/icons/search_gray.svg" alt="/icons/search_gray.svg" width="40px" /> **Developers**

</aside>

- [Murray Lab](https://www.notion.so/Murray-Lab-498206a6c19444f7a1cee90a528f72d4?pvs=21)

<aside>
<img src="/icons/verified_gray.svg" alt="/icons/verified_gray.svg" width="40px" /> **Testers**

</aside>