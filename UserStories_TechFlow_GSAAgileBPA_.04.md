![](UserStories_TechFlow_GSAAgileBPA_.04-media/media/image1.gif)

TechFlow, Inc. Response to

Request for Quotation (RFQ)

4QTFHS150004

Agile Delivery Services (ADS I)

User Stories

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

The purpose of this document is to familiarize the reader with the user
stories developed by TechFlow the Food and Drug Administration (FDA) in
support of the Drug and Risk Information (DARI) public information
website. It includes the stories grouped by product increments and the
acceptance criteria around which the stories will be evaluated.

User stories were developed with attention to the end user’s point of
view and were grouped to provide discrete pieces of functionality that
deliver business value. User stories providing basic functionality were
prioritized first in the backlog with increased functionality
prioritized later.

We intentionally drafted more stories than could be delivered in the
development timeframe to indicate stretch goals. Additional backlog
items and one known defect based on sprint review feedback were also
incorporated into the backlog; anticipated delivery of those items
extending beyond the delivery of the initial product increments.

User Stories
============

Minimally Viable Product (MVP) Basic Search
-------------------------------------------

### Story 1 Search Returns Label Info – EFFORT = 13

As a user interested in researching drugs and their side effects,\
I want to be able to search on a drug and be presented with general
information regarding the drug\
so that I can educate myself to make the best decision regarding drug
usage.

-   **acceptance criteria**

    -   user is able to input a drug generic name into a text box and
        initiate a search on that particular drug - exact name match,
        case insensitive

    -   user is able to execute a new search with existing search
        results displayed

    -   system displays FDA provided drug label information for the drug
        queried

    -   system displays search drug label (possible field values, when
        available)

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

### Story 2 Disclaimer – EFFORT = 3

As a system administrator,\
I want a disclaimer displayed in the footer of all pages accessible by
any user interacting with the system\
so that the scope of rights and obligations inherent with the use of the
system are clearly communicated.

-   **acceptance criteria**

    -   disclaimer is displayed on page footer

    -   disclaimer text is indicative of sites with similar
        functionality

        -   *The prescription drug related information on this website
            is meant for basic informational purposes only. It is not
            intended to serve as medical advice, substitute for a
            doctor's appointment or to be used for diagnosing or
            treating a medical condition. Users of this website are
            advised to consult with their physician before making any
            decisions concerning their health.*

### Story 3 FDA API Error Handling – EFFORT = 5

As a user searching drugs and their side effects,\
I want to be prompted when an error occurs with my search attempts\
so that I am aware of the status of my search and so that I can initiate
a new one as needed.

-   **acceptance criteria**

    -   system provides an alert message on the interface that indicates
        that the FDA data is not available

    -   system provide a means to initiate a new search from the same
        interface after the alert is displayed

Product Increment Search Enhancements
-------------------------------------

### Story 4 Search Returns Adverse Events – EFFORT = 8

As a user interested in researching drugs and their side effects,\
I want to be able to search on a drug and be presented with adverse
events and the number of occurrences of those events\
so that I can educate myself to make the best decision regarding drug
usage.

-   **acceptance criteria**

    -   system displays FDA provided adverse event information for the
        drug queried

    -   system displays search results aggregated by drug and event

        -   Adverse Event

        -   Occurrences

### Story 5 Search Returns Graphical Representation – EFFORT = 8

As a user interested in researching drugs and their side effects,\
I want to be able to search on a drug and be presented with a graphical
representation of the search results data returned\
so that I can educate myself to make the best decision regarding drug
usage.

-   **acceptance criteria**

    -   system displays a bar chart that demonstrates FDA provided
        adverse event information for the drug queried

        -   adverse events & aggregate \# of occurrences for each drug
            queried

### Story 6 Add Links to Footer – EFFORT = 1

As a system administrator,\
I want the search page footer to display a link to the code repository
and a link to the TechFlow website on all pages that are accessible to a
user interacting with the system\
so that links to the code and TechFlow are available for RFQ evaluators.

-   **acceptance criteria**

    -   a link to the code repository is present and working at the
        bottom of the page

    -   a link to ‘about TechFlow’ is present and working at the bottom
        of the page

### Story 7 Auto-Complete – EFFORT = 8

As a user interested in researching drugs and their side effects,\
I want drug search inputs to auto-complete based on my initial
keystrokes\
so that I may execute my searches more efficiently.

-   **acceptance criteria**

    -   system auto-completes drug names based on initial keystrokes

    -   auto-complete options displayed will match partial search text
        against brand name information and will continue to display
        until search text does not match

    -   user is able to select an auto-complete suggestion and execute
        successful search on the suggested drug

    -   user is able to not select an auto-complete suggestion and
        execute successful search

### Story 8 Google Analytics – EFFORT = 5

As a system administrator,\
I want to incorporate Google analytics into the drug search page

so that I can drive more users to the site and improve the overall
search experience.

-   **acceptance criteria**

    -   Google analytics are enabled on the website

Product Backlog
---------------

### Story 9 Expand Search Capabilities

As a user searching drugs and their side effects,\
I want to be able to have additional search capabilities\
so that I may execute my searches more efficiently.

-   **acceptance criteria**

    -   hover graph

    -   implied wildcards on partial text strings

    -   Auto-complete ‘no suggestion’ text change – use ‘fuzzy search’
        (did you mean…)

### Story 10 Expand Search Parameters

As a user searching drugs and their side effects,\
I want to be able to search utilizing different search parameters\
so that I may have greater flexibility with my searches.

-   **acceptance criteria**

    -   multiple drugs

    -   adverse effects

    -   indications

### Story 11 Results Filter

As a user reviewing search results,\
I want to be able to filter search results by age and/or sex\
so that I may have the ability to further refine my search results.

-   **acceptance criteria**

    -   filter by sex

    -   filter by age

### Story 12 Label Info UI Cleanup

As a user reviewing drug search results,\
I want drug label information to be displayed in a manner that is more
user friendly\
so that I may view my search results easier.

-   **acceptance criteria**

    -   raw text within 'Read More' windows are parsed

### Story 13 508 Compliance

As the application owner,\
I want the application site to be 508 compliant\
so that it may be accessible to users with disabilities.

-   **acceptance criteria**

    -   DARI site is 508 compliant

### Story 14 Additional Google Analytics Metrics

As the application owner,\
I want additional Google Analytics metrics deployed

so that I may actionable feedback from the users interacting with the
application.

-   **acceptance criteria**

    -   keyword search metrics

Known Defects
-------------

### Defect 1 Auto-Complete Suggestions Not Receiving Search Results

In some cases the suggestions made by the auto-complete functionality
are not producing search results. If the auto-complete is making a
suggestion, the suggestion should yield results. Possible root cause is
a difference in source of the auto-complete and actual drug information
and adverse events search.

-   **Steps to reproduce**

    -   Type ‘inm’

    -   System will suggest InMind

    -   Select suggestion and click search

    -   System shows ‘drug not found’ message
