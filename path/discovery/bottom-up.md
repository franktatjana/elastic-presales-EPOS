# Mapping Technical Requirements/Expectations to Business Challenges

## Bottom-up (question driven) 
> //TODO: fix

[Example](link)

> //TODO: explain

1. **Conduct a technical analysis**: identify key technical needs and requirements of the project in general, analyze the **IT landscap**e, infrastructure, dependencies and technology stack; review technical documentation and data sources if available. Important contribution is the information about existing solutions, and if the team is searching to replace or improve their experience with this solution. **Provide a list of discovery questions, ask to share at least 5-10 questions from the team to derive their needs and priorities.** Create a matrix of **stakeholders** to start evaluating engagement, championship and necessary contacts for validation of identified business challenges and proper impact quantification.

2. **Determine the specific need to address:** discuss existing workflows, scenarios and areas of improvement like increased visibility in IT landscape, increased alerting efficiency or decreased MTTR, if there are any existing KPIs, SLA/SLOs or other specific aspects for optimization. Identify the business critical process, that is searched to be improved and why, analyze how it is integrated / supports the company's product or service.

>ESAT (link and definition)
>

1. **Validate the requirements**: validate the results with the middle and top management stakeholders to ensure that the technical analysis accurately reflects the business processes and relevant needs and challenges.
2. **Analyze the impact of technical challenges on business goals and Quantify the benefits:** Once you have identified the technical challenges, analyze how they impact the business goals. Quantify the benefits in terms of cost savings, increased revenue, improved customer satisfaction, or any other relevant metric. This will help make a stronger case for the technical solution and demonstrate its potential impact on the business.
3. **Prioritize technical challenges based on business impact:** After analyzing the impact of technical challenges on business goals, prioritize them based on their potential impact on the business. For example, if increasing revenue is the most critical business goal, prioritize the technical challenges that can help achieve that goal / plan implementation.

  --- 

- **(WHY, but actually WHAT)** Outline all available data sources, IT landscape, infrastructure, dependencies, technology stack, and solutions.
    
    → AI prompt
    > Act as a solution architect and generate **[number]** specific questions about available data sources, IT landscape, infrastructure, dependencies, technology stack, solutions, **[information from SDR/sales reps]**. The questions will be addressed to **[personas in team, e.g. SRE, sysadmin, developer],** provide in a list form what is important for each stakeholder and what IT tasks they are responsible for.
    >

- **(HOW)** Identify areas of inefficiency or duplication within the existing IT landscape, identify opportunities to consolidate or streamline systems and processes, and map it to elastic solution capabilities and values
    
    → AI prompt
    > Act as a solution architect and  please help me by generating a list of questions to achieve the following goals:
    Identify areas of inefficiency or duplication within the existing IT landscape **[information from SDR/sales reps]**.
    Identify opportunities to consolidate or streamline systems and processes **[information from SDR/sales reps]**.
    Map it to elastic solution capabilities and values.
    >
    
- **(WHAT, but actually WHY)** Ensure that the process has a measurable impact on internal business processes/ customer-facing products or services, is embedded in projects supporting the organization's strategic goals and objectives, finds challenges or potential risks associated with the process/service
    
    → AI prompt
    > Act as a solution architect and  please help me by generating a list of questions to achieve the following needs:
    Ensure that the process has a measurable impact on **[internal business processes or customer-facing products or services]**.
    Embed the process in projects that support the **[organization's]** strategic goals and objectives and **[industry]** trends.
    Identify challenges or potential risks associated with the **[process]** or **[service/ product].**
>

### Mapping Top-Down Analysis Results to ESAT

| ESAT | Analysis |
| --- | --- |
| Current Architecture | IT Landscape, data sources, SLA/SLOs, workflows |
| Future Architecture | Service/process to improve and why |
| Executive summary | Prioritised and quantified need, aligned with business goals |