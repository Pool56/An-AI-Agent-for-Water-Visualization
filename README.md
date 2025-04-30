

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

_INSTRUCTIONS: Below are the suggested sections to include in your README file to make sure your project is well documented. You can remove this instruction text._

## Project summary
Public water management agencies face increasing pressure to deliver clean, safe and reliable water amid growing urban populations, aging infrastructure, environmental instability and limited operational budgets. Traditional water monitoring and infrastructure management systems are often fragmented, reactive, and labor-intensive, lacking the real-time visibility and automation necessary for modern utility challenges.
Moreover, there are water engineers who are either visually impaired or due to age are partially  and have difficulty using software such as Microsoft Fabric due to limited vision



### The issue we are hoping to solve
Issues being solved  include for water engineers:

1. Inability to continuously monitor and respond to environmental threats such as seismic activity and temperature fluctuations.

2. Limited visibility into internal water quality factors such as salinity, which affect treatment efficiency and public health.

3. Poor inventory tracking of critical infrastructure such as pipelines, valves, and treatment units, leading to maintenance delays and asset loss.

4. High dependence on manual processes for analysis, reporting, and application development, which reduces operational agility.

Another issue being solved for water engineers with limited vision who struggle to read most of the text that is placed on the software.

### How our technology solution can help
Our technology helps water engineers to effectively evaluate factors that could undermine performance of infrastructure used in a water industry.

Moreover, our solution ensures that the visually impaired are able to access software such as Microsoft Copilot or Microsoft Fabric  through use of plastic braille material.  


### Our idea

To address these problems, we have formulated an  AI- agent that unifies real-time monitoring (through use of Microsoft Fabric), three-dimensional simulation and agile application development. 
We are using Microsoft Fabric and Microsoft Copilot together with data obtained from Internet of Things sensors that are placed in water infrastructure such as in pipes.
So as to refine the data obtained from Internet of Things sensors we are using three-dimensional software such as NX software from Siemens and Autocard.



More detail is available in our [description document](./docs/DESCRIPTION.md).

## Technology implementation

### Microsoft services used
Microsoft Copilot
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

Microsoft Fabric 

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
- Empowers non-technical users to solve domain-specific problems, improves response times, and reduces reliance on IT backlogs.
- 

- [Microsoft Fabric]( https://www.microsoft.com/en-us/microsoft-fabric) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- Streamlines asset management and minimizes downtime due to untracked infrastructure.

- [Azure AI Playground](https://microsoft.github.io/azure-openai-service-proxy/playground/) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- Watsonx assistant was integrated with watsonx.ai so as to provide a  simple way to perform an integration between a dialog flow and generative AI inferencing services in watsonx.ai.

- 

### Other non-Microsoft technologies used

- [NX software](https://plm.sw.siemens.com/en-US/nx/) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
Watson Machine learning  was an associated service when using the watsonx. ai

- [AutoCAD](https://en.wikipedia.org/wiki/AutoCAD) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- Watson studio was accessible by use of the cloud pak for data, i used it in my solution by using templates provided in the cloud pak for data. Additionally I created a learning material which contained application of the use of Watson Studio from the IBM SkillsBuild. The title of the course was Clean, Refine and Visualize Data with IBM Watson Studio

### Solution architecture
Diagram and step-by-step description of the flow of our solution:

![image](https://github.com/user-attachments/assets/b1c9e62d-30dd-4592-955d-c3a9b759f470)


Solution for water engineers to get real time  insights for infrastructure such  
as pipes
![image](https://github.com/user-attachments/assets/232b60b3-f202-4340-bba0-e33c5c16d7cf)

Solution for water engineers  who are fully visually impaired or partially impaired
![image](https://github.com/user-attachments/assets/c3800ca8-45f3-4614-98d4-b4ded6e2902a)



![Video transcription/translaftion app]( )



## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video
### 
[![Watch the video] 

### Project development roadmap

The project currently does the following things.

- Feature 1. Use of watsonx.ai for generation of new content and use watsonx.governance for examining coppyright infringement
- Feature 2. Use of watsonx.ai ( for prediction and creation of responses from data obtained from Maximo Application Suite , Environmental Intelligence Suite and Envizi) and watsonx. orchestrate (automation of repetitive tasks). The results are placed into the IBM Cognos Analyics for deriving further data insights 


In the future we plan to use watsonx. data  for data management and other IBM technologies such as watson discover for intelligent document processing 

See below for our proposed schedule on next steps after Call for Code 2024 submission.
### https://drive.google.com/file/d/1tV-6Blomms2woXUWXRhw3Q3s8BatA8xW/view?usp=sharing
![Roadmap]()

## Additional details



### How to run the project



### Live demo


You can find a running system to test at...

See our [description document](./docs/DESCRIPTION.md) for log in credentials.

---



### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors


- ** John Maina** - _Initial work_ - 

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on Microsoft websites of sustainability and Corporate Social Responsibility. Additionally courses from Microsoft from Microsoft Learn
![image](https://github.com/user-attachments/assets/4c24676b-9061-46ca-a1b7-5939a6321e22)


![image](https://github.com/user-attachments/assets/60721a1d-e84a-412f-b72f-a6c7b3e43f6c)

![image](https://github.com/user-attachments/assets/986956ef-372b-427c-a0c8-306b7108d607)



