# Shared Information and Data Model

This BSS.Entities Shared Information and Data Model (formerly named as Natec.Entities) is used for generating Visual Studio Project templates to implement the custom business logic of BSS Entities and Action entire the Telecom BSS domain. This SID model is aimed to support the NGOSS concept, developed based on ITUT (M.3050) of the TM Forum organization, and is the basis for the integration of OSS/BSS (Operation Support System/Business Support System).

Before you contribute, please look through the guide [Creation of Backend package from the template](https://mef.dev/dev_guides/first_backend_plugin.md) 


The BSS.Entities SID Model is key part of the MEF.DEV [Reference Architecture](https://mef.dev/plugin_basics/introduction.md#domain-driven-reference-architecture), that gives independent developers open access to the main operational processes of consumer support, such as Fulfilment, Assurance, and Billing (FAB).

|![BSS.Entities diagram](https://mef.dev/images/plugin_basics/introduction/sid.png)|
| :--: |

The BSS.Entities SID-model is the set of Entities and Actions (atomic part of the process flow) allocated based on the experience of real projects in the Telecom BSS domain. The Telecom provider can build the custom flow based on the existing sets of Actions, which will allow, due to their combination and unification, to implement their specific “end-to-end” scenario with the help of which these processes ensure the implementation of the purpose of the company's business activities.

## Why is the Telecom BSS Domain BSS.Entities SID Model Needed?

+ The BSS.Entities model provides a standard structure, terminology, and classification scheme for describing business processes and their building blocks
+ The BSS.Entities model offers a framework for applying typical business process design principles across the enterprise.
+ The BSS.Entities model provides a framework for understanding and managing an application portfolio in terms of business process requirements.
+ The BSS.Entities model enables the creation of holistic, high-quality workflows of end-to-end processes to reuse existing processes and systems, including reducing costs and increasing efficiency.

## When will Telecom BSS Domain BSS.Entities SID Model Help? 

The BSS.Entities SID model diagram is a part of the business analysis of existing product management processes in an organization and the development of new services or products. It can help you identify processes that provide the same business function, eliminate possible duplication, detect gaps, accelerate new product development, and reduce inconsistencies. The BSS.Entities SID model allows you to assess the significance of individual processes used in an organization to evaluate the impact when a new process or product is launched. The SID model simplifies relationships with partners in product development, as it allows you to identify and standardize the processes used when interacting with them. Likewise, you can place the critical processes used in customer interactions and assess whether these processes are performing as expected by the end customers.

### Useful links
 
- Ready-to-use BSS.Entities package is available as [Nuget package](https://www.nuget.org/packages/BSS.Entities)
- XML Schema is available in [XSD](https://github.com/mef-dev/model-first-backend-plugin/blob/master/models.xsd)
