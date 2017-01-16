**THREE TIER GOVERNANCE**
*Created by @eric_bickel*

In order to maintain quality of work, it is incumbent upon the organization to ensure proper governance takes place. This governance must flow across the entire stack of analysis, beginning with the data and end at reporting. 

To limit control from the top, governance should be managed within each team, ideally with appointed individuals to monitor and track each of the three main processes: DATA, ANALYTICS, REPORTING.

**DATA GOVERNANCE**
Great analysis must begin with great data. This means that the data that we use must be properly sourced from both a credibility and legal standpoint, and the source(s) must be adequately cited throughout the analysis.

In addition to credibility in source, any cleansing of the data after harvesting should be properly defined. While in-depth details may not be necessary, a brief summary or guideline of the process used should be provided. This serves two purposes:
This ensures that we are not overriding the quality of good data with bad cleansing practices
It helps in the analytical process to understand how the data has been processed and munged when they are determining their methodologies

Within each team, a section within the README file outlining the scope should be developed to list all sources of data and links to their data.world location as well as the cleansing process of said data. 

**ANALYTIC GOVERNANCE**
Analysis is both an art and a science, which means there will always be some flexibility for creativity when deciding the methodology used to run it. However, it is necessary to ensure that the methodology is adequate for the problem at hand and implemented correctly. 

Within the same README file outlining the scope, one section should be dedicated to the analysis. This can be done in one of two ways:
A written section outlining the analysis performed on the data
A link to the analysis performed (e.g. ipynb or rmd files hosted on the team’s GitHub repo) 

Additionally, within each team the Project Lead should formalize a process for reviewing pull requests outlining any changes to the analysis by collaborators. This includes assigning individuals as designated reviewers of those requests, and ensuring transparency in any changes made in the README in cases where the changes materially affect the analysis.

**REPORTING GOVERNANCE**
Finally, proper reporting of the analysis out to the broader D4D community or general public is essential. No matter what we do to solve a problem, we cannot fully come to a solution if it is unsuccessfully communicated. While tracking governance from data collection to analysis will help us to properly communicate the process involved to come to a conclusion, each team should identify one individual to collect the results and disseminate through a single report. In addition to this one individual, at least two editors should be identified as well (ideally one heavily involved in the data collection and one heavily involved the analysis) to review the work and edit for accuracy.

Finally, each report should have a link to the README file to ensure total transparency. 
