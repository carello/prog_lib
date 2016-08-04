# prog_lib

This repo is a starting point for programmability related to ACI and Open NX-OS. Below is an overview and links to tools and resources. Also, I've include links to my repos of code examples for NXOS, ACI, Spark and more:  

* Scripts that highlight ACI and Spark: 
<https://github.com/cpuskarz/ahs>

* Scripts that hightlight Nexus standalone programming: <https://github.com/cpuskarz/nxos-aci-examples>

* Scripts that highlight ACI and vCenter:
<https://github.com/cpuskarz/epgpgattr>  



#ACI and Nexus Programmability Overview  

ACI, Nexus 9k, and Open NXOS are designed for programmability. 
 
Cisco ACI is a comprehensive SDN solution, making the application the focal point. It is delivered on an agile, open, and highly secure architecture. Its application-based policy model offers speed through automation, reducing errors and accelerating application deployment and IT processes from weeks to minutes.  Supporting Docker containers, Micro-Segmentation, Choice of Cloud Management Platforms and Service Insertiion and Chaining.  

Below are descriptions and links to tools and resources.

###ACI
**GUI:** APIC controller has a GUI enabled interface to allow for configuration and operations. There are many resources on Cisco.com. To get started, please take a look at these links:  
[Getting started with a basic configuration](http://www.cisco.com/c/en/us/td/docs/switches/datacenter/aci/apic/sw/1-x/basic-config/b_ACI_Config_Guide.html)  
[Detailed guides](http://www.cisco.com/c/en/us/support/cloud-systems-management/application-policy-infrastructure-controller-apic/tsd-products-support-series-home.html)



**REST APIs:** APIC can be configured, managed and operated through APIs if desired, (as well as through the GUI). Using API's, its possible program, automate, orchestrate the ACI infrastructure and services. Tools such as Python, UCS Director, CloudCenter are just a few. Documentation can be found [here.](http://www.cisco.com/c/en/us/td/docs/switches/datacenter/aci/apic/sw/1-x/api/rest/b_APIC_RESTful_API_User_Guide.html)


**VISORE** This is a tool within the APIC controller. It allows the programmer to navigate the Management Information Tree (MIT). Bascially this would provide information on the structure/syntax of APIs that would be needed to make REST calls. [Here's a nice introduction.]
 (http://www.cisco.com/c/en/us/support/docs/cloud-systems-management/application-policy-infrastructure-controller-apic/118839-technote-visore-00.html)


**API INSPECTOR:** Also, included in ACI. The is a tool that captures any REST calls the the GUI or system is making. This is handy to quickly find the API calls for a specific task. For example: 'create tenant RED'. You would see the REST formatting. These can quickly be posted into a REST Client such as POSTMAN for quick formatting. [Here's a good introduction with examples.] (http://www.cisco.com/c/en/us/td/docs/switches/datacenter/aci/apic/sw/1-x/api/rest/b_APIC_RESTful_API_User_Guide/b_IFC_RESTful_API_User_Guide_chapter_0100.html)





###Open NX-OS 
Open NX-OS on the Cisco Nexus platform is a rich software suite built on a Linux foundation that exposes APIs, data models, and programmatic constructs. Using Application Programmatic Interfaces (APIs) and configuration agents, operators can affect configuration changes in a more programmatic way. Cisco provides various tools and frameworks to enable developers automate and program Nexus devices, including – NX-API REST (brings Model Driven Programmability (MDP) to standalone, Python, Puppet, Chef, Ansible etc. 
 
NX-OS provides a **NXAPI Sandbox**. It is a web-based user interface that you use to enter the commands, command type, and output type for the Cisco Nexus 9000 Series device using HTTP/HTTPS. After posting the request, the output response is displayed. The following links can get you started.

**NX-OS** [Getting Started](https://opennxos.cisco.com/public/getting-started)  
**NX-OS** [Detailed Programmability Guide ](http://www.cisco.com/c/en/us/td/docs/switches/datacenter/nexus9000/sw/7-x/programmability/guide/b_Cisco_Nexus_9000_Series_NX-OS_Programmability_Guide_7x.html)  
**NX-API REST SDK** [User Guide and API Reference] (https://opennxos.cisco.com/public/api/nxapi-rest/)




###OTHER TOOLS

**COBRA SDK:** Cobra is the officially supported python bindings for Cisco APIC REST API. It provides a pythonic library that allows developers to quickly develop and test applications to program the Cisco ACI through the APIC.  

[Overview and Installation on Github](https://github.com/datacenter/cobra)   
[Documentation](https://developer.cisco.com/media/apicDcPythonAPI_v0.1/)


**ARYA**   
[Arya](https://github.com/datacenter/arya) is a tool that will convert APIC object documents from their XML or JSON form into the equivalent Python code leveraging the Cobra SDK.


**POSTMAN:**  POSTMAN REST Client from Google, for testing web services. Postman makes it easy to test APIs quickly, by putting together both simple and complex HTTP requests.   [Docs and Blogs](https://www.getpostman.com/docs/blog_mentions)







