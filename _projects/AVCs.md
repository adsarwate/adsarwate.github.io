---
layout: page
title: COINSTAC
description: between worst and average case communication
img: assets/img/gen_plotkin_geom_cone.png
importance: 2
category: work
---

This is a line of work I have been pursuing since graduate school on how we model communication systems and what models lie between the two "classical" models of communication: one that assumes the channel behaves randomly (which we call "Shannon") and one that assumes the channel can behave adversarially (which we call "Hamming"). We define a variety of *adversarial channel models* known as arbitrarily varying channels (AVCs) to give a unified framework for understanding what lies between the two classical views.

We think of the channel as controlled by an adversary, or jammer. The behavior of the jammer is constrained by their view of what is being transmitted. An oblivious jammer cannot see the transmitted codeword. An omniscient jammr can (non-causally) see the transmitted codeword. These correspond to the Shannon and Hamming models. However, when the jammer has partial knowledge of what is transmitted things get interesting. We look at cases where they get to see a noisy version of the codeword (a myopic adversary) and when they can see the codeword as it is being transmitted  (a causal adversary). 

Understanding both coding schemes and optimal attack strategies shows the importance of coding primitives such as stochastic encoding and list decoding. While this [NSF-funded project](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1909468) is ending soon, we have a number of results in the pipeline which should be forthcoming soon. In particular, we have just completed a monograph on these topics.