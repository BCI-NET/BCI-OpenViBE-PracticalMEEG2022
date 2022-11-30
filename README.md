# Brain-Computer Interface (BCI) using OpenViBE, an open-source software platform
---
:computer: Hands-on tutorial organized for [PracticalMEEG conference, December 14 – 16, 2022](https://practicalmeeg2022.org/). Special session: [Toolboxes Bouquet](https://practicalmeeg2022.org/bouquet/)

:clock830: Wednesday, December 14th, 2:00pm – 6:00pm (CEST)

:busts_in_silhouette: Organizers:

* [Arthur Desbois](https://www.linkedin.com/in/arthur-desbois-801a9313a/), Research Engineer, Aramis team-project, Inria Paris, Paris Brain Institute
* [Marie-Constance Corsi](https://marieconstance-corsi.netlify.app), Postdoctoral Researcher, Aramis team-project, Inria Paris, Paris Brain Institute

---

## Audience/Prerequisites
* EEG/MEG users, researchers curious about BCI
* No particular requirement for following the demo. Some basic knowledge in EEG signal processing & machine learning can be helpful!
* Participants interested in using OpenViBE can download the installer from [this page](http://openvibe.inria.fr/downloads/). Linux users need to follow the [build instructions](http://openvibe.inria.fr/build-instructions/)

## Objectives
* Get familiar with the main concepts of BCI
* Discover the main features proposed by OpenViBE 
* Manipulate the fundamental blocks of OpenViBE
* Get a glimpse of more advanced capabilities using OpenViBE
* Getting a hint of the main challenges in BCI research

---
## Timetable

### Introduction - 5'

### Part 1, talks and Q&A - 25'
* What is BCI? Context, paradigms and applications
* What is OpenViBE? 
* Concrete examples of use of OpenViBE
* How does OpenViBE work?
* Q&A-1

### Part 2, Motor Imagery protocol, OpenViBE fundamentals - 2h to 2h30
We will perform a simulation of motor imagery-based BCI experiment with a virtual subject. To this end, we will use OpenViBE to extract, preprocess and classify the EEG data.

* Intro - Prerequisites before performing a MI-BCI experiment
  * Neurophysiological mechanisms
  * Motor imagery-based BCI in practice
* Demo - setting-up the protocol in OpenViBE 
  * Part 1 - Training data acquisition
  * Part 2 - Classifier training scenario
  * Part 3 - Online feedback
  * Optional - More advanced concepts
* Q&A-2

### Concluding remarks & Perspectives - 45'
* Going further with OpenViBE
  * Developing & prototyping OpenViBE boxes
  * Forum, scripts & community 
  * Scenario tutorials
  * External scripting & interfacing using Python
  * Using BCI pipelines easily with *HappyFeat*
* BONUS - BCI research
  * Current challenges
  * Machine & User-centered approaches

---
## Tools & resources
* OpenViBE - [official website](http://openvibe.inria.fr) & [citation](https://hal.archives-ouvertes.fr/hal-00477153)
  * download
  * tutorials
  * technical documentation
  * forum

* Python toolboxes
  * Open datasets and pipelines to perform replicable BCI studies: [Mother of All BCI Benchmarks (MOABB)](https://github.com/NeuroTechX/moabb)
  * M/EEG data analysis: [MNE-Python](https://mne.tools/stable/index.html)
  * Machine Learning tool: [scikit-learn](https://scikit-learn.org/stable/)
  * LSL using Python - [pyLsl](https://github.com/labstreaminglayer/liblsl-Python)

## References
* Papers
  * [[Wolpaw et al, Clin Neurophysiol, 2002]](http://www.sciencedirect.com/science/article/pii/S1388245702000573) -> to start in the BCI domain
  * [[Pfurtscheller et al, Clin Neurophysiol, 1999]](https://www.sciencedirect.com/science/article/abs/pii/S1388245799001418) -> to learn more about event-related EEG/MEG (de)synchronization
  * [[Lotte et al, JNE, 2018]](https://iopscience.iop.org/article/10.1088/1741-2552/aab2f2) -> to learn more about classification algorithms used in EEG-based BCI
 
* Books
  * [[Clerc et al, Wiley, 2016a]](https://www.wiley.com/en-us/Brain+Computer+Interfaces+1%3A+Methods+and+Perspectives-p-9781848218260) -> Methods and Perspectives
  * [[Clerc et al, Wiley, 2016b]](https://www.wiley.com/en-us/Brain+Computer+Interfaces+2%3A+Technology+and+Applications-p-9781848219632) -> Technology and Applications

---
## To go further...
Previous OpenViBE workshops materials:
* [6th International Brain-Computer Interface Conference](http://openvibe.inria.fr/openvibe-workshop-2014-contents/)
* [2016 International BCI meeting](http://openvibe.inria.fr/the-2nd-international-openvibe-workshop-2016-contents/)
* [IEEE International Conference on Systems, Man and Cybernetics (IEEE SMC 2018)](http://openvibe.inria.fr/openvibe-workshop-2018/)
* [CuttingEEG'21 - 5th Symposium on cutting-edge methods for EEG research](https://cuttingeeg2021.org) - [OpenViBE Workshop](https://github.com/Inria-NERV/BCI-OpenViBE-PracticalMEEG2022/)


To learn more about BCI research & events:
* International BCI Society: [Webpage](http://bcisociety.org/)
* French BCI Society: [CORTICO](https://www.cortico.fr/)
* Competitions to promote BCI with end users: [Cybathlon](https://www.youtube.com/watch?v=5jGcNbQhbg8)
