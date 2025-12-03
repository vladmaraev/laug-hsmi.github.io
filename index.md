---
layout: page
---

<div class="buttons" id="sticky-nav">
  <a class="button btn btn-primary" href="#call-for-submissions">Submission Process</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a class="button btn btn-warning" href="#dates">Important dates*</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a class="button btn btn-secondary" href="#schedule">Workshop Schedule</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a class="button btn btn-info" href="#speakers">Speakers</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a class="button btn btn-light" href="#people">People</a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a class="button btn btn-dark" href="#sponsors">Sponsors</a>
</div>

**▶️ Recording Online**: [SlidesLive Access](https://slideslive.com/icml-2025/terrabytes-towards-global-datasets-and-models-for-earth-observation)

**📅 When:** 19 July 2025

**📍 Where:** Vancouver, Canada

**Official workshop schedule on ICML website**: [ICML.cc - TerraBytes 2025](https://icml.cc/virtual/2025/workshop/39951)

**Submission website:** [OpenReview - TerraBytes 2025](https://openreview.net/group?id=ICML.cc/2025/Workshop/TerraBytes)

### About the workshop

Earth Observation (EO) presents unique challenges and opportunities that set it apart from other fields of machine learning
(ML) and computer vision (CV) (Rolf et al., 2024). EO data is abundant, repeatedly covering a large but limited environment:
our planet. The colocation and evolution of these observations is a rich, emergent source of information, of multimodal and
multitemporal nature. However, due to both local and global changes, especially climate change, the statistical distribution
of EO data is inherently non-stationary (Tarasiou et al., 2023). These properties break some of the usual assumptions of
ML, and EO data require special care for data handling and modeling (Mai et al., 2022). In addition, current EO datasets
are sampled with spatio-temporal biases. Some areas, e.g., the global South, are strongly under-represented within EO
datasets (Cornebise et al., 2022). In optical imagery, cloud cover is undesirable, thus leading to datasets that remove cloudy
images at the risk of biasing their geographical coverage (Tiede et al., 2021). Addressing these distributional biases is of
primary importance, as they have an impact on the performance and reliability of models for downstream applications in
ecology, geosciences, agriculture, urban planning, etc. (Kattenborn et al., 2022).

TerraBytes is an initiative to address these challenges. At the intersection of data curation, data archiving, and representation learning, this workshop will
foster a holistic discussion covering major steps in the EO from downlinked satellite data, training paradigms to downstream applications. 

<h3 id="call-for-submissions">Call for submissions</h3>

We invite submissions on the following topics:

* Large-scale Earth observation datasets and benchmarks:
  - curation of new large-scale vision datasets for EO,
  - augmentation techniques for EO data and their impact on learning, data traceability and expansion of existing datasets,
  - re-use and adoption of existing datasets in new scenarios,
  - impact of training data quality and size on downstream tasks under domain shifts.
* Efficient and continual representation learning for remote sensing:
  - weakly and self-supervised learning for EO data,
  - domain adaptation strategies to deal with temporal, geographical or sensor gaps,
  - continual and online learning, to update models when facing distribution shifts,
  - active learning and reinforcement learning.
* Real-world applications:
  - early detection, monitoring and assessment of disasters e.g. floods, landslides, wildfires,
  - large-scale Land Cover and Land Use mapping,
  - 2D and 3D change detection in urban and rural areas,
  - estimation of biophysical parameters (biomass, biodiversity, soil stress, etc.).

<h3 id="submissions">Submission process</h3>

Submission to the TerraBytes workshop is **double-blind**. The workshop accepts short research papers (4 pages, excluding references) and full-length papers (8 pages, excluding references). Authors are required to follow standard ICML paper format ([LaTeX style files](https://media.icml.cc/Conferences/ICML2025/Styles/icml2025.zip)). Short research papers can described work in progress, opinion papers or datasets and research papers that have been already published in another venue (conference or journal) in the last 6 months that are relevant the TerraBytes' topics of interest. For already published works, please submit a summarized four-pages short paper. We are especially looking to broadcast *journal papers* to a larger audience during the workshop.


All submissions should be submitted through [OpenReview](https://openreview.net/group?id=ICML.cc/2025/Workshop/TerraBytes) before the deadline (see important dates below).

{% include figure.html img="https://proceedings.mlr.press/assets/images/logo-pmlr.svg" alt="PMLR Logo" width="25%" %}
Note that the workshop will not publish proceedings under the ICML conference. However, **authors of accepted papers will be able to opt-in for a special issue comprised of the accepted full-length paper in [PMLR](https://proceedings.mlr.press/). Please note that accepted papers will not go through another reviewing process to be published in the PMLR volume. Also, all the papers accepted for the PMLR proceedings are expected to be original contributions (i.e. no dual submissions are allowed).**
All submissions will be reviewed by at least two non-conflicting reviewers. All papers will be presented during a dedicated poster session. Full-length papers and selected short papers will also be presented as spotlight presentations throughout the day.

It is expected that at least one author of each accepted paper will register for the workshop and present the article during the event. Online presentations will be considered for presenters that are not allowed to come, e.g. to visa or personal constraints. If you have any questions, do not hesitate to contact the organizers (see contacts below).

<h3 id="dates">Important dates</h3>
---

* Papers submission deadline: **May 23rd, 2025** (extension!) ~~**May 16th, 2025**~~
* Papers acceptance notification: June 9, 2025
* Pre-recorded 5 minutes video: July 7th 23:59 AoE, 2025
* Camera-ready: TBD
* Workshop: July 19, 2025

<h3 id="schedule">Program</h3>
---

**Morning session**

* 9:00-9:10: Opening remarks [[Watch Online]](https://slideslive.com/39044616/opening-remarks?ref=folder-199217)
* 9:10-9:50: **Keynote: Sujit Roy** (NASA IMPACT) *"Building Scientific AI Foundation Models for Earth"* [[Watch Online]](https://slideslive.com/39044617/building-scientific-ai-foundation-models-for-earth?ref=folder-199217)
* 9:50-10:10: **Paper spotlights:** Benchmarks and Deployments
* Coffe break
* 10:40-11:20: **Keynote: Razvan Cosac** (ESA Ground Segment) *"From TerraBytes to PetaBytes: ESA Earth Observation Framework and Copernicus Data Ecosystem"* [[Watch Online]](https://slideslive.com/39044622/from-terrabytes-to-petabytes-esa-earth-observation-framework-and-copernicus-data-ecosystem?ref=folder-199217)
* 11:20-12:00: **Paper spotlights:** Multimodality

**Afternoon session**

* 13:15-14:00: **Paper spotlights:** New Methods
* 14:00-15:00: **Poster session**
* Coffee break
* 15:30-16:10: **Keynote: Erin Trochim** (University of Alaska Fairbanks) *"Building Trust in GeoAI and Earth Observations: Lessons from Complex Systems"* [[Watch Online]](https://slideslive.com/39044635/building-trust-in-geoai-and-earth-observations-lessons-from-complex-systems?ref=folder-199217)
* 16:10-17:10: **Panel session:** *"Towards Global Geospatial Models"* [[Watch Online]](https://slideslive.com/39044636/panel-session?ref=folder-199217)
  * Ritwik Gupta, Incoming Assistant Professor at the University of Maryland
  * Tanya Nair, Senior Machine Learning Engineer at Floodbase
  * Ryan Avery,Senior Machine Learning Engineer at Wherobots
  * Mikhail Klassen, Senior Machine Learning Engineer at Planet
* 17:10-17:20: European Space Agency [Copernicus AI Report](https://asterisk.coop/project-pages/project-copernicus-report.html): Stakeholder Feedback Session [[Watch Online]](https://slideslive.com/39044637/copernicus-feedback?ref=folder-199217)
* 17:20-17:30: Closing remarks [[Watch Online]](https://slideslive.com/39044638/closing-remarks?ref=folder-199217)

<h3 id="speakers">Speakers</h3>
---

**Sujit Roy** (NASA IMPACT)
> Dr. Sujit Roy works as a Lead AI Researcher and Computer Scientist at NASA’s Interagency Implementation and Advanced Concept Teams (IMPACT), where he leads the development of foundational models for analyzing satellite imagery, enhancing weather forecasting and Heliophysics, resulting in multiple practical scientific applications. Prior to his tenure at NASA IMPACT, Dr. Roy contributed to the field of Explainable AI at the University of Manchester. He received his PhD (UKIERI fellowship) in Computer Science from Ulster University in collaboration with the Indian Institute of Technology Kanpur, India. In his PhD, he contributed to the domain of Computational Neuroscience by developing algorithms for Advancing MEG- and EEG-Based Decoding of Motor Imagery for Practical Brain-Computer Interfaces. 

**Razvan Cosac** (ESA Ground Segment)
> Razvan has a background in Earth Sciences and has been working in the Earth observation domain for the past 12 years. He joined the European Space Agency (ESA) in 2013 as a Young Graduate Trainee working as part of the Long Term Data Preservation programme. He then continued his career in industry, working on various ESA projects regarding the processing, consolidation, archiving and dissemination of EO satellite imagery. Razvan rejoined ESA in 2019 as Copernicus Ground Segment Engineer, where he contributed to the Copernicus Space Component (CSC) ESA Earth Observation Framework (EOF) and data management operations, focusing on the data access and dissemination activities. Razvan is currently managing several ESA CSC EOF service operations contracts in this domain, the largest and most impactful one being the coordination of the Copernicus Data Space Ecosystem (CDSE).

**Erin Trochim** (University of Alaska Fairbanks)
> Erin Trochim is a geospatial data scientist developing better data and decisions for energy and its uses in the north. She values a collaborative approach to research. During 2022, she was a project lead for the University of Washington’s Data Science for Social Good program and is a co-investigator for the NSF Research Experience for Undergraduates at ACEP. PredictFest, a hackathon event founded by Trochim, was most recently supported by NSF’s Navigating the New Arctic initiative. She was an inaugural Google Cloud Research Innovator in 2021. Trochim earned a Ph.D. in remote sensing and hydrology from UAF, supported by a NASA Earth and Space Science graduate fellowship. Her postdoctoral experience included producing permafrost information for policy application through the NSF SEARCH program with the Alaska Climate Adaptation Science Center. Present energy-related projects include the Railbelt Decarbonization study, the Arctic Energy Atlas, and creating environmental data for marine and hydrokinetic applications. Trochim is from Whitehorse, Yukon, Canada. Winter is her favorite season; her huskies keep her active with skijoring long distances, which helps during masters ski club training.

<h3 id="papers">Accepted papers</h3>

See all accepted papers on [OpenReview](https://openreview.net/group?id=ICML.cc%2F2025%2FWorkshop%2FTerraBytes).

<h4>Long papers</h4>

**Label-Efficient Hyperspectral Image Classification via Spectral FiLM Modulation of Low-Level Pretrained Diffusion Features** [OpenReview](https://openreview.net/forum?id=l9wTrSu9i9)
*Yuzhen Hu, Biplab Banerjee, Saurabh Prasad*
        
**Smoothing Continual Segmentation Oscillations with Latent Domain PPCA Decoder** [OpenReview](https://openreview.net/forum?id=gLzh8JDIpp)
*Marie-Ange Boum, Pierre Fournier, Dawa Derksen, Stéphane Herbin*

**High-Resolution LFMC Maps for Wildfire Risk From Multimodal Earth Observation Data** [OpenReview](https://openreview.net/forum?id=DxVmDkRYTV)
*Patrick Alan Johnson, Gabriel Tseng, Yawen Zhang, Heather Heward, Virginia Sjahli, Favyen Bastani, Joseph Redmon, Patrick Beukema*
      
**Optimizing Cloud-to-GPU Throughput for Deep Learning With Earth Observation Data** [OpenReview](https://openreview.net/forum?id=Kqse3quRaX)
*Akram Zaytar, Caleb Robinson, Girmaw Abebe Tadesse, Tammy Glazer, Gilles HACHEME, Anthony Ortiz, Rahul M Dodhia, Juan M Lavista Ferres*

**Shaping Fine-Tuning of Geospatial Foundation Models: Effects of Label Availability and Temporal Resolution** [OpenReview](https://openreview.net/forum?id=CLTEaA2mtC)
*Giovanni Castiglioni, Nicolás Gonzalo Isla Fernández, Cristian Buc Calderon, Javiera Castillo Navarro, Sébastien Lefèvre, Valentin Barriere*
    
**The Cloud-Based Geospatial Benchmark: Challenges and LLM Evaluation** [OpenReview](https://openreview.net/forum?id=oaYShIy3Xe)
*Jeffrey A. Cardille, Renee Johnston, Simon Ilyushchenko, Johan Kartiwa, Zahra Shamsi, Matthew Abraham, Khashayar Azad, Kainath Ahmed, Emma Bergeron Quick, Nuala Caughie, Noah Jencz, Karen Dyson, Andrea Puzzi Nicolau, Maria Fernanda Lopez-Ornelas, David Saah, Michael Brenner, Subhashini Venugopalan, Sameera S Ponda*
    
**AirCast: Improving Air Pollution Forecasting Through Multi-Variable Data Alignment** [OpenReview](https://openreview.net/forum?id=bUJt8lifOT)
*Vishal Nedungadi, Muhammad Akhtar Munir, Marc Rußwurm, Ron Sarafian, Ioannis N. Athanasiadis, Yinon Rudich, Fahad Shahbaz Khan, Salman Khan*

**Resampling Augmentation for Time Series Contrastive Learning: Application to Remote Sensing** [OpenReview](https://openreview.net/forum?id=K2AIo78B9V)
*Antoine Saget, Baptiste Lafabregue, Antoine Cornuéjols, Pierre Gançarski*

**Deploying geospatial foundation models in the real world** [OpenReview](https://openreview.net/forum?id=eHW9HWitP0)
*Christina Butsko, Gabriel Tseng, Kristof Van Tricht, Giorgia Milli, David Rolnick, Ruben Cartuyvels, Inbal Becker Reshef, Zoltan Szantoi, Hannah Kerner*

**Where are the Whales: A Human-in-the-loop Detection Method for Identifying Whales in High-resolution Satellite Imagery** [OpenReview](https://openreview.net/forum?id=Qn3Zsu35Fu)
*Caleb Robinson, Kimberly T. Goetz, Christin B. Khan, Meredith Sackett, Kathleen Leonard, Rahul M Dodhia, Juan M Lavista Ferres*

**Using Multiple Input Modalities can Improve Data-Efficiency and O.O.D. Generalization for ML with Satellite Imagery** [OpenReview](https://openreview.net/forum?id=p5nSQMPUyo)
*Arjun Rao, Esther Rolf*

<h4>Short papers</h4>

**High-Performance Lightweight Vision Models for Land Cover Classification with Coresets and Compression** [OpenReview](https://openreview.net/forum?id=fZ6Jj51tNj)
*Tushar Shinde*

**Enhancing Generative Seismic Modeling via Proposed Paired Dataset Construction Method** [OpenReview](https://openreview.net/forum?id=JmT8P9nudc)
*Jaehyuk Lee, Jaeheun Jung, Hanyoung Kim, Chang-Hae Jung, Donghun Lee*

**Less is More? Data Specialization for Self-Supervised Remote Sensing Models** [OpenReview](https://openreview.net/forum?id=2nS8UcH2VG)
*Alvard Barseghyan, Ani Vanyan, Hakob Tamazyan, Evan Shelhamer, Hrant Khachatrian*

**Open-source federated learning across multi cloud environment** [OpenReview](https://openreview.net/forum?id=qcEiUMXZTn)
*Leonardo P. Tizzei, Gabrielle Nyirjesy, Levente J Klein, Theodore van Kessel, Maciel Zortea, Marcus Freitag, ILDAR KHABIBRAKHMANOV, Hendrik Hamann, Kamal Das*

**A Multimodal Deep Learning Framework for Locating Nomadic Pastoralists to Strengthen Public Health Outreach** [OpenReview](https://openreview.net/forum?id=qHf2txksNZ)
*Benjamin Liu, Stace Maples, Jessie Kong, Francesco Fava, Nathaniel Jensen, Philemon Chelanga, Sergio Charles, Theodore Utomo, Aritro Chatterjee, Kevin Zhu, James Hassell, Lance W. Robinson, Luke Glowacki, Michele Barry, Hannah Wild*

**GeoCrossBench: Cross-Band Generalization for Remote Sensing** [OpenReview](https://openreview.net/forum?id=7MNndxX1Xq)
*Hakob Tamazyan, Ani Vanyan, Alvard Barseghyan, Anna Khosrovyan, Evan Shelhamer, Hrant Khachatrian*

**The Missing Piece: Standardising for AI-ready Earth Observation Datasets** [OpenReview](https://openreview.net/forum?id=HV6F0dsGLK)
*Cesar Aybar, Julio Contreras, Chen Ma, Oscar J. Pellicer-Valero, Gonzalo Mateo-García, Luis Gómez-Chova, Gustau Camps-Valls, Nils Lehmann, Mikolaj Czerkawski, David Montero, Miguel D. Mahecha, Ingrid Aybar*

**Towards Scalable Foundation Model for Multi-modal and Hyperspectral Geospatial Data** [OpenReview](https://openreview.net/forum?id=PuOclbrcO6)
*Haozhe Si, Yuxuan Wan, Minh N. Do, Deepak Vasisht, Han Zhao, Hendrik Hamann*

**Galileo: Learning Global & Local Features of Many Remote Sensing Modalities** [OpenReview](https://openreview.net/forum?id=a2Qn7lTYWL)
*Gabriel Tseng, Anthony Fuller, Marlena Reil, Henry Herzog, Patrick Beukema, Favyen Bastani, James R Green, Evan Shelhamer, Hannah Kerner, David Rolnick*

**End-to-End Reconstruction of High-Resolution Temperature Data Using Physics-Guided Deep Learning** [OpenReview](https://openreview.net/forum?id=zMIlyzDf3p)
*Shengjie Liu, Lu Zhang, Siqin Wang*

**Transfer Learning for Onboard Cloud Segmentation in Thermal Earth Observation: From Landsat to a CubeSat Constellation** [OpenReview](https://openreview.net/forum?id=XEfg5YE5Mw)
*Niklas Wölki, Lukas Kondmann, Christian Mollière, Martin Langer, Julia Gottfriedsen, Martin Werner*

**Landsat-Bench: Datasets and Benchmarks for Landsat Foundation Models** [OpenReview](https://openreview.net/forum?id=ab70e2WB19)
*Isaac Corley, Lakshay Sharma, Ruth Crasto*

**Towards LLM Agents for Earth Observation** [OpenReview](https://openreview.net/forum?id=1ozeeVxfNd)
*Chia Hsiang Kao, Wenting Zhao, Shreelekha Revankar, Samuel Speas, Snehal Bhagat, Rajeev Datta, Cheng Perng Phoo, Utkarsh Mall, Carl Vondrick, Kavita Bala, Bharath Hariharan*

<h3 id="people">People</h3>
---

<h4 id="organizers">Organizers</h4>
---
* [Nicolas Audebert, LASTIG, IGN](https://nicolas.audebert.at)
* [Hossein Azizpour, KTH Royal Institute of Technology](https://www.csc.kth.se/~azizpour/)
* [Valentin Barriere, University of Chile](https://www.copernicuslac-chile.eu/en/persona/valentin-barriere/)
* [Javiera Castillo Navarro, CNAM](https://javi-castillo.github.io/)
* [Mikolaj Czerkawski, Asterisk Labs](https://mikonvergence.github.io/)
* [Heng Fang, KTH Royal Institute of Technology](https://hfangcat.github.io/)
* [Alistair Francis, Asterisk Labs](https://asterisk.coop/)
* [Valerio Marsocci, ESA Phi Lab](https://sites.google.com/uniroma1.it/valeriomarsocci)
* [Andrea Nascetti, KTH Royal Institute of Technology](https://www.kth.se/profile/nascetti)
* [Ritu Yadav, KTH Royal Institute of Technology](https://www.linkedin.com/in/ritu-yadav-5a810158/)

<h4 id="committee">Program committee</h4>
---
* Adam J Stewart, Technische Universität München
* Alistair Francis, Asterisk Labs
* Andrea Nascetti, KTH Royal Institute of Technology
* Anna Jungbluth, European Space Agency
* Arjun Rao, University of Colorado at Boulder
* Arnaud Breloy, Conservatoire national des arts et métiers
* Burak Ekim, Universität der Bundeswehr München
* Cassio Fraga Dantas, INRAE
* Cesar Aybar, Universidad de Valencia
* Charlotte Pelletier, Université de Bretagne Sud
* Diego Marcos, INRIA
* Dino Ienco, National Institute for Agriculture, Environment and Food
* Elliot Vincent, Institut national de l'information géographique et forestière
* Emanuele Dalsasso, EPFL - EPF Lausanne
* Eric Brune, KTH Royal Institute of Technology
* Gencer Sumbul, EPFL - EPF Lausanne
* Georges Le Bellier, Conservatoire national des arts et métiers
* Guillaume Astruc, ENPC, Ecole Nationale des Ponts et Chausees
* Heng Fang, KTH Royal Institute of Technology, Stockholm, Sweden
* Hongruixuan Chen, The University of Tokyo
* Jakob Gawlikowski, Technische Universität München (TUM)
* Javiera Castillo Navarro, Conservatoire national des arts et métiers
* Jente Bosmans, European Space Agency
* Kelsey Doerksen, University of Oxford
* Kriti Goyal, Apple
* Loic Landrieu, Ecole Nationale des Ponts et Chausees
* Lorenzo Papa, European Space Agency
* Marc Rußwurm, Wageningen University
* Marcin Kluczek, University of Warsaw
* Mathilde Letard, Technische Universität München
* Miguel Espinosa, University of Edinburgh, University of Edinburgh
* Mikolaj Czerkawski, Asterisk Labs
* Nicolas Audebert, Ecole Nationale des Sciences Géographiques
* Nikolaos Dionelis, European Space Agency
* Patrick Ebel, European Space Agency
* Peter Jack Naylor, ESA
* Pierre Adorni, IRISA, Université Bretagne Sud
* Rachael Joanne Laidlaw, University of Bristol
* Ramesh Nair, Planet Labs
* Riccardo Contu, University of Roma "La Sapienza"
* RITU YADAV, KTH Royal Institute of Technology
* Robert Cowlishaw, University of Strathclyde
* Ruben Cartuyvels, European Space Agency
* Saba Gachpaz, University of Roma "La Sapienza"
* Sebastian Gerard, KTH Royal Institute of Technology
* Sebastian Hafner, University of Glasgow
* Silvia Valero, IRD
* Sophie Giffard-Roisin, University of Grenoble-Alpes
* Sylvain Lobry, Université Paris Cité
* Valentin Barriere, Universidad de Chile
* Valerie Zermatten, EPFL - EPF Lausanne
* Valerio Marsocci, European Space Agency
* Vishal Nedungadi, Wageningen University
* Vit Ruzicka, Department of Computer Science
* Xikun Hu, National University of Defense Technology
* Yuru Jia, KU Leuven
* Zhuo Zheng, Stanford University

**Primary Contacts**: Valerio Marsocci (valerio.marsocci@esa.int), Nicolas Audebert (nicolas.audebert@ign.fr)

<h3 id="sponsors">Sponsors</h3>
------

We thank CopernicusLAC and CMM for their sponsorship of this event. This event received funding from Proyecto Basal ANID FB210005.

{% include figure.html img="logo_copernicuslac_chile.png" alt="CopernicusLAC Chile sponsor" width="25%" %}
{% include figure.html img="logo_CMM_25_EN_color.png" alt="CMM CNRS sponsor" width="25%" %}

