# What's new in v0.2

This is the release of v0.2.0, which includes stable Nucleus content (i.e., passing our internal testing and generally working). 

`````{admonition} Release
:class: attention
August 6, 2024
`````

---

In the v0.2.0 release we have validated the Nucleus DNA collection and used it to successfully make PURE; we have upgraded the corresponding [protocols for PURE production](https://www.notion.so/PURE-Protocols-0cd5d3af44aa4d5e85871a75a7c9161b?pvs=21). Nucleus PURE now achieves 70% of the protein yield of commercially-available PURE, and we anticipate its yield to rise as we further optimize the system.

````{sidebar}
```{figure} ./images/v0.2_img1.png
:name: fig1

Increase in performance of Nucleus PURE.
```
````

We have made great strides on the detector cell, demonstrating that the[TetR Inducible Module](https://www.notion.so/TetR-Inducible-Module-6017996fbe48465ea29aee31e8fe7101?pvs=21) works *in vitro* and constructing a first integrated [TetR Detector Cell](https://www.notion.so/Detector-cells-55bf87b1319b448d901a3411c6c31786?pvs=21). We’re presently working on optimizing and further improving functionality, and will be sharing a first protocol in the coming weeks. Work has also begun on our first emitter module: the [Quorum-sensing Emitter](https://www.notion.so/Quorum-sensing-Emitter-0d3ed8a7378242dd9c2a42009bacd629?pvs=21).

In terms of tools, we’ve released the first version of our Kinetics Analysis Toolbox on Github, allowing standard kinetic parameters to be determined from plate reader time series data. This follows on from conversations and community discussions around standard measurement techniques for cell-free and liposome data, and we hope the tool will feed into an emerging information standard for comparable data sharing. We’ve also [shared some data](https://www.notion.so/The-effect-of-DNA-concentration-on-expression-in-liposomes-fa68677f9b1b4e67bd63344f710b4c1d?pvs=21) from our liposome analysis toolbox; we’re still working on making the tool easier to use—expect it in an upcoming release.

```{figure} ./images/v0.2_img2.png
:name: fig2

Kinetic analysis of plamGFP expression in liposomes.
```

Container protocols have been updated for clarity and ease of use, and we have added a [new education module](https://www.notion.so/Liposome-workshop-module-677c525fbb8d4a5e8da2f6f7b46ed3dc?pvs=21) to get started building liposomes and synthetic cells. We used this education module to [teach 6 undergraduates how to make liposomes](https://www.notion.so/Liposome-construction-workshop-at-Caltech-818c58b9b1d143f180e3c31cf1c2d003?pvs=21), with all of the students achieving success.

# New to v0.2.0

::::{grid}
:::{grid-item-card} 
<div style="background-color: #dfe2e8; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Development</strong>
</div>
:::
::::

- Our kinetics analysis toolbox is now available [on GitHub](https://github.com/bnext-bio/nucleus/tree/main/cdk/analysis/cytosol-analysis). This toolbox allows you to analyze time-series plate reader information to derive kinetic parameters such as lag time, maximum velocity, and steady state.

::::{grid}
:::{grid-item-card} 
<div style="background-color: #d7a2e2; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Community</strong>
</div>
:::
::::

- New blog post documenting our workshop at Caltech: [Liposome construction workshop at Caltech](https://www.notion.so/Liposome-construction-workshop-at-Caltech-818c58b9b1d143f180e3c31cf1c2d003?pvs=21). Six undergraduate students successfully made “Hello, world” PURE liposomes in two days.
- Introduces [Nucleus Community Contributions](https://www.notion.so/Nucleus-Community-Contributions-0cc4d80c9448403f9f308b983999bd0e?pvs=21): a place for community members to share Modules and other components that are complementary to the Nucleus Ecosystem.
    - [MphR Sensing Module (Stemloop)](https://www.notion.so/MphR-Sensing-Module-Stemloop-0fbed2b3c77f4350b46174b7218cf224?pvs=21): our first community module. This module uses the allosteric transcription factor MphR to sense macrolides.

::::{grid}
:::{grid-item-card} 
<div style="background-color: #d8dcf4; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Container</strong>
</div>
:::
::::

- Updates Liposome protocols for [Buffer-in-Buffer Liposomes](https://www.notion.so/Buffer-in-Buffer-Liposomes-c15ada1e2f19426fa955d73138249eb9?pvs=21) and [“Hello, world” PURE Liposomes](https://www.notion.so/Hello-world-PURE-Liposomes-412dfbe9ffd941bfab16b69ec866de27?pvs=21) for clarity and to include our latest protocol improvements; updates Bills of Materials; and adds protocol timelines and and printable PDFs of protocols.
- Publishes [The effect of DNA concentration on expression in liposomes](https://www.notion.so/The-effect-of-DNA-concentration-on-expression-in-liposomes-fa68677f9b1b4e67bd63344f710b4c1d?pvs=21). In this post, we varied DNA concentration and measured the effect on GFP expression in liposomes. This post also highlights our liposome analysis toolbox (in-development), and discusses some interesting behavior of populations of liposome.

::::{grid}
:::{grid-item-card} 
<div style="background-color: #e8ecdc; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Cytosol</strong>
</div>
:::
::::

PURE documentation and protocols describing the process for making Nucleus PURE v0.2.0, including: 

- A new end-to-end protocol describing purification and assembly of proteins into PURE protein mix (see [Make Protein Mix](https://www.notion.so/Make-Protein-Mix-78b432dd513d4f2e81a0bdf18e3c8de5?pvs=21)).
- Updated Bills of Materials: now includes all materials used to build Nucleus PURE; updated links, part numbers, and costs; and edits for consistency.
- Updated  [Exchange Buffers and Concentrate by Spin Filtration](https://www.notion.so/Exchange-Buffers-and-Concentrate-by-Spin-Filtration-1b5fcf32943144c4a7a436a9efb173ce?pvs=21) protocol: we now recommend exchanging buffers using centrifugal filters rather than desalting columns.
- New protocols for analysis, specifically documenting the use of a [Pierce660 Assay](https://www.notion.so/Pierce660-Assay-d2328927b1484016805b7fc6692fcdbc?pvs=21) as an improvement over BCA Assay for protein quantification.

::::{grid}
:::{grid-item-card} 
<div style="background-color: #f8d4d4; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Content</strong>
</div>
:::
::::

- Updates Detector modules with clearer design drawings and new implementation data: [Modules](https://www.notion.so/Modules-20f5eabc66874b26aa361ea0e22ff257?pvs=21).

::::{grid}
:::{grid-item-card} 
<div style="background-color: #f0dcf4; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Synthetic cell</strong>
</div>
:::
::::

- Demonstrates a functional TetR Detector Cell. See [Detector cells](https://www.notion.so/Detector-cells-55bf87b1319b448d901a3411c6c31786?pvs=21). We are actively working on further optimization and sharing a first protocol.

## In Development

We are actively developing the following features. They are intended to be fully released in a future release. Keep up to date on the current status of these features by joining our mailing list at [bnext.bio/build](http://bnext.bio/build).

- The Emitter Cell module is under active development, with DNA constructs synthesized and experiments beginning. See [Quorum-sensing Emitter](https://www.notion.so/Quorum-sensing-Emitter-0d3ed8a7378242dd9c2a42009bacd629?pvs=21) for a description of our first Emitter Cell module.
- We are actively onboarding new contributors to the [Nucleus Community Contributions](https://www.notion.so/Nucleus-Community-Contributions-0cc4d80c9448403f9f308b983999bd0e?pvs=21) collection, where people can share information, modules, and other information outside of the main Nucleus distribution. Get in touch if you’d like to contribute.

`````{admonition} Known issues
:class: warning
Two (2) of the PURE genes (ArgRS and LeuRS) were not synthesized for the Nucleus DNA v0.1.0 release and will be included in the v0.2.0 DNA Distribution.
`````

`````{admonition} More information
:class: info
- Code and DNA designs are available on [Github](https://github.com/bnext-bio/nucleus/tree/main).
- To ask questions or participate in the development of Nucleus, join our [nucleus-discuss mailing list](https://groups.google.com/a/bnext.bio/g/nucleus-discuss).
`````