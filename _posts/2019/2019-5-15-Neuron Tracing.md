---

layout: post
title:  "Neuron Tracing"
date:   2019-05-04 1:29:38 -0800
author: conor
image:
categories: [research, IR, neuron, firing, firing pattern, fluorescent, life, biology, bioluminescence, biofluorescence, fNIRs, optogenetics, neural photonics]
featured: true
visible: 1
---

This article was inspired by a Nova Documentary, [Creatures of Light](https://www.pbs.org/wgbh/nova/video/creatures-of-light/), it's a pretty amazing documentary about bioluminescent and bioflorescent life.

But, it takes an interesting turn when scientists discuss how the fluorescent proteins synthesized by certain types of aquatic life can be inserted other organisms.

Currently Green Fluorescent Protein (GFP) has been used in cats to study FIV, a viral relative to HIV.

This works because of the skull thickness of felines is thin enough that most of the green light passes through and isn't lost to absorption and scattering 

But for thicker skulls, e.g. Humans, you need to use a longer wavelength to transmit any signal from within the skull to the outside.

The setup and idea goes as follows.

Insert the genetics to biosynthesize an IR fluorescent protein in-vivo to human neuronal cells so once they proliferate you can literally *"see"* them firing in real time. This field of study is called optogenetics.

You effectively amplify the IR signature of your brain, like putting IR light-houses all over your brain signaling your internal neural structure and activity outwards.

[fNIRs](https://en.wikipedia.org/wiki/Functional_near-infrared_spectroscopy) is another technology seeking to use the latent IR signature of the brain and is currently being used for BCIs.

However fNIRs is limited in a similar way standard EEG is and, *"cannot be used to measure cortical activity more than 4 cm deep due to limitations in light emitter power and has more limited spatial resolution"*

To get information about the the brain many different depths you need 

Ideally you'd want a far IR fluorescent protein, but as the scientists in the documentary say, *

There are red fluorescent proteins which exist like, *

The documentary was released in *, so I started looking into Red and IR fluorescent proteins to see if anything new and promising can has been found interim.

In the article [Bright monomeric near-infrared fluorescent proteins as tags and biosensors for multiscale imaging](https://www.nature.com/articles/ncomms12405) by [Daria M. Shcherbakova](https://www.nature.com/articles/ncomms12405#auth-1), [Mikhail Baloban](https://www.nature.com/articles/ncomms12405#auth-2), [Alexander V. Emelyanov](https://www.nature.com/articles/ncomms12405#auth-3), [Michael Brenowitz](https://www.nature.com/articles/ncomms12405#auth-4), [Peng Guo](https://www.nature.com/articles/ncomms12405#auth-5) & [Vladislav V. Verkhusha](https://www.nature.com/articles/ncomms12405#auth-6) in 2016,

 "Currently available monomeric far-red GFP-like FPs, including mKate2 (ref. [10](https://www.nature.com/articles/ncomms12405#ref10)), TagRFP657 (ref. [11](https://www.nature.com/articles/ncomms12405#ref11)), mCardinal and mNeptune2.5 (ref. [12](https://www.nature.com/articles/ncomms12405#ref12)), are suboptimal for deep-tissue imaging because their excitation maxima do not exceed 611 nm."

The idea is the longer the wavelength the deeper you can measure neuron activity, but you also lose spacial resolution.

The primary constituents of human tissue that contribute to the IR range are Blood, Fat/Lipids, and H20

The ["optical window"](https://en.wikipedia.org/wiki/Near-infrared_window_in_biological_tissue) for human skin is roughly 650-1350nm

Hemoglobin is optically excited around 400-450nm

<img src=https://upload.wikimedia.org/wikipedia/commons/8/80/Fig_1_-_The_molar_extinction_coefficient_of_HbO2_and_Hb.png>

To measure a length scale, L within the human brain, I'd expect that it, in its most general form, would depend on the distribution of wavelengths present in your optical source, its amplitude/power, and the density of tissue it traverses through.

So if $\phi_\lambda$ is our distribution of wavelengths something like,

{%raw%}

L = $LossFactor(\phi_{\lambda} , \rho_{tissue}, Power_\phi) * E[\phi_{\lambda}]$

{%endraw%}

Without being able to map the entirety of neuronal circuitry, you lose a lot of information about how the different systems of the brain inter-relate.

It's as if you're tracking a flow of birds and suddenly they cross the grand canyon, good luck knowing *, the trail stops cold.