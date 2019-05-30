+++
title = "Lexical Database Archiving Questionnaire"
date = 2013-11-26T16:12:45-07:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Archive", "Digital Archival", "FLEx", "ToolBox", "Lexical Database"]
categories = ["Digital Archival", "Linguistics", "Lexicography"]

#It used to be that math and highlight were controlled per post... not sure why not now.
#math = false
#highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = "headers/Database-Questionnaire-Header-image-wide.png"
caption = ""
preview = false

# Left to do for this post:
# - Take it out of draft.
# - Fix the centering on the image of the data... can I make a dynamic data graph from data in a table?
# - Fix all the wordpress short codes.
# - Fix links to other related posts from Hugh.thejourneyler.org back to the New CV.
# * http://hugh.thejourneyler.org/share-the-questionnaire/understanding-archive-resource-publicity/
# * http://hugh.thejourneyler.org/share-the-questionnaire/engaging-archives/
# * http://hugh.thejourneyler.org/share-the-questionnaire/
# * http://hugh.thejourneyler.org/2013/lexical-database-archiving-questionnaire/
# * http://hugh.thejourneyler.org/share-the-questionnaire/dichotomy-of-lexical-resources/
# - Add redirects from old site to this site.
# - Fix broken or outdated links.
# - Find a way to do image captions.
# -- https://www.xaprb.com/blog/how-to-style-images-with-markdown/
# -- http://sparkandshine.net/en/insert-images-with-captions-in-markdown/
# -- https://gohugo.io/content-management/shortcodes/#figure
# -- Load the CSV file from https://gohugo.io/templates/data-templates/
+++
I am asking around on different mailing lists to gain some insight into the archiving habits of linguists who use lexical databases. I am specifically interested in databases created by tools like [FLEx](http://fieldworks.sil.org/), [ToolBox](http://www-01.sil.org/computIng/toolbox/), [Lexus](http://tla.mpi.nl/tools/tla-tools/lexus), [TshwaneLex](http://tshwanedje.com/tshwanelex/), etc.

## Background Story
<!--more-->
Hugh Paterson III, in cooperation with Jeremy Nordmoe of the SIL Language and Culture Archive, is investigating the trend among lexical database users to archive their work. In their <a href="http://hugh.thejourneyler.org/2013/challenges-of-implementing-a-tool-to-extract-metadata-from-linguists-the-use-case-of-ramp/" title="Challenges of implementing a tool to extract metadata from linguists: the use case of RAMP" target="_blank">poster presented at ICLDC3</a>, it was claimed that less than 1% of SIL projects archive lexical datasets. Hugh and Jeremy want to know if this is common among all lexical database users or just SIL users of FLEx & ToolBox.

## Preliminary Results

{{< figure src="/Hugh-CV/post/lexical-database-archiving-questionnaire/Preleminary-Responses-as-of-November-26-2013.jpg" title="Preliminary Responses as of November 26 2013"  caption="N=59 (based off unique data sets across the respondents). The chart above plots total respondents by SIL/Non-SIL distinction. The taller columns indicate total responses. Lower numbers in the chart represent those respondents who indicated that they have archived their content at an institutional repository." alt="Preliminary Responses as of November 26 2013">}}

## Communities invited to participate
We are open to having more communities participate. So far we have posted notices on the following mailing lists:

{{ $dataC := getCSV "," "post/lexical-database-archiving-questionnaire/14-Linguistic-Communities-2019-05-23.csv" }}
[table id=14 /]



Next Communities to invite
<ul>
<li>[SSILA](http://listserv.linguistlist.org/cgi-bin/wa?SUBED1=SSILA&A=1)</li>
<li>ALT</li>
	<li>[DELAMAN](http://www.delaman.org/index.html)</li>
It would also be nice to contact archives like TLA, ELAR, AILLA, LACITO, and PARADISEC, to see if they can provide data for the lexical databases they do have. I am sure that such data would also help us understand more holistically the lexical database archiving trends. (Necessary data would be: Tool of database production i.e. FLEx, ToolBox, etc., Date of accession, Researcher/Creator, ISO 639-3 code of content language, Were there derivative published works? Y/N). <a href="http://hugh.thejourneyler.org/share-the-questionnaire/engaging-archives/" title="Engaging Archives" target="_blank">More on engaging Archives here</a>.
</ul>
<em>Want to share the questionnaire with your community of linguists?</em> <a href="http://hugh.thejourneyler.org/share-the-questionnaire/" title="Share the Questionnaire" target="_blank">Click here for more info on how</a>.


## Take the Questionnaire
It is an open questionnaire; anyone can fill it out. We plan on releasing more specific results (as appropriate) at a later time.
<hr/>
We are asking a few questions about your current Lexical Database use.
In 2012, Hugh Paterson and Jeremy Nordmoe did their initial research on the success of RAMP. During that year only 10 Lexical database projects (4 FLEx, 6 ToolBox) had been submitted to the SIL Archive. (See link to research poster after submitting the questionnaire). We are looking to see if that is a trend among all Lexical Database users or just SIL users of FLEx & ToolBox.
<iframe src="https://docs.google.com/forms/d/101lf-QCLdt64s8e6KIsHluG1f4NGnng3y-U5WdDcjd0/viewform?embedded=true" width="760" height="1658" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>

## Engaging Archives

In my Lexical Database Archiving Questionnaire I begin to talk about engaging archives to find out which archives have lexical databases and what languages they are describing. During the initial stages of this discussion there are several issues or questions which have come to the surface which deserve an answer. I will do my best to record these thoughts here (please realize that this page will be updated periodically).

### Why not look at OLAC?

Date added:12. December 2013
Short answer: We do and have.
Long Answer:
This is a great question, I have and I do search OLAC records. I will be posting more about the role OLAC records have had in this project.
So far I can say:

1. Not every organization (archive) submits the same kind of records. - (project records vs. item records)
2. When institutions do provide multiple records for the same item (describing different scopes of the object) then these records are not always clearly linked.
3. Not all records are tagged the same way within the same organizations. -
4. Not all institutions, nor all records from some institutions have the minimum valid metadata for the OLAC 1.1 standard.
5. Some organizations prevent this level (Lexical Database) of metadata from being distributed by policy - (SIL).
6. Sometimes "Toolbox files" when mentioned in records refer to text markups rather than lexical datasets.
7. Not all OLAC data providers provide end pages to the items they mention (Hawai'i, TLA, U-de, etc.)

### What about privacy? When asking archives to divulge their records, sometimes archives can only provide general information, not as detailed as you are currently asking for.
Date added: 12. December 2013
Short answer: _If it is too sensitive to let the world know it exists, then don't share it with us._

Long answer:
This is another great point. It deserves a detailed answer. I have put it on its own page. You can find what I would suggest is a simple taxonomy of archive resources on its own page. The Taxonomy of Archivable Resources and their publicity levels. According to this taxonomy, we are interested in anything that would fit in Grey, Yellow, and Green boxes. We are not interested in anything which would fit in the Red box.

>Understanding Archive Resource Publicity
This section attempts to express an overview of options within the language archiving enterprise with respect to the discoverability and accessibility of resources.

#### All Archivable Resources

##### Un-archived Resources
May be:

* known (common knowledge, grant funded, etc.)
* unknown (e.g. individual research projects, that only select few know to exist)
* discoverable (posted on a personal or departmental website)
* privately kept (without public discovery)

However, no instance (and therefore also record) of these resources exists in the curated catalogs of professional libraries or institutional archives dedicated to the care and stewardship of language resources. Furthermore, in the above scenarios there is no long term preservation plan for these resources, even if a redundancy fallback copy of the data exists.

##### Archived but Private Resources

Resources in this category are severely restricted. Most people (including specialists in the language family, some archive staff and even some community members) do not know about them.

* Meta-data is hidden (not shared publicly).
* Archived objects have restricted access.

While archives may not be able to directly report on these objects, they can indirectly report what percentage of the archive's total content these items comprise.

>__Example of an indirect report__: 10% of XYZ archive's total contents are severely restricted. Most corpora contain less than 0.1% of severely restricted content.

Such indirect reporting is healthy for:

* **Funders** - to help understand the nature of how language data is viewed by various communities. It also communicates that the archiving institution is being as transparent as possible with the data it does have - a mark of faithful stewardship.
* **Archive administrators** - to monitor basic trends across individual corpora, across their entire archive's submissions, and across the larger language archiving community.
* **Language and linguistic specialists** - to realize that these options do exist and if these options need to be exercised, that these options for archiving are used within industry "norms". To this end, linguists also need some example use cases.
* **Communities** - to realize that archives have not forgotten that they have a connection with communities which are not listed in more public places.

Some restrictions are necessary. They help to build trust in archiving institutions and appropriate expectations for various stakeholders.
Note: The reasons for these restrictions should be documented so that when archive staff change, the rational for the restrictions is not lost. Additionally, the archive staff and the depositors should be in contact at a pre-determined interval to establish the continued necessity for this level of resource suppression. Frequency of communication can vary (but 3-5 years is a long time in today's world).

##### Archived but Restricted Resources

Meta-data is publicly advertised via a clean navigable website, is discoverable to industry leading search engines, and through specific archiving and linguistic industry standard venues like OLAC. In contrast the the high visibility of the meta-data, the archived objects have restricted (permissions based) access.

* Meta-data is open and discoverable.
* Items have restricted access.

To maintain trust in this context, items should have: a stable endpoint (URI address) for citation purposes and a contact method for requesting access to the item (not necessarily the whole corpus). Resource items also need to be able to display their relationship to (1) the corpus as a whole and (2) other items in the corpus (especially those which are needed to function together). Additionally, archives should have in place a stewardship protocol granting them authority to administer the deposits in such cases that the original depositor is disinclined to remain alive or in contact with the archive.

##### Archived and Open Resources

Meta-data is publicly advertised, and the resource is openly available.

* Meta-data is open and discoverable.
* Items are open to public access either through direct click and download or through an automated human verification (like login or recaptcha).

### What is 'an Archive'?
Date added: 14. December 2013

_This question is asked more than I initially thought it would be. It deserves an answer._

## Engaging People

The following questions are often asked by individuals but also pertain to institutions as well.

### What is a lexical Resource?

Date added: 14. December 2013

Short answer: _It varies._

Long answer:

This is an important question. I don't have all the answers. As I get them, I will modify the discussion below.

#### Dichotomy of Lexical Resources
This section attempts to express the range of resources in the lexical resource category. This is hard to do in a straight forward manner.

##### All Lexical Resources

###### Resource Types

A consistent typology of lexical resources is challenging for several reasons. One of those reasons is that lexical resources are usually at the apices of several intersecting continuums. Some of these continuums are presented below.

<img src="/Hugh-CV/post/lexical-database-archiving-questionnaire/Lexicon-continuums.png" alt="Continuums upon which to evaluate lexicons" width="713" height="492" />

Beyond these continuums there is also purpose, where the interactive ideal is established. If we take the dictionary as an example, then there is the "Learner's dictionary", the "Bi-lingual dictionary", the "Picture dictionary", the "Domain specialist dictionary", etc.

###### Databases Types

Beyond the description of the thing-ness of lexical databases using the continuums above, there is the technical description of the database. We can talk about character sets (UTF-8, UTF-16, etc.), and we can also talk about the description of "the thing" by the application which we used to create "the thing". So it might be a ToolBox database or a FLEx database, etc. But even within these descriptions there issues like database schemas, or customizations which need to be documented if we are going to think about passing our data on to other users.

---------------------------------------------------------------

A second thing to think about is data licensing --- talk here about the onion model

<!-- A point to the issues of licensing.  There have been several cases in the Americas Area when I was there where there is a legitimate question about the ethics of licensing.

As the story was related to me by Pat Kelley. There is a man who has a Waroni parent. He keeps asking Pat for the dictionary. Pat's inclination is that he wants to print it and sell it to the Waroni. So the question is: Is it ethical to give this man the PDF of the dictionary so that he can sell it to the tribe? if SIL is unwilling to  "profit" off of the "product" is it even ethical to give the "data" to someone who will profit off of the data?

If we take the above example and contrast it with the dictionary project that Doris Payne has been doing on a language in Africa and has gotten U.S. federal grant money (NSF I think) to conduct and is conducting it partially under SIL and partially under the University of Oregon. There is several conflicts here - what is SIL's policy for handling data which is acquired with public funding? but also what is SIL's policy for datasets collected when the person leading the project has dual allegiances or agencies which could claim that that individual is "working for hire"? But both of these questions are really side issues, because Doris would say that copyright should belong to the consultants who helped build it, even though they were paid to build it. - This view stands in opposition to the view that  the dataset should belong to the the language community. But if we look at the rapid word collection method and look a distributed model for dictionary dataset creation (i.e. via the web or syncing) then we need to look at who is contributing what to make the "dataset".  One way to look at this is segmentally, like an onion. The "headwords" are contributed by someone then someone else contributes the definitions and then a third party adds images, etc. It is possible to layer copyright per layer and then require Creative Commons licensing for all contributions to the project - in the end the sum of the parts is greater than the whole. In some ways this is the same model that software developers use when they license a library which gets included in an application. Each part can be copyright to the contributor and the whole dataset lives on because of licensing. The challenge is that Creative Commons does not cover datasets - if would cover the output products like a PDF or a book. This is why the OpenData license is needed: http://opendatacommons.org/ (same principals as Creative Commons but for Data).

In fact, I suggested using the onion model of licensing for AMA's involvement with the Rapashana project in South America. In the case of the Rapashana there was a lexical database which was created by an SIL team (unpublished - and unarchived, if I remember correctly) and someone in the community wanted to "enrich" the dataset (aka. "work on the dictionary"). So I asked the question: How is the enrichment going to be archived and fed back into the original dataset? I also asked is this person working for SIL as they "enrich the data set"? and the answer was "No, they are not working for SIL". (So, technically the Language and culture archive cannot receive data from a non-SIL project/person - but an entity's archive can chose to archive if they want to.) AMA did not find a licensing solution and ended up just giving the data to the individual. So my question is, if this individual does publish a dictionary and it contains SIL's data then the credit goes to that individual - (I am not even concerned about the credit). But lets say after they publish (and they copyright the work) someone else in the community wants to work on a non-copyrighted dictionary "for the community" and they send off to SIL and ask for a copy of the SIL work, how does SIL prove that it still has first authorship rights and rights for distribution for the content in this "original" dataset?

In the Rapashana case there was a lot of resistance from the AMA Linguistics Services Coordinator on using Creative Commons Licensing. (I am not sure exactly why. Is this more of an "SIL does not endorse CC or OpenData licensing", thing or was this an individual opinion and judgment call kind of thing?).
It seems to me that SIL International will continue to have their hands tied and be unable to efficiently and clearly communicate licensing issues, practices and service agreements to the Lexicography Service users as long as various entity licensing practices exist - entity directors are the ones accountable for intellectual property created and licensed under their administrative units. At the core of this licensing question is also the question: is the customer/consumer of the service a customer of SIL International or are they the customer of the "local" entity. If SIL can clear up some of these challenges in operational practices then it would really help resolve some of the issues that Mike Cahill brings up that are challenging GPS - they look to guidance from the local projects partially because there is significant variation in operations.

ReplyEditDeleteLikeSep 20, 2012 comment on : https://gateway.sil.org/display/DLS/Lexicography+Summit+Results -->

---------------------------------------------------------------
So, what is this "thing" we need to actually submit to the archive?

In a complete toolbox project file one should expect to find the following.
```
Some-zipped-toolbox-project.zip
├── .typ - File defining the database structure
├── .lng - File defining the Language encoding
├── .prj - Project file
└── Datafile - with one of the following file types
   ├── .db
   ├── .dic
   ├── null - meaning no file ending
   ├── .txt
   └── .xml
```
In a complete FLEx 6 and previous project file one should expect to find the following.

In a complete FLEx 7 and Newer project file one should expect to find the following.

---------------------------------------------------------------
Is a dictionary a lexical database? are they the same thing? - If they are not then should they be put in the same record (Item) or should they be independent items with a relationship connecting them?
```
Archive Institution
└── DSpace
   ├── Community 1
   │   ├── Collection 1
   │   │   ├── Item 1
   │   │   │   ├── Bitstream 1
   │   │   │   └── Bitstream 2
   │   │   └── Item 2
   │   └── Collection 2
   └── Community 2
```
What does a dictionary entry look like for archiving?

Best practices for file archiving of lexical databases and Dictionaries in SIL's Archive.

All dictionaries should have a lexical database associated with them.
All dictionaries should have a PDF with them.
All dictionaries should have the cover or jacket PDF.
All fonts and scripts used to format the lexical data into the PDF should be included.
All dictionaries should have a write up of which materials in the Lexical database were included in the dictionary and how this was decided.
All dictionaries with more than lexical content should include source files for those pages of the dictionary.

All ShoeBox files should have_____ file ending
All ToolBox Files should have_____ file ending
In all ToolBox files should be ______ components.
A remark about SFM v.s MDF

All FLEx databases should have_____ file ending
All FLEx databases should have a remark about the FLEx version.

Not all lexical data sets have a dictionary output. All lexical datasets should have a .lift output. (even thought .lift is not everything in a FLEx dataset.)

===Data maintenance strategy===

All Shoebox, ToolBox and FLEx databases should be archived one a year, at project's end and prior to conversion to another format (or version of)- like a FLEx database.

All Data conversion should be first attempted by the active project. All data from inactive projects should be updated annually with the release cycles of newer versions of FLEx. - This might could be scripted and conducted in the collaboration between the SIL Archive and the SIL Lexicography Data Conversion Service.

Lexical content Browser

###### Anatomy of archived lexical data sets
In a complete toolbox project file one should expect to find the following.
.zip
```
├── Database\ structure - .typ
├── Datafile - with one of the following file types
│   ├── .db
│   ├── .dic
│   ├── null - meaning no file ending
│   ├── .txt
│   └── .xml
├── Language encoding file - .lng
└── Project file - .prj
```
###### Last thing


### What is the difference between archiving and back-up?

Date added: 13. December 2013
Short answer: Back-up protects us from data-loss, whereas archiving inducts the data into practices of: data preservation, formal description, systematic access, and data protection.

Long answer

_Archiving and Back-up are different!_
First lets explain what we mean by, "Copy" and "Back-up" and then we will contrast this with what we mean by "Archive". In the IT industry there are generally three kinds of Back-up (explained below). Additionally, we often see the word "archive" associated with IT products. e.g. Google Mail (Gmail) has a feature called "archive", as do many IMAP email systems. Amazon Cloud Storage promotes their some of their data storage products as being "good for 'archiving'". We take issue with how the term is used in these contexts and clarify what we mean by archiving below.

**'Copy' and 'Back-up'**

1. Same Drive - Onsite :: we call this a Copy. - If your computer is stolen or the drive goes bad both "copies" are lost. This is not a back-up.
2. Separate Drive - Onsite :: This is where a copy of the data lives on a second drive, but the drive is in the same location as you computer where the file exists. If one of the two drives dies then the data is recoverable from the second drive. However, because both drives are in the same location, it is highly probable that if there was a catastrophic event: Fire, Explosion (war), or theft, that both devices would be rendered unusable. An example of this kind of back-up solution for OS X is Time-Machine.
3. Separate Drive - Offsite :: This kind of back-up solution may come in two varieties: (1) Same Region or (2) Different Region.
	* Same Region works like this: The person backing things up takes the drive and makes a back-up copy and passes the drive off to a custodian who stores the drive (and data) entrusted to them in a secondary location in some other part of the city or small country. Often for this to work well, it must be done at regular intervals. In one language documentation project Hugh Paterson was involved in he used Time-Machine and replaced data on the offsite disk weekly. - Note: many linguistic field projects, including SIL entities around the world have solutions at this level.
	* Different Region works like this: The person backing things up (usually) uses a dynamic service which stores a copy of their hard drive in one or more data centers. There are several commercial services which work like this but all function slightly different. For example: CrashPlanPROe, [Carbonite](http://www.carbonite.com/), or [RebuSync](https://rebu.kkoncepts.net/) (though RebuSync as of 2010 did not keep versions of files, and was difficult to work with the large file size of primary data in a language documentation project). At this level of back-up solution, if a datacenter in a hurricane zone like Florida was destroyed, then the data would be expected to be stored somewhere else like Los Angles, or Tokyo. The data could then be restored or accessed from this second location.

**Note**: _What about Google Drive, Sugar Sync, or DropBox aren't these back-up solutions?_ No. We would not classify these as back-up solutions. We classify them as collaboration and file sharing solutions. Here is why: when these kinds of solutions are used they, (typically) sync materials from your computer to the user's cloud account. If a user accidentally deletes their content from their computer then this deletion is also replicated to these remote file stores. Thereby also deleting the file in the offsite location. (We recognize that some services do offer versioning which does give users limited capability to recover deleted files, but these features are not automatic, and usually come bundled with premium version of these products/services.)

**So then what does 'Archived' mean and how is it different from 'Back-up'?**  - Whereas back-up is primarily concerned with data loss prevention, Archiving is concerned with preservation of usability (of the data), discoverability, provenance (history) and identification (of the data), and then also access to data.

### If my Data is in the cloud does that mean it is archived?

Date added: 13. December 2013
Short answer: No.

Long Answer
This is also a great question, because there are a lot of issues involved with cloud data. First cloud data is often social, and implies variation though versions (updates or changes to the same dataset) and forks (dataset splits where each set is then modified independently). Second cloud data is not on the local machine and therefore can feel to some like an "offsite back-up" solution.
With regards to lexical datasets SIL offers two independent cloud services:

* languagedepot.org - A web service which enables the send and receive functions of lexical dataset building teams to share their data with each other through FLEx's built in Send/Receive function.
* webonary.org - A website where FLEx data can be hosted and viewed.
http://en.wikipedia.org/wiki/Gnolia
http://www.wired.com/business/2009/01/magnolia-suffer/

First lets address the cloud social data and the iterative nature of lexical resources. There are lots of tools like DropBox, SugarSync, Google Drive, etc. These are not necessarily even successful back-up strategies.


## Share the Questionnaire
Want to share the questionnaire with your community of linguists?
We are happy to help (or be helped as it were).

Below is the text we have been sending out.
___
Subject line:
Lexical Database Archiving Questionnaire
___
Email Text Body:

>Last year the SIL Archive did an analysis of what kinds of materials are being submitted to SIL's Language and Culture Archive. During the 2012 year only 4 FLEx data sets were submitted to the archive (and about 6 Toolbox datasets). The archive is looking to see if this is a broader trend among linguists (and more generally lexical database users) or if it is unique to SIL contexts.

>We are particularly expecting responses from people who work with minority languages but all lexicographic database users are open to respond to the Questionnaire. We are asking 4 questions and we estimate the whole thing takes about three minutes to complete:

>If you are a creator or user of lexical databases (like Toolbox, FLEx, or Lexus, etc.):
Please take a quick moment to fill out the following online questionnaire: http://bit.ly/19QSPMb

>Though

>For those in a bandwidth restricted situation feel free to reply to the questions below with answers to: Hugh_Paterson [ at ] sil.org

>Four questions:

>1. What is your Lexical Database Management solution? Options generally include: FLEx, ToolBox, Lexus, other:____, etc :
2. What is the ISO code of the language you are using it with?:
3. Have you ever archived a version of your current Lexical Database at an official archive? (An archive like SIL's L & CA -REAP-, or SOAS's ELAR, or MPI's TLA, or PARADISEC. - Though it doesn't have to be one of these four. ) - Yes / No:
4.  Have you ever produced a Print or Digital Publication from your Lexical data (like a Glossary or a Dictionary)? if so we would like to hear about it, got a link or a citation?:

>-----------------------------------------

>One entry per language. If you work with more than one language, feel free to submit one answer per language or add a comment to that effect with a list of the ISO 639-3 codes or language names.
Personal details (email address and name) will be kept confidential, other data and generalizations of trends may be published.

>-----------------------------------------

>Thank you for the work you do and the effort you make to serve speakers of minority languages.

>~ Hugh Paterson
