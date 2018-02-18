+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Learning Resource Metadata for SIL Curriculum"

# Project summary to display on homepage.
summary = "Architecting and documenting the business need for LRMI metadata within the mission of the Language and Culture Archive of SIL."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Architecture", "SIL-International", "Metadata"]

# Optional external URL for project (replaces project detail page).
external_link = "https://github.com/silinternational/lrmi-lo-lr-silc"

# Does the project detail page use math formatting?
math = false

#Draft Status
draft = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

#Draft Status
draft = true

+++

## Background discussion
### Discussions
This proposal comes out of several important discussions.

* The move in Global Language Program Services towards organizing around Services.

* The current inadequacies in the SIL Institutional Repsoitory's metadata schema to easily allow for the deployment of content to targeted market segments by our service via business intelligence and customer engagement platforms.

* The initial set of metadata for training resource objects in REAP was never really hammered down as solidly as other interactions in the schema. That is, it was always acknowledged that this portion of the schema would need to be revisited.

* The status quo for training material description can be read here: Submissions using REAP §e.iii.

### Current organization of collections in REAP
    The current status quo is that each SIL entity has a "training collection" in REAP. However, we feel that organizational arrangement needlessly inhibits productive cross-pollination of training ideas, and the efficient re-use of training materials. We would like to see training materials hosted in a single collection under the administration of the Training Provisioning Service (this is in essence a reconceptualized ILPT - a simplified name might be SIL Training Service). It is a service which operates globally and is organizationally anchored as part of Global Language Program Services. A second service, the curriculum development service would operate with the same global scoping and be anchored at the same node in our organizational structures. This second service would be responsible for maintaining the quality and the life-cycles of our training curriculum/materials.

### Anticipated scope of contributions

SIL staff produce a wide variety of training materials. It is very hard, even with the SIL staff and entities who use REAP, to know what materials (and SIL's staff's time) has gone into the production of training materials. We expect that the training materials which are produced by SIL staff as part of their assignments (which are fulfilling a training contract or MOU), training materials produced for another organization per contract or MOU, or training materials belonging to other IP holders but certified as meeting the SIL standard learning objectives would be stored in this collection. This collection would not cover materials which belong to others, but have not been certified though the ILPT Certification Service.

Note: we are not describing courses or workshops (which ILPT is doing, but elsewhere - and others do this also). We are describing the materials used in the training process (those courses and workshops).

#### Anticipated utility of scope of LRMI metadata within SIL operations

SIL's training operations (university partnerships and various workshops) are not the only curriculum materials produced by SIL staff. A great many mother-tongue literacy materials are used and created with SIL input. Much of the descriptive power of LRMI could be leveraged in the literacy domain to make their content more easily accessible and targetable to their audiences. Additionally, when materials produced are tagged for LRMI metadata (also described in more detail below), it allows SIL's business intelligence to look at macro-trends across a wide range of customers. Such an investigation on the utility of LRMI to the literacy area of operations has not been conducted. ILPT is interested in thoughtful feedback (and perhaps collaboration on this proposal) from the managers of literacy services in SIL. ILPT feels that the total impact of this work will be greater and the "dollars better spent" if the solution crafted for ILPT can also be crafted to increase the responsiveness of SIL's Literacy Services.

Because Paterson, Hugh has also taken SIL's literacy mega-course he is aware of some of the ways that literacy consultants look at the world. That is a reading primer might be targeted for adult learners, or child learners; LRMI can describe this difference. Another way to describe a reading primer is by if the reading primer is designed for a person who can already read, but in another language; or if it is designed for someone who is completely new to reading. A third way that describing a primer is by the methodology it uses to teach reading, for example: does it teach sight reading (whole word memory) or does it teach phonetic reading (for further explanation see [wikipedia](https://en.wikipedia.org/wiki/Teaching_reading:_whole_language_and_phonics)). This has been over generalized as top-down and bottom-up learning style. Within SIL there are several "recommended methods" for creating primers. These recommendations roughly follow the axises created with the previously mentioned three dichotomies.

When we think about literacy services in SIL, we could think about dollars, and follow the dollars. Simply following the supply and demand, servicing those who can pay to make a "literacy curriculum" happen is not a bad option. However, SIL would be uniquely situated to be able to show the results of the impact of literacy curriculum if a metadata proposal like LRMI were adopted. This would greatly add to the value of consulting with SIL for a language project's literacy needs. For instance, let's suppose that a certain language has agglutinative morphology, leaders in the development of this language are interested in lowering the language's EGIDS value (more support/wider use). They want to look at example primers from other agglutinative languages, to see if there was an impact for choosing a top-down, vs. bottom-up approach with adult learners. SIL is in the unique situation where it could deliver answers to these complex questions via business intelligence. Currently without something like LRMI SIL is not able answer questions which involve teaching style, target learner, and linguistic complexity. Literacy consultants grapple with current customers to find solutions, and relationships are generally managed well. However, the de-coupled nature of SIL's organizational structure prevents many consultants from giving informed answers from outside of their immediate experience. That is, very few consultants could answer a question regarding linguistic complexity, based on language data from any three of the global SIL Areas. (Americas, Asia, Pacific, Africa, Eurasia, etc.) Often, the basis of answers, is to create a comparison based on relationships to languages the client might know, rather than on the basis of languages which function in a similar way to how the client's language functions.

##Governance metadata elements
###Current governance of metadata elements

Current amendments to the metadata schema in REAP is done via a proposal system on a special page set up for proposals to changes in REAP metadata: Archiving Development Forum: Metadata topics Decision Register. Proposals are made and then the REAP architecture team inclusive of Spanne, Joan and Nordmoe, Jeremy, make decisions based on feed back from the proposal's commenters.
###Governance of future metadata elements
The current process for approval or removal of metadata elements from REAP does not necessarily include provision for, or require the REAP architecture team to, account for specific business processes by specific service units within SIL. That is, ILPT may ask for metadata elements to be added, and then those metadata elements may be approved or denied. And then if approved, they may be deprecated at any time, without regard to our (ILPT's) current business models and impact thereon. This poses a great deal of risk for ILPT as we consider REAP and the services that the Language & Culture Archive offers us as a critical partner in offering our training provisioning service.
To mitigate this risk I propose that the metadata related to training materials be governed more closely to the locus of management for the training provisioning service. In this manner, we at ILPT can be have guaranteed direct input into metadata elements which will impact our business intelligence.
Such independence in governance need not be without the consultation of the REAP architecture team. All effort should be made to not duplicate metadata elements across the schemas used in the REAP system.
##Referenced Standards in the Metadata Schema

The following discussion of metadata elements refences several standards maintained by SIL. Some of these standards need to be made public and hosted in a public place. The following chart attempts to list the standards and their purposes.

| Standard                                          | Purpose of Standard/ Definition of Standard                                                                                                                                                                                    |
|---------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Corporate Competencies index                      | This is a list of the competencies that SIL uses and recognizes.                                                                                                                                                               |
| Curriculum Development and Publication Guidelines | This is the standard to which SIL curriculum should be developed. It also contains the publication guidelines for SIL curriculum. It is the,standard we reference when we do our consulting for the development of curriculum. |
| SIL Acknowledged Educational Frameworks           | This is a list of the educational frameworks that SIL supports referencing via our Metadata schema.                                                                                                                            |
| SIL Standard Course index                         | This is the list of all competency exchange events SIL offers.                                                                                                                                                                 |
| SIL teaching pedagogy standards                   | This is the standard to which SIL courses should be taught. It is the,standard that SIL licensed vendors are expected to maintain when they have a "license to teach SIL curriculum".                                          |
| SIL's list of defined subject terms               | A list of subject terms with specific meanings. These meanings are referenced and searchable.                                                                                                                                  |
