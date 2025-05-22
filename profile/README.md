## Hi there 👋  - A warm welcome to OPC UA LADS - the "Laboratory & Analytical Device Standard" built on OPC UA
<b>Browse the standard: https://reference.opcfoundation.org/LADS/v100/docs/</b>
## 

We want to help you get started and enable you to enter the strong foundations of the OPC UA ecosystem for your laboratory/analytical devices.

#
<h2>1. Learn about OPC UA</h2>
As a first step we want to encourage you to learn more about OPC UA, so it becomes even cleare why we chose to create LADS upon this strong foundation:

https://youtu.be/-tDGzwsBokY?si=pps0To__1PdD_2nt

and for more information have a look at this playlist:

https://youtube.com/playlist?list=PLROM1mLWekVCzxGMs6kzpBnJiDh3fiquD&si=C4AJLMzhdeQlbYNV

#
<h2>2. Learn about the concepts of OPC UA LADS</h2>
If you directly want to dive into OPC UA LADS, we can recommend recorded talks by Dr. Matthias Arnold, the lead author of OPC UA LADS 30500:

LADS OPC UA at Jasis 2023:

https://youtu.be/ddMEdx3CwAk?si=lv2ZlyeNN9NnmN0s

LADS OPC UA at OPC Days 2023:

https://www.youtube.com/watch?v=eUcpQdN2Xek&list=PLROM1mLWekVBo57WTnReI_-5yVbIK4koW&index=5

#
<h2>3. Create a OPC UA LADS device</h2>
If you are all prepared with the theory, then you may want to get started with our workshop example:
https://github.com/opcua-lads/workshop

The workshop provides a complete device model and a server utilizing nodejs/ts.

Soon we will link additional exmaples to use the workshop device model also with prominent stacks for C/C++ and C#

#
<h2>4.Ecosystem Projects - FAIR by design</h2>
We are continuously growing the OPC UA LADS ecosystem to accelerate the development of FAIR-by-design laboratory data infrastructures. Two new open-source components are now available:

### [`lads-server-collection`](https://github.com/opcua-lads/lads-server-collection)
A curated collection of simulated OPC UA servers that implement the **LADS (Laboratory and Analytical Device Standard)** Companion Specification. These servers:

- Deliver data modeled using the **Allotrope Foundation Ontologies (AFO)**  
- Provide structured result data in **ASM (Allotrope Simple Model)** format  
- Are **FAIR by design**, ensuring that results are Findable, Accessible, Interoperable, and Reusable  
- Demonstrate end-to-end **semantic integration** with OPC UA dictionary references (Part 19), aligning real-time device data with high-level semantic context

This collection enables plug & play demonstrations of semantic lab integration – from basic instruments to high-end analytical systems.

### [`lads-client-py`](https://github.com/opcua-lads/lads-client-py)
A Python-based client application and library for interacting with LADS-compatible OPC UA servers. It includes:

- A **user interface** for browsing and operating LADS servers
- Semantic tooltips and context based on **AFO**
- Functionality to test whether a server:
  - Follows the expected LADS object model
  - Provides semantically correct annotations
  - Outputs results in valid ASM JSON format


#
<h2>5. Helpful tools for OPC UA LADS</h2>
For the time being, have a look at these stacks and tools to get setup properly:

<b>Modellers:</b>

SioME provided free of charge by Siemens:
https://support.industry.siemens.com/cs/document/109755133/siemens-opc-ua-modeling-editor-(siome)?dti=0&lc=en-DE

Unified Automation Modeller, wit basic functionality for free:
https://www.unified-automation.com/de/produkte/entwicklerwerkzeuge/uamodeler.html

<b>Generic clients:</b>

Unified Automation UA Expert:
https://www.unified-automation.com/de/produkte/entwicklerwerkzeuge/uaexpert.html

Prosys OPC UA:
https://prosysopc.com/products/opc-ua-browser/

<b>Technology stacks to get started:</b>
There are more stacks out there, this is the list of the most prominent ones used at the LADShack hackathons:

nodejs/typescript:
https://github.com/node-opcua/node-opcua

C# / .Net:
Official stack by the foundation: https://github.com/OPCFoundation/UA-.NETStandard

Stack provided by unified automation: https://www.unified-automation.com/de/produkte/server-sdk/net-ua-server-sdk.html

Ansi C/ C++:
https://github.com/open62541/open62541


