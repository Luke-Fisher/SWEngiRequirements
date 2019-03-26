# Open Source Maintainer Assesses Risk Related to Project Turnover
Created by Carter Landis and edited by Paul Gillis and Luke Fisher

## Description 
Open source maintainers who maintain particularly sizable or useful projects may be widely depended on across the OSS ecosystem as well as within the corporate realm. To that end, such groups may wish to acquire an open source project or contribute to it regularly to ensure the survival of that on which they depend. As such, these groups may be concerned about the intellectual property that their members would be enabled to under the project's license, and the maintainer needs an accurate overview of their project's licenses so that they can provide the company with this information as determine what rights they would reserve as the original creator of the project and how much influence they would have over its future. Thus, there exists a need for a tool to determine a project's licensing within Augur.

## Triggers 
1. An open source maintainer is looking to turn control over their project over to a new group of open source maintainers or to a company.
2. An open source maintainer is contacted by a company or group of open source maintainers who are looking to adopt the maintainer's project.
3. An open source maintainer is trying to assess the licenses of their source code to determine if a license change is needed and possibly if one is even permitted.

## Actors 
1. An open source maintainer who has a project for which they are the only developer
2. A group of developers (in open source or at a company) who are looking to contribute to or utilize a project

## Preconditions 
1. The project must have a license in at least one file checked into Git.
2. The software must be open source and able to be accessed by Augur.

## Main Success Scenario (Goals)
The maintainer obtains information about all the licenses of the files in their project and the differences among them, providing them with information about the risk of turning a project turnover as it relates to their ability to maintain intellectual rights to the code already written as well as their rights to control who uses their software and which sections.

## Alternate Success Scenarios 
The maintainer obtains a very high level overview of licensing information for the project as a whole, enabling them to at a glance form an opinion about their whole project's licensing state. This is separate from the above condition in that license information about each file is not permitted, meaning that the developer would be unaware of source code files which have different licesnses.

## Failed End Condition 
The maintainer is either unable to view ANY licensing information about their project at all, or is not able to understand the provided information. 

## Extensions and Steps of Execution
1. Provide Augur with the URL for the project in question
    a. The project might be stored locally.  In this case, the user would be prompted to select the repository from their computer.
2. Select scan "depth:" shallow or deep.
3. Initiate scan.
4. Parse the relevant returned licensing information.

## Use Case Diagram
[Diagram](https://github.com/Luke-Fisher/SWEngiRequirements/blob/master/OpenSourceMaintainerUseCase.png)
