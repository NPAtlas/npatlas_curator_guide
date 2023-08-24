---
layout: default
title: FAQ
nav_order: 3
---

# Frequently asked questions

Introduction
------------

Thank you for participating in data curation for the Natural Product Atlas! The Atlas is available at [npatlas.org](npatlas.org), please sign up and have a look around.

For a tutorial on how to use the Curator, watch [this video](https://youtu.be/DMpSUehCOI4).

FAQ
---

#### Compounds

Q: _“The reference for my compound is not about natural products. Should I reject this article?”_

A: Yes. We are curating on an article basis, so you can reject papers that do not report new microbial NPs.

* * *

Q: _“This compound is in the paper as a new compound, but the structure is all garbled/ wrong”_

A: If the structure is corrupted, try and find the right structure from Pubchem and replace the SMILES string. If the structure doesn’t match the paper try searching Pubmed for structure revisions before correcting. This is a bit confusing, but we want the original isolation reference in all cases (even if the structure was subsequently revised). We will also find all reassignment references. If you have found a reassignment reference, please say this in the notes box, check ‘needs work’ and submit.

* * *

Q: _“The double bonds in the structure have wiggly lines”_

A: This is a known bug in our software display tool. We’re working on it. It is OK to submit these.

* * *

Q: _“Amide bonds in the structure look strange (wrong tautomer)”_

A: This is a problem that you need to fix. Please try to find the correct structure, or check ‘needs work’ and add ‘wrong tautomer’ in the notes field.

* * *

Q: _“The compound has a water/ HCl/ second molecule/ MeOH in the image”_

A: We need to fix this. Please find the right SMILES and replace, or paste the SMILES into Chemdraw, fix, and copy the corrected SMILES back into the curator.

* * *

Q: _“The paper contains both new and known compounds. Do you want me to add them all?”_

A: No thank you. We only want the new compounds. Sometimes it can be tricky to figure out what is new and what is known. Please read the introduction carefully if you are not sure.

* * *

Q: _“This is not an original isolation but it is the first time that the compound has been found naturally from a microbial source. Should I curate this?”_

A: Yes as this should be the first appearance the compound will have in the atlas.

* * *

Q: _“How should I approach enantiomers”_

A: If they have actually been separated please put them as separate compounds. If not then put them as (±)-compound A.

* * *

Q: _“The paper is not an original isolation paper but it is the first time that the enantiomers have been separated. Should I curate this?”_

A: If it is not already in the atlas then include. If it is then flag this as "needs work".

* * *

Q: _“The new compound does not have a name. What should I call it?”_

A: If there is no trivial or IUPAC name at all, or if it is only called ‘compound 1’ then please put the name as ‘Not named’.

* * *

Q: _“I have come across a new compound structure but the name has been used before (e.g. Aspergilline A has been ‘discovered’ twice, but each with a different structure).”_

A: Curate this anyway, would be helpful if you could leave a comment regarding this in the notes box.

* * *

Q: _“Should the compound be added to the atlas if the paper only shows partial elucidation of the structure? e.g.: missing functional groups”_

A: Disregard compounds that do not have the full structure elucidated. We will accept papers that provide the full planar structure even if the stereochemistry is unknown, but not papers where there is ambiguity about the structure itself.

* * *

Q: _“What should I do if a compound that was newly discovered by a paper has the same structure as a compound that was characterized in a previous paper but has a different name and source organism? (both reported as new) ”_

A: Make sure that the compounds are identical (they could potentially have different stereochemistry) and if they are identical, report the one that was the first to be discovered.  Please also add a  note that there is another paper with a synonym, and give the other citation and name in the notes.

* * *

Q: _“The compounds were not properly isolated, but annotated with MS. Should I reject this paper?”_

A: In general, we reject MS-only papers. The only exception are cases where one compound was fully solved with MS and NMR and then other members were solved using MS. In those cases we will accept them all.

* * *

#### Citations

Q: _“The citation data is correct, but the doi is missing”_

A: This is OK. Click submit and move on. We will fix missing doi’s using an automated script.

* * *

Q: _“Everything is OK, but the issue number is missing”_

A: This is OK. Click submit.

* * *

Q: _“This is an ejournal that doesn’t have volume/ issue/ page numbers”_

A: Add the doi to the doi box and put the rest of the information in the page numbers box.

* * *

Q: _“The author list also has a bunch of unrelated citation data in it”_

A: Please delete this. Author list should be authors only.

* * *

#### Source organisms

Q: _“What source organisms should I include?”_

A: Include: bacteria, fungi, yeast, mushrooms, lichen, cyanobacteria.
   Disregard: plants, animals, insects, corals, protists, phytoplankton.

* * *

Q: _“The authors only report the taxonomy to the genus level”_

A: This is OK. Put ‘Streptomyces sp.’ (or whatever the genus is) in the source organism box.

* * *

Q: _“The source fungus/ bacterium was not identified at all”_

A: Put ‘unknown bacterium’ (or fungus) in the source organism box.

* * *

Q: _“The fungus is a plant endophyte. Should I include the plant in the list of sources?”_

A: No. We are only capturing data about the actual microbial source organisms.

* * *

Q: _“Should I include the strain?”_

A: Yes. You should this like the following "*Talaromyces sp. SCSIO 041201*".

* * *

#### Fermentation Methods

Q: _“Is culturing the same isolate under different fermentation conditions OK?”_

A: Yes, this is fine.

* * *

Q: _“What about feeding cultures with NaBr to make brominated products?”_

A: This is in a grey area, but we decided to include these compounds.

* * *

Q: _“What about the use of elicitors (e.g. HDAC inhibitors in fungal cultures) to induce new products?”_

A: These are OK.

* * *

Q: _“What is the policy about co-culture?”_

A: Compounds derived from co-culture are fine. If the producing strain is known, just include this one in the source organism box. If it is not known which source organism produces it, you can put ‘Co-culture’ and include both source organisms as separate entries in the source organism box.

* * *

#### Biosynthesis/ genetic manipulation

**In general you should follow the rule that the NP Atlas only includes compounds if they could plausibly be found in nature**

**(No semi-synthesis, no biotransformation, no non-natural BGC products (e.g. from deleting genes etc).**

Q: _“Should I include compounds from heterologous expression?”_

A: Yes. Provided that the work incorporated an entire biosynthetic gene cluster. In these cases, the source organism is the organism from which the cluster was derived (if known), or ‘eDNA’ if derived from DNA assemblages.

* * *

Q: _“When an article talks about heterologous expression in a new host, which microorganism would be the source organism? ”_

A: The source organism would be the one that originally has the gene/DNA in their genome, the host organism would not be the source organism.

* * *

Q: _“What about compounds made by feeding building blocks to cultures?”_

A: If the building block is natural (e.g. proteinogenic amino acids) that is OK. If it is non-natural (e.g. fluoro-phenylalanine) this should be rejected. If you are not sure, check ‘Needs work’ and put a comment in the comments field.

* * *

Q: _“What about studies that delete/ activate regulators of biosynthetic machinery?”_

A: These are OK.

* * *

Q: _“What about microbial transformation of a plant metabolite?”_

A: Biotransformation is not OK. We only want true NPs that are found in the environment.

* * *

Q: _“What about shunt products made by deleting enzymes in the pathway?”_

A: Nope. This is considered ‘non-natural’. It would be helpful if you could put ‘Biosynthetic engineering’ in the notes box in case we decide later on to go back and include these.

* * *

Q: _“If a genetic modification is made in a microorganism to help the expression of a gene such as the deletion of another gene to help express cryptic genes, would the produced natural product from the mutant organism be curated? ”_

A: This is more difficult because it depends on the type of genetic modification. If the mutation (deletion, insertion…) does not alter the structure of the produced natural product, then it is a natural product that we are interested in adding to the atlas.  If the mutation alters the structures to give new “unnatural” natural products, then it is disregarded (ex: synthetic biology, genetically modifying enzymes such as PKS and NRPS…).
