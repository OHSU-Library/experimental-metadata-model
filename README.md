# experimental-metadata
*A framework for a simple, domain-independent, and extensible experimental metadata model.*

This repository holds artifacts related to the specification of a simple, domain-independent, and extensible experimental metadata model for describing research objects (ROs) such as datasets, protocols, experimental records, and publications. This work is in its early stages, and initial efforts were funded by [Elsevier](http://www.elsevier.com/). The documents contained here describe requirements and use cases that informed our model, present an environmental scan that identifies related efforts, and presents somme initial straw-man modeling proposals.  More formally defined models and documentation are to come, but at present the *best place to start* is to review the following docs:

* The **slide deck [here](https://github.com/OHSU-Ontology-Development-Group/experimental-metadata-model/raw/master/docs/Brush_Elsevier_Webinar_2015_11_03.pdf)** gives an overview of our work to date.
* The **document [here](https://github.com/OHSU-Ontology-Development-Group/experimental-metadata-model/blob/master/docs/EMM_Summary_2015_11_03.docx?raw=true)** goes into greater detail about certain aspects of the work (e.g. the core concept glossary). 
* The **spreadsheets [here](https://github.com/OHSU-Ontology-Development-Group/experimental-metadata/blob/master/docs/Landscape%20Analysis.xlsx?raw=true)** contain some of the initial landscape analysis efforts we performed to inform our work.


In this work we are clear to distinguish the notion of **general metadata**, which describes attributes of a research object such as a dataset, from that of **experimental metadata**, which describes an experiment related to the dataset. There are many well established standards that can be used to describe general metadata about things like datasets (e.g. [DC](http://dublincore.org/), [DCAT](http://www.w3.org/TR/vocab-dcat/), [PROV](http://www.w3.org/TR/prov-o/)), and recommendations about how to apply these (e.g. the [HCLS Dataset Description Standard](http://www.w3.org/2001/sw/hcls/notes/hcls-dataset/) ). The greater and more interesting challenge is to define standards around capturing experimental metadata - which describes how entities such as **techniques**, **specimens**, and **variables** are applied in an experiment that generated a dataset.


