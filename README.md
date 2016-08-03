# prog_lib

#### To make things easier to find... This is a master repo with references/links to my specific repos of code examples for NXOS, ACI, Spark and more.  

Scripts the highlight ACI and Spark: 
<https://github.com/cpuskarz/ahs>

Scripts that hightlight Nexus standalone programming: <https://github.com/cpuskarz/nxos-aci-examples>

Scripts that highlight ACI and vCenter:
<https://github.com/cpuskarz/epgpgattr>  



#ACI and Nexus Programmability Overview  

ACI as well as standalone NXOS are designed for programmability. The software has APIs and tools to enhance the programmability experience.  
 
Cisco ACI is a comprehensive SDN solution, making the application the focal point. It is delivered on an agile, open, and highly secure architecture. Its application-based policy model offers speed through automation, reducing errors and accelerating application deployment and IT processes from weeks to minutes.  Supporting Docker containers, Micro-Segmentation, Choice of Cloud Management Platforms and Service Insertiion and Chaining.

###ACI  (need to add links)
**GUI:** APIC controller has a GUI enabled interface to allow for configuration and operations.  

**REST APIs:** APIC can be configured, managed and operated through APIs if desired, (as well as through the GUI). Here using API's, its possible program, automate, orchestrate the ACI infrastructure and services. Tools such as Python, UCS Director, CloudCenter are just a few.

**VISORE** This is a tool within the APIC controller. It allows the programmer to navigate the Management Information Tree (MIT). Bascially this would provide information on the API calls that would be needed to make REST calls. Here's a nice introduction:
 <http://www.cisco.com/c/en/us/support/docs/cloud-systems-management/application-policy-infrastructure-controller-apic/118839-technote-visore-00.html>


**API INSPECTOR:** The is a tool that captures any REST calls the the GUI or system is making. This is handy to quickly find the API calls for a specific task. For example: 'create tenant RED'. You would see the REST formatting. These can quickly be posted into a REST Client such as POSTMAN for quick formatting. Here's a good introduction with examples: <http://www.cisco.com/c/en/us/td/docs/switches/datacenter/aci/apic/sw/1-x/api/rest/b_APIC_RESTful_API_User_Guide/b_IFC_RESTful_API_User_Guide_chapter_0100.html>





###NXOS on Nexus 9k  
NXAPI
(work do be done here...)


###OTHER TOOLS (work to be done here)
- POSTMAN
- COBRA
- ARYA
work to be done here....





