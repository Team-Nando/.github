# Welcome to Team Nando's Public Repositories!

***Interested in Distribution Networks, Distributed Energy Resources (DERs), and Smart Grids?***

Here you will find multiple repositories produced by [Prof Nando Ochoa](https://sites.google.com/view/luisfochoa)’s Research Team at [The University of Melbourne](https://electrical.eng.unimelb.edu.au/power-energy). These repositories can help you understand and develop advanced techniques to model and analyse distribution networks with DERs such as residential solar PV ☀️🏡, electric vehicles 🔌🚗, batteries 🔋, etc.

The repositories have been designed for power engineering students (undergraduate and postgraduate), power engineers, researchers, consultants, etc. They require some knowledge of coding (of course! 🤓) but not too advanced. If you are a decent coder, you will manage 😉.

In most of our repositories, you will be using [OpenDSS](https://www.epri.com/pages/sa/opendss) - an open-source distribution network analysis tool developed by the [Electric Power Research Institute (EPRI)](https://www.epri.com/), USA. OpenDSS will be used here entirely with Python code thanks to the [dss_python](https://github.com/dss-extensions/dss_python) module developed by researchers at the [University of Campinas](https://www.unicamp.br/unicamp/), Brazil. You will also use anonymised network and demand data that was kindly provided by the Australian distribution company [AusNet Services](https://www.ausnetservices.com.au/). So, thanks to our colleagues and friends at EPRI, UNICAMP, and AusNet Services for these important contributions to the world! 🙏

## 1. Tutorial on DER Hosting Capacity
This tutorial will guide you, using interactive code via Jupyter Notebook and Python, through the different steps to run advanced, detailed time-series simulations to properly assess the technical impacts of DERs (such as solar photovoltaics) on realistic three-phase unbalanced distribution networks.
- [Part 0: Using dss_python](https://github.com/Team-Nando/Tutorial-DERHostingCapacity-0-dss_python)
- [Part 1: Advanced Tools for the Analysis of Three-Phase Unbalanced LV Networks](https://github.com/Team-Nando/Tutorial-DERHostingCapacity-1-AdvancedTools_LV)
- [Part 2: Time-Series Analysis and PV Hosting Capacity of LV Networks](https://github.com/Team-Nando/Tutorial-DERHostingCapacity-2-TimeSeries_LV)
- [Part 3: Volt-Watt Control and PV Hosting Capacity of LV Networks](https://github.com/Team-Nando/Tutorial-DERHostingCapacity-3-VoltWatt_LV)
- [Part 4: Monte Carlo Assessment of PV Hosting Capacity of an Integrated MV-LV Network](https://github.com/Team-Nando/Tutorial-DERHostingCapacity-4-MonteCarlo_MV-LV)

> *Want to learn more about **DER Hosting Capacity***? Check out these reports [[1]](https://www.researchgate.net/publication/349312771_Deliverable_6_Consolidation_of_Findings_Final_Report), [[2]](https://www.researchgate.net/publication/360887067_Milestone_8_EV_Management_and_Time-of-Use_Tariff_Profiles), these papers [[3]](https://www.researchgate.net/publication/282539912_Probabilistic_impact_assessment_of_low_carbon_technologies_in_LV_distribution_systems), [[4]](https://www.researchgate.net/publication/362559464_Recommendations_for_the_Planning_of_PV-Rich_Distribution_Networks_An_Australian_Case_Study), [[5]](https://www.researchgate.net/publication/362243134_Assessing_the_EV_Hosting_Capacity_of_Australian_Urban_and_Rural_MV-LV_Networks) and the webinars of our projects [PV-Rich Distribution Networks](https://electrical.eng.unimelb.edu.au/power-energy/projects/project-edge) and [EV Integration](https://electrical.eng.unimelb.edu.au/power-energy/projects/ev-integration).<br>
> *Want to learn more about **Model-Free DER Hosting Capacity***? Check out the webinars and reports of our [Model-Free Project](https://electrical.eng.unimelb.edu.au/power-energy/projects/model-free-operating-envelopes).<br>

## 2. Operating Envelope (OE) Algorithms
These repositories demonstrate, using interactive code via Jupyter Notebook and Python, different Operating Envelope (OE) algorithms that could be implemented by distribution companies. This work is part of the CSIRO-funded project [Assessing the Benefits of Using OEs to Orchestrate DERs Across Australia](https://electrical.eng.unimelb.edu.au/power-energy/projects/assessing-the-benefits-of-OEs-across-Australia)
- [OE Algorithm 1: Ideal](https://github.com/Team-Nando/OE1-Ideal)
- [OE Algorithm 2: Asset Capacity](https://github.com/Team-Nando/OE2-Asset_Capacity)
- [OE Algorithm 3: Asset Capacity & Critical Voltage OE](https://github.com/Team-Nando/OE3-Asset_Capacity_Critical_V)
- [OE Algorithm 4: Asset Capacity & Delta Voltage OE](https://github.com/Team-Nando/OE4-Asset_Capacity_Delta_V)

> *Want to learn more about **Operating Envelopes***? Check out this article [[6]](https://www.nxtbook.com/nxtbooks/pes/powerenergy_070821/index.php#/p/52), these papers [[7]](https://www.researchgate.net/publication/351196031_Ensuring_Distribution_Network_Integrity_Using_Dynamic_Operating_Limits_for_Prosumers), [[8]](https://www.researchgate.net/publication/361412635_Using_OPF-Based_Operating_Envelopes_to_Facilitate_Residential_DER_Services), [[9]](https://www.researchgate.net/publication/371686444_Assessing_the_Pros_and_Cons_of_Different_Operating_Envelope_Implementations_Across_Australia) and the webinars of our projects [Project EDGE](https://electrical.eng.unimelb.edu.au/power-energy/projects/project-edge) and [Assessing the Benefits of Using OEs to Orchestrate DERs Across Australia](https://electrical.eng.unimelb.edu.au/power-energy/projects/assessing-the-benefits-of-OEs-across-Australia).<br>
> *Want to learn more about **Model-Free Operating Envelopes***? Check out these papers [[10]](https://www.researchgate.net/publication/366030346_Electrical_Model-Free_Voltage_Calculations_Using_Neural_Networks_and_Smart_Meter_Data), [[11]](https://www.researchgate.net/publication/373990780_From_Model-Driven_to_Model-Free_Comparisons_using_Real_Smart_Meter_Data_and_Real_Distribution_Network_from_Australia_Study) and our [Model-Free Project](https://electrical.eng.unimelb.edu.au/power-energy/projects/model-free-operating-envelopes).<br>

## 3. Australian MV-LV Networks and Demand/DER Profiles
This repository provides four real large-scale three-phase Australian MV (22kV L-L) distribution networks and corresponding _European-style_ LV (400V L-L) networks down to the connection point of single-phase customers. It also includes a large pool of real 30-min resolution residential demand (kW) profiles.
- [MV-LV Networks](https://github.com/Team-Nando/MV-LV-Networks)

This repository provides realistic time-series EV profiles necessary to carry out detailed distribution network studies.
- [EV Profiles](https://github.com/Team-Nando/EV-Demand-Profiles)

> *Want to learn more about **MV-LV Networks***? Check out this paper [[12]](https://www.researchgate.net/publication/344346531_On_the_role_of_integrated_MV-LV_network_modelling_in_DER_studies) and these reports [[13]](https://www.researchgate.net/publication/334458042_Deliverable_1_HV-LV_modelling_of_selected_HV_feeders), [[14]](https://www.researchgate.net/publication/354907164_Milestone_6_Network_Modelling_and_EV_Impact_Assessment), and the webinars of our projects [Advanced Planning of PV-Rich Distribution Networks](https://electrical.eng.unimelb.edu.au/power-energy/projects/pv-rich-distribution-networks) and [EV Integration](https://electrical.eng.unimelb.edu.au/power-energy/projects/ev-integration).<br>
> *Want to learn more about **EV Profiles***? Check out this paper [[15]](https://www.researchgate.net/publication/360936789_Producing_Realistic_EV_Demand_Profiles_for_Distribution_Network_Studies) and the webinars of our project [EV Integration](https://electrical.eng.unimelb.edu.au/power-energy/projects/ev-integration).<br>

## 4. AC Optimal Power Flow for Distribution Networks
These repositories provide examples of how the AC Optimal Power Flow (OPF) can be used for different distribution network applications.
- [Balanced AC OPF for DG Studies](https://github.com/Team-Nando/Balanced-AC-OPF-for-DG-Studies)

> *Want to learn more about **AC OPF for Distribution***? Check out this article [[16]](https://www.nxtbook.com/nxtbooks/pes/powerenergy_010220/index.php#/p/62) and these papers [[17]](https://www.researchgate.net/publication/224082932_Network_distributed_generation_capacity_analysis_using_OPF_with_voltage_step_constraints), [[18]](https://www.researchgate.net/publication/313344969_AC_OPF_for_smart_distribution_networks_An_efficient_and_robust_quadratic_approach), [[19]](https://www.researchgate.net/publication/340239922_On_the_Fairness_of_PV_Curtailment_Schemes_in_Residential_Distribution_Networks), [[20]](https://www.researchgate.net/publication/348676876_On_the_Implementation_of_OPF-Based_Setpoints_for_Active_Distribution_Networks), [[21]](https://www.researchgate.net/publication/336361185_Implementable_Three-Phase_OPF_Formulations_for_MV-LV_Distribution_Networks_MILP_and_MIQCP), [[22]](https://www.researchgate.net/publication/361412635_Using_OPF-Based_Operating_Envelopes_to_Facilitate_Residential_DER_Services), [[23]](https://www.researchgate.net/publication/346220786_Exploring_the_Use_of_an_ADMM-Based_Three-Phase_AC_OPF_in_PV-Rich_MV-LV_Networks).<br>

## Contact
Nando Ochoa (luis.ochoa@unimelb.edu.au ; https://sites.google.com/view/luisfochoa)
> ***Want to learn more about our research with industry?*** Check out [Our Projects](https://electrical.eng.unimelb.edu.au/power-energy/projects).<br>

## Acknowledgement
The contents of these repositories have been produced with direct and/or indirect inputs from multiple members (past and present) of Prof Nando Ochoa’s Research Team. So, special thanks to all of them (many of whom are now in different corners of the world).<br>
* https://sites.google.com/view/luisfochoa/research/research-team
* https://sites.google.com/view/luisfochoa/research/past-team-members
  
We also would like to thank [AusNet Services](https://www.ausnetservices.com.au/) for making it possible to share anonymised data with the power community around the world. 🙏
<!--
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
