---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Ines and here you will find some of my personal and work related projects. I am currently a postdoctoral researcher in the group [Seismology and wave physics](https://cos.ethz.ch/) at ETH Zurich with a focus on medical ultrasound. Prior to this, I completed my PhD on wave-based imaging methods at the Institute of Geophysics at ETH Zurich. If you are not familiar with wave propagation, it may not be trivial to connect seismology with medical ultrasound. If you keep on reading and browsing through this website, however, I hope that I can convince you that these two fields of research have many common aspects and transferring knowledge between the two research communities is a very interesting and active field of research. 


From seismics to medical ultrasound: _a journey across scales_
======
Our interest in waves and wave propagation modelling stems from the fact that waves are excellent carriers of information and may be used to probe unknown objects in order to learn about their internal structure. Emitted from a source (for instance an earthquake or an ultrasonic transducer), a wave travels through the medium and its propagation path and speed is influenced by the medium's properties and structure. Here is an example of how a 2D numerical simulation of an acoustic wave traveling through a human breast looks like. 
<br>
<br/><img src='/images/wavefieldforwardSim_crop.gif' width='500'><br>
<br>
With a rigorous mathematical understanding of how waves propagate in different media, we can thus deduce material properties of an unknown object from the observation of waves. This fundamental idea has allowed us to obtain a profound knowledge on the internal structure of human bodies, but it has also allowed us to deduce the internal structure of the Earth from which we do not have direct information in the sense of probes (the deepest borehole on Earth only cuts through less than 0.2 % of Earth's radius). The fact that we can use indirect information carried by waves in order to generate an image of an object that we cannot access directly is the fundamental concept of tomography. In a mathematical setting, tomography can be stated as a nonlinear PDE-constrained optimization problem governed by the wave equation. Almost all the research you will find on this page is centered around methods that treat, simplify or solve this optimization problem in a setting that will be referred to as the inversion process.

From a mathematical and physical point of view, wave propagation phenomena or rather the way we describe them are independent of scale. In principle this means that methods developed for instance in geophysics may be transferred to small scale applications such as medical ultrasound, but also to non destructive testing in civil engineering. This ability to translate imaging methods rests on the fact that, considering common frequencies and material properties, the kinematic and dynamic scaling properties are very similar in seismics (especially exploration geophysics) and medical ultrasound. For a detailed comparison between important quantities in exploration geophysics and medical ultrasound, check out [this paper](https://www.researchgate.net/publication/323295721_Medical_ultrasound_tomography_lessons_from_exploration_geophysics). During my PhD, this transfer of knowledge between the two fields of research has been my main focus and to this date I find it quite fascinating how we can _travel through scales_ by exploiting the coherent mathematical formulation of wave propagation.  


**Forward - Inverse modelling in a nutshell**

If you are not familiar with computational imaging methods, here is just a very short and high-level description of the main idea behind the common imaging methods one comes across in the hospital, but also in seismic imaging. Based on the mathematical knowledge of wave propagation (described by the wave equation), we can simulate/model how a wave would propagate in any kind of medium, given we have generated a computational model (think of digital twin) of the object we are interested in and a computational model of the source and receiver characteristics. This is what is referred to as the *forward problem*, which may be seen as a digitized form of a real-life experiment. However if we think about a medical examination for instance, we can design an acquisition device that can perform such an _wave propagation experiment_ through a certain part of the body and record a set of measurements, which I will also refer to as waveforms in the following and other posts. However, we don't know the structure of the object we are imaging, in fact this is the very thing we want to learn about! All we have is thus a set of measurements and a physical understanding of wave propagation, with the goal to finding out what kind of structure and material parameters inside the measured object generates the recorded measurements. Consequently what we want to to is take the *inverse* path that was taken in the forward problem, thus from a set of measurements, deduce the material properties. 



<!-- ------
At the end, I want to send out a motivational line (mostly for myself :-)): 

Keep on searching and stay curious!

![](../images/castlesreen_crop.jpeg) -->


