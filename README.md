# prog_lib

#### To make things easier to find... This is a master repo with references/links to my specific repos of code examples for NXOS, ACI, Spark and more.  

Scripts the highlight ACI and Spark: 
<https://github.com/cpuskarz/ahs>

Scripts that hightlight Nexus standalone programming: <https://github.com/cpuskarz/nxos-aci-examples>

Scripts that highlight ACI and vCenter:
<https://github.com/cpuskarz/epgpgattr>


##ACI and Nexus Programmability Overview  

ACI as well as standalone NXOS are designed for programmability. The software has APIs and tools to enhance the programmability experience. 

###ACI  (need to add links)
**GUI:** APIC controller has a GUI enabled interface to allow for configuration and operations.  

**REST APIs:** APIC can be configured, managed and operated through APIs if desired, (as well as through the GUI). Here using API's, its possible program, automate, orchestrate the ACI infrastructure and services. Tools such as Python, UCS Director, CloudCenter are just a few.

**VISORE** This is a tool within the APIC controller. It allows the programmer to navigate the Management Information Tree (MIT). Bascially this would provide information on the API calls that would be needed to make REST calls. 

**API INSPECTOR:** The is a tool that captures any REST calls the the GUI or system is making. This is handy to quickly find the API calls for a specific task. For example: 'create tenant RED'. You would see the REST formatting. These can quickly be posted into a REST Client such as POSTMAN for quick formatting.

###NXOS on Nexus 9k  
NXAPI
(work do be done here...)


###OTHER TOOLS (work to be done here)
- POSTMAN
- COBRA
- ARYA
work to be done here....





