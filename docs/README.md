# Background Research
This section will provide a breif overview from the source projects being evaluated. 

## Evaluation and Characterization of Available Bandwidth Probing Techniques \[1\]
In a work authored by Ningning Hu and Peter Steenkiste and published in the IEEE JSAC Special Issue in Internet and WWW Measurement, Mapping, and Modeling, Vol. 21(6), Aug. 2003, Hu and Steenkiste present Initial Gap Increasing and Packet Transmission Rate (IGI and PTR).  The work was originally published by Hu and Steenkiste as a Carnegie Mellon University Technical Report: [CMU-CS-02-166 Estimating Available Bandwidth Using Packet Pair Probing](http://reports-archive.adm.cs.cmu.edu/anon/2002/abstracts/02-166.html)


### Abstract
The packet pair mechanism has been shown to be a reliable method to measure the bottleneck link capacity on a network path, but its use for measuring available bandwidth is more challenging. In this paper, we use modeling, measurements, and simulations to better characterize the interaction between probing packets and the competing network traffic. We first construct a simple model to understand how competing traffic changes the probing packet gap for a single-hop network. The gap model shows that the initial probing gap is a critical parameter when using packet pairs to estimate available bandwidth. Based on this insight, we present two available bandwidth measurement techniques, the initial gap increasing (IGI) method and the packet transmission rate (PTR) method. We use extensive Internet measurements to show that these techniques estimate available bandwidth faster than existing techniques such as Pathload, with comparable accuracy. Finally, using both Internet measurements and ns simulations, we explore how the measurement accuracy of active probing is affected by factors such as the probing packet size, the length of probing packet train, and the competing traffic on links other than the tight link.

## References
\[1\] N. Hu and P. Steenkiste, "Evaluation and Characterization of Available Bandwidth Probing Techniques," in IEEE Journal On Selected Areas In Communications, Vol. 21, NO. 6, August 2003 p 879.  \[Online\]. Available: http://www.cs.cmu.edu/~hnn/papers/igi-jsac.pdf
