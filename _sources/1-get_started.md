# Get started here!



## Welcome!

Synthetic cells are a powerful tool for designing and building biotechnology. Assembling cells “bottom-up” from individually purified components allows us to build defined systems and test every part, enabling modular, scaleable engineering. 

Building a synthetic cell from scratch involves three main processes:

1. Assembling a cytosol.
2. Adding functional modules (encoded in DNA) to the cytosol.
3. Encapsulating the cytosol in a lipid membrane.

Nucleus aims to provide a single, integrated site providing all the open protocols, materials, and tools required to support these processes.

## What’s on Nucleus?

We divide each Nucleus release into four broad categories: 

**Container:** the means to separate the inside of a synthetic cell from its environment.

**Cytosol:** the mixture within a synthetic cell.

**Content:** biological programs which operate in the synthetic cell. 

**Synthetic Cell:** containers, cytosols, and content combined together (”integrated”) into a particular working cell.

You can read more about each category below. For a more detailed discussion of the current status of Nucleus and its contents, please see [What’s new in v0.2.0](https://www.notion.so/What-s-new-in-v0-2-0-71c57989721b4f1f95af1a188907626a?pvs=21).

::::{grid}
:::{grid-item-card} 
<div style="background-color: #d8dcf4; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Container</strong>
</div>
:::
::::

Containers separate the interior of synthetic cells (cytosol and DNA) from the exterior environment. 

```{sidebar} **What’s in Container:**

[Container Documentation](https://www.notion.so/Container-Documentation-240c571e846945428c158d75350e5ffd?pvs=21)

[Container Protocols](https://www.notion.so/Container-Protocols-55946f13bc304b40bf3ca0dc87bd7cd9?pvs=21)
```





The process of putting these interior contents inside a container is called “encapsulation”. There are many types of containers and multiple ways to encapsulate things for any given type of container.

Nucleus currently includes one type of container: lipid vesicles (or liposomes). 

::::{grid}
:::{grid-item-card} 
<div style="background-color: #e8ecdc; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Cytosol</strong>
</div>
:::
::::

Cytosol is the aqueous mixture of all the molecules that you want inside your cell. 

```{sidebar} **What’s in Cytosol:**

[Cytosol Documentation](https://www.notion.so/Cytosol-Documentation-3f6df25b984a4e64b5e3b37a2da8b07e?pvs=21) 

[PURE Protocols](https://www.notion.so/PURE-Protocols-0cd5d3af44aa4d5e85871a75a7c9161b?pvs=21)
```

Cytosols can be very simple (e.g., water plus dye) or extraordinarily complex (e.g., cell lysate). Cytosols provide the molecular machinery and resources for a synthetic cell to work. In order for your cell to do what you want, you have to pick the right cytosol.

If you need transcription and translation, we recommend using PURE, a cell free expression system built from individually purified components. DNA plasmids encoding the thirty-six (36) proteins composing the PURE system, as well as plasmids which operate in PURE, are included in the Nucleus DNA distribution.

If you need a simple cytosol to prototype other processes (e.g., encapsulation) we recommend using water + HPTS, a fluorescent dye (see [Container Protocols](https://www.notion.so/Container-Protocols-55946f13bc304b40bf3ca0dc87bd7cd9?pvs=21) / [Inner and Outer Solutions](https://www.notion.so/Inner-and-Outer-Solutions-34b49e957050422e980002052dd72b80?pvs=21)  for more details).

::::{grid}
:::{grid-item-card} 
<div style="background-color: #f8d4d4; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Content</strong>
</div>
:::
::::

Content means two things: Abstractly, content includes all the biological functions that you might want to augment your synthetic cells with, logically separated into “modules”. Concretely, content also means the explicit implementations of those functions. 


```{sidebar} **What’s in Content:**

[Modules](https://www.notion.so/Modules-20f5eabc66874b26aa361ea0e22ff257?pvs=21) 

[DNA Distribution](https://www.notion.so/DNA-Distribution-6d3e45ae88b84a038828b815ed54e8bc?pvs=21)
```

Nucleus includes both abstract designs of modules and explicit implementations of those modules in DNA. All DNA content on Nucleus is open source and released under the OpenMTA, meaning you can share and remix these sequences as you see fit, for personal, academic, or commercial use.

Nucleus now includes two detector modules: lacO, a lactose responsive expression system; and tetO, a tetracycline responsive system.

Additionally, Nucleus includes a collection of generally useful open source DNA parts, including protein reporters (fluorescent and colorimetric), bacterial promoters and translation initiation sites for building new modules, and an open source plasmid backbone called pOpen. All these parts are designed to be composable with MoClo assembly, and are compatible with a number of other common DNA assembly methods.

::::{grid}
:::{grid-item-card} 
<div style="background-color: #f0dcf4; padding: 0; margin: 0; height: 100%; padding: 1em;">
    <strong>Synthetic cell</strong>
</div>
:::
::::

Synthetic cells are the final result of taking cytosols, adding content, and encapsulating them in a container. Synthetic cells can be as simple as liposomes encapsulating water, as complicated as you like, and one day, we hope, as capable as and more capable than  natural cells.

```{sidebar} **What’s in Synthetic Cell:**

[Booting up a simple synthetic cell](https://www.notion.so/Booting-up-a-simple-synthetic-cell-cbafa6d239714913a3186cd07a9d01aa?pvs=21) 

[Detector cells](https://www.notion.so/Detector-cells-55bf87b1319b448d901a3411c6c31786?pvs=21)
```

Nucleus now includes protocols to make two (2) different types of integrated cells. 

[Booting up a simple synthetic cell](https://www.notion.so/Booting-up-a-simple-synthetic-cell-cbafa6d239714913a3186cd07a9d01aa?pvs=21) 

[Detector cells](https://www.notion.so/Detector-cells-55bf87b1319b448d901a3411c6c31786?pvs=21) 

Getting started? Follow this protocol: [Booting up a simple synthetic cell](https://www.notion.so/Booting-up-a-simple-synthetic-cell-cbafa6d239714913a3186cd07a9d01aa?pvs=21). You will take commercially available cytosol (NEB PURExpress) and encapsulate it in a simple liposome.

Want to implement the detection modules? We are developing the following protocol: [Detector cells](https://www.notion.so/Detector-cells-55bf87b1319b448d901a3411c6c31786?pvs=21) . You will make cells capable of detecting and responding to lactose and tetracycline.

## “Hello, world!”

**Booting up a simple synthetic cell 👋🏾**

If you’re new to building synthetic cells, it can be a challenge to learn multiple new protocols, get them to work, and then get them to work *together*. We recommend practicing these protocols by building the “simplest” synthetic cell. 
<div style="display: flex; justify-content: center; align-items: center;">
    <video width="640" height="480" 
        src="/Users/antonmolina/Documents/code/nucleus-book-local/nucleus-book/videos/syntheticcell_GFP_expression.mp4"
        controls>
    </video>
</div>

The simplest cytosol to start working with with is the PURE system. PURE is a defined set of proteins, RNA, and small molecules that together can transcribe DNA into RNA and translate RNA into proteins. Multiple commercial implementations of PURE are available, but we recommend PURExpress. 

The simplest DNA module to start working with is a fluorescent reporter, like amajLime (included in the Nucleus DNA collection). Whatever module you use, make sure that it has an appropriate promoter for the cytosol that you’ve chosen. PURE expresses proteins under the T7 RNA Polymerase promoter (pT7).

The simplest encapsulation method involves phase-transfer with POPC lipids (mixed with rhodamine tagged lipids for visualization). Once you have all the materials, implementing your first synthetic cell should take a day. A time-lapse video of simple synthetic cells is shown on the right (40x magnification).

Check out [Booting up a simple synthetic cell](https://www.notion.so/Booting-up-a-simple-synthetic-cell-cbafa6d239714913a3186cd07a9d01aa?pvs=21).

## Developing with synthetic cells 🛠️

For full-stack development with synthetic cells, you’ll want to:

- Build defined cytoplasm directly from individual proteins, RNA, and small molecules. Nucleus includes DNA encoding the thirty-six proteins composing the PURE system. Information for getting started can be found here: [PURE Guide](https://www.notion.so/PURE-Guide-0991591e9f474a5bbc934dc141503ae2?pvs=21).
- Develop and test your own modules. Nucleus v0.1 includes a range of DNA module reporters, including validation modules and detector modules capable of simple logic. It also includes a set of level-matched T7 promoters for expression control. Information can be found here: [DNA Distribution](https://www.notion.so/DNA-Distribution-6d3e45ae88b84a038828b815ed54e8bc?pvs=21).
- Encapsulate cytosol and modules. Nucleus v0.1 supports encapsulation with the phase transfer method & fluorescent microscope-based imaging. Get started here: [Container Protocols](https://www.notion.so/Container-Protocols-55946f13bc304b40bf3ca0dc87bd7cd9?pvs=21).
