---
layout: archive
title: ""
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research overview
======

I am extremely interested in developing future micro-/nano-scale sensors for healthcare applications, autonomous vehicles, and environmental monitoring.

For these applications, it is very important to achieve <i>high resolution</i> and <i>high sensitivity</i>, as they can help us saving lives (healthcare) and preserving the environment (environmental monitoring) by detecting abnormalities early.

Meanwhile, it is also very important in realising <i>low power</i> sensor systems, for a more sustainable future.

# I. MEMS sensors

In MEMS sensor research, we are hitting a bottleneck in achieving <i>high resolution</i> and <i>high sensitivity</i>. Conventionally, we are focusing on only individual structures/modes, or unrelated arrays of such individual structures. Also, it was thought that nonlinear effects within MEMS structures are to be avoided, as nonlinear effects bring instability.

However, our research show that we could make a breakthrough by making full use of structural/modal interactions and nonlinear effects. By mixing & matching a variety of interesting effects, we have successfully realised a series of MEMS sensors with high sensitivity and high resolution since 2017.

## I.1 Structural/modal interactions

### I.1.a Structural interactions (Mode localization)

The first thing we did is to link the unrelated arrays of individual <a href="https://en.wikipedia.org/wiki/Resonator"><b>resonators</b></a> through energy coupling mechanisms.

<img align="left" src="/images/CoupledResonators.PNG" height="268" width="239">

<br>
In (a), Res1 and Res2 are two individual resonators coupled together via CpB (coupling beam).

In (b), the equivalent coupled <a href="https://en.wikipedia.org/wiki/Effective_mass_(spring%E2%80%93mass_system)">spring-mass model</a> of the coupled resonator structure.

###### * Image source: <a href="https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.12.044005"> Towards High-resolution Inertial Sensors Employing Parametric Modulation in Coupled Micro-mechanical Resonators</a>.

<br>
<br>

After introducing the coupling mechanisms, a very interesting phenomenon of <a href="https://www.sciencedirect.com/science/article/abs/pii/0022460X8890226X"> <b>mode localization</b></a> occurs. Essentially, the amplitude ratio between the two resonators will change with respect to an external stimulus, e.g. stress due to acceleration.

* <b>Demonstration of mode localization</b>

<img align="left" src="/images/InPhaseModeBalanced.gif" height="240" width="180">
In-phase mode <i>balanced</i> case (before introducing external stimuli)
<br>
<br>
<br>
<br>
<br>
<br>

<img align="left" src="/images/InPhaseModePerturbed.gif" height="240" width="180">
In-phase mode <i>perturbed</i> case (after introducing external stimuli)

You can clearly observe the amplitude ratio change between the two resonators.
<br>
<br>
<br>
<br>

As it turns out, the sensitivity of the sensors utilising this <b>mode localization</b> effect can be significantly boosted by orders of magnitude. Consequently, the resolution of the sensors can also be significantly improved.

### I.1.b Modal interactions

In addition to the interactions between two individual resonators, interactions between two <a href="https://en.wikipedia.org/wiki/Vibration#Illustration_of_a_multiple_DOF_problem"> modes</a> within a single resonator exist.

<img align="left" src="/images/Modalinteraction.PNG" height="500" width="400">
<br>
The modal interactions between two modes within a ring resonator.
###### * Image source: <a href="https://www.nature.com/articles/s41467-019-12796-0.pdf"> Dynamic Modulation of Modal Coupling in Microelectromechanical Gyroscopic Ring Resonators</a>.

<br>
<br>
<br>
<br>
<br>
<br>
<br>

More recently, we have discovered that the modal interactions or energy coupling can be used to transfer sensitivity between the modes, thereby enhancing both the sensitivity and resolution of a sensor (see <a href="https://ieeexplore.ieee.org/abstract/document/9439932/"> this journal paper</a> and <a href="https://ieeexplore.ieee.org/abstract/document/9375348/"> this conference paper</a> for more details).

## I.2 Nonlinear dynamics

Nonlinear effects are fascinating.

<img align="left" src="/images/NonlinearDoubleHysteresis.PNG" height="364" width="456">

See these beautiful frequency responses of coupled MEMS resonators described by 5th order nonlinear equations.
###### * Image source: <a href="https://ieeexplore.ieee.org/abstract/document/8091122/"> Experimental Observation of Noise Reduction in Weakly Coupled Nonlinear MEMS Resonators</a>.

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

In fact, nonlinear effects can be very useful. For instance, by operating MEMS resonators as a <a href="http://www.scholarpedia.org/article/Duffing_oscillator"> Duffing oscillator</a> (described by the <a href="https://en.wikipedia.org/wiki/Duffing_equation"> Duffing equation</a>), oscillator phase noise and amplitude noise can be effectively reduced. Therefore, we made prototype sensors employing this Duffing nonlinearity (see <a href="https://ieeexplore.ieee.org/abstract/document/8640054"> this journal paper</a> for more details).

Interestingly, there are an ocean of nonlinear effects within MEMS structures (check out <a href="https://onlinelibrary.wiley.com/doi/book/10.1002/9783527617586"> this fascinating book</a> by A. H. Nayfeh and D. T. Mook). There are still plenty of room for us to explore!

# II. Energy harvesters

In order to reduce the power consumption of sensor systems, <a href="https://en.wikipedia.org/wiki/Energy_harvesting">energy harvesters</a> are very efficient for this purpose, via harnessing ambient energy to support the miniature sensors.

Previously, we have worked on piezoelectric vibration energy harvesters (check out <a href="https://www.sciencedirect.com/science/article/pii/S0924424717302194">this paper</a> as a starting point). I am very interested in continuing this research, and potentially expanding to other related energy harvesting approaches.

Structural/modal interactions and nonlinear effects can be very useful in this part of research, too!

# III. FET-based Sensors & diode-based sensors

I am also very interested in developing micro-/nano-scale sensors based on field-effect transistors (FET) (e.g. <a href="https://en.wikipedia.org/wiki/ISFET"> ISFET</a>) and diodes (e.g. <a href="https://en.wikipedia.org/wiki/Photodiode"> photodiode</a>) , for a variety of applications, such as biosensors. Check out our most recent <a href="https://pubs.acs.org/doi/abs/10.1021/acsnano.0c08075"> ACS Nano paper</a> in this area.
