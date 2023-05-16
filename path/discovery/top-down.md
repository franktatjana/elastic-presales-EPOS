# Mapping Business Challenges to Technical Requirements/Expectations 

## TOP-DOWN Analysis (research-driven approach)
>//TODO: fix

[Example](link)
[Example Comdirect (top-down)](link)

 >//TODO: explain

### Title 
- **Conduct a business analysis**: information about the customer's business, industry, size, and operations; the company's mission statement and strategic plans. Reference sources are the company website, annual reports, or industry reports.

- **Determine the specific need to address:** the operational business process, new directions in strategy, customer journey, industry challenges and risks, service KPIs, new products, etc., and prioritize the requirements based on their importance to the business objectives by working with the customer to establish criteria for prioritization.

- **Validate the requirements**: Validate the requirements with the customer to ensure that they accurately reflect their needs and that the software will meet their expectations. This can be done through a formal requirements review process or through ongoing communication with the customer. 

  --- 
 >//TODO: explain

1. (WHY) Generate a company profile describing its mission and vision, goals and objectives, products and services the company offers, USP and competitive advantage, organizational structure and c-suite, financial highlights, challenges, and opportunities, future plans.
    - → AI prompt

        > Act as a management consultant and describe briefly and specifically the following aspects of the company **[company’s name]**: mission and vision of the company, goals and objectives, products and services the company offers, unique selling proposition and competitive advantage, organizational structure and C-suite, financial highlights, challenges and opportunities, digital maturity, and future plans. For reference, you can look up "**[URL]**". Format as a list of each aspect and provide relevant links as a reference
        > 
    - → Refinement
    
        * Review the Mission and Vision of the Company: check  info about the purpose and future goals, and analyze to understand priorities, values, and direction.
        
        * Analyze the Goals and Objectives: understand what the company is trying to achieve and how it plans to get there. These could be related to revenue, market share, customer satisfaction, and product innovation.
        
        * Study the Products and Services Offered: determine the target market, customers' needs, and preferences, and its competitive position. You can also find out the company's approach to innovation, product development, and customer service.
        
        * Evaluate Unique Selling Proposition (USP) and Competitive Advantage: understand how the company differentiates itself from its competitors and why customers should choose its products or services over others. By analyzing this, you can identify the company's strengths and weaknesses and what it needs to do to stay ahead in the market.
        
        * Study the Organizational Structure and C-suite: get a better understanding of the company's leadership style, decision-making process, communication channels, values, and management philosophy.
        
        * Analyze Financial Highlights_: get a clear picture of its financial health, growth potential, and profitability. You can also find out how the company is funded, its cash flow situation, and its investment priorities. Reference: news and IR reports.
        
        * Evaluate Challenges and Opportunities: identify the factors that are affecting its growth and what it needs to do to overcome them. You can also determine the company's potential for growth, its market position, and its competitive landscape.
        
        * Analyze Future Plans: understanding the company's plans will help you evaluate its growth potential, its strategic priorities and long-term goals.
        
2. (WHAT) Select a specific product or service and derive related processes including potential business challenges or problems, figure out what is needed to improve in the process, consider and estimate the impact on the company in case of process failure
    - → AI prompt
        
        > Act as a management consultant and describe in detail the business process of **[creating the company’s product or providing service]**, what potential business challenges might be faced, who is at the company responsible for the process, what process failures might occur, and estimate how it might impact the company’s business in general. Provide relevant links as a reference. Check recent news about the company.
        > 

    - → Refinement
        
        * Identify business processes: start by analyzing the business processes and make sure you understand how they work. Identify key steps in the process and points where problems may arise.
        
        * Identify Problems: use your experience and communication with employees to identify problems the business is having. Problems may be related to process efficiency, product or service quality, or other aspects of the business.
        
        * Figure out what data is needed: determine what data is needed to improve business processes. Figure out what data is collected, where it is stored, and how it is used.
        
        * Consider IT capabilities: examine what technology solutions can be applied to solve business problems. Consider software, data analytics, cloud solutions, and other technologies that can help improve business processes.
        
        * Identify potential benefits: determine what benefits can come from using IT to solve business problems. Consider the potential economic, operational, and strategic benefits.
        
        * Create an action plan: based on an analysis of business problems and IT opportunities, create an action plan. Include goals, objectives, resources, timelines, and evaluation of results.
        
3. (HOW) Select a specific problem, figure out what data is needed to improve the process, and examine what technology solutions can be applied to solve business problems
    - → AI prompt
        >  Describe specific ways to improve the business process of **[creating the company’s product or providing service]**, how **[“above stated potential business challenges” OR selected challenge]** might be handled with technology, what data or KPIs are relevant, and what outcomes to expect. Provide a specific example with elastic solutions.
        > 
    - → Refinement
        
        * Analyze the Current Process: review the process to identify bottlenecks, inefficiencies, and areas of improvement. Use process mapping tools to visualize the process flow and identify areas where time, resources, or effort are being wasted.
        
        * Identify Technology Solutions: look for technology solutions that can help address the identified challenge. **For example, if the challenge is 24/7 monitoring of customer-facing applications, then using automation tools with advanced analytics, implementing end-to-end holistic monitoring principles, or adopting a new workflow to manage the process could help.
        
        * Determine Relevant Data and KPIs: ídentify the key performance indicators (KPIs) that are relevant to the challenge you are addressing. For example, if the challenge is improving customer-facing application performance, then KPIs such as average page load time, and error rate could be relevant. Collect data on these KPIs to track progress and identify areas for further improvement.
        
        * Expected Outcomes: the expected outcomes of the process improvement will depend on the specific challenge being addressed. For example, if the challenge is reducing the error rate, the expected outcome could be increased efficiency or improved customer satisfaction. Set goals and regularly evaluate progress against them to ensure that the expected outcomes are being achieved.
        


## Mapping Top-Down Analysis Results to ESAT
>//TODO exaplain

| ESAT | Analysis |
| --- | --- |
| Project Background | Company profile & future plans, specific process or product to improve |
| Executive Summary | Service/process to improve and why |
| Solution Overview | Technology to improve the process/service |


## ESAT Building Blocks for Executive Summary

### Project Background
→ AI prompt
>
On the basis of the previous replies generate a description of the project addressing the business process of **[creating the company’s product or providing service]**, from the perspective of the company profile, goals, and USP.
>
**Business challenges**

→ AI prompt
> Validate if the description below satisfies the requirements for the definition of a business challenge and suggest improvements including a more strategic perspective and implying a technical solution **[business challenge definition]**
>
**Executive Summary**

→ AI prompt
> On the basis of the above information generate an executive summary for the project with the key goal of improving **[business problem/challenge in focus]** by **[approaches from HOW]**. Include top and bottom line arguments and measurable objectives with relation to elastic solutions  "https://www.elastic.co/products/". Format as a list.
>
**Solution Overview**

→ AI prompt
> On the basis of the above information generate a description of a specific elastic solution that can target **[project key goal]** and its capabilities that can target **[top and bottom line arguments].** Add a short list of advantages of the solution's capabilities in the context of requirements.
>
**Discovery**

→ AI prompt
> Act a CIO and on the basis of the above information generate a list of **3** specific measurable questions to the top management,  **5** specific questions to the middle management, and **7** questions to the technical team.  Answer questions as a hypothesis.
>