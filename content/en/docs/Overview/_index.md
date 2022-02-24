---
title: "Overview"
linkTitle: "Overview"
weight: 1
description: >
  What is SOGNO and what services does it include?
---

## Vision

The energy decarbonisation increases the share of renewables based distributed generation that is connected to the distribution level of grids. Similarly, the electrification of mobility and heating as well as the flexibility offered by customers result in new power profiles and have a
large impact on the operation of distribution grids. Network reinforcements are not sufficient any longer to deal with the increasing complexity of distribution systems. The deployment of advanced distribution management systems down to the low voltage network is required.

SOGNO aims at facilitating the transition to a modular microservices based control center software solution for distribution system operators. This allows operators to adapt faster because components can be updated more independently from each other. It provides system operators and automation software developers with an open source framework that exposes open APIs to plug in new automation functions and supports industry standards such as CIM IEC61970 and IEC61850. The vision is to integrate today’s SCADA systems with SOGNO and gradually move functionalities into microservices.

A preliminary set of automation functionalities will be provided together with the framework and should be further developed as part of the SOGNO project:
- state-estimation
- load forecasting
- voltage control

The functionalities developed as part of the project will not be treated differently from any other SOGNO compatible automation functions developed externally and use the same interfaces. Due to modules for real-time simulation, the SOGNO project supports a seamless integration of
development, testing and deployment. New automation functionalities can be developed and thoroughly tested against a virtual real-time representation of the power system.

## Components

{{< readfile file="/static/architecture.svg" markdown="true" >}}

## Data Flow

{{< readfile file="/static/service-dataflow.svg" markdown="true" >}}

