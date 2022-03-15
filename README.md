<h1 align="center">MPS500-Capabilities</h1>
<div align="center">
    <img width="800px" src="https://github.com/hsu-aut/MPS500-Capabilities/blob/documentation/images/documentation/images/MPS500-Layout.png?raw=true">
</div>
<hr>

## Introduction
A semantic capability model for the modular laboratory production system "MPS500". Capabilities are used to describe processes that machines are able to perform. We make use of ontologies and especially so called *Ontology Design Patterns* (ODPs) based on standards. Check out our repositories of variuous standard-based ontologies, e.g. this one of VDI 3682: https://github.com/hsu-aut/IndustrialStandard-ODP-VDI3682.

Central to the way we model capabilities is VDI guideline 3682 (Formalized Process Description aka FPD). FPD is a rather simple way to model processes with their input and output products, information or energies. Processes may be decomposed in order to describe a process in more detail.
Input and output elements may have so-called *Data Elements* according to [IEC 61360](https://github.com/hsu-aut/IndustrialStandard-ODP-DINEN61360) which are used to model all kinds of properties. A Data Element always consists of a *Type Description* which defines everything about the type of a property (e.g. an ID, a unit of measure, ...) and an *Instance Description* which is used to describe specific occurences / values of a property. Properties may be modelled as a requirement, assurance or an actual value.

Our capability model features additional standards such as [DIN 8580](https://github.com/hsu-aut/IndustrialStandard-ODP-DIN8580) and [VDI 2860](https://github.com/hsu-aut/IndustrialStandard-ODP-VDI2860) which are both used to specify the type of a capability (e.g. drilling, handling, ...). Furthermore, capabilities may be related to *skills* which are the executable counterpart. Skills describe a way to automatically invoke the functionality that is modeled as a capability. Skills are out of scope for this repository - you can find out more about our complete capability and skill model in [this repository](https://github.com/aljoshakoecher/machine-skill-model).


## A more detailed look
🚧 Additional documentation coming soon 🚧
