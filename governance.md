**THREE TIER GOVERNANCE**

*Created by @eric_bickel*

In order to maintain quality of work, it is incumbent upon the organization to
ensure proper governance. We maintain quality of work by embedding governance
at every step of the process: data ingestion to data analytics to report
generation.

To encourage governance that is molded to each team, each team must appoint
individuals to monitor and track each of the three main processes: DATA,
ANALYTICS and REPORTING. This document aims to provide guidance for those
individuals that are responsible for each of these three processes.

**DATA GOVERNANCE**

Great analysis must begin with great data. For credibility and legality, the
data that we use must be properly sourced and adequately cited throughout our
processes.

Additionally, data cleansing efforts must be properly defined. When in-depth
details are not necessary, a brief summary or guideline of the process(es) used
should be provided. This serves two purposes:

- Ensure that we are using best practices for data cleansing to avoid reducing
  the quality of the incoming data.
- Help downstream analysis by clearly defining how the data has been processed.
  This may be relevant to determining which analytic methodology to use.

To implement these data cleansing guidelines, dedicate a section called "Data
Ingestion" within each team's README file. List all data sources along with
links to their data.world location. Include descriptions of any cleansing that
has been done to the data in the Project.

**ANALYTICS GOVERNANCE**

We recognize that analysis is both an art and a science, so flexibility and
creativity are absolutely encouraged. It is also necessary to ensure that the
chosen methodology is appropriate and correctly implemented. 

Dedicate one section to analysis Within the team's README file called "Data
Analytics". This section can be either:

- A written section outlining the analysis performed on the data
- A link to the analysis performed (e.g. ipynb or rmd files hosted on the
  team’s GitHub repo) 

It is the responsibility of the individual Project Leads to formalize a process
for managing changes to the analytic methodology as defined in the README. A
formalized change process is especially relevant when proposed changes
materially affect the analysis. The Project Leads should designate
individual(s) as reviewers of such requests to promote decision making
transparency.

**REPORTING GOVERNANCE**

Effectively communicating the analytic results to the broader Data4Democracy
community and the general public is essential. Even the best analytic results
can lose potency when communication methods are not ideal.

Each team should appoint one individual to champion each report. There should
be at least two editors for each report to review and ensure accuracy. One
editor should be appointed that was substantially involved in data ingestion
and another that was substantially involved in the analytics. Any additional
editors can be appointed at the discretion of the Project Lead.

Each report must link back to the Project's README file to ensure total
transparency. 

If a Project materially deviates from these Reporting suggestions, add a
section to the Project's README file under the heading "Data Reporting" and
detail the reporting practices of the Project. 

