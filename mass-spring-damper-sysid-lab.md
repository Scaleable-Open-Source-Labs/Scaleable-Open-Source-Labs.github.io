# Preamble

## Motivations
System identification (SysID) is a fundamental skill in modelling and control, enabling us to select and tune mathematical models of real-world systems from experimental data.

In this lab, you will explore both:
1. A physics-informed approach — where you construct a model based on assumed system dynamics, and tune parameters based on real-world data, and,
2. A black-box approach, where you select a candidate transfer function based on the response and directly fit it's parameters to suit measured input–output data.

By engaging with both approaches, you will build an appreciation for the trade-offs between interpretability, accuracy, and effort in modelling real systems. You will also develop practical skills in experimental design, data acquisition, and parameter estimation.

## Learning Outcomes

Upon completing this lab, you will be able to:
1. Design and conduct experiments to obtain dynamic response data from a real physical systems,
2. Interpret free-response behaviour to estimate parameters of a physical system model,  
3. Fit and evaluate black-box transfer function models using measured input–output data,  
4. Compare physics-informed and black-box modelling approaches, including their assumptions and limitations,  
5. Process and visualise experimental data to support model development and validation, and,  
6. Critically assess model fidelity and sources of error in system identification.  

## Generative AI Use

> [!CAUTION]
> This laboratory is _unassessed_, and exists only to help you develop fundamental skills in experiment design, data collection, processing, systems modelling, and parameter estimation. Aspects of this laboratory can be trivially completed using generative AI. Using genAI to complete this lab will only rob you of a valuable learning experience. _You are strongly encouraged to complete this lab without the assistance of genAI_.

# System Background
This lab centres on the canonical, idealised _mass-spring-damper_ system, shown in Figure 1.

<div style="text-align: center;">
  <img src="images.jpg" alt="Mass-Spring-Damper Setup" width="500">
  <p><em>Figure 1: Mass–spring–damper experimental rig</em></p>
</div>

The system entails:
1. A mass _m_ which moves rectilinearly between two fixed endpoints,
2. Springs _$k_1$_ and _k_2_, each attached to both the mass and one endpoint, and,
3. Friction acting on the mass, which can be modelled by dampers _b_1_ and _b_2_.

The system parameters (_m_, _k_1_, _k_2_, _b_1_, and _b_2_) are unknown to you.

# Physical Lab Rig
This ideal system has been realised in the form of a handheld, _scaleable lab rig_ that you are free to use. The rig:
- contains a sliding 'mass', tension springs, and frictive elements,
- is approximately the size on an iPhone and can be disturbed by hand using the 'plectrum',
- measures the instantaneous position of the mass and displays this on a digital readout, and,
- has the ability to record this position over a short time window and provide a `.csv` file to your computer for copying and analysis by presenting as a USB drive.

The rig is encased in acrylic and is intrisically safe. You do not need to complete a risk assessment to use the rig.

# Your Task
> [!NOTE]
> This is a note callout.

> [!TIP]
> This is a tip.

> [!IMPORTANT]
> Key information goes here.


## Hand Calculations
To begin

## Taking Measurements


## Data Processing


## System Identification (SysID)

## Teardown
