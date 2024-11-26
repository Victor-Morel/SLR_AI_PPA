# SoK: A classification for AI-driven personalized privacy assistants
## Objective
AI-driven Personalized Privacy Assistants (AI-driven PPAs) are agents or assistants leveraging Artificial Intelligence (AI) to automate or support end-users in making privacy decisions.
These AI-driven PPAs can harvest significant benefits for users, who may otherwise struggle to decide on their privacy in information-saturated environments.
However, no study systematically inquired whether these AI-driven PPAs are, for instance, privacy-friendly, or which specific kind of decisions they consider, their efficiency, etc.

In fact, there have been no surveys or systematic reviews on the topic of AI-driven PPAs.
This lack of systematization of knowledge prevents other researchers from identifying existing gaps in the field and efficiently addressing the challenges.
To address this lack of coherence, provide a common vocabulary, and better compare and categorize the different solutions, we propose a Systematization of Knowledge (SoK) of the last decade of research based on a Systematic Literature Review methodology.

## Rationale
During the planning phase, our first activity was determining the need for this SLR. Several databases were searched to verify if any surveys or reviews had been conducted on AI-driven PPAs.
Search terms such as privacy, data protection, assistant, agent, artificial intelligence, and machine learning were used.
However, we could not identify any survey or systematic reviews on the topic, reassuring the need for an SLR.


## Research questions
The main Research Question (RQ) that guided this SLR is the following: **What are the existing AI-driven agents and assistants for automating and supporting the privacy decisions of end-users for IT systems?**
Therefore, the remaining phases of this SLR reflect the RQ in the search process, selection criteria, and data synthesis, presented in the following subsections.

## Methods
### Design
This SoK study adopts the widely known methodology for SLRs proposed by (Kitchenham 2004) [^1].
The SLR methodology offers us a well-defined and rigorous sequence of methodological steps consisting of three main phases: (1) planning, (2) conducting, and (3) reporting the review.

### Eligibility criteria
Based on the research questions, and to reduce the likelihood of bias, the following inclusion and exclusion criteria are followed.
#### Inclusion criteria
- Provides a technical solution (implemented or theoretical) to help end-users automate personal (and personalized) privacy decisions with an assistant (or artificial agent) in IT systems.
- Papers from 2013 onward to concentrate on the state-of-the-art.
- The concept of AI needs to be explicitly stated in the papers.

#### Exclusion criteria
- Papers with solutions that are purely theoretical without substantial explanations on how they could be implemented in practice.
- Papers with solutions that solely automate the analysis of privacy policies but without any type of personalization.
- Papers with poor scientific quality (e.g., lack objectives or research questions, the methodology is not described, the solution is insufficiently/vaguely described, etc.)

## Information sources and search strategy
Four scientific databases were selected, i.e., Scopus, Web of Science, IEEE Xplore, and ACM Digital Library, due to their high relevance to the areas of computer science and engineering, comprising the vast majority of published research in the field.
We also specified inclusion and exclusion criteria (see above) used during the screening of publications retrieved from the databases.
Before starting the search process, two authors piloted the searches on all databases and ran a *calibration exercise* to verify the consistency of the inclusion criteria.
For that, the authors independently screened 10\% of the results and discussed their decisions.
The conflicts were all discussed and solved, sometimes with the help of a third author.
This process was repeated a second time, screening another 10\% of the papers, at a point that the authors agreed with the consistency of the selection process.

Based on our RQ and previous preliminary searches when designing the SLR Protocol, we identified a list of nine relevant keywords, i.e., privacy, data protection, assistant, agent, artificial intelligence, machine learning, intelligent, automatic, and personalized. These keywords were used to construct the following search query:

`(privacy OR "data protection") AND (assistant* OR agent*) AND ("artificial intelligence" OR "machine*learning" OR intelligent OR automat* OR personali*ed)`

As such, the search query targets papers working on three joint topics: 1) privacy (or data protection), using either 2) an assistant or an agent, and leveraging 3) artificial intelligence or personalization.


## Study records
### Data management
To manage the screening process, we will export search results from each database and then import them to the RAYYAN software (https://rayyan.ai/), allowing two reviewers to select papers independently (i.e., double-blinded) and manage conflicts by a third reviewer.
Duplicated publications can also be removed using RAYYAN during the selection process.
Bibliographies of final results will be exported to Zotero (for citing and sharing research).

### Data extraction
Preliminary components to be extracted:
- Bibliographic information, such as title, abstract, authors and affiliations, venues, year of publication, etc.
- Key information of the AI-driven PPA, such as its source(s) of data, its eventual architecture, its system context, the type of privacy decision considered, the accuracy of the decisions, the type of AI used, etc.
- The presence of a user study
- Extent of evaluation – scale of validation activity that is measured
- Quality assessment and critical appraisal of the studies that have validated or evaluated the AI-driven PPA
- Features of users control over decisions

### Types of contributions
Inspired by Kuhrmann et al.[^2] and Shaw[^3], we classified publications by their types of contributions (i.e., multiple choice) according to the following:
- **Model**, Representation of observed reality by concepts after conceptualization.
- **Theory**, Construct of cause-effect relationships.
- **Framework**, Frameworks/methods (related to automated privacy decisions).
- **Guidelines**, List of advice.
- **Lessons learned**, Set of outcomes from obtained results.
- **Advice**, Recommendation (from opinion).
- **Tool**, A tool to automate privacy decisions.

### Data synthesis
We collate and summarize results into classification tables.
We compose a narrative synthesis for papers that meeting our inclusion criteria.

Preliminary components of the data synthesis:
- Overall identification and classification of AI-driven PPAs in published research
- Classification tables presenting features of AI-driven PPAs used to coherently organize the solutions surveyed
- Comparison analysis -- based on the features of AI-driven PPAs --, and narrative synthesis


[^1]: Barbara Kitchenham. Procedures for performing systematic reviews. Technical Report 2004, Keele, UK, Keele University
[^2]: Marco Kuhrmann, Philipp Diebold, and Jürgen Münch. Software process improvement: a systematic mapping study on the state of the art
[^3] M. Shaw. Writing good software engineering research papers. In 25th International Conference on Software Engineering, 2003
