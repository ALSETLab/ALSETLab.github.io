---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

---
# Research Areas

I work in the engineering domains of electrical power systems (power grid), electrified aircraft, and combined energy systems (e.g. heat and power networks, power-to-X).

Where I am interested in applying:
* Modeling and simulation using object-oriented equation-based formalisms via the Modelica language, for multi-domain system integration, for example to model power systems or the electrical propulsion system of aircrafts.
* Real-time simulation, hardware-in-the-loop simulation, controller hardware-in-the-loop simulation, power-hardware-in-the-loop simulation for testing of methods, software tools or technologies for control and protection.
* System Identification Methods for measurement-based identification of cyber-physical power system models, monitoring technics and control systems.
* Measurement technologies and analytics (PMU Applications).
* AI and machine learning for designing, operating and decision making in power systems.

and developing/supporting/using open source software and open access standards.

---

# Research Projects
## Current Research Projects
- (2022 - 2024) NSF-funded project: "Enhanced Power System Resiliency through Adaptive Automatic Remedial Action Selection using Multi-Agent Reinforcement Learning", with [Dr. Tetiana Bogodorova](https://ecse.rpi.edu/people/research-scientist/tetiana-bogodorova) as CO-PI.
  - Abstract: see the published abstract in NSF's website, [here](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2231677).
  - Note: to be completed in 2025, under 6-month no cost extension.
- (2020 - 2024) DOE-funded project "OpTEN": [Optimal Co-Design of Integrated Thermal-Electrical Networks and Control Systems for Grid-interactive Efficient District (GED) Energy Systems](https://sites.psu.edu/sbslab/research/city/grid-interactive-efficient-district-energy-system/).
  - Abstract: see project website [here](https://sites.psu.edu/sbslab/research/city/grid-interactive-efficient-district-energy-system/) and a summary slide-set (circa 2022) [here](https://www.energy.gov/sites/default/files/2022-09/3.07%20-%20Baker%20and%20Zuo.pdf).
  - Note: to be completed in 2025, under 6-month no cost extension.

To be updated, some may be missing...

## Long Term Research Projects  

- The [OpenIPSL.org](http://openipsl.org) project works in the development of a Modelica library for power system dynamic modeling and simulation. It is the bases for my work on cyber-physical power system design and analysis methods. This project is a continuation of work started in 2012 in the use of the Modelica language for power systems.
  - See [OpenIPSL.org](http://openipsl.org) for members, results and documentation.
  - Currently partially supported by [this project](https://sites.psu.edu/sbslab/research/city/grid-interactive-efficient-district-energy-system/).
  - Contact me to support this project!

- [ALSETLab](https://alsetlab.github.io/lab/): a time-sensitive and real-time simulation-based hardware & software development and testing platform for cyber-physical power systems with power hardware-in-the-loop smart inverter testing capabilities.
    - Currently unfunded.
    - Contact me to donate equipment, or to support this project further!

## Past Research
### Past Funded Research in the USA (Partial List, incomplete, ask for more details if interested)
- (2024) New York Independent System Operator (NYISO) Funded Project: "Analysis of Embedded High Voltage Direct Current (HVDC) Links in a Synchronous Dispatch Zone".
  - Abstract: High Voltage Direct Current (HVDC) technologies have been adopted for the development of two important projects in New York State, the Champlain Hudson Power Express (CHPE) and Clean Path New York (CPNY, https://www.cleanpathny.com/). CHPE will link New York City with clean energy resources in Quebec through underwater and underground HVDC facilities for 339 mi (546 km) and at a rating of 1,200 MW. Meanwhile, CPNY will build a 175 mi (28 km) underground and submarine link from Delaware County and the Hudson River transporting up to 1,300 MW. To understand the amount of power these HVDC lines will carry, consider the Robert Moses Niagara Hydroelectric Power Station, NYS’ largest electricity producer that has an installed capacity of 2,525 MW. This implies that roughly, each of this HVDC lines will transport ½ Niagara’s capacity, and consequently, any factors that impact their operation would have important consequences to reliability and resiliency of the overall NYS grid. More importantly, while CHPE is asynchronous (i.e., its terminals are in two non-synchronized grids), CPNY is within a single dispatch zone operated by the NYISO. Consequently, continuous operation of HVDC lines must be carefully planned out through steady-state, dynamic and electro-magnetic transient studies to avoid unforeseen technical operational challenges that if not properly addressed, may result in the malfunctioning, poor operation, under-performance of such advanced technologies. This project aims to address some fundamental aspects of these embedded HVDC links.

- (2020 - 2024) Integrated Hardware-in-the-Loop Testing of Converter-Interfaced Distributed Energy Resources. Funded by the New York State Energy Research and Development Agency (NYSERDA) under Agreement No. 149165.  Collaboration with Smarter Grid Solutions, NY. Selected as winner of the [“Future Grid Challenge,” of NYSERDA](https://news.rpi.edu/content/2020/07/08/state-support-rensselaer-lab-play-key-role-integration-solar-power).
  - Abstract: In this project, Orange and Rockland Utility (O&R) seeks to understand smart inverter functions and develop procedures that will help grid operators utilize their grid support functions. The underlying problem is that the required standards and operating procedures to integrate smart inverter protocols have not been implemented in the field. Concerns also exist that grid support functions may not work when called upon, either autonomously or manually, or there may be yet undiscovered operating issues that have not been fully addressed. Left unresolved, these issues create a lack of understanding and confidence in new smart inverter technology that can lead to degraded grid performance and missed opportunities from smart inverter technology. This demonstration project aims to provide a suite of testing environments that will be used to validate smart inverter functions. At RPI, a real-time power hardware-in-the-loop simulation testbed is being developed to perform testing of the different inverter control functions and testing of the integration of smart inverter interoperability capabilities into a larger DistributedEnergy Resource Management System (DERMS) and Advanced Distribution Management System (ADMS) platforms.
- (2021 - 2024), “Cloud-based integrated model-and-measurement analytics for power system applications,” funded by Dominion Energy, Richmond, Virginia.
   - Abstract: This project aims at the deployment of interoperable and portable models of major generation assets at Dominion Energy, and their integration with measurements within a cloud-based system, the PingThings platform, used at Dominion energy. To this end, a number of power plant models needed have been developed in the Modelica language and validated against PSS/E. Next, work on automated Modelica model assembly starting from PSS/E files and the automated generation of Functional Mockup Units was conducted. This has resulted in a new tool capable of taking power plant models and producing both Modelica models based on the OpenIPSL library with their corresponding FMUs. The models are being deployed and integrated with measurements in the PredictiveGrid platform, where generic model calibration, ambient data-based model calibration, trajectory sensitivities and sensitivity analysis with uncertainty quantification, and estimation analytics are being developed.

- (2019-2022) CHEETA: NASA ULI Center for Cryogenic High-Efficiency Electrical Technologies for Aircraft, website: [here](https://cheeta.illinois.edu/)
  - Funded by NASA University Leadership Initiative (ULI), see [here](https://nari.arc.nasa.gov/uliround2)
  - PI: [Prof. Phillip J. Ansell (UIUC)](https://aerospace.illinois.edu/directory/profile/ansell1)
  - RPI Co-PI: Prof. Luigi Vanfretti
  - Abstract: The aeronautics industry has been challenged on many fronts to increase efficiency, reduce emissions, and decrease dependency on carbon-based fuels. With subsonic transports serving as the dominant contributor to the carbon footprint of global aviation, these aggressive goals have been met with a boom of research in the field of aircraft propulsion electrification across industry, government, and academic organizations. Most recently, a number of studies have revealed the viability of turboelectric and hybrid-electric aircraft systems for future commercial aircraft, though these studies have definitively identified battery energy storage as a key technological bottleneck to the near- and mid-term feasibility of commercial transport-class aircraft propulsion hybridization. In order to overcome this technological issue, the proposed ULI study will introduce the development of a Cryogenic Hydrogen-Energy Electric Transport Aircraft (CHEETA) design concept. The research activities of this ULI program will lead to ground-level technological development and conceptual design of a fully-electric, commercial aircraft architecture that utilizes liquid hydrogen energy storage with fuel cell energy conversion and an electrically- driven distributed propulsion system. This vehicle concept will utilize an on-board cryogenic system to store and maintain liquid hydrogen, which is used not only as an energy storage strategy, but also to enable highly efficient superconducting electric systems.
  - Additional Information:
    - See the news release from RPI by [clicking here](https://news.rpi.edu/content/2019/05/28/electrical-and-systems-engineers-support-nasa-funded-research-electric-aircraft).
    - See the news release from UIUC by [clicking here](https://grainger.illinois.edu/news/30918).

- (2021) Methods and Tools for Continuous Model Development, Testing and Verification, funded by the Oak Ridge National Laboratory, Oak Ridge, TN.
   - Abstract: The purpose of this project was to create a methodology and a prototype software toolchain for continuous integration, testing and verification of simulation models using web technologies for automation. The work required collaboration between ORNL and RPI to define functional requirements, for which surveys among specialists were conducted to determine the needed functionalities. After the initial definition of functional requirements of the software toolchain, the workflow for continuous integration of Modelica models has been developed using GitHub Actions, making the approach entirely based on web-based technologies. An example of running a Modelica model through GitHub Actions functionalities has been provided to illustrate the potentialities of this new approach. Finally, some guidelines about the modeling process for Modelica models have been described.

- (2020-2021) Model Validation Workflows for Dominion Energy’s Power Plants Leveraging Modelica and the FMI Technologies, funded by Dominion Energy, Richmond, Virginia.
  - Abstract: This project aimed at the development of a proof of concept software workflow enabling model validation within the measurement-based PredictiveGrid platform used at Dominion Energy. The work was divided into the following major tasks. First a list of generator station units (GSUs) provided by Dominion Engineers were modeled in Modelica. This required expanding the component models available in the OpenIPSL library in order to assemble GSU models. This was followed by a software-to-software model verification of the GSU models developed with the Modelica language against a traditional tool that is PSS/E. Next, to leverage the value of these models within Dominion, integration with the PingThings platform was needed. Hence, a proof-of-concept workflow that used the models within the PredictiveGrid platform to perform model validation was developed. This required to survey available Python-based tools that could be deployed within the platform and to prototype a workflow consisting of several Jupyter Notebooks to mimic how Dominion Engineers would perform model validation tasks. From the modeling end, bringing the GSU models into the cloud was facilitated by rearranging the developed GSU models and exporting them as a Functional Mock-up Unit that included C-source code, so that they could be run in the platform. From the modeling validation end, the models were coupled with real-world data processed in Python, and with an open source optimization tool to perform parameter calibration. The proof of concept was demonstrated by calibrating one of the plants, retrieving the real measurements data, processing and using it for estimating parameters of the selected plant model exported as FMU. The obtained results show that the proposed solution, as proof-of-concept, can be further developed for an extensive use in power systems models calibration.

- (2019-2022) GridX: The Autonomous Grid Digital Grid
  - Funded by the Center of Excellence for NEOM Research at King Abdullah University of Science and Technology, Saudi Arabia.
  - PI: [Prof. Shehab Ahmed](https://www.kaust.edu.sa/en/study/faculty/shehab-ahmed)
  - RPI Co-PI: Prof. Luigi Vanfretti
  - Abstract: The ‘Future of Energy’ envisioned by [NEOM](https://www.neom.com/) challenges the energy community to rise above today’s incremental development and deployment of power grid technologies. The city envisions a 100% renewables powered electrical infrastructure fed by any renewable source (solar, wind, geothermal, algae...). Furthermore, city planners have been mandated to minimize CAPEX intensive centralized infrastructure in favor of a modular distributed infrastructure that can grow with the city’s needs. The project aims to develop the knowledge needed to design a scalable, reconfigurable, self- optimizing, self-organizing electrical power network that ensures sustainable, economic and reliable performance while systematically integrating energy in all forms.

- (2019-2021) Mitigation and Modeling for Ground Fault Over-Voltages of Inverter-Based Distributed Energy Resources
  - Funded by NYSERDA through the Electric Power Transmission and Distribution (EPTD) High Performing Grid Program Program Opportunity Notice (PON) 3770.
  - RPI PI: Prof. Luigi Vanfretti
  - In collaboration with JEM Engineering Services LLC, Project Manager: [Michael Ruppert](https://www.linkedin.com/in/michael-ruppert-8935856/).
  - Abstract: This project proposes an Hardware-In-the-Loop-based demonstration of the fast overvoltage detection capability within DER inverters. The result will be educational materials for NY and other utilities regarding real-world inverter capabilities in this regard and help to show under which conditions grounding bank transformers are effective. The project consists of 3 parts, first it aims to illustrate how the fast overvoltage detection within the inverter maintains effective grounding, secondly to provide inverter simulation models, and lastly develop guidelines for future simulation models.

- (2018-2021) (BableGrid) Model Translations for Smart Grid Applications Study
  - Funded by NYSERDA through the Electric Power Transmission and Distribution (EPTD) High Performing Grid Program Program Opportunity Notice (PON) 3770.
  - RPI PI: Prof. Luigi Vanfretti
  - In collaboration with New York Power Authority, Advanced Grid Innovation Lab for Energy (AGILe), and managed by [George Stefopoulos](https://www.linkedin.com/in/georgestefopoulos/).
  - Abstract: The current state of modeling and simulation technologies in the power industry results in a complex model management problem where models that only operate in specific tools need to be developed, maintained/updated, homogenized within that specific tool only. Such model management issues create not only modeling intractability and uncertainty, but also unnecessarily limit engineers from utilizing and exploiting to the fullest a large number of diverse and powerful simulation tools. Currently, the great majority of studies are done with a single software tool (PSS/E), and this fact creates barriers for the utilization and understanding provided by other analysis tools and methods. This project aims to survey, analyze, select and adopt methods and tools from computer science to enable model management using the latest advances in the field of model-driven software engineering (MDE). The developed methods and technologies can become the cornerstone of high-efficiency model management while at the same time providing model users with model views in multiple simulation platforms.
  - Additional Information: see the news release [here](https://www.nypa.gov/news/press-releases/2019/20190717-rensselaer).

- (2018-2021) (DeepGrid) Deep Learning for Resilient Grid Operation Study
  - Funded by NYSERDA through the Electric Power Transmission and Distribution (EPTD) High Performing Grid Program Program Opportunity Notice (PON) 3770.
  - RPI PI: Prof. Luigi Vanfretti
  - In collaboration with New York Power Authority, Advanced Grid Innovation Lab for Energy (AGILe), and managed by [Atena Darvishi](https://www.linkedin.com/in/atenad/).
  - Abstract: This project proposes to develop a Machine Learning (ML)-based software tool capable of providing early warnings for current operating conditions, and more importantly, a “recommender system” capable of providing potential preventive or corrective actions to operators. This will be achieved by combining the predictive power of model-based power system simulation and early warnings from synchrophasor data & applications. The goal is to enable rapid operational decision support, moving forward from today’s real-time monitoring into predictive analytics and fast decision making. This tool aims to enhance the operation of generation and transmission assets and to increase its power transmission by avoiding the constrains that today’s conservative operation limits impose while at the same time enable fast decision making during severe events through fast decision-making using recommender systems, and thus, the proposed system would allow utilities to plan for daily operations as well as for the unexpected with invaluable cost savings.
  - Additional Information: see the news release [here](https://www.nypa.gov/news/press-releases/2019/20190717-rensselaer).

- (2018-2019) Flexible Alternating Current Transmission System Modeling and Performance Analysis using Measurement Data
  - Funded by [Dominion Energy](https://www.dominionenergy.com/).
  - Abstract: With the complexity of the control systems and operational modes of Dominion Energy STATCOMs, and existing fleet of SVCs and STATCOMs, this study will evaluate actual measurement data STATCOMs to evaluate their performance and response to system events (such as faults, generation trips, and other dynamic events).  These evaluations will be critical to ensuring we have the accurate settings, control set points, and operational modes enabled for our new STATCOMs to ensure the correct and proper response to these events throughout the many different system events that occur on our grid. To evaluate the measurement data, simulation models of Dominion’s STATCOMs will be developed in the Modelica language and compared to existing models from conventional simulation tools. Different disturbances will be analyzed to assure that the models in Modelica provide the same response, and then, the models will be used to asses the performance of STATCOMs.

- (2018) Computer Model Architecture and Requirements Study: Integrating an Energy Transfer Station Storage Facility (300 kW Fuel Cell, 1 MW Electrolyzer) with Distributed Energy Resources (DER) interfaced to the grid
  - Funded by the [Standard Hydrogen Corporation](http://www.standardhydrogencorp.com/).
  - Abstract: This project developed an initial object-oriented computer model architecture and associated modeling and simulation requirements that can be re-used: (i) to study multi-domain (electrical, electrochemical, and digital control) aspects of the SHC-ETS (Standard Hydrogen Corporation's Energy Transfer Station ), (ii) to explore different electrical designs and power electronic conversion configurations for SHC-ETS grid integration to maximize renewable energy (e.g.: PV, wind, hydro, etc.) harnessing, and (iii) to address system integration requirements for the overarching sensor, dispatch control and communication architectures for integrated SHC-ETS

- (2018) NeuralNet Foundations for the GridCortex Platform
  - Funded by [NeuralNet](https://www.cebip.org/neuralnet).
  - Abstract: This project carried out the the design of a first-of-a-kind smart grid platform for multi-tier sensing, communication and data-based monitoring and control applications to facilitate enhanced management of renewable and distributed energy sources at different voltage levels and from disparate generation sources.

### Major Funded Projects in Europe
Below, I list only the most relevant and large projects that I've carried out in my past career in Europe, in order of relevance; the ones that I liked the most are first.

Contact me for further information regarding smaller past projects carried out in Europe.

The Top Three Past Projects:
- [opencps.eu](https://opencps.eu): Open Cyber-Physical System Model-Driven Certified Development. With tool interoperability, vendor lock-ins and tool life-cycle support as major challenges, this research project focuses on interoperability between the Modelica/Unified Modeling Language (UML)/Functional Mock-up Interface (FMI) standards, improved (co-)simulation execution speed, and verified code generation.
  - **OpenCPS received the ITEA Award of Excellence September 2019 during the ITEA PO Days 2019, more information: [click here](https://saabgroup.com/media/stories/stories-listing/2019-09/research-results-leads-to-award-for-new-energy-efficient-aerial-vehicles-platform-concepts/).**

- The [FP7 IDE4L project](https://cordis.europa.eu/project/id/608860) project developed a substation automation architecture, and we contributed with a synchrophasor protocol gateway and PMU for distribution networks.
- The [FP7 iTesla](http://cordis.europa.eu/project/rcn/101320_en.html) project developed a dynamic security assessment software platform, mostly used in France.

### While you are here, take the chance to ...
  - See how you can help! Click [here](https://alsetlab.github.io/donate/).
