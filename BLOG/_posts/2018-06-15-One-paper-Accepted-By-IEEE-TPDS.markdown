---
layout: post
title:  "Article accepted by IEEE TPDS"
date:   2018-06-15
categories: publications
---

## Putting the Next 500 VM Placement Algorithms to the Acid Test

*Adrien Lebre, Jonathan Pastor, Anthony Simonet, Mario Südholt*

Most current infrastructures for cloud computing leverage static and
greedy policies for the placement of virtual machines. Such policies
impede the optimal allocation of resources from the infrastructure
provider viewpoint. Over the last decade, more dynamic and often more
efficient policies based, e.g., on consolidation and load balancing
techniques, have been developed. Due to the underlying complexity of
cloud infrastructures, these policies are evaluated either using
limited scale testbeds/in-vivo experiments or ad-hoc simulators. These
validation methodologies are unsatisfactory for two important reasons:
they (i) do not model precisely enough real production platforms
(size, workload variations, failure, etc.) and (ii) do not enable the
fair comparison of different approaches. More generally, new placement
algorithms are thus continuously being proposed without actually
identifying their benefits with respect to the state of the art.

In this article, we show how VMPlaceS, a dedicated simulation
framework enables researchers (i) to study and compare VM placement
algorithms from the infrastructure perspective, (ii) to detect
possible limitations at large scale and (iii) to easily investigate
different design choices. Built on top of the SimGrid simulation
platform, VMPlaceS provides programming support to ease the
implementation of placement algorithms and runtime support dedicated
to load injection and execution trace analysis. To illustrate the
relevance of VMPlaceS, we first discuss a few experiments that enabled
us to study in details three well known VM placement
strategies. Diving into details, we also identify several
modifications that can significantly increase their performance in
terms of reactivity. Second, we complete this overall presentation of
VMPlaceS by focusing on the energy efficiency of the well-know FFD
strategy. We believe that VMPlaceS will allow researchers to validate
the benefits of new placement algorithms, thus accelerating placement
research and favouring the transfer of results to IaaS production
platforms.
