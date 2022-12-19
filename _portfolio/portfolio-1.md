---
title: "Diffuse ultrasound computed tomography"
excerpt: "_Active_ noise tomography for medical ultrasound?<br/>
<br/>
<center><img src='/images/checkerboard.png' width='500'>"
collection: portfolio
---

If the terms _diffuse ultrasound_ seem a bit diffuse for you, don't worry, I'll do my best to explain this on a conceptual level as well as a bit more in detail for the interested reader. To start off, let's define the main purpose of this study: transferring a concept called interferometry from seismic imaging to medical ultrasound with the specific application to breast cancer screening. Before I briefly describe seismic interferometry, I want to mention a few points.
Current state-of-the-art breast cancer screening mostly relies on mammography with additional data added by MRI or hand held ultrasound. For more information check out ...portfolio on medical ultrasound/breast cancer screening. Ultrasound has many attractive features that would make it a preferable screening device (for more information also see the linked post from above). Thus designing ultrasound devices for breast cancer screening is an active field of research. With this study, we focussed on an alternative method to speed up the data acquisition of a breast cancer scan, which at it's core makes use of the principle applied in seismic interferometry.

**Interlude: Seismic interferometry**
The main interest of seismic imaging is to generate an image of the subsurface using a tomographic method analogously to the aim in medical imaging, where one is interested in an image of the internal structure of a certain body part. The general concept of acquiring an image contains several parts:
    1. we need a device that can perform an experiment or measurement and acquire some data
    2. we need a way to link this data to a model of the imaged object's structure
The second aspect is largely referred to _solving the inverse problem_, but this is not what this post is about. Here, we concentrate on the first aspect, namely how to acquire data that we can use to find out more about the object's structure. 


To start off a a bit luridly, think of a bubble bath, the one where you enjoy  

From a mathematical and physical point of view, wave propagation phenomena or rather the way we describe them are independent of scale. In principle this means that methods developed for instance in geophysics where we are interested to image large subsurface structures may as well be applied to a small scale application as in medical ultrasound. This ability to translate imaging methods rests on the fact that considering common frequencies and material properties, the kinematic and dynamic scaling properties are very similar in exploration geophysics and medical ultrasound (for a detailed comparison see the paper by Pratt [1]). 
I have been involved in translating imaging methods from seismics to medical ultrasound for some time now. One major project was to apply the interferometry concept [2][3] extensively used for passive seismic imaging with noise sources to setups used for breast cancer screening with ultrasound computed tomography [4][5]. These setups commonly use a 2D ring aperture with transducers (ultrasonic sources and receivers) mounted on the ring. This allows to enclose the breast from all sides, which is from a geophysical point of view a very ideal imaging setup (considering that for the common exploration geophysical imaging setup, we cannot enclose our target, i.e. a part of the subsurface with sources and receivers). 
The accompanying publication can be found [here](https://doi.org/10.1121/10.0011540).


[1] Robert Pratt, Medical ultrasound tomography: lessons from exploration geophysics, _Proceedings of the 1st International Workshop on Medical Ultrasound Tomography_, 2017 [url](https://www.researchgate.net/publication/323295721_Medical_ultrasound_tomography_lessons_from_exploration_geophysics)

[2] Kees Wapenaar, Deyan Draganov, Roel Snieder, Xander Campman, Arie Verdel, Tutorial on seismic interferometry. Part I: Basic principles and applications, _Geophysics_, 2010 [url](https://www.researchgate.net/publication/215754427_Tutorial_on_seismic_interferometry_Part_I_Basic_principles_and_applications)

[3] Kees Wapenaar, Evert Slob, Roel Snieder, Aandrew Curtis, Tutorial on seismic interferometry. Part II: Underlying theory and new advances, _Geophysics_, 2010 [url](https://www.researchgate.net/publication/215754426_Tutorial_on_seismic_interferometry_Part_2_-_Underlying_theory_and_new_advances)

[4] Cuipinl Li, Nebojsa Duric, Peter Littrup, Lianjie Huang, In vivo breast sound-speed imaging with ultrasound tomography, _Ultrasound in Medicine & Biology_, 2009 [url](https://www.sciencedirect.com/science/article/pii/S0301562909002373)

[5] James Wiskin, Bilal Malik, Rajni Natesan, Mark Lenox, Quantitative assessment of breast density using transmission ultrasound tomography, _Medical Physics_, 2019 [url](https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.13503)