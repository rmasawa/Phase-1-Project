# Phase 1 Project Description

## Project Overview

For this project, you will use data cleaning, imputation, analysis, and visualization to generate insights for a business stakeholder.

### Business Problem

Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

**Table of Contents**

1. [Introduction](#introduction)
2. [Business Understanding](#businessunderstanding)
3. [Libraries](#libraries)
    - [Importing Libraries](#importinglibraries)
    - [Loading Data Sets](#loading-data-Sets)
4. [Understanding the Data](#contrUnderstandingthedata)
5. [Data Processing](#dataprocessing)
6. [Data Cleaning](#datacleaning)
7. [Analysis](#analysis)
8. [Recommendations](#recommendations)
9. [Conclusion](#conclusion)


# Introduction
The analysis aims to assess safety and operational risks across different aircraft models to help the company choose low-risk airplanes for its new aviation business. 


# Understanding the Data
#### Understanding the Culumn and categorizing them twith respect to the required Analysis

The Aviation Dataset enatails several features that can be attributed to aircraft accidents and those that are safety related. For instance;

**Information about Events**

- Event.ID
- Unvestigation.Type
- Accident.Number
- Event.Date
- Location, Country,Lattitude, Longitude
- Airport.Code, Airport.Name
- FAR.Description

**Injury and Damage Information**
- Injury.Severity
- AirCraft.Damage
- TOtal.Fatal.Injuries, Total.Serious.Injuries, Total.Minor.Injuries, Total.Uninjured

**Aircraft and Flight Information**
- Aircraft.Category
- Registration.Number
- Make, Model
- Amateur.Built
- Number.of.Engines, ENgine.Type
- Schedule, Purpose.of.Flight

**Flight COndition and Weather**
- Weather.Condition
- Broad.phase.of.flight

#### Relevant Columns for Risk Analysis
- Aircraft.Damage - This will determin how severe the accidents were which closely relates to the level risk associated with the specific aircrafts
- Total.Fatal.Injuries, TOtal.Serious.Injuries, Total.Minor.Injuries - Provides into how safe an aircraft can be
- Aircraft.Category - helps in identifying whether the aircraft is commercial or private which inturn helps in identifying the threshold of the risk We can also check the Purpose.of.flight Column
- Make, Model -  Helps in analysziing Trends with rerspect to safety and performance among different aricrafts
- Engine.Type - Helps to know if certain Engines have safety records
- Weather.Condition - WIll be used to check if adverse weather conditions plays a role in causing accidents with respect to aircraft
- Broad.phase.of.flight - will be used to identify if specific phases of a flight like landing or takeoff would be a potential risk for specific aircrafts

# Recommendations
- Turbofan Engines which are mostly used for commercial aircrafts caused fewer accidents compared to reciprocating which are primarily piston based and commonly used for small jets. Therefore the organization should consider Purchasing Turbo Engines. On the other hand Engines like Electric and LR and Hybrid Rocket recorded low accidents. They caould also be considered
- It is important to know that many accidents in the aviation sector occur during landing and takeoff. This means that the organization should consider training their pilots frequetly not only on safety procedures but also profeciency and keenness.
- More accidents are experienced when the purpose is to fly the aircraft personally. This could be associated to the fact that private pilots are not professional and tend to fly cassually and carelessly. The organization should enact rules that will allow private customers to be flown by a professional pilot provoded by the organization.
