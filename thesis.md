---
layout: post
title: Properties and Impact of Vicinity in Mobile Opportunistic Networks <br> T. Phe-Neau @ UPMC Sorbonne Université
---

Manuscript in [PDF](http://tel.archives-ouvertes.fr/docs/00/95/78/64/PDF/these_archivage_2865518.pdf).

## Slides

<center><script async class="speakerdeck-embed" data-id="b71d86da78244f32bc5c4dc17f8aeb85" data-ratio="1.41436464088398" src="//speakerdeck.com/assets/embed.js"></script></center>




## Abstract

The market of mobile devices, such as smartphones, tablets, game stations, or laptops has exponentially grown over the latest years. When people carry such equipments along their daily commuting, they become mobile information vectors. They are able to carry, send, or receive information whenever they meet each other. The networking paradigm using such information vectors is known as disruption-tolerant networks (DTN) or opportunistic networks. Even if some of their properties are quite well known today, the relationship between a given node and its vicinity has not been thoroughly studied yet. In this thesis, we show how this closeness notion is a key ingredient to improve opportunistic network forwarding.

We begin by identifying and investigating the binary assertion issue in opportunistic networks. We notice how most DTNs mainly analyze nodes that are in contact (at a topological 1-hop distance). This vision implies that all nodes that are not in contact, are in intercontact. Nevertheless, when two nodes are not in contact, this does not mean that they are topologically far away from one another. For instance, a 2- or 3-hop path may link them. Following this chain of thoughts, we propose a formal definition of vicinities in DTNs called “k-vicinity” and study the new resulting “contact/intercontact” temporal characterization. We show how extended temporal distributions differ from previous binary distributions.

Then, we examine the internal organization of vicinities using the asynchronous vicinity motion (AVM) framework. We highlight movement types such as birth, death, and sequential moves. We analyze a number of their characteristics and extract vicinity usage directions for mobile networks. Based on the vicinity motion outputs and extracted directions, we build TiGeR (a synthetic TImeline GEneratoR) that simulates how pairs of nodes interact within their vicinities. Vicinity motion and TiGeR are able to take into account various types of networks to generate synthetic vicinity behaviors following similar patterns.

Finally, we inquire about the possibilities of vicinity distance prediction. We expose a vicinity motion-based heuristic for pairwise shortest distance forecasting. We find that our heuristics perform quite well with performances up to 99% for the synchronous vicinity motion-based scheme and around 40% for the asynchronous one. We must note that these measures are enhanced by the fact that our heuristic often predicts infinite pairwise distances (i.e., pure intercontact) and most of the datasets we observe are mainly disconnected. Still, they are interesting indicators of whether two nodes are likely to be close in the future.


## Defense committee
- [André-Luc BEYLOT](http://irt.enseeiht.fr/beylot/), _Reviewer_, Professeur ENSEEIHT
- [Emmanuel LOCHIN](https://personnel.isae-supaero.fr/emmanuel-lochin/), _Reviewer_, Professeur ISAE
- [Aline CARNEIRO VIANA](https://sites.google.com/site/alinecviana/), _Examiner_, Chargée de Recherche -INRIA
- [Vania CONAN](https://fr.linkedin.com/in/vaniaconan), _Examiner_, Directeur de recherche, Thales
- [Anne FLADENMULLER](https://www-npa.lip6.fr/~fladenmu/), _Examiner_, Maître de Conférence UPMC
- [Vincent GAUTHIER](https://complex.luxbulb.org/), _Examiner_, Maître de Conférence Télécom SudParis
- [Marcelo DIAS DE AMORIM](https://www-npa.lip6.fr/~amorim/), _Advisor_, Directeur de recherche, CNRS & UPMC

## Bibtex Entry

	@PhDThesis{pheneau.thesis,
	author = {Phe-Neau, Tiphaine},
	title = {Properties and Impact of Vicinity in Mobile Opportunistic Networks},
	school = {UPMC Sorbonne Universités},
	year = {2014},
	}

