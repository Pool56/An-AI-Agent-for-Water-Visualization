

# Table of contents for an AI agent for water visualization

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [Microsoft services used](#microsoft-services-used)
  - [Other technology used](#other-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)



## Project summary
Public water management agencies face increasing pressure to deliver clean, safe and reliable water amid growing urban populations, aging infrastructure, environmental instability and limited operational budgets. Traditional water monitoring and infrastructure management systems are often fragmented, reactive, and labor-intensive, lacking the real-time visibility and automation necessary for modern utility challenges.
Moreover, there are water engineers who are either visually impaired or due to age are partially  and have difficulty using software such as Microsoft Fabric due to limited vision



### The issue we are hoping to solve
Issues being solved  include for water engineers:

1. Inability to continuously monitor and respond to environmental threats such as earth quakes (seismic activity which could damage water pipes that are located underground)  and temperature fluctuations such as intense heat which abnormally raises water temeperature and even destroys electrical components.

2. Limited visibility into internal water quality factors such as salinity, which affect treatment efficiency and public health.

3. Poor inventory tracking of critical infrastructure such as pipelines, valves, and treatment units, leading to maintenance delays and asset loss.

4. High dependence on manual processes for analysis, which reduces operational agility.

Another issue being solved for water engineers with limited vision who struggle to read most of the text that is placed on the software.

### How our technology solution can help
Our technology helps water engineers to effectively evaluate factors that could undermine performance of infrastructure used in a water industry.
The objective is using IoT sensors together with software that could report current information to water engineers. The goal is to use real-time data so as to effectively analyse the currrent status of equipment used for water distribution. 

Moreover, our solution ensures that the visually impaired are able to access software such as Microsoft Copilot or Microsoft Fabric  through use of plastic braille material.  


### Our idea

To address these problems, we have formulated an  AI- agent that unifies real-time monitoring (through use of Microsoft Fabric), three-dimensional simulation and agile application development. 
We are using Microsoft Fabric and Microsoft Copilot together with data obtained from Internet of Things sensors that are placed in water infrastructure such as in pipes.
So as to refine the data obtained from Internet of Things sensors we are using three-dimensional software such as NX software from Siemens and Autocard.




## Technology implementation

### Microsoft services used
# Microsoft Copilot
Microsoft Copilot empowers utility staff and engineers to create custom applications, automate tasks, and generate insights without deep technical expertise.
Key Applications of Copilot in Water Management:
Task Automation:

Automatically summarize incoming data from sensors or reports.

Generate real-time incident response plans based on external environmental data.

Auto-generate email alerts, maintenance schedules, and compliance documentation.

App Development:

Use natural language to design low-code apps for field engineers to log equipment status or perform site inspections.

Build user interfaces for asset tracking, predictive maintenance, or leak reporting with Copilot in Power Apps.

Create chatbots for internal teams to quickly retrieve infrastructure data or environmental conditions.

Integration with Fabric:

Connect Copilot-developed apps to Fabric’s Lakehouse, Real-Time Analytics, or Power BI workspaces.

Use AI to suggest data model improvements, KPI formulas, or visualization strategies.

# Microsoft Fabric 

Leveraging Microsoft Fabric Event Analytics for Real-Time Monitoring and Management
Microsoft Fabric provides a unified data platform that supports real-time analytics, large-scale data integration, and intelligent infrastructure monitoring through the following components:

1. Real-Time Intelligence for External Environmental Monitoring
Use Case:
Monitor and react to seismic activities (via Richter scale) and temperature shifts that may affect pipeline integrity or water supply stability.

Functionality:

Real-Time Intelligence connects to sensor feeds via IoT Hub or Event Hub.

Enables rule-based monitoring (such as ground motion exceeding threshold) with alerts.

Supports visualization in Power BI for fast decision-making.

Value:
Improves disaster readiness and infrastructure risk awareness.

2. Event Stream for Internal Condition Monitoring ( such as salinity)
Use Case:
Continuously analyze salinity levels within pipelines or reservoirs to ensure compliance and operational quality.

Functionality:

Event Stream captures real-time readings from internal water quality sensors.

Performs transformations such as filtering, enrichment, and routing to Lakehouse for deep analytics.

Enables triggers when thresholds are crossed.

Value:
Supports dynamic water treatment optimization and early anomaly detection.

3. Dataflow Gen2 for Infrastructure Inventory Management
Use Case:
Maintain up-to-date records of pipes, fittings, and facility components across the water network.

Functionality:

Automates ingestion and transformation of asset data from spreadsheets, ERP systems, or operational logs.

Cleans, enriches, and stores the inventory in a structured format ( such as  Lakehouse tables).

Feeds Power BI dashboards with asset lifecycle, maintenance status, and risk factors.

**Importance of software used**

- [ Microsoft Copilot](https://copilot.microsoft.com/) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
-  Microsoft Copilot was used to create AI agents which function as  assistants especially the agent where an activity map was used to examine accuracy of responses.
-  Microsoft Copilot was  used to generate code by use of C# programming language
- Microsoft Copilot was also used to automate tasks by use of flows which a sequence of actions were triggered based on certain conditions

- [Microsoft Fabric]( https://www.microsoft.com/en-us/microsoft-fabric) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- Streamlines asset management and minimizes downtime due to untracked infrastructure.

- [Azure AI Playground](https://microsoft.github.io/azure-openai-service-proxy/playground/) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- The Azure AI playground was used as an alternative for performing computations for analysis of mechanical components of pumps as well as designing of braille material.
- Below  are videos illustrating how Azure AI playground was used;
- https://youtu.be/YaWbm4kgBLE
- https://youtu.be/Q4NB53KcXyw
- Below are drive documents that documents how Azure AI playground
- https://drive.google.com/file/d/1KiEtQ_rS3asNua6qjxeVET7DrvpQ7Qjo/view?usp=sharing
- https://drive.google.com/file/d/1PGbdhzFXoV2jKtFQ-FE5Kc5G22gBJLKe/view?usp=sharing
- https://docs.google.com/document/d/1dUcu80sCvpVxI0mM4A6t4p5i_fw-G-wl/edit?usp=sharing&ouid=115192565142409982962&rtpof=true&sd=true
  

### Other non-Microsoft technologies used

- [NX software](https://plm.sw.siemens.com/en-US/nx/) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- NX software is used for three- dimensional simulation of aspects such as force which it is able to offer information of how the different  structures are impacted by factors such as temperature.
- It is used in the solution by placing the analytical information into Microsoft Copilot which provides more detailed data which could aid water engineers to make accurate decisions


- [AutoCAD](https://en.wikipedia.org/wiki/AutoCAD) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- Was used in the design of braille material, for this solution AutoCAD guided us in determining dimensions to use for construction of Braille material

### Solution architecture
Diagram and step-by-step description of the flow of our solution:

![image](https://github.com/user-attachments/assets/b1c9e62d-30dd-4592-955d-c3a9b759f470)


Solution for water engineers to get real time  insights for infrastructure such  
as pipes

![image](https://github.com/user-attachments/assets/0fbe0aa5-d132-491f-b438-b4f587d5b500)



Solution for water engineers  who are fully visually impaired or partially impaired
![image](https://github.com/user-attachments/assets/f727fc07-8633-4137-b0e8-7bc41ad1c73d)



## Presentation materials

https://docs.google.com/presentation/d/1w21sWLBfeAatAISrgv7epF6ibtaqZ4i4/edit?usp=sharing&ouid=101103218955394927682&rtpof=true&sd=true

### Solution demo video


### Project development roadmap

The project currently does the following things.

In the future we plan to use other Microsoft software such as Github for Copilot


## Additional details



### How to run the project

The project is run by use of Microsoft Copilot

### Live demo
You can find a running system to test at...

https://copilotstudio.microsoft.com/environments/Default-6e2cc058-79af-4df8-92e6-ee6e0d1dea3e/bots/crf8a_dataVisualizerForWaterEngineers/canvas?__version__=2&enableFileAttachment=true



---



### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

The version is based on use of Microsoft Copilot together with  other Microsoft services such as Microsoft Fabric

### Authors


- ** John Maina** - _Initial work_ - 

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

-  I would seek to acknowledge where we referenced our project based on Microsoft websites of sustainability with regard to water positive  as well as the global diversity and inclusion report of the year 2024. Additionally courses from Microsoft from Microsoft Learn. The information outlined from both the website and courses were  what inspired us.
-  https://learn.microsoft.com/en-us/collections/7wyni8tnojw5xq?ref=collection&listId=8wy3iztmn7j2p5&sharingId=6A9F03F25E12DA9E  (AI Skills Fest Challenge: AI for Public Sector Upskilling)
-  https://blogs.microsoft.com/on-the-issues/2019/03/22/on-world-water-day-microsoft-is-delivering-new-approaches-to-ensure-we-leave-no-one-behind/
-  https://www.microsoft.com/en-us/diversity/inside-microsoft/annual-report
  
![image](https://github.com/user-attachments/assets/4c24676b-9061-46ca-a1b7-5939a6321e22)


![image](https://github.com/user-attachments/assets/60721a1d-e84a-412f-b72f-a6c7b3e43f6c)

![image](https://github.com/user-attachments/assets/986956ef-372b-427c-a0c8-306b7108d607)



