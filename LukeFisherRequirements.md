# Corporate Project Manager Assesses Risk Related to Project Adoption

## Description 
Often times when reviewing a project to adopt, community managers wish to assess the risk associated with adoption. After all, companies will often be spending large sums of money and time supporting, maintaining, and improving the projects they adopt. Risk comes in many forms, often not obvious or easily measurable. Measures of risk that companies are insterested in include how expensive the project would be to maintain, how much time would need to be spent maintain the project, licensing and legal issues that may appear (such as copyleft vs non-copyleft), system reliability (especially true for safety critical systems), system security (especially where user information or money is involved), what such a project could do to the company image, and competitive risk. 

## Triggers 
1. A project manager notices an open source project they find useful and want to see is it's possible to support it.
2. A project manager finds that their team or company relies on an open source project and wants to see if it's possible to support it.
3. A group of project managers from various companies want to see if it's possible to pool their resources to adopt a project they all find usefull.

## Actors 
A project manager
OSS manager

## Preconditions 
1. A company uses or heavily relies on open source sofware and believes it would be beneficial to support it.
2. The company has some resources avaliable to dedicate to maintaining the project.
3. The software must be open source and able to be assessed with augur.

## Main Success Scenario (Goals)
The project manager assess risk associated with project adoption, decides the risk is tolerable, and adopts the project.

## Alternate Success Scenarios 
The project manager assess risk associated with project adoption, decides the risk is too high, and decides not to adopt the project.

## Failed End Condition 
1. The project manager doesn't see enough risk metrics to feel comfortable making a decision.
2. The risk measurements are clear enough or well-documented enough to be understood.

## Extensions
1. Suggest risk evaluation metric
2. Contact project current OSS project developer
3. Get help
4. View metric details

## Steps of Execution
1a) User notices a metric they would find useful isn't implemented in augur
1b) Click "Suggest New Metric" button
1c) A form opens up prompting the user to enter a metric suggestion, description of the metric, and contact info
1d) User submits form and resumes

2a) User wishes to contact open source manager
2b) User clicks "Contact OSS Manager" button
2c) User is directed to the OSS manager's GitHub page

3a) User is having trouble using augur's risk evaluation tool
3b) user clicks "Help" button
3c) User is directed to a help page regarding the risk evaluation tool

4a) User wants to view details about a specific metric
4b) User clicks "View Metric Details" button
4c) Pop-up with graphs, explanations, and data pops up.
4d) User closes pop-up and resumes
## A use case diagram
(following the UML Standard for expressing use cases.)

## Dependent Use Cases