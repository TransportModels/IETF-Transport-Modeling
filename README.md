#IETF-Transport-Modeling

Modeling of Transport Usecase using IETF Models 

##Background

Transport network domains, such as Optical Transport Network (OTN) and Wavelength Division Multiplexing (WDM) networks, are built using equipments from a single vendor and are managed using proprietary interfaces to dedicated Element Management Systems (EMS) / Network Management Systems (NMS).

A common open interface to each domain controller/management system is pre-requisite for network operators to control multi-vendor/multi-domain networks and also enable service provisioning coordination/automation.  This can be achieved by using standardized YANG models, used together with an appropriate protocol (e.g., RESTCONF).  However, there is no common understanding, and often confusion, on how existing models from SDOs, like IETF, can be used for transport networks. Furthermore, there is no clear answer to the question whether there is missing information in the existing models, or even missing models since existing drafts focus on providing only the YANG models and explanation around them.

##Design Team Goals

The following are the goals of the transport modeling design team:
1) Identify use cases and perform gap analysis of existing models against these set of use cases; The expected output should be either providing comments directly to the existing model drafts, if there is any, or produce new drafts if there is no model available.

2) Providing guidelines in terms of how all the related models can be used in a step-wise manner, using a couple of identified transport network use cases.

##Contributors
- Anurag Sharma
- Xian Zhang
- Sergio Belotti
- Oscar González de Dios
- Tara Cummings
- Dieter Beller
- Daniele Ceccarelli
- Karthik Sethuraman
- Ricard Vilalta
- Victor Lopez
- Rajan Rao
