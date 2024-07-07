# Deep Learning for monitoring and forecasting natural hazards with earth observation data

![cover_photo](/static/igarss_2024_dl4nh_cover.jpg)

This is the repository for the Tutorial [A Practical Session on Deep Learning Advances for Monitoring and forecasting Natural Hazards](https://www.2024.ieeeigarss.org/tutorials.php#tut6) in IGARSS 2024.

Presented by [Nikolaos-Ioannis Bountos](https://ngbountos.github.io/) (1), [Ioannis Prapas](https://iprapas.github.io) (1, 2), [Spyros Kondylatos](https://github.com/skondylatos/) (1, 2), [Maria Sdraka](https://github.com/paren8esis/) (1), and [Ioannis Papoutsis](https://scholar.google.gr/citations?user=46cBUO8AAAAJ) (1) 

(1) [Orion Lab](http://orionlab.space.noa.gr/), Institute for Astronomy, Astrophysics, Space Applications and Remote Sensing, National Observatory of Athens & National Technical University of Athens

(2) [Image & Signal Processing Group](https://isp.uv.es/), Universitat de València

## Previous Versions

* [2023 DL4NH IGARSS, Pasadena USA](https://github.com/Orion-AI-Lab/igarss23_DL4NH)

## 🕸️ Agenda & Quick Links

| Time          | Title          | Resources                       | Presenter         |
|---------------|----------------|---------------------------------|-------------------|
| 16.00 - 16.15   | Introduction   | [slides](https://docs.google.com/presentation/d/13lw30timAkBxFZdK5bjuVf9pnPOJC3Ut/edit?usp=drive_link&ouid=103666319609428787109&rtpof=true&sd=true)                | Ioannis Papoutsis |
| 16.15 - 17.30  | Spatiotemporal Datacubes for Earth System Modeling | [slides](https://docs.google.com/presentation/d/15KGojGurKJSj3t9N48wKMCVtxVSbSHaN2VboDnwtlDA/edit?usp=drive_link) [notebook](https://colab.research.google.com/drive/1NY-a5cYLLfMwrTFigY5VczKym849MkN4?usp=drive_link)  | Ioannis Prapas    |
| 17.30 - 18.15 | Advanced ML methods for Natural Hazard Monitoring | [notebook](https://drive.google.com/file/d/1uPJv3sqboHExOem9X2q_mzPqfIqeodzk/view?usp=drive_link)                | Nikolaos Bountos, Maria Sdraka  |
| 18.15 - 19.00 |  Probabilistic ML in Natural Hazards| [slides](https://docs.google.com/presentation/d/1wqmp-dySFcVE7bWHFy5O-Nk_mcmiZTQLiDl8YnhFQJ8/edit?usp=drive_link) [notebook](https://colab.research.google.com/drive/1zCruqMbsoQkLWX8UEnt_RnBDQEfBjsdq?usp=drive_link)  | Spyros Kondylatos |

Link to all resources: [gdrive](https://drive.google.com/drive/folders/1kKqHuIQkoLPwgrR3DTbY-ZkRv8CCYM46?usp=drive_link)

## Description

The rapid advances of Deep Learning (DL) combined with the diverse and massive amount of freely available earth observation (EO) data open new paths for monitoring and predicting the risk of natural hazards and assessing their impact. Monitoring (e.g. providing early warnings or estimating the extent of the disaster promptly), as well as risk prediction (e.g. forecasting disasters) can prove to be crucial for decision making, allowing for improved emergency response, potentially reducing the casualties and negative effects. This tutorial will provide a complete guide on the subject, starting from foundational ideas and data handling, to state-of-the-art artificial intelligence methods dealing with a diverse set of natural hazards including wildfires, volcanic activity, floods and earthquakes. The ultimate goal is to attract researchers and geoscientists to work on such crucial tasks and equip them with the necessary tools and knowledge needed to tackle them. In particular, the tutorial will cover applications of DL for all the three stages of the emergency management cycle (forecasting and preparedness, early warning, monitoring and impact assessment), covering the curation of spatio-temporal datasets and presenting common problems in the context of DL for Natural Hazards management, such as lack of labels and naturally occurring class imbalance as well as methods to work around them. Finally, as emergency management requires action, the last part of the tutorial will cover methods that enhance the interpretability of the models with focus on explainable AI and Bayesian methods that provide an estimate of uncertainty. The tutorial will cover different types of remote sensing datasets, including multi-spectral, synthetic aperture (SAR) data, interferometric SAR data along with meteorological, landscape and other geospatial data.

## Learning Objectives

This tutorial aims to train the attending researchers on the use of state-of-the-art artificial intelligence methods to develop early warning, forecasting and monitoring systems for natural hazards using multi-modal remote sensing datasets. The tutorial will be split into two parts. The first part will focus on theoretical aspects, common problems, workarounds, tips and tricks. The second part will involve the demonstration of SoTA methods through Python Jupyter notebooks that can be run by the participants. Due to the nature of DL algorithms requiring significant time to train, toy dataset examples and/or pretrained models will be prepared.

The tutorial will cover the following subjects in particular:

* Spatiotemporal Datacubes for Earth System Modeling:
	* Guidelines on accessing and handling of spatio-temporal datacubes
	* Creation of DL datasets from spatiotemporal datacubes
	* Application of DL pipelines for forecasting problems
	* Common pitfalls and insights on spatio-temporal forecasting
* Advanced ML methods for Natural Hazards
	* Rapid flood mapping using Synthetic Aperture Radar timeseries
	* Wildfire forecasting using Bayesian/uncertainty-aware methods


## Prerequisites

We assume basic knowledge of ML/DL methods, python and earth observation.

In this tutorial, we will provide working examples in the form of Jupyter notebooks along with the necessary data. 

The users are required to have a laptop equipped with a modern browser. 

**An account is required for access to [google colab](https://colab.research.google.com)**.

## Access 

For access to the in-person tutorial, [registration](https://2023.ieeeigarss.org/registration.asp) is needed. All material (jupyter notebooks, presentations) will be made freely available through this repository.

Time: Sun, 7 Jul, 16:00 - 19:00 Easter European Summer Time (EEST)

Location: MC 3 Hall, MAICC, Athens Greece 

## Contact us 

For any communication about this tutorial, [please submit an issue](https://github.com/Orion-AI-Lab/igarss23_DL4NH/issues/new/choose) or [email us](mailto:ipapoutsis@noa.gr).

## Acknowledgements

This work has received funding from the European Union’s research and innovation projects DeepCube and TREEADS, under grant agreement numbers 101004188 and 101036926 respectively.
