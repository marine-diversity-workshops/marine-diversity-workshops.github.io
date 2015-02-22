---
layout: page
title: DNA Barcoding
---

What is DNA barcoding?
==================

At the supermarket, the cashier scans the barcode of your groceries. The widths
of the black stripes on the produce are read by a scanner and converted into a
number. This number is unique to each grocery item so it can be looked up in a
database to determine what it is and how much it costs.

In the early 2000s, a group of scientists from the University of Guelph in
Ontario, Canada, proposed to apply a similar approach to life. They thought that
it should be possible to find a portion of DNA that would be unique to each
species, and therefore that could be used to identify species the same way a
barcode is used to identify groceries at the supermarket.

In animal cells, DNA can be found in the nucleus and in the
mitochondria. Different parts of the DNA evolve at different rates. Some evolve
fast to distinguish between individuals of the same species. These are the parts
that are used in forensic tests to identify crime suspects. Other parts evolve
so slowly that they are very similar from bacteria to humans. In between these
extremes, a portion of the mitochondrial genome, the cytochrome oxidase I (COI)
gene has been identified to evolve at the appropriate rate to differentiate
species across most animals. This gene is now considered the “barcoding gene”,
and typically about 650 base pairs (the DNA letters) are sequenced.

DNA evolves by mutations: base pairs composing the DNA sequence (A, C, T and G)
are substituted by other base pairs. Chance and natural selection interplay, and
after generations of interbreeding, new mutations are shared across individuals
of the same species.

One of the strengths of DNA barcoding compared with morphologically-based
identification methods is that because it is based on genetics, it tracks the
interbreeding individuals, and therefore closely matches our modern species
concept (i.e., “a group of living organisms consisting of individuals capable of
interbreeding and producing fertile offsprings”). However, barcoding is not
without issues, and can be misleading in some (rare) situations.

How do you obtain DNA barcodes?
===========================

Obtaining the DNA barcode from an animal involves three steps:

- DNA extraction: to separate the DNA from the other cell components and
    make it available for amplification;
- PCR amplification: to generate many copies of the desired DNA barcode gene fragment so it can be
    sequenced using the Polymerase Chain Reaction (PCR);
- Target sequencing: to determine the sequence of DNA nucleotides in the
    amplified genes, so that they can be analyzed and used to identify the
    organisms.

DNA extraction
--------------

DNA stores the information that cells use to function. Because of this critical
role, DNA is protected within the cells by the double membrane of the nucleus or
the mitochondrion. Furthermore, because DNA is a long and thin molecule, it is
wrapped around proteins. Therefore, we first need to isolate the DNA. In other
words, we need to make it accessible by breaking down the cell membranes and
dissociate it from the proteins it is attached to. Some enzymes in the cells
also attack and digest free DNA (the nucleases) which need to deactivated so
they don't digest our gene of interest.

To this end, a cocktail of chemical products are used to break down the cell
membranes and the proteins: chaotropic salts that destabilize chemical bonds,
detergents to solubilize lipids from the cell membranes and proteins, and
enzymes (mostly proteinases) to denature proteins and in particular the
nucleases. To separate these cell debris and the DNA, most modern DNA extraction
protocols involve a silica membrane that binds DNA molecules but let the cell
debris go through. To remove any other potential chemical compounds (e.g.,
sugars, pigments), the membrane is washed several times. Finally, the membrane
is dried and the DNA is released by eluting it in a buffer with a slightly basic
pH to keep the DNA molecule stable for several years when stored in a freezer.

Here, we will use a faster protocol that doesn’t generate a pure DNA solution
but works very well for barcoding purposes with most organisms. It uses a
combination of heat, proteinases and a chelating ligand called Chelex.

### How to do it? Protocol for the Chelex Extraction

1.  Sterilize your forceps and scissors by flaming them over an alcohol
    burner. This will remove any contaminants from your instruments.

2.  Cut a small piece of tissue (about 1 mm<sup>2</sup>) from your sample and
    place it in a 1.5 mL tube. Larger tissue samples may inhibit your PCR
    reactions.

3.  Add 150 µL of Chelex bead solution to your 2 mL tube.

4.  Add 10 µL of Proteinase K to your tube.

1.  Vortex the mixtures for 20 seconds

5.  Spin your tube in the centrifuge for several seconds. Make sure the
    centrifuge is balanced with every tube having a similar tube opposite to it.

6.  Incubate your tube at 95°C for at least 20 minutes (or at 60°C overnight)

PCR amplification
---------------------

Once the DNA is isolated, we want to amplify targeted sequence (DNA
barcode). The amplification process produces millions of copies of the
barcode. The process of generating these copies is called PCR (Polymerase Chain
Reaction). It uses a mix of chemical products and enzymes to amplify a specific
region of the DNA. This cocktail needs to include:

- template: a small amount of your DNA solution that was extracted from your
    sample;

- primers: two short, manufactured fragments of DNA of a sequence that should
    closely complement the two ends (forward and reverse) of the desired gene
    fragment, thus attach and amplify it;

- oligonucleotides: a solution of the building blocks ("letters") of DNA (A, C,
     T, G) that will be assembled to create copies of the barcode sequence;

- polymerase: this enzyme will assemble the oligonucleotides to create copies of
    the targeted sequence, using your DNA sample as a template;

- various chemicals that create a suitable environment for the polymerase to
    function properly.

The PCR consists of 3 steps (Fig 1):

- Denaturation: the PCR cocktail is heated to 95°C. At this
    temperature, the hydrogen bonds linking the two DNA strands are dissociated,
    leading to single-stranded DNA.

- Annealing: the temperature is decreased to 45-65°C. This temperature is
    typically too high for the DNA to become fully double-stranded but is low
    enough that the short primer sequences can attach specifically to the part
    of the DNA that matches their sequences.

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

![Illustration of the PCR process]({{ site.baseurl }}img/Polymerase_chain_reaction.svg)

<div class="caption"> 1. The DNA template (blue) is denatured by bringing the
solution to 95°C. The DNA becomes single-stranded. 2. The temperature drops to
45-65° to allow the primers (in red) to anneal to each DNA strand. The the
polymerase (green sphere) attaches to this short fragment of double-stranded
DNA. 3.  The temperature goes back up to 72°C for the elongation to take place
which creates copies of the barcode (in green). The process is repeated 30 to 40
times, generating an exponentially increasing number of copies of the barcode at
each occurrence of the cycle. From:
[Wikipedia](http://commons.wikimedia.org/wiki/File:Polymerase_chain_reaction.svg).
</div>

### How to do it? Protocol for PCR

Before we start, we need to figure out how much of each reagent we need to use
for our PCR. Each reaction uses a total volume of 25 µL (24 µL of
Master Mix and 1 µL of DNA template from your extraction).

We use a pre-made Taq Master Mix (that includes oligonucleotides, polymerase,
and other chemicals) that needs to be diluted with water, and to which we also
need to add the primers.

For each reaction, we need:

- 12.5 µL of Taq Master Mix

- 1 µL of each of forward and reverse primers

- 9.5 µL of water

In addition to amplifying our sample, we also want to try to amplify a tube that
does not contain any DNA to make sure that our Master Mix is not
contaminated[1]. So, if you have 11 extractions to amplify, you need to prepare
enough Master Mix for 12 samples[2]. Use the table below as a template to
determine how much of each reagent you need for your reaction (volumes are in
µL):

|Reagent|Volume per reaction|Number of samples|Total volume|
|:------|:-----------------:|:---------------:|:----------:|
|Taq Master Mix|12.5|12|150|
|Water|9.5|12|114|
|Primer (forward)|1|12|12|
|Primer (reverse)|1|12|12|


Once you are done with the math, you need to:

1.  Label a 1.5 mL tube “Master Mix”

2.  Label as many 0.8 mL tubes (PCR tubes) as you have samples with the sample's
    extraction number, plus one more for your negative control.

3.  Add each reagent (in decreasing order of volume as it makes it easier to
    pipette) to the 1.5 mL tube labelled “Master Mix”.

4.  Vortex the Master Mix tube for 5 seconds, and then centrifuge it briefly

5.  Place the PCR tubes in a rack with ice (or in a cold bloc)

6.  Dispense 24 µL of master mix into each PCR tube, and close the negative
    control tube as soon as you are done.

7.  Add 1 µL of each extraction to the PCR tube labeled with that extraction
    number. Be careful to avoid contamination (change tips after each sample,
    close the tubes as soon as you put your template in, count to keep track of
    where you are etc.)

8.  Transfer the PCR tubes to the thermocycler, close the lid, and run the
    appropriate program

Checking that the PCR worked
----------------------------

After amplification, a small amount of the amplified sample is run on an agarose
gel to determine whether the amplification was successful. A few microliters of
the amplified sample is mixed with a loading dye solution. The loading dye makes
the DNA solution denser than the solution in which the gel floats, so it can
sink to the bottom of the gel. The dye also colors the PCR product, so we can
see how fast it moves through the gel.

After loading the sample, the gel is submitted to an electrical current that
drives the DNA molecules in the gel. DNA is negatively charged and will travel
towards the positively charged anode. Larger molecules move more slowly than
small ones, and thus will travel a smaller distance.

To visualize the DNA, we added a chemical to the gel that binds to the DNA and
makes it fluoresce under ultra-violet light. If the PCR was successful and DNA
was amplified, it will appear as a single band on the gel. Because DNA fragments
of different sizes will move across the gel at different speeds, we can also use
this process to check that we amplified the correct fragment, by seeing whether
it has the expected length. The approximate length can be inferred against a
"DNA ladder" (solution that contains DNA fragments of known lengths) loaded into
another unused well.

#### Notes

- If you are having issues with your amplifications, you may also want to add a
positive control (a sample you know amplified correctly in the past)

- If you prepare more than 24 samples, add additional samples to compensate
for the liquid that will be lost during pipetting, count 1 extra for each 24
reactions


### How to do it? Protocol for running a gel

1.  Pour the gel (0.8% agarose gel with GelRed added) in the rig to cover
    the bottom generously (~ 1/4 in deep)

2.  Position the combs to create the wells into which the samples will be
    pipitted

3.  On a piece of parafilm, use the micropipette to mix ~2 µL of PCR product and
    2µL of loading dye from each PCR sample

4.  Once the gel sets (20+ minutes), pull out the combs, turn the gel 90
    degrees, and add TBE buffer to fully cover the gel

5.  Load each well with the mix PCR product + loading dye

6.  Run the gel at about 100 V for 20 min

7.  Place the gel on the UV table (don’t forget to wear appropriate eye
    protection)

8.  Take a picture of the gel

Target sequencing
------------------

The process of sequencing “reads” the series of nucleotides in the amplified DNA
sequence, and converts it to human-readable letters denoting the four bases: the
A, C, T and G. This is now fully automated and done in sequencing facilities.

It uses the same approach as the PCR reaction, except that the oligonucleotides
used are modified to include a fluorescing dye. When they are incorporated into
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

Step 1: Aligning sequences
--------------------------

DNA mutations are rare and there is a lot of DNA in each cell. So, if two
species share a common mutation, it is most likely because they share a common
ancestor.

<!--
here insert drawing that shows 3 sequences and related tree
-->

During the sequencing, the machine that converts the DNA molecule in letters
that can be interpreted by humans has a hard time reading the beginning and the
end of the molecule. Therefore, the sequences obtained do not start or end at
exactly the same position.

<!--
drawing here representing full molecule, what we amplify, what we sequence
-->

However, to infer the phylogenetic relationships among the sequences, we need to
ensure that the base pairs are aligned so we can determine which positions are
the same across sequences, and which positions have changed. These changed
positions will help us decide mutations that can be used to infer shared
ancestry.

<!--
drawing here showing how alignment works
-->

### How to do it?

1. Start SeaView and open the alignment file provided
1. Use the space bar and backspace on your keyboard to move the sequences around
   so they align
1. If you have a large alignment or if you have a difficult time finding
   positions that are conserved enough to build your alignment, you can use one
   of the automated alignment method provided in SeaView:
   - Align > Alignment options, choose `muscle`
   - Align > Allign all


Step 2: Building trees
----------------------

We are going to use the number of base pairs that differ across the sequences in
our sample, and build a tree that will help us visualize these genetic
distances.  Individuals that belong to the same species will have identical
sequences (genetic distance = 0) or very similar sequences, while individuals
belonging to different species will have significative amount of divergence. It
depends of the groups and of the evolutionary of the groups, but typically,
individuals that diverge by more than 2-5% will be different species.

### How to do it?

1. Click on Trees > Distance Methods
1. Keep the default values and click "Go"


Step 3: Interpreting trees
--------------------------

Here we use a basic method (Neighbor-Joining) to build trees that gives good
result with DNA barcoding data if your goal is to (1) identify species limits;
(2) assign sequences to species based on existing sequences. The tree obtained
with DNA barcoding data and this method approximate a phylogenetic tree but is
not reliable to infer relationships among species that are not very closely
related.

Trees such as the one we just generated contain a lot of information, represented
in a compact way.

This is what the program will output:

![Example of a phylogenetic tree]({{ site.baseurl }}img/example_tree_simple.svg)

To understand better this figure and to facilitate its interpretation, we annotated it:

![Example of a phylogenetic tree]({{ site.baseurl }}img/example_tree_annotations.svg)

The red dots represent the internal nodes, the blue dots the terminal nodes
commonly called the tips. The black lines connecting the nodes are the
branches. Branches are

Neighbor-Joining



What can you do with DNA barcodes?
==============================

In order for species to be identified from DNA, they need to be matched against
a sequence coming from an identified specimen.  Thus the first goal of DNA
barcoding is to build a library of sequences linked to identified specimens
(knowns).  Once sufficiently developed, a library allows identification of other
samples simply through their DNA sequences.

In the first case, the species the barcode comes from is known or can be
identified unambiguously. In other words, the whole animal is available for
study, typically deposited in a natural history collection. The barcode will be
submitted to a public database along with information about the specimen: its
species name, collection information, picture, and the location of the deposited
specimen in a collection. This sequence can then be used as a reference for other
applications.

In the second case, the barcode comes from a piece of the animal, an egg, a
larva or another life stage that do not allow the specimen to be identified, or
is taken from a specimen where the specimen was not kept. Usually, in this
situation the barcode will be matched against the available public barcodes and
will be used to attempt to put a species name of the animal the tissue comes
from. This is one of the strengths of barcoding: it can work on small parts,
even parts that are too small or indistinct to permit identification of the
animal. However, this approach only works if there a reference library of the
barcodes, in other words if the animal for which you only have a part has
previously been identified and barcoded.

Building a DNA barcode library
-------------------------------------------------------

### Biodiversity documentation

One of the main goal of DNA barcoding is to document biodiversity. Given the
huge number of species on Earth, much work remains in building barcode
libraries, even for well-known groups and areas. To get an idea of the amount of
DNA sequence variation within species, it is also important to obtain DNA
barcodes from multiple inviduals from a variety of locations.

These barcodes are deposited in public databases
([Genbank](http://www.ncbi.nlm.nih.gov/genbank/),
[BOLD](http://www.boldsystems.org/)) so they can be retrieved, compared and
matched with other barcodes generated by the community.

### Species delimitation

Barcodes provide an independent line of evidence that can be used to test
whether morphologically variable or similar forms are the same or different
species. If two populations that are genetically different do not interbreed,
their DNA will not mix and this will be apparent in different DNA sequences,
even when not indicated by their morphological appearance. Thus DNA sequences
can be used to document species limits, and determine whether variation in color
patterns, habitat preference, behavior, size, and so forth, are simply
intraspecific or indicative of separate species.


Using a DNA barcode library to identify unknowns
----------------------------------------------------------

### Life stages identification

Very often larvae and juveniles look nothing like the adults. They often exhibit
fewer morphological features which can make their identification particularly
challenging. A tedious, impractical, expansive and often impossible solution
would be to raise the larvae or the juveniles to their adult stages to see what
adult they become. However, as these early life stages carry the same DNA as
their adult conspecifics, if a barcode for the adult form is available, it is
possible to match the barcode from the larvae to the adult form to identify
them. This approach can in turn be used to describe the morphology of the larvae
or to better understand their ecology (e.g., when are the larvae released? Does
this correspond to a particular lunar cycle?)

### Who eats whom?

Because barcodes can be obtained from small pieces of an organism, it is
possible to barcode the stomach content of a predator to identify the prey it
eats. This works particularly well if the prey have been recently eaten. For
instance, a recent study recently showed that some species of fish which live
inside coral colonies (and therefore hard to observe), have very diverse diets
of smaller fishes, crabs, shrimps and other crustaceans. This study was made
possible because the vast majority of the invertebrates and fishes where the
study took place had already been barcoded.

Does it always work?
--------------------

Barcoding works best when one (or a few) barcode matches exactly one
species. This one-to-one (or many-to-one) correspondence insures that the
barcode is specific to the species to be identified. However if the barcode is
shared by multiple species, it won’t be possible to identify the source species
exactly.

Two main factors can be responsible for having shared barcodes between species.

- The species diverged so recently that their DNA sequences have not diverged.
This can be either because the DNA of a particular group evolves very slowly
(e.g. in corals), or because the morphology evolves very fast – so we can
distinguish species morphologically before they have evolved distinct DNA
barcodes.  In these cases more involved genetic methods are needed for species
identification.

- The species are (or have been) inbreeding, and thus DNA from one species has
  passed (introgressed) into the other, preventing identification by that part
  of the DNA sequence.  Introgression is especially common with mitochondrial
  DNA, like COI.
