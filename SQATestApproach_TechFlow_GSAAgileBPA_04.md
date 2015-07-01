![](SQATestApproach_TechFlow_GSAAgileBPA_04-media/media/image1.gif)

TechFlow, Inc. Response to

Request for Quotation (RFQ)

4QTFHS150004

Agile Delivery Services (ADS I)

Test Approach

June 24, 2015

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

Purpose and Overview
====================

<span id="_Toc319537319" class="anchor"><span id="_Toc319670474"
class="anchor"><span id="_Toc319670687"
class="anchor"></span></span></span>The purpose of this document is to
familiarize the reader with the test activities executed by TechFlow for
the Food and Drug Administration (FDA) in support of the Drug and Risk
Information (DARI) public information website. It includes the
verification points of each user story grouped by product increment
based on the acceptance criteria. It presents the objectives, scope,
approach and focus of the testing effort for the DARI product.

During the development of the DARI product, for each product increment,
Software Quality Assurance (SQA) will perform functional, end-to-end and
regression testing to ensure that the overall business objectives
outlined in the user stories are complete and stable.

The overall business objectives include:

-   First product increment; Minimally Viable Product (MVP) – Basic
    Search

    -   The user is able to search the Food and Drug Administration’s
        (FDA) database for information about a drug that will help them
        make the best decision about its usage.

-   Second product increment – Search Enhancements

    -   The user is also presented with adverse events and number of
        occurrences of those events in the search results of a specified
        drug to further educate themselves on proper drug usage and
        potential side effects. The user is also presented with an
        auto-complete search feature intended to increase search
        efficiency.

The successful completion of the test activities for each product
increment is dependent on ensuring the aforementioned business
objectives are successfully implemented and that the Graphical User
Interface (GUI) is Section 508(a) compliant.

Testing
=======

<span id="_Toc319537325" class="anchor"><span id="_Toc319670480"
class="anchor"><span id="_Toc319670693"
class="anchor"></span></span></span>Test activities will be based upon
the verification points outlined in the [Test Iteration Missions Section
2.4](#_Test_Iteration_Missions). Each test will be executed and
evaluated on an individual basis. When the actual result does not meet
the acceptance criteria, a possible failure occurs. The tester will
explore the reason for failure and reproduce prior to reporting the
system deficiency to the development team.

System deficiencies will be raised and managed on the scrum board.

Test Mission*The overall test mission of the ADS I MVP Phase 1 and 2 product includes validating the following:*
----------------------------------------------------------------------------------------------------------------

*The overall test mission of the ADS I MVP Phase 1 and 2 product
includes validating the following:* *The overall test mission of the ADS
I MVP Phase 1 and 2 product includes validating the following:*The
overall test mission of the DARI product includes validating the
following:

-   Basic Search:

    -   A bug in this part of the system could cause the user community
        to not be able to search for the data corresponding to the drug
        they are researching, or could display inaccurate results that
        may lead to bodily harm.

    -   Testing challenges: Large Data Set

    -   Dependencies: None

-   *Search Results Additions:*Search Enhancements:

    -   A bug in this part of the system could display inaccurate
        results that may lead to bodily harm.

    -   Testing challenges: Large Data Set

    -   Dependencies: None

Test Thresholds
---------------

This section outlines the key metrics used to steer the product. These
include values for test coverage and release criteria. These thresholds
help testers focus on the most important aspects of the product with
respect to test.

  **Planned Test Coverage / Release Criteria for:**   **Supporting Development**                                                                                                             **Challenging Product**
  --------------------------------------------------- -------------------------------------------------------------------------------------------------------------------------------------- ----------------------------------------------------------------------------------------------------
  Scenarios                                           *N/A*                                                                                                                                  *100% of the Scenarios will be tested*
  Key Quality of Service Requirements (enumerate)     *N/A*                                                                                                                                  *N/A*
  Key Risks                                           *N/A*                                                                                                                                  *N/A*
  Defects                                             *High-Severity, High-Priority Defects Found during Development will be addressed during development or added to the product backlog*   *100% of the Defects Found during Testing will be addressed or added to the product backlog*
  Build Verification                                  *Jenkins code check-in notification logs will be closely monitored for each build*                                                     *N/A*
  Configurations                                      *N/A*                                                                                                                                  *N/A*
  Release                                             *N/A*                                                                                                                                  *Increments of the DARI product will not be submitted with any Severity Level 2 or Higher Defects*

The overall test mission of the ADS I MVP Phase 1 and 2 product includes
validating the following:

Test Techniques
---------------

This section outlines the methods used to obtain some of the goals set
forth in the test thresholds section.

  **Planned Test Techniques for:**                  **Tests Supporting Development**                                                                    **Tests Challenging Product**
  ------------------------------------------------- --------------------------------------------------------------------------------------------------- -------------------------------------------------
  Scenarios                                         *Manually testing the Integration of the code will be the responsibility of the Development Team*   *Manual Testing and Manual Exploratory Testing*
  Key Quality of Service Requirements (enumerate)   *N/A*                                                                                               *N/A*
  Key Risks                                         *N/A*                                                                                               *N/A*
  Defects                                           *Defects will be tracked using the scrum board*                                                     *Defects will be tracked using the scrum board*
  Build Verification                                *Jenkins code check-in notification logs will be closely monitored for each build*                  *N/A*

Test Iteration Missions
-----------------------

This section contains the Test Mission, including goals and techniques,
for each iteration of the DARI product. The section of the document will
be updated to include the current iteration as the product progresses.

### First Iteration Goals & Techniques (Minimally Viable Product)

The entrance criteria for the official test activities of the DARI
product MVP include the following:

-   The TF Development team provides confirmation that the code is ready
    for testing.

-   The TF SQA team has confirmed that the Test Environment is prepared
    and test ready.

-   The TF SQA team has updated to the latest version of Google Chrome
    (PC & Mobile), Microsoft Internet Explorer, and Mozilla Firefox; as
    these will be the platforms where the test execution will occur.

The goals and techniques of the DARI product MVP include the following:

-   Search Returns Label Information

    -   Verify that the user is able to input a drug generic name into a
        text box and initiate a search on that particular drug.

        -   The text box is dependent upon an exact name match or
            partial match.

        -   The text box is not case sensitive.

    -   Verify that the user is able to execute a new search with
        existing search results displayed.

    -   Verify that the system displays FDA provided drug label
        information for the drug queried.

    -   Verify that the system displays the drug label with the
        following information when available:

        -   Generic Name

        -   Brand Name

        -   Manufacturer name

        -   Purpose

        -   Indications and Usage

        -   Adverse Reactions

        -   Active Ingredients

        -   Inactive Ingredients

        -   Warnings

        -   Stop Use

        -   Do Not Use

        -   Ask Doctor

        -   Ask Doctor or Pharmacist

        -   Dosage

-   Disclaimer

    -   Verify that the disclaimer is displayed at the bottom of every
        page.

    -   Verify that the disclaimer text is indicative of sites with
        similar functionality.

        -   The prescription drug related information on this website is
            meant for basic informational purposes only. It is not
            intended to serve as medical advice, substitute for a
            doctor's appointment or to be used for diagnosing or
            treating a medical condition. Users of this website are
            advised to consult with their physician before making any
            decisions concerning their health.

-   Error Handling

    -   Verify that the system provides an alert message on the
        interface that indicates a search failure has occurred.

    -   Verify that the system provides a means to initiate a new search
        from the same interface after the message is displayed.

### Second Iteration Goals & Techniques (Second product increment)

The goals and techniques of the second increment of the DARI product
include the following:

-   Search Return Adverse Events

    -   Verify that the system displays FDA provided adverse event
        information for the drug queried.

    -   Verify that the system displays search results aggregated by
        drug and event:

        -   Adverse Event

        -   Occurrences

-   Search Returns Graphical Representation

    -   Verify that the system displays a bar chart that demonstrates
        the FDA provided adverse event information for the drug queried.

        -   Adverse events and aggregate the number of occurrences for
            each drug queried.

-   Links Added to Footer

    -   Verify that the system displays a link to the code repository
        and a link to the TechFlow main site.

-   Auto-Complete

    -   Verify that the search box lists suggestions for searching based
        upon the initial characters typed by the user.

        -   Matches are based against brand names; generic matches will
            not be list

        -   Users can select and search on suggested matches

        -   User can elect not to select the suggestions and search on
            any string

        -   When no matches, the auto-complete will relay no matches to
            the user

-   Google Analytics

    -   Verify that the system displays site traffic metrics to system
        admins.

Test Reporting
--------------

Each manual test will be executed and evaluated on an individual bases.
When the actual result does not meet the expected result, the actual
result will be recorded. The results of iterations of the execution of a
test case is recorded on the scrum board.

A Test Analysis Report will be generated when TF SQA testing is
complete. This report will contain the results and recommendations of
the TF SQA team for the submission of each phase of the product for
review.
