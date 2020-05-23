# Deep Learning for Medical Resource Allocation in a Pandemic

## Abstract

COVID-19 is a novel pandemic with serious clinical manifestations. Insofar, it has reached more than 180 countries and territories. During the time of the pandemic, the entire US community is facing medical resource scarcities. The problem of how to efficiently allocate and deliver a fixed amount of medical resources including but not limited to masks, potential vaccines and ventilators subject to constraints such as inter-county transportation and limited budget for delivery costs remain unsolved. In this study, we develop a model that utilizes the minimum covered vertex set as a solution to optimal resource allocation. Based on the minimum covered set, a traveling salesman problem (TSP) model is used to determine the optimal path of delivery which incurs minimum total cost.

## Introduction

In December, 2019, Wuhan, Hubei province, China, became the centre of an outbreak, which raised intense attention not only within China but internationally. In a short time, COVID-19 became a new pandemic with nearly three million confirmed cases all around the world. In the current COVID-19 outbreak, infection control and clinical management efforts are necessarily being implemented on a larger scale than in any previous outbreak, and it is therefore appropriate to reassess the allocation methods for medical resources. Deep-learning algorithms has been used by many researchers to provide more insight into different aspects of previous pandemics from infection to disease management. In the current study,a geographic dataset of Maryland counties has been used to develop a model that utilizes the minimum vertex cover set as a solution to optimal resource allocation. Based on the minimum cover set, a traveling salesman problem (TSP) model is used to determine the optimal path of delivery which incurs minimum total cost.


## Model Setting
Let $G = (V,E)$ be a graph object consisting a distance function $w: E \rightarrow \mathbf{R}^+$. The node set $V$ represents the set of agents we are studying for and can be in state, county, or even individual level. Edge set $E$ contains all the edges between each pair of nodes (i.e. it is a complete graph). The distance function $w(e)$ maps the traveling distance between two agents connected by edge $e$. 
