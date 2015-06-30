![](GSA_Agile_BPA_ProjectCharter__04-media/media/image1.gif)

TechFlow, Inc. Response to

Request for Quotation (RFQ)

4QTFHS150004

Agile Delivery Services (ADS I)

Project Charter

June 23, 2015

***Proprietary Information Notice***: This document/proposal includes
data that shall not be disclosed outside the Government and shall not be
duplicated, used, or disclosed – in whole or in part – for any purpose
other than to evaluate this and the accompanied proposal. If, however, a
contract is awarded or modified as a result of, or in connection with
the submission of this data, the Government shall have the right to
duplicate, use or disclose the data to the extent provided in the
resulting contract. This restriction does not limit the Government’s
right to use information contained in this data if it is obtained from
another source.

<span id="_Toc393268130" class="anchor"><span id="_Toc423438686" class="anchor"><span id="_Toc423438992" class="anchor"></span></span></span>Project Information
================================================================================================================================================================

  Project Name                 Drug and Risk Information (DARI)
  ---------------------------- ----------------------------------------------------------------------------------------------------------------------------------
  Customer                     General Services Administration (GSA) Office of Integrated Technology Services (ITS) and U.S. Food and Drug Administration (FDA)
  Charge Activity              Bid and Proposal (B&P)
  Sponsor                      TechFlow
  Government Program Manager   N/A
  Government Project Manager   N/A
  TechFlow Program Manager     Mike Harp
  TechFlow Product Owner       Aristo Mitchell
  TechFlow Scrum Master        Elijah Miller
  TechFlow Business Analyst    Anthony Kimpo

The Drug and Risk Information (DARI) program provides the most current
information about drugs, both over-the-counter and prescription. This
allows a consumer to make timely and informed decisions such as use or
purchase of a drug. The TechFlow application, in support of the FDA
strategic initiative (Approved Risk Evaluation and Mitigations
Strategies), is designed to provide health professionals and consumers
the ability to view the labeling information without having to acquire
the drug.

<span id="_Toc393268132" class="anchor"><span id="_Toc423438688" class="anchor"><span id="_Toc423438994" class="anchor"></span></span></span>Requirements
---------------------------------------------------------------------------------------------------------------------------------------------------------

The TechFlow application supports the FDA strategic initiative (Approved
Risk Evaluation and Mitigations Strategies) by providing a solution that
a consumer and health professional can use to search and display FDA
information on-demand through the Internet and mobile devices.

In 2014 the FDA Risk Evaluation Team established the scope for the Drug
and Risk Information (DARI) program as the review of drug labeling
information. This scope is focused on developing a website with a
user-friendly interface that will allow searching of label data from the
FDA database. The website will also incorporate adverse events that have
been reported to the FDA. The scope is limited to the user-interface
design and the process to which the data will be pulled through the
available FDA API.

The TechFlow application will include the following functionality:

-   Search that returns label information, adverse events, and graphical
    representation of adverse events.

-   FDA API Error Handling

-   Auto-Complete

-   Google Analytics

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  For:            General consumers, healthcare and legal professionals.
  --------------- -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Who             Are seeking readily available FDA data that is searchable and can be available through the Internet and mobile devices.

  The:            Drug and Risk Information

  Is an:          Initiative to build a search driven user interface using FDA data provided through an FDA API. This website will allow the user to obtain detailed information on any drug in FDA’s database.

  That:           Provides users with searchable FDA data through an intuitive user interface.

  Unlike          The current situation which does not allow users to access FDA data through an effective search method to view pertinent drug information.

  Our Product:    > Connects to the FDA drug data
                  
                  > Pulls the data based on the data call
                  
                  > Presents the data to the user in a clear, concise & easy-to-use interface

  This supports   FDA’s ability to communicate effectively and efficiently with the general consumers, healthcare and legal professionals.
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------------------------
  **Name**              **Role**                                **Responsibilities**
  --------------------- --------------------------------------- -------------------------------------
  Aristo Mitchell       Product Owner                           Develop/Maintain Roadmap
                                                                
                                                                Develop/Maintain Release Plan
                                                                
                                                                Develop/Maintain Product Backlog
                                                                
                                                                Conduct Sprint Planning
                                                                
                                                                Perform User Story Acceptance
                                                                
                                                                Conduct Sprint Reviews
                                                                
                                                                Attend Sprint Retrospectives

  Elijah Miller         Scrum Master                            Conduct Daily Scrum
                                                                
                                                                Remove Obstacles
                                                                
                                                                Attend Sprint Reviews
                                                                
                                                                Conduct Sprint Retrospectives

  Anthony Kimpo         Product Development Team                Develop User Stories
                                                                
  David Anderson                                                Estimate User Stories
                                                                
  Danny McAllaster                                              Attend Sprint Planning
                                                                
  Kirby Domingo                                                 Develop, Test Code
                                                                
  Elijah Miller                                                 Attend Sprint Reviews
                                                                
  Cathy Artigues                                                Attend Sprint Retrospectives
                                                                
  Hung Chau                                                     
                                                                
  Thuy Cao                                                      

  Mike Harp, TechFlow   Program Manager                         Attend Sprint Reviews
                                                                
                                                                Attend Sprint Retrospectives

  ITS                   Project Sponsor / Product Owner         Attend Release Planning
                                                                
                        (GSA Stakeholder)                       Attend User Story Reviews
                                                                
                                                                Approve Non-Functional User Stories
                                                                
                                                                Attend Sprint Reviews
                                                                
                                                                Attend Sprint Retrospectives

  Matt Staples          Test Coordinator                        Attend Sprint Reviews
                                                                
                                                                Attend Sprint Retrospectives
                                                                
                                                                Coordinate UATs

  FDA                   Business Line Sponsor / Product Owner   Attend Release Planning
                                                                
                        FDA Stakeholder                         Attend User Story Reviews
                                                                
                                                                Approve Non-Functional User Stories
                                                                
                                                                Attend Sprint Planning
                                                                
                                                                Attend Sprint Reviews
                                                                
                                                                Attend Sprint Retrospectives
                                                                
                                                                Coordinate UAT Participants

  18F                   Business Line SMEs                      Attend User Story Reviews
                                                                
                        FDA Stakeholders                        Approval Functional User Stories
                                                                
                                                                Attend Backlog Grooming Sessions
                                                                
                                                                Attend Sprint Reviews
                                                                
                                                                Attend Sprint Retrospectives
                                                                
                                                                Attend UATs

  Other                 Stakeholders                            Attend Sprint Reviews
                                                                
                                                                Attend Sprint Retrospectives
  ---------------------------------------------------------------------------------------------------

  User Story                                                           Estimation
  -------------------------------------------------------------------- ---------------
  Search Returns Label Info                                            13 points
  Disclaimer                                                           3 points
  FDA API Error Handling                                               5 points
  The 3 user stories above constitute the MVP.
  Search Returns Adverse Events                                        8 points
  Search Returns Graphical Representation                              8 points
  Add Links to Footer                                                  1 point
  Auto-Complete                                                        8 points
  Google Analytics                                                     5 points
  The 5 user stories above constitute the next product increment.
  Expand Search capabilities                                           Not Estimated
  Expand Search Parameters                                             Not Estimated
  Results Filter                                                       Not Estimated
  Label Info UI Cleanup                                                Not Estimated
  The 4 user stories above constitute the remaining product backlog.

This project will execute 2 sprints lasting 8 days with one release to
production at the end.

Budgetary estimate.

**Assumptions:**

There are no assumptions for this project.

**Constraints:**

We have not identified any constraints for this project.
