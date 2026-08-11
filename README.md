 # Research Article: TLBO-Driven Energy Optimization and Storage Coordination in Multi-Bus DC Microgrids
# Manuscript ID: [IEEE LAT AM T] Submission ID: 10462

## Authors and Affiliations

**Sujatha Banka**, Research scholar, Electrical and Electronics Engineering Department at JNTUA Ananthapuramu, A.P, India and Associate Professor in Electrical and Electronics Engineering Department at BVRIT HYDERABAD college of Engineering for Women, Hyderabad, Telangana, India

**D. V. Ashok Kumar**, Professor, Department of Electrical and Electronics Engineering, RGM College of Engineering and Technology, Nandyala, Andhra Pradesh, India.

## Abstract

Effective energy management is critical for DC microgrids (DCMG) where bus voltage stability, proportional load sharing, and coordinated operation of battery and super-capacitor units must be maintained under rapidly changing PV generation and load demand. Existing approaches—model-based, data-driven and heuristic—face limitations such as dependence on accurate system models, high training overhead, or sensitivity to parameter tuning, making them less suitable for real-time deployment under uncertain operating conditions. This work proposes a computationally lightweight model-independent energy management strategy (EMS) using a Teaching-Learning-Based Optimization (TLBO) framework. The method optimizes battery and supercapacitor (SC) power commands using a unified cost function that accounts for bus voltage deviation, power balance error, SoC disparity, and supercapacitor over-utilization. TLBO improves candidate solutions through teacher-guided global updates and peer-learning interactions without requiring algorithm-specific parameters or large datasets. The resulting optimal power setpoints are translated into converter current references for coordinated storage control. The simulation results under load variations and photovoltaic fluctuations demonstrate improved voltage regulation, balanced storage utilization, and faster recovery compared to conventional methods. The proposed TLBO-based EMS offers a robust and practical solution for real-time DCMG control under model uncertainty and dynamic operating scenarios.**

## Research Objectives

Develop a TLBO-based EMS for a multi-bus DC microgrid.

Coordinate battery and supercapacitor power sharing.

Minimize DC-bus voltage deviation and power-balance error.

Improve storage SoC coordination.

Reduce excessive supercapacitor utilization.

Evaluate the EMS under photovoltaic intermittency and load variations.

Develop a computationally strategy suitable for real-time-oriented implementation.

## Optimization Objectives

The TLBO optimization considers:

DC-bus voltage deviation

Power-balance error

Battery/supercapacitor SoC disparity

Supercapacitor over-utilization

Coordinated battery–supercapacitor power allocation

The exact mathematical formulation and parameter values should be taken from the corresponding manuscript and simulation files included in this repository.

## Software  Requirements
MATLAB 2023b or later

The exact MATLAB release and toolbox requirements should be checked in the individual scripts and model files.

## MATLAB_Code
Contains MATLAB script/function  used for implementation and analysis of the proposed TLBO-based EMS.

# For more info, Contact:
sujatha.b@bvrithyderabad.edu.in
