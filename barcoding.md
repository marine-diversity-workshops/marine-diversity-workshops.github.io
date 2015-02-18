---
layout: page
title: Barcoding
---

What is barcoding?
==================

At the supermarket, the cashier scans the barcode of your groceries. The widths
of the black stripes on the produces are read by a scanner and converted into a
number. This number is unique to each grocery so it can be looked up in a
database to determine what it is and its price.

In the early 2000s, a group of scientists from the University of Guelph in
Ontario, Canada, proposed to apply a similar approach to life. They thought that
by using DNA, it should be possible to find a portion of DNA that would be
unique to each species, and therefore that could be used to identify species the
same way a barcode identify groceries at the supermarket.

In animal cells, DNA can be found in the nucleus and in the
mitochondria. Different parts of the DNA evolve at different rates. Some evolve
fast and can be used to distinguish between individuals of the same
species. These are the parts that are used in forensic tests to identify crime
suspects. Other parts evolve really slowly such that the same DNA sequence is
very similar from bacteria to humans. In between these two extremes, a portion
of the mitochondrial genome, the cytochrome oxidase I (COI) has been identified
to evolve at the appropriate rate to be able to differentiate between species
across most animals. This gene is now considered the “barcoding gene”, and
typically about 650 base pairs (the DNA letters) are sequenced.

Protein coding genes such as COI evolve by mutations: base pairs composing the
DNA sequence (A, C, T and G) are substituted by another base pair. Chance and
natural selection interplay, and after multiple generations of interbreeding,
these new mutations will be shared among individuals of the same species.

One of the strengths of barcoding compared to morphologically-based
identification methods is that because it is based on genetics, it tracks the
interbreeding individuals, and therefore match closely our modern species
concept (i.e., “a group of living organisms consisting of individuals capable of
interbreeding and producing fertile offsprings”). However, barcoding is not
without any issues, and can be misleading in some (rare) situations.

How do you obtain barcodes?
===========================

Obtaining the barcode from a animal involves three steps:

- DNA extraction: to separate the DNA from the rest of the cell component and
    makes it available for amplification;
- Barcode amplification: to generate many copies of the barcode so it can be
    sequenced;
- Barcode sequencing: to convert the DNA molecule into a series of letters that
    can be analyzed and be used to identify the organisms from which it’s from.

DNA extraction
--------------

DNA stores the information that the cells use to function. Because of this
critical role, DNA is protected within the cells by the double membrane of the
nucleus or the mitochondrion. Furthermore, because DNA is a long and thin
molecule, it is wrapped around proteins. Therefore, we first need to isolate the
DNA. In other words, we need to make it accessible by breaking down the cell
membranes and dissociate it from the proteins it is attached to.

To this end, a cocktail of chemical products are used to break down the cell
membranes and the proteins: chaotropic salts that destabilize chemical bonds,
detergents to solubilize lipids from the cell membranes and proteins, and
enzymes (mostly proteinases) to denature the proteins. To separate these cell
debris and the DNA, most modern DNA extraction protocols involve a silica
membrane that binds DNA molecules but let the cell debris go through. To remove
any other potential chemical compounds (e.g., sugars, pigments), the membrane is
washed several times. Finally, the membrane is dried and the DNA is released by
eluting it in a buffer with a slightly basic pH to keep the DNA molecule stable
for several years when stored in a freezer.

Here, we will use a faster protocol that doesn’t generate a pure DNA solution
but works very well for barcoding purposes with most organisms. It uses a
combination of heat, proteinases and a chelating ligand called Chelex.

### How to do it?: Protocol for the Chelex Extraction

1.  Sterilize your forceps and scissors by flaming them over an alcohol
    burner. This will remove any contaminants from your instruments.

2.  Cut a small piece of tissue about the size of this dot \( \bullet \) (1
    mm<sup>2</sup> from your sample and place it in a 2 mL tube. Larger tissue
    samples may inhibit your PCR reactions.

3.  Add 150 µL of Chelex bead solution to your 2 mL tube.

4.  Add 10 µL of Proteinase K to your tube.

5.  Spin your tube in the centrifuge for several seconds. Make sure the
    centrifuge is balanced with every tube having a similar tube opposite it.

6.  Incubate your tube at 95°C for at least 20 minutes.

Barcode amplification
---------------------

Once the DNA is isolated, we want to amplify the barcode. The amplification
process produces millions of copies of the barcode. The process of generating
these copies is called PCR (Polymerase Chain Reaction). It uses a mix of
chemical products and enzymes to amplify a specific part of the DNA. This
cocktail needs to include:

- the template: a small amount of your DNA solution that was extracted from your
    sample;

- the primers: these two short fragments of DNA of known sequences will anneal
    (i.e., attach) to the DNA from your sample (template) and target the
    fragment of DNA you wish to amplify;

- the oligonucleotides: a solution of the building blocks of DNA molecules, the
    single letters (A, C, T, G) that will be assembled to create the copies of
    the barcodes;

- the polymerase: this enzyme will assemble the oligonucleotides to create the
    copies of the barcode, using your DNA sample as a template;

- various chemicals that create a suitable environment for the polymerase to
    function properly.

The PCR consists of 3 steps (Fig [fig:pcr]):

- Denaturation: the PCR cocktail is heated to 95°C. At this
    temperature, the hydrogen bonds linking the two DNA strands are dissociated,
    leading to single-stranded DNA.

- Annealing: the temperature is decreased to 45-65°C. This
    temperature is typically too high for the DNA to become fully
    double-stranded but is low enough that the short primer sequences can attach
    specifically to the part of the DNA that matches their sequences.

- Elongation: the temperature is brought back up to 72°C, the optimal
    temperature at which the DNA polymerase functions. The polymerase recognizes
    and attaches to the short double-stranded piece of DNA formed by the DNA
    template and the primer, and starts to use the oligonucleotides found in the
    cocktail to create copies of the barcode using the template DNA from the
    sample.

These steps are repeated 30-40 times, and each cycle doubles the number of new
copies being produced. Therefore, the number of barcodes in the solution
increases exponentially through time. These heating and cooling cycles are
automated and take place in the thermocycler. Typically, the amplification
process takes about 2.5-3 hours.

![1. The DNA template (blue) is denatured by bringing the solution to 95°C. The DNA becomes single-stranded. 2. The temperature drops to 45-65° to allow the primers (in red) to anneal to each DNA strand. The the polymerase (green sphere) attaches to this short fragment of double-stranded DNA. 3.  The temperature goes back up to 72°C for the elongation to take place which creates copies of the barcode (in green). The process is repeated 30 to 40 times, generating an exponentially increasing number of copies of the barcode at each occurrence of the cycle. From: ](500px-PCR)



### How to do it? Protocol for PCR {.message}

Before we start, we need to figure out how much of each reagent we need to use
for our PCR. Each reaction uses a total volume of 25 µL (24 µL of
Master Mix and 1 µL from the DNA extraction).

We use a pre-made Master Mix that needs to be diluted with water, and to which
we will need to add the primers.

For each reaction, we need:

- 12.5 µL of Master Mix

- 1 µL of each primer

- 9.5 µL of water

In addition of our sample, we also try to amplify a tube that does not contain
any DNA to make sure that our Master Mix is not contaminated[1]. If you have 11
extractions to amplify, you need to prepare enough Master Mix for 12 samples[2].

|Reagent|Volume per reaction|Number of samples|Total volume|
|:------|:-----------------:|:---------------:|:----------:|
|Taq Master Mix|12.5|12|150|
|Water|9.5|12|114|
|Primer (forward)|1|12|12|
|Primer (reverse)|1|12|12|

Once you are done with the math, you need to:

1.  Label a 1.5 mL tube “Master Mix”

2.  Label as many 0.8 mL tubes (PCR tubes) as you have samples + 1 for your
    negative control.

3.  Add to the 1.5 mL tube labelled “Master Mix” each reagent (in decreasing
    order of volume as it makes it easier to pipette).

4.  Vortex for 5 seconds and centrifuge briefly the Master Mix

5.  Place the PCR tubes in a rack with ice (or in a cold bloc)

6.  Dispense 24 µL of master mix in each one of the PCR tube, and close
    the negative control as soon as you are done.

7.  Add 1 µL of each of your extraction to the PCR tubes. Be careful to
    avoid contamination (change tips after each sample, close the tubes as soon
    as you put your template in, count to keep track of where you are etc.)

8.  Transfer the PCR tubes to the thermocycler, close the lid, and run the
    appropriate program.

Checking that the PCR worked
----------------------------

After amplification, a small amount of the solution is run on an agarose gel to
determine whether the amplification was successful. A few microliters of the
reaction is mixed with a loading dye solution. The loading dye makes the DNA
solution denser than the solution in which the gel floats so it sinks at the
bottom of the gel. The dye also colors the PCR product, so we can see how fast
it moves through the gel.

After loading the sample, the gel is submitted to an electrical current which
carries the DNA molecules. DNA is negatively charged and will travel towards the
positively charged anode. Larger molecules will move slowly through the gel
while small ones will move faster. Therefore, large molecules will travel less
distance on the gel than smaller ones.

To visualize the DNA, we added a chemical to the gel that binds to the DNA and
makes it fluoresce under ultra-violet light. If the PCR was successful and DNA
was amplified, it will appear as a single band on the gel. Because DNA fragments
of different sizes will move across the gel at different speeds, this process
also ensures that we amplified the correct fragment by checking that it has the
expected length. The approximate length can be inferred by comparison with the
position of a DNA ladder (solution that contains DNA fragments of known
lengths).

### How to do it? Protocol for running a gel

1.  Pour the gel (0.8% agarose gel with GelRed added) in the rig to cover
    generously the bottom (total thickness about 1/4 in)

2.  Position the combs

3.  On a piece of parafilm, use the micropipette to mix for each reaction: 2
    µL of PCR product, and 2µL of diluted loading dye

4.  Once the gel is fully settled (20+ minutes), add TBE buffer to fully cover
    the gel

5.  Load each well with the mix PCR product + loading dye

6.  Run the gel at about 100 V for 20 min

7.  Place the gel on the UV table (don’t forget to wear appropriate eye
    protection)

8.  Take a picture of the gel

Barcode sequencing
------------------

The process of sequencing “reads” the series of nucleotides of the DNA sequence
and converts it to human-readable letters: the A, C, T and G. This is now fully
automated and done in sequencing facilities.

It uses the same approach as the PCR reaction, except that the oligonucleotides
used are modified and include a fluorescing dye. When they are incorporated into
the sequences during the elongation process, the fluorescing dye is released and
emits light. Each type of oligonucleotide (A, C, T and G) emits a different
color which is picked up by the sequencer. The succession of the different
colors provides a signal that is then interpreted by a computer program to
reconstruct the DNA sequence.

### How to do it? Demonstration using Geneious

Unfortunately, the analysis of chromatograms requires proprietary software that
is relatively expensive. For this workshop, I will demonstrate how to use it.


How do you analyze barcoding data?
==================================

For this we will use [SeaView](http://doua.prabi.fr/software/seaview).

Aligning sequences
------------------



### How to do it?

1. Start SeaView and open the alignment file provided
1. Use the space bar and backspace on your keyboard to move the sequences around
   so they align


Building trees
--------------

### How to do it?

1. Click on Trees > Distance Methods
1. Keep the default values and click "Go"


What can you do with barcodes?
==============================

Once the sequence of the barcode has been obtained, there are usually two
scenarios.

In the first case, the name of the species the barcode comes from is known or
can be identified unambiguously. In other words, the whole animal is available
for study and typically deposited in a natural history collection. In this
situation, the barcode will be submitted to a public database alongside with the
information about the specimen: its species name, the collection information,
its picture, and in which museum the specimen is deposited. This sequence can be
used as a reference for other applications.

In the second case, the barcode comes from a piece of the animal, an egg, a
larva or another life stage that do not allow the specimen to be
identified. Usually, in this situation the barcode will be matched against the
available public barcodes and will be used to attempt to put a species name of
the animal the tissue comes from. That is one of the strength of barcoding: it
can work on small parts, even parts that are too small or too in-distinctive to
allow the identification of the animal. However, this approach only works if
there a reference library of the barcodes, in other words if the animal for
which you only have a part has previously been identified and barcoded.

When the animals the tissue come from can be identified
-------------------------------------------------------

### Biodiversity documentation

One of the main effort in barcoding is to document biodiversity. Given the
number of species on Earth, there is a lot of species for which we need to
obtain barcodes that need to be associated with species names, live photographs
and museum vouchers. To have an idea of the variation of the barcodes within
species, it is also important to obtain barcodes from multiple individuals from
a variety of locations.

These barcodes are deposited in public databases so they can be retrieved,
compared and matched with other barcodes generated by the community.

### Species delimitation

Barcodes provide an independent line of evidence that can be used to test
whether morphologically variable forms are effectively reproductively isolated
(i.e., they are different species). Because DNA is passed on through generations
at the time of fecundation, if two populations which are genetically different
do not interbreed, their DNA will not mix and there will be a correlation
between their morphological appearance and their DNA. Using these
characteristics, it becomes possible to determine whether variations seen in
color patterns, habitat preference, behavior, size, and so forth, are simply
intraspecific variation or whether these differences are indicative that the
individuals under consideration actually represent multiple species.

When the animals the tissue come from cannot be identified
----------------------------------------------------------

### Life stages identification

Very often larvae and juveniles look nothing like the adults. They often exhibit
less morphological features which can make their identification particularly
challenging. A tedious, impractical, expansive and often impossible solution
would be to raise the larvae or the juveniles to their adult stages to see the
animal they become. However, as these early life stages carry the same DNA as
their adult conspecifics, if a barcode for the adult form is available, it is
possible to match the barcode from the larvae to the adult form to identify
them. This approach can in turn be used to describe the morphology of the larvae
or to understand better their ecology (e.g., when are the larvae released? Does
it correspond to a particular lunar cycle?)

### Who eats who?

Because barcodes can be obtained from only small pieces of an organism, it is
possible to barcode the stomach content of a predator to identify the preys it
eats. This works particularly well if the preys have been recently eaten and it
has hard parts that can protect some of the prey tissues from the gastric juices
of the predators. For instance, a recent study recently showed that some species
of fish which live inside coral colonies (and therefore hard to observe), have a
very diverse diet of smaller fishes, crabs, shrimps and other crustaceans. This
study was made possible because the vast majority of the invertebrates and
fishes where the study took place had been barcoded.

Does it always work?
--------------------

Barcoding works best when one (or a few) barcode matches exactly one
species. This one-to-one (or many-to-one) correspondence insures that the
barcode is specific to the species to be identified. However if the barcode is
shared by multiple species, it won’t be possible to attribute the species from
which the small piece of tissue the barcode comes from. In the case of species
delineation, it is also an issue as the barcode will not help to attribute a
particular sequence to a particular species. Furthermore, in most cases, these
situations happen in species that are closely related and that might be
difficult to tell apart based on morphological characters.

Two main factors can be responsible for having shared barcodes between species.

- The species diverged very recently, and their morphological appearance had
    time to accumulate differences that make them obvious to tease apart based
    on their morphology. For instance, they might have different
    colors. However, their DNA has not recorded the signature of this recent
    speciation event and does not bear mutations which allow to discriminate the
    two species unambiguously.

- The species are (or have been) inbreeding. They might have stopped
    interbreeding and exchanging genes for some period of time which allow them
    to accumulate mutations on their DNA and differences in their morphology,
    but the barrier that prevented them from interbreeding stopped functioning,
    and they can interbreed again. During the fecundation process, the mum will
    pass on her mitochondrial DNA (and therefore her barcode) to the
    progeny. The offsprings may end up looking like their dad, but will bear the
    signature of being the result of an hybrid crossing because it will carry
    the barcode copy from their mum’s species.

[1] If you are having issues with your amplifications, you may also want to add
a positive control (a sample you know amplified correctly in the past)

[2] If you prepare more than 24 samples, add additional samples to compensate
for the liquid that will be lost during pipetting, count 1 extra for each 24
reactions
