![](SQATestAnalysisReport_TechFlow_GSAAgileBPA_03-media/media/image1.gif)

TechFlow, Inc. Response to

Request for Quotation (RFQ)

4QTFHS150004

Agile Delivery Services (ADS I)

Test Analysis Report (TAR)

June 30, 2015

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
familiarize the reader with the test results executed by TechFlow for
the Food and Drug Administration (FDA) in support of the Drug and Risk
Information (DARI) public information website. It details the analysis
of the testing performed and documents the results.

Testing commenced on June 23, 2015. The Test Phase conclusion coincides
with the end of the second sprint iteration on June 30, 2015. Tests were
composed and executed based on the acceptance criteria identified in the
user stories for both product increments.

-   Product Increment 1: Basic Search (MVP)

-   Product Increment 2: Search Enhancements

The TechFlow Software Quality Assurance (SQA) team executed 8 scenario
based tests comprised of functional and end-to-end testing. The purpose
of this testing was to confirm that the product implementation satisfies
the DARI product acceptance criteria for completion.

Scope
=====

<span id="_Toc319537325" class="anchor"><span id="_Toc319670480"
class="anchor"><span id="_Toc319670693"
class="anchor"></span></span></span>The following section presents the
verification points that were tested utilizing the latest versions of
Google Chrome (PC & Mobile), Microsoft Internet Explorer, Mozilla
Firefox:

Search Returns Label Information*The overall test mission of the ADS I MVP Phase 1 and 2 product includes validating the following:*
------------------------------------------------------------------------------------------------------------------------------------

-   Verified that the user is able to input a drug’s generic name into a
    text box and initiate a search on that particular drug.

    -   Verified that the text box is dependent upon an exact name match
        or partial match.

    -   Verified that the text box is not case sensitive.

-   Verified that the user is able to execute a new search with existing
    search results displayed.

-   Verified that the system displays FDA provided drug label
    information for the drug queried.

-   Verified that the system displays the drug label with the following
    information when available:

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

Disclaimer*The overall test mission of the ADS I MVP Phase 1 and 2 product includes validating the following:*
--------------------------------------------------------------------------------------------------------------

-   The overall test mission of the ADS I MVP Phase 1 and 2 product
    includes validating the following:Verified that the disclaimer is
    displayed at the bottom of every page.

-   Verified that the disclaimer text is indicative of sites with
    similar functionality.

    -   The prescription drug related information on this website is
        meant for basic informational purposes only. It is not intended
        to serve as medical advice, substitute for a doctor's
        appointment or to be used for diagnosing or treating a medical
        condition. Users of this website are advised to consult with
        their physician before making any decisions concerning their
        health.

FDA API Error Handling
----------------------

-   The overall test mission of the ADS I MVP Phase 1 and 2 product
    includes validating the following:Verified that the system provides
    an alert message on the interface that indicates a search failure
    has occurred.

-   Verified that the system provides a means to initiate a new search
    from the same interface after the message is displayed.

Search Returns Adverse Events
-----------------------------

-   Verified that the system displays FDA provided adverse event
    information for the drug queried.

-   Verified that the system displays search results aggregated by drug
    and event:

    -   Adverse Event

    -   Occurrences

Search Returns Graphical Representation
---------------------------------------

-   Verified that the system displays a pie chart that demonstrates the
    FDA provided adverse event information for the drug queried.

    -   Verified adverse events and aggregate the number of occurrences
        for each drug queried.

Add Links to Footer
-------------------

-   Verified that a link to the code repository is displayed in the
    footer and active

-   Verified that a link to the TechFlow website homepage is displayed
    in the footer and active

Auto-Complete
-------------

-   Verified that the system displays auto-complete suggestions for
    partial text strings typed into the search box

-   Verified that searches can be conducted on auto-complete suggestions

Google Analytics
----------------

-   Verified that the system displays traffic monitoring metrics

Test Analysis
=============

Each manual test scenario is executed and evaluated on an individual
basis. When the actual result does not meet the expected result, the
actual result will be recorded. The results of iterations of the
execution of test scenarios is recorded on the scrum board.

Development Phase Unit and Integrated Testing
---------------------------------------------

<span id="_Toc322594500" class="anchor"></span>The TechFlow development
team is responsible for Unit Testing and Integration Testing to make
sure the application developed is functioning according to the
acceptance criteria and design specifications. The unit testing utilized
JUnit tests, which are created for any new services and modified
services when applicable. The JUnit tests are designed to test
individual functional units of the software to make sure they work in
isolation.

Additionally, the Integration testing utilized Java based Selenium
tests, which were created to exercise the Graphical User Interface (GUI)
to ensure that the normal workflow is functioning properly prior to
handing off the testing activities to SQA.

System Testing
--------------

System Testing is the primary testing activity in the Test Phase and is
comprised of multiple types of testing: functional, end-to-end,
regression, usability, and 508(a) compliance, which were performed as
part of the DARI product testing. The majority of the testing is
performed manually in the application. The results of each test case run
were recorded on the scrum board.

### Functional Testing

There are no outstanding system deficiencies to report for the DARI
product deliverable.

There are no outstanding suggested enhancements to report for the DARI
product deliverable.

### Regression Testing

Regression testing was performed to confirm the any new DARI product
code and configuration did not negatively impact the functionality that
already passed testing. There are no outstanding items to report.

Conclusion
==========

Demonstrated Capability
-----------------------

8 test scenarios were executed based on the acceptance criteria
identified in the user stories for the DARI product.

-   As of June 30, 2015, the test scenario progress is as follows:

    -   8 Passed

    -   0 Failed

System Deficiencies
-------------------

There is one reported defect for the DARI product. The defect has been
added to the product backlog.

Recommended Improvements
------------------------

There are no outstanding recommended improvements to report for the DARI
product.

System Readiness for Review
---------------------------

The TechFlow SQA team concludes that the testing performed provides
evidence that the DARI product acceptance criteria has been successfully
implemented, the product is stable, and ready for delivery based on the
following:

-   The test approach was fully executed and satisfied via system
    testing.

-   The test scenarios were executed with one non-critical outstanding
    system deficiency.

-   Regression testing that has been performed has not exposed any
    defects related to new code.
