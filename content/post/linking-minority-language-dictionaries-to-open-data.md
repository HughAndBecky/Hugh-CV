+++
title = "Linking Minority Language Dictionaries to Open Data"
date = 2012-06-11T14:14:38-07:00
draft = true


# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Archives", "Dictionaries", "Dictionary", "Language Document", "LinkedData", "RDF", "SIL International", "UI", "UX"]
categories = ["Access", "Digital Archival", "Language Documentation", "Lexicography", "Linguistics"]

#It used to be that math and highlight were controlled per post... not sure why not now.
#math = false
#highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = ""
caption = ""
preview = true

# Originally posted at: http://hugh.thejourneyler.org/2012/linking-minority-language-dictionaries-to-open-data/ I need to: 1. figure out what to do about the images; 2. I need to add the redirects to wordpress; 3. I need to figure out pull quotes. 4. I need to process the tags; 5. I need to make sure the styles transfer; 6. I need to add a way to do bibliographies; 7. I need to transfer the header image.
+++

## What is the role of a dictionary?
Is the role of a dictionary to regulate or to standardize spelling? Is it to validate a speech variety as being real or a _bon fide_ language? Or is it for documenting and establishing the relationships and connections between things (plants, animals, fish, spirits/gods, medicines, etc.) as they are emicly viewed, for connecting people via collaboration, or connecting related concepts and their classes together into documented sets? Or even connecting these things and relationships as they are viewed in one culture to the same things and relationships as they are viewed in another culture or more broadly cross-culturally?Of course this begs the question: _What kind of a dictionary are we talking about?_ But I think that the goal here in talking about linking to Open Data would infer digital resources and likely also infer web-based resource. The question of collaborative editing via a web platform is still open. In referring to Open Data, and to LinkedData, throughout this post I am referring to data which is both Open and LinkedData through RDF technologies. Though I am not excluding the possibility for linking to data with technologies which are not RDF. For additional clarity on these terms there are several clear blog posts which I will site (and in doing so hope to mediate the effects of link rot). Paul Walk[ref 1] provides this definition:

1. data can be _open_, while **not** being _linked_
2. data can be _linked_, while **not** being _open_
3. data which is both _open_ **and** _linked_ is increasingly viable
4. the Semantic Web can only function with data which is both _open_ **and** _linked_

This might best be understood in a venn diagram (idea borrowed from Christopher Gutteridge[ref 2] ):

LinkedData RDF and Open Data
LinkedData RDF and Open Data with the convergent set of data shown in the grey area surrounded by a green outline.

### OTHER RELATED ARTICLES TO THE DEFINITION OF LINKEDDATA AND OPEN DATA
It's All Semantics: Open Data, Linked Data & The Semantic Web[ref 3]
Linked data vs Open Data[ref 4]

Dictionaries for minority languages have contained within them little bits of information about societies When the dictionary is created by someone external to the culture, the dictionary might be said to contain information about a society, but when the dictionary is interactively created by people in the society, one must ask: _Does the dictionary actually contain part of the society?_ and the way those groups of people interact with their environments and among themselves. For example, dictionaries may include the names of fish, places and clarify terms for relationships among family or social groups. Often in the data management and internet realms these objects, activities and relationships are codified. Sometimes these things are codified through LinkedData or RDF. Additionally, there are ever increasingly large data sets which describe the world in which researchers and minority language speakers alike live and make observationsThere are a lot of LinkedData sets describing government actions and environmental factors. This website has several LinkedData sets from Europe and several very interesting websites which present this data so that audiences can understand the huge quantity of tokens in the datasets..

An important question emerges:
<!--Figure out what I want to do with block quotes or pull quotes. see: https://discourse.gohugo.io/t/blockquote-migrating-from-octopress/3124/6 -->
How should Dictionaries be linked to other online resources and ontologies? This question does not just pertain to minority language dictionaries, but should also be considered for all forms of interactive, on-line lexicography.

If one takes a traditional view, dictionaries are static, edited, and then published, books, PDFs and in modern cases versioned datasets. One example of perspective applied to linking LinkedData to minority language dictionaries might be linking the names of the species of animals in indigenous/minority languages to resources on those species using lists (ontologies) which already exist in the LinkedData world. An additional step would be to hyper-link to resources which match these definitions. There is already a lot of LinkedData out there. If minority language communities are "linked" to that data through their dictionaries, then the dictionary not only serves as a record of their culture and language but also serves to bridge that community of dictionary users to knowledge areas and experience outside the community about things and relationships which exist inside of that community.

To continue the example of LinkedData for animal species, terms could be linked to Wikipedia. However, Wikipedia is not in general specific enough, nor stable enough (and one should also ask how stable these other digital resources are). A more specific resource would be the ICUN Red List of threatened species (which also makes its data available through LinkedData and RDF).

San Jose Brush Rabbit - on The Red List
The Red List
Example of the Sylvilagus mansuetus
Conejo de la Isla San José
San Jose Brush Rabbit
from The Red List

Protected Planet is another website which has some work on species, but extends its knowledge into the larger ecosystem, not just a list of species. Either of these two resources would provide useful comparative data for minority language speakers. The connectivity would also provide content or format models for how they share their own valuable knowledge. Of course such linking assumes a common language and would also likely require consultation with experts in the domain of knowledge being linked to, in this case Biology.

## The Cautions
In language documentation, documenters (and often native minority language speakers in collaboration with these researchers) are interested in getting "snapshots" of language use and cultural events, ideas, and practices which describe the uniqueness of that society. Documenters work with archives to preserve this record. The foundational assumption is that this record is static in its baseline form. That is, the baseline contains a certain set of documents, which might be added to, or enriched (i.e. via transcriptions or annotations) through time, but will never change or go away. However, in thinking through dictionaries as part of language development, we must think dynamically rather than statically. For example, let's take SIL International's definition of language development Nowhere does SIL International publicly claim that dictionary production is part of language development, though few, if any would argue against the notion that dictionary production is part of language development. Additionally, circumstantial evidence through SIL International's bibliography suggests that quite a few dictionaries have been produced by SIL International in the course their activities (in addition to tools like FLEx, Toolbox, Webonary, and DDP which have been produced to help in the dictionary creation process).:

Language development is the series of ongoing planned actions taken to ensure that a language continues to serve the changing social, cultural, political, economical and spiritual needs and goals of its speakers.

This definition of language development suggests that as a community or a society changes its pursuits and communicative activities the undergirding technologies enabling that communication should also change with it to support the designs of the communication. I think this is spot on. As a community changes so the terms in their dictionary should also increase to cover these changes. As words are used in new senses, these senses need to be added to the dictionary. Therefore, this perspective on language development should lead us to consider language resources in a dynamic context rather than in a static context. This perspective is both:

an analogy to how language can be viewed in a dynamic, diachronic context
a contrast to how language resources have existed in the past (considering static materials like bound media, printed media and PDFs.)
When resources and even language use, moves into a dynamic medium, like a digital medium, then recording and documenting the language takes on new challenges or tasks. In digital mediums, like web presentations, the communication and the medium are inseparable. The delivery mechanism is part of the total message.[ref 5]
In terms of language documentation,[ref 6] the dynamic presentation of data or the linking of data to other sources should be preserved to maintain a record of that language and culture at that time. As language documenters (and archivists) we must ask the question: How is the original work preserved?

To answer this question, some have said that to archive data driven resources like dictionaries, what is needed is to archive the database (as apposed to the final product: i.e. a book, or a PDF or a MS Word Document). This is a good strategy if the data driven resource is static in nature (i.e. a FLEx or Toolbox database), and conventional in access/production mode (i.e. a FLEx or Toolbox program). This also works if the archive has a version of the program and many dictionaries in the file formats of the program (much like a CD player and many CDs). Access to the data and editorial abilities can be restored. Then tools which are dependent on these programs (Like SIL International's Pathway product) for producing usable product (books, PDFs, websites, etc.) from the dataset can access the data. However, if we hold that it is true that, the cognitive interaction between the database user and the database is defined by the interaction with the output through a chosen medium then, Have we really archived the resource if we do not also archive the output display as well? For an example, if we have a static dataset, imported to a WordPress or Drupal database and use the visual logic of these CMS programs to present various kinds of relationships in a web 1.0 kind of way, then archiving should include the presentation mechanism of the data as well as the data itself. This may mean theme files or CSS files. But including the code of the presentation of the data is, in a web 1.0 sense, not fundamentally important. Now, if we are talking about presenting the data in a web 2.0 kind of way then something else should be required. - No. We have only archived a component of the resource. This is fine and even preferable in some use cases where there are various kinds of presentations of a static, edited, compiled dataset. However, this is dispreferred when not just the presentation is dynamic, but also the information architecture and the visual presentation form driving the communicative interaction is also dynamic then archiving under traditional mindsets and practices can actually lead to failing to document a language. - The irony would be to have a 50 year old dictionary which would not document the language (over the course of 50 years).

Going back to SIL's definition of Language Development and considering that many dictionaries today are digital, and that in today's collaborative web-based environment, a society which desires to and is capable of using web tools to produce minority language dictionaries, the actual information architecture becomes important of "the work". It is no-longer just the tokens of the lexeme field which are important. Understanding the Why to how the data is arranged minimally in the minds of the users and potentially even on screen becomes important as well. This is important not just to the web-aplication developers, and information architects, but is really important to the users of the data contained in the various fields of the database portion of the web-application. These relationships between various fields in the database portion of the web-application are not always transparent to those who view data contained in the lexeme fields (or other various fields). This means that reality to the viewer is determined by the way that the viewer experiences their interaction with the data, and that this reality can be very different from what is archived.

If a dynamic-social dictionary is constantly changing to meet the ongoing needs of a speech community in a multitude of ways, then it should be expected to minimally change in these ways:

in the visual presentation of the dataInteraction with the data could happen through several venues
Visually through the website
Visually through an application via an API
With a database management tool like phpmyadmin.
End users are the target of both of the first two elements. However, a website's visual presentation of the data is not required to present all the ways that the data could be arranged. A third party app for mobile connecting via an API is not required to support all the functionality of the API. So even if users are connecting with some portion of the data, their interactive reality is still only a sub-set of what is being contained in the database. What is important to realize is that this interaction with a sub-set of the data is really a new context and affects the cognitive reality of users. - affecting the way that people cognitively interact with the data.

in the connected state of the data (both internally and externally) - the technically implemented state of cognitive relationships between database elements which already existing in the culture
in the content of the database (quantity of lexems, definitions, photos, pronunciations, part of speech, etc.)
in the structure of the database (additional fields added or additional relationships added to the database) - as the community changes over time some database categories will become less obvious or needed.
Given these kinds of changes in the dictionary's data structure, then the issue of permanence and diachrony still needs to be addressed to satisfy language documentation practices. The interactive, dynamic and web-based dictionary stands in contrast to the long standing traditional view on lexicography and publishing practices which look towards a stable out-put. In web technology, for users to realize (be exposed to) changes in the database often the presentation layer also has to change. This is one reason that archiving the code presenting the data is important as well in these kinds of use cases. However, this does not completely explain how archiving the visual mode is important to the issue of linking terms or lexems in lexical databases (online or not) to Open Data. To see this relevance I think it is important to understand that linking is communication and that communication is a two way street.

## Communication is a two way street
The communicative process is a negotiation of thought and ideas from one entity to another entity. So in the case of LinkedData and linking to Open Data in or from minority language dictionaries, the act of associating these traditional knowledge sets with mainline (global) knowledge sets can have the effect of changing the traditional knowledge set, or minimally, changing the perspective of indigenous/minority language users on the status of traditional knowledge. Let me give a hypothetical example.

David Harrison in his book, When languages die[ref 7] (page 44) Tells the story of a macro-class of fish in a native American language. This macro class happens to follow the scientific distinction (genetic classification) of the fish, whereas the English names of the fish would lead English speakers to sub-divide these fish into different classes.

When Languages Die
When Languages Die

So, if the anthropological taxonomy of fish is represented in a single database or ontology then changing that database or ontology will affect the documentation of that language or people group. However, if the editors of the dataset, even if they are native speakers of the language are editing ontologies, then are they editing the record of the culture?The problem here is not one of a speech community having ownership or editorial rights to datasets and ontologies which describe their speech, it is one of how clear is it that they are editing these things? Websites and social attitudes towards using web-tools are often driven by functional prerogatives. - Hence the market in User Experience Design. Even if changing that database will meet the needs of that language group in the future (or currently in some future time). LinkingData is a two way street. If "A" is related to "B" then "B" is related to "A", though this may not be expressed in visual manifestations of the linkage. When a society is confronted with new knowledge, because it is linked to it, the community has to choose what do with that new knowledge, and in web technology it may not be immediately obvious that cognitive and even behavioral change is occurring. Not that change is bad, because change is bound to occur. Additionally, when we are talking about a speech community which is dealing with LinkedData via the web, we are talking about many web based influences not just those from the LinkedData. However, the editorial state of the database due to other arrangements of data is something of which to be mindful.

## Acknowledgments
A special thanks to Pat Kelley and Steve Marlett who have both worked on dictionaries and have inspired me through conversations on these issues to think about and write something down.
