Content-Type: text/x-zim-wiki
Wiki-Format: zim 0.6
====== Supernova_Ejecta_Interacting_with_a_Circumstellar_Disk._I_-_Two-dimensional_Radiation-hydrodynamic_Simulations_-_Suzuki_2019_ApJ_887_249.pdf ======
Text date: [[Zettelkasten:2024:03:07|2024-03-07]] Modi date: [[Zettelkasten:2024:03:05|2024-03-05]]
@ARTIKEL  
[*] **[[../Supernova_Ejecta_Interacting_with_a_Circumstellar_Disk._I_-_Two-dimensional_Radiation-hydrodynamic_Simulations_-_Suzuki_2019_ApJ_887_249.pdf]] **
https://doi.org/10.3847/1538-4357/ab5a83


{{../Supernova_Ejecta_Interacting_with_a_Circumstellar_Disk._I_-_Two-dimensional_Radiation-hydrodynamic_Simulations_-_Suzuki_2019_ApJ_887_249.pdf.avif?width=500}}

Pages:           27


The Astrophysical Journal, 887:249 (27pp), 2019 December 20

https://doi.org/10.3847/1538-4357/ab5a83

© 2019. The American Astronomical Society. All rights reserved.

Supernova Ejecta Interacting with a Circumstellar Disk. I. Two-dimensional Radiationhydrodynamic Simulations
1

Akihiro Suzuki1

, Takashi J. Moriya1,2

, and Tomoya Takiwaki1,3

Division of Science, National Astronomical Observatory of Japan, 2-21-1 Osawa, Mitaka, Tokyo 181-8588, Japan; akihiro.suzuki@nao.ac.jp
2
School of Physics and Astronomy, Faculty of Science, Monash University, Clayton, VIC 3800, Australia
3
Center for Computational Astrophysics, National Astronomical Observatory of Japan, 2-21-1 Osawa, Mitaka, Tokyo 181-8588, Japan
Received 2019 July 26; revised 2019 November 20; accepted 2019 November 20; published 2019 December 26

Abstract
We perform a series of two-dimensional radiation-hydrodynamic simulations of the collision between supernova
ejecta and circumstellar media (CSMs). The hydrodynamic interaction of a fast ﬂow and the surrounding media
efﬁciently dissipates the kinetic energy of the fast ﬂow and is considered as a dominant energy source for a speciﬁc
class of core-collapse supernovae. Despite some observational evidence for aspherical ejecta and/or CSM
structure, multidimensional effects in the ejecta–CSM interaction are relatively unexplored. Our numerical
simulations equipped with an adaptive mesh reﬁnement technique successfully reproduce hydrodynamic
instabilities developing around the ejecta–CSM interface. We also investigate effects of disklike CSMs on the
dynamical evolution of supernova ejecta and bolometric light curves. We ﬁnd that emission powered by ejecta–
disk interaction exhibits signiﬁcant viewing angle dependence. For a line of sight close to the symmetry axis, the
observer directly sees the supernova ejecta, leading to a short brightening timescale. For an observer seeing the
emission through the CSM disk, thermal photons diffuse throughout the CSM, and thus the light curve is severely
smeared out.
Uniﬁed Astronomy Thesaurus concepts: Supernovae (1668); Hydrodynamics (1963); Hydrodynamical simulations
(767); Circumstellar gas (238); Stellar evolution (1599); Radiative transfer (1335); Shocks (2086)
reaching the consensus that the required CSM masses can vary
widely from one event to another. Most extreme cases of
superluminous Type IIn SNe often require as much as ∼10 Me.
For such massive CSMs, the star is covered by an optically
thick medium, and the photosphere is no longer located at the
stellar surface. The energy source of the bright optical
emission, the ejecta–CSM interface, is initially hidden in the
deep interior of the massive CSM. Thus, the energy produced
due to the ejecta–CSM collision is reprocessed and then
diffuses out through the photosphere in the CSM. More recent
studies have shown that a considerable fraction of Type II SNe
also exhibit observational features indicating an enhanced CSM
density in the immediate vicinity of exploding stars (Gal-Yam
et al. 2014; Yaron et al. 2017; Förster et al. 2018).
Despite this growing evidence, how exactly massive stars
shed their envelopes immediately before the gravitational
collapse is still debated. For example, the most extreme case of
SN 2006gy requires a mass-loss rate of the order of ∼1 Me
yr−1, which is obviously beyond the normal rates inferred from
Galactic massive stars (e.g., Hamann et al. 2006; Sander et al.
2012; Smith 2014) and cannot be explained by the current
standard theory of steady stellar winds. Unusual mass-loss
events associated with the ﬁnal evolutionary state of massive
stars, such as wave-driven mass loss (Quataert & Shiode 2012;
Shiode & Quataert 2014; Fuller 2017; Fuller & Ro 2018),
envelope ejection due to binary interaction (e.g., Chevalier
2012; Soker & Kashi 2013), fossil disks around massive stars
(Metzger 2010), and so on, may be responsible for the origin of
massive CSMs. However, no general consensus has been
reached yet. From the observational viewpoint, several Galactic
luminous blue variables (LBVs; e.g., Humphreys & Davidson 1994), e.g., η Carinae, have massive CSMs in their vicinity.
Such mass-loss events long before the iron core collapse are
likely to be eruptive (e.g., Pastorello et al. 2007), thereby

1. Introduction
It is ﬁrmly believed that the circumstellar media (CSMs)
play important roles in stellar explosions. Massive stars are
thought to produce CSMs by shedding a part of their envelopes
via several mechanisms, e.g., stellar winds and binary
interactions. When a massive star undergoes the gravitational
collapse of the iron core, a core-collapse supernova (CCSN)
happens, and its bright emission illuminates the surrounding
media. Commonly, CCSNe showing observational signatures
of hydrogen-rich CSMs are found in SN surveys, and they
make up a special spectral class, known as Type IIn SNe
(Schlegel 1990; Filippenko 1997; Blinnikov 2017; Smith 2017).
Type IIn SNe are deﬁned as SNe showing narrow emission/
absorption line features superposed on commonly found broad
P Cygni proﬁles, thereby indicating the presence of slowly
moving gas ahead of the fast SN ejecta. They constitute a
nonnegligible fraction of CCSNe (∼7%; e.g., Li et al. 2011;
Smith et al. 2011; Shivvers et al. 2017). The well-studied
examples include SN 1988Z (Stathakis & Sadler 1991; Turatto
et al. 1993; van Dyk et al. 1993; Chugai & Danziger 1994;
Aretxaga et al. 1999), 1998S (Fassia et al. 2000, 2001; Leonard
et al. 2000), and 2010jl (Patat et al. 2011; Stoll et al. 2011;
Zhang et al. 2012; Fransson et al. 2014; Ofek et al. 2014b). The
ejecta–CSM collision can efﬁciently dissipate the kinetic
energy of the ejecta and release the dissipated energy as bright
thermal radiation. Therefore, the ejecta–CSM interaction is
considered as a dominant power source for luminous SNe like
SN 2006gy (Ofek et al. 2007; Smith et al. 2007, 2010a).
Theoretical studies on the ejecta–CSM interaction have been
conducted extensively in both analytical and numerical ways
(e.g., Chevalier 1982a, 1982b; Chevalier & Fransson 1994;
Smith & McCray 2007; Chevalier & Irwin 2011; Moriya et al.
2011, 2013a; Ginzburg & Balberg 2012; Dessart et al. 2015),
1

