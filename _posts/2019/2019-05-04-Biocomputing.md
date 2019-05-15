---
layout: post
title:  "Biocomputing"
date:   2019-05-04 1:29:38 -0800
author: conor
image: https://www.kurzweilai.net/images/profiler.png
categories: [research, biocomputing, genetics, molecular engineering, genetic engineering, therapeutics]
featured: true
---

Recently a paper by Hyojin Kim, Daniel Bojar, and Martin Fussenegger, titled
 [“A CRISPR/Cas9-based central processing unit to program complex logic computation in human cells”](https://www.pnas.org/content/116/15/7214), was brought to my attention by a friend.

Let's break down that title, because its at least 3 mouthfuls.

The core idea behind the paper is rather amazing, and seeks to answer the questions

- Could use Cas9 as a CPU in a biocomputational architecture?
- How can we control gene expression with biological logic gates?

This lead me to a question of my own

- Where does this type of genetic engineering architecture lead to for the future of humanity?

To me this is an incredible idea which may lead to a future where if it would be possible to create artificial feedback loops using Cas9 and other genetic tools to regulate expression in a robust and controllable way.

Their paper they outline approximate digital logic gates for AND, OR, NOR, XOR, and NIMPLY.

Bearing in mind that it is possible to perform any arbitrary computation using only [NOR or NAND gates](https://en.wikipedia.org/wiki/Functional_completeness) this is pretty exciting.

Honestly, I had to lookup what the hell a [NIMPLY gate](https://en.wikipedia.org/wiki/NIMPLY_gate) is, I’d never come across it before.
So I educated myself about it and made a wikipedia page for it.

A NIMPLY gate is only 1 if its first input is 1 and its second input is 0.
In this case it signals the sole presence of its first igRNA input by forming green fluorescent protein (GFP) as an output signal.

Here’s a cool [link to a tutorial on genetic circuits](http://www2.cds.caltech.edu/~murray/waitwhat/tutorial.html) for reference.

There’s an interesting note in the article about the dual-core NIMPLY gate, 

“Importantly, the dual-core NIMPLY gate also functioned in immortalized human mesen-chymal stem cells (hMSCs), suggesting potential applicability of this system for therapeutic applications.”

hMSCs are heavily used in cancer research because they are heavily involved with [tumor progression](https://molecular-cancer.biomedcentral.com/articles/10.1186/s12943-017-0597-8) and cancer development.


In practice, it may turn out to be practically infeasible to make such a general purpose computation at scale because of some current biological or technological constraint, but the prospect is still there.

An entire field of study for optimizing biological operations would have to be further explored to determine more optimal ways to perform certain complex biochemical processes.

What is one to even call this type of genetic engineering optimization into the domain of genetic circuits?
It certainly is within the domains of genetic engineering, biocomputing, and synthetic human biology, but I propose that a more precise term is needed.

The terms Genetic Programming and Genetic Algorithms have unfortunately already been taken to have certain meanings in Computer Science, and although these definitions could be overloaded, I prefer to use the term 

- Metabolic programming

You may imagine a world where it would be possible to update your genetics simply through your personal smart device of the future, if you are already setup with such an internal system.

However, currently the authors recommend the following use cases of this genetic architecture,
“For biomedical application of synthetic circuits, a device could be developed to detect specific biomarkers as input signals for an inducible igRNA expression system, to process the information, and then to produce therapeutic outputs” 

Or more simply you encode the biomarkers of a certain disease into input guide RNA to your biocomputer, setup a computation, and then potential therapeutic solutions will be synthesized for you to test.

This technology may be further amplified with the use of [CLASP’s Molecular Metaprogramming](https://github.com/clasp-developers/clasp)
lead by [Christian Schafmeister’s Group @ Temple University](https://chem.cst.temple.edu/schafmeister.html)

The big idea there is to use Spiroligomers as flexible building blocks to build unique biologically active structures with specific purposes.

A few examples given in [Christian’s Google Talk](https://www.youtube.com/watch?v=8X69_42Mj-g) are 

- General Purpose Antimicrobials,
  Long Term Molecular Sensors
  Water Purification 

Their work reaches more into the realm of molecular engineering, and takes a more structural engineering approach to the problem of creating new therapeutics.

It may be possible to merge these two technologies by automating the synthesis of these compounds by using bacteria.

Instead of using GFP as an output, you could output some metabolic signal to these bacteria to start synthesizing these compounds.

A step further once this technology has been proven would be to carry out this automated process in vivo.

Although in my mind you'd need to target hMSCs in a patient and isolate them for a sort of computation and  space for personalized therapeutic development. 

I'm not sure how sensitive all these biochemical processes are to the myriad of external factors that may arise within the human body.

hMSCs are abundance in tooth pulp and bone marrow so there maybe a way to isolate a therapeutic staging grounds to a single tooth.

By loading this computation and synthesis system into the body to encode genetic factors that will biologically synthesize these Spiroligomers in vivo and have them spontaneously carry out their given purpose, automated personally tailored therapeutic treatments may be possible.

I'm sure we're at least a decade from such technology, but it's quite an exciting prospect, it would open an entirely new methodology for synthesizing therapeutic solutions in synthetic biology.








