# A Day Full of Azure Data Factory

![Data Factory Icon](https://mrpaulandrew.files.wordpress.com/2020/08/m00-intro-and-agenda.png)

Hello friends and welcome to this full day workshop on Azure Data Factory. Today we will be all becoming advanced factory workers!... And we completely recommend this description when describing your job to family members. But be warned, if you go on to tell them that the factory is in the cloud you are likely to be branded as crazy. However, here and now that is ok. You are amongst like-minded geeky friends that all want to become cloud factory workers as well :-)

On a more serious note; throughout our day of training you will quickly notice, like with most technologies, there are an awful lot of different ways you can implement this Azure orchestration service and understanding the best way to do something is often the biggest challenge. That said, if you only take away one thing from today I would ask that you have an appreciation of this fact. Then when delviering solutions you take a step back from the requirements and think about the overall technical design and how Azure Data Factory should fit into your platform as a core component.

All too often with new and shiny services we start playing around then try to make the technology fit our solution. Rather than thinking about the solution requirements and which technology meets our needs. This is true of all developers, I don't want to preach, so am simply asking for a little bit of mindfulness.

___

## Session Abstract

__A Day Full of Azure Data Factory__

To achieve any data processing in Azure you need an umbrella service to manage, monitor and schedule your solution. For a long time when working on premises, the SQL Agent has been our go-to tool, combined with T-SQL and SSIS packages. It’s now time to upgrade our skills and start using cloud native services to achieve the same thing on the Microsoft Cloud Platform. Within a PaaS-only Modern Data Platform, the primary component for delivering that orchestration is Azure Data Factory, combined with various other compute resources.

In this full day of training you’ll start with the basics and learn how to orchestrate your Azure Data Platform end to end. You will learn how to build Azure ETL/ELT pipelines using all Data Factory has to offer. Plus, consider hybrid architectures, dynamic design patterns, think about lifting and shifting legacy packages, and explore complex bootstrapping to orchestrate everything within your solution.

We’ll breakdown the content for this rich Azure PaaS resource as follows:

* Azure Data Factory fundamentals. What is it and why use it?
* Uploading data from on-premises to Azure.
* Using SSIS packages in Azure.
* Data Factory Mapping & Wrangling Data Flows.
* Dynamic metadata driven pipelines.
* Data Factory alerting, security and monitoring.
* Pipeline pricing.
* Data Factory CI/CD using Azure DevOps.
* Using Azure Data Factory in production.

If that's not enough content for one day, you will also get access to a set of hands-on labs that you can work through at your own pace. Whether you are new to Azure Data Factory or have some experience, you will leave this workshop with new skills and ideas for your projects.

___

## Full Agenda

* __Module 1:__ [Data Factory Fundamentals](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M01%20-%20Fundamentals.pdf)
    * What is it and why use it?
    * Resource Components
    * Common Activities
    * Execution Dependencies

* __Module 2:__ [Uploading Data to Azure](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M02%20-%20Uploading%20Data.pdf)
    * Integration Runtimes
      * Azure IR
      * Hosted IR
    * Hosted IR Patterns
      * Demo - Linked IR's 
      * Demo - Simple Data Upload
    * Private Endpoints

* __Module 3:__ [Using SSIS Packages in Azure](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M03%20-%20Using%20SSIS%20Packages.pdf)
    * SSIS Integration Runtime
    * Packages Running on PaaS
    * Scaling Out Package Execution
      * Demo - Scale Out Execution of Anything

* __Module 4:__ [Data Flows](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M04%20-%20Data%20Flows.pdf)
    * Mapping Data Flows
      * Demo - Building a Mapping Data Flow
    * Wrangling Data Flows
      * Demo - Using a Wrangling Data Flow
    * Configuration
    * Use Cases

* __Module 5:__ [Metadata Driven Pipelines](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M05%20-%20Metadata%20Driven.pdf)
    * Expressions
    * Dynamic Pipelines
      * Demo - Data Discovery and Upload
      * Demo - Simple Metadata and Upload
      * Demo - Lazy SQLDB Replication
    * Orchestration Framework - [procfwk.com](http://procfwk.com/)
      * Demo - Framework Failure Handling & Restart

* __Module 6:__ [Monitoring Alerting Security](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M06%20-%20Monitoring%20Alerting%20Security.pdf)
    * Logging
    * Alerting
      * Demo - How To Build Alerting
    * Using Azure Key Vault
    * Access & Permissions

* __Module 7:__ [Pricing & Limitations](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M07%20-%20Pricing%20%26%20Limitations.pdf)
  * Cost
    * Activities
    * Data Integration Units
    * Data Flow Compute
    * Wider Platform Orchestration
  * Resource Limitations

* __Module 8:__ [CI/CD with Azure DevOps](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M08%20-%20CICD%20with%20Azure%20DevOps.pdf)
    * Source Control vs Developer UI
    * ARM Template Deployments
      * Demo - Basic Deployment via Azure DevOps
    * PowerShell Deployments

* __Module 9:__ [Data Factory in Production](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M09%20-%20ADF%20in%20Production.pdf)
    * Testing
      * Demo - Running NUnit Tests
    * Bootstrapping
    * Best Practices

* __Module 10:__ [Wrap Up](https://github.com/mrpaulandrew/A-Day-Full-of-Azure-Data-Factory/blob/master/Slides/M10%20-%20Wrap%20Up.pdf)
    * Conclusions
    * Questions
    * Homework

___

## Training Day Contributors
### Paul Andrew 
__Principal Consultant - Solution Architect & Data Platform MVP @ Altius Consulting Ltd__

Paul is a Microsoft Data Platform MVP with 15+ years’ experience working with the complete on premises SQL Server stack in a variety of roles and industries. Now as an industry leading consultant has turned his keyboard to big data solutions on the Microsoft cloud platform. Specialising in all things data engineering (Data Factory, Data Bricks, Data Lake and Stream Analytics). Paul is also a STEM Ambassador for the networking education in schools’ programme, PASS chapter leader, a member of the Data Relay committee, SQL Bits, SQL Saturday, SQL Day, SQLGLA, PASS Summit speaker and helper.

You can contact Paul via:

- Email [paul@mrpaulandrew.com](mailto:paul@mrpaulandrew.com)
- Twitter [@MrPaulAndrew](https://twitter.com/MrPaulAndrew)
- LinkedIn [In/mrpaulandrew](https://www.linkedin.com/in/mrpaulandrew/)
- Blog [mrpaulandrew.com](https://mrpaulandrew.com)

### Richard Swinbank
__Senior Data Engineer @ Boomin__

Richard is the author of the lab materials provided as part of the workshop. He is an experienced data engineer specialising in the Microsoft Azure and SQL Server data platforms. An active member of the Microsoft data platform community, Richard is a speaker, blogger, volunteer and Data Relay event organiser. His book _Azure Data Factory by Example_ will be published by Apress in early 2021.

You can contact Richard via:

- Email [richard@richardswinbank.net](mailto:richard@richardswinbank.net)
- Twitter [@richardswinbank](https://twitter.com/RichardSwinbank)
- LinkedIn [In/richardswinbank](https://www.linkedin.com/in/richardswinbank/)
- Blog [richardswinbank.net](https://richardswinbank.net)

___
