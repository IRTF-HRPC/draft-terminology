---
title: Terminology, Power, and Inclusive Language in Internet-Drafts and RFCs
abbrev: Terminology
docname: draft-knodel-terminology-14
date: 2023-08-24
category: info

ipr: trust200902
area: IETF
keyword: Internet-Draft
stand_alone: yes
pi:
rfcedstyle: yes
toc: yes
tocindent: yes
sortrefs: yes
symrefs: yes
strict: yes
comments: yes
inline: yes
text-list-symbols: -o*+

author:

-
       ins: M. Knodel
       name: Mallory Knodel
       organization: Center for Democracy & Technology
       email: mknodel@cdt.org

-
       ins: N. ten Oever
       name: Niels ten Oever
       organization: University of Amsterdam
       email: mail@nielstenoever.net

normative:

   RFC2119:
   RFC8174:

informative:

   RFC7322:
   RFC8499:
   RFC8782:
   RFC8783:
   RFC8612:

   Burgest:
      title: “Racism in Everyday Speech and Social Work Jargon.”
      author:
         - ins: David R. Burgest
      date: 1973
      seriesinfo: "Social Work, vol. 18, no. 4, 1973, pp. 20–25"
      target: www.jstor.org/stable/23711113.

   Eglash:
      title: "Broken Metaphor: The Master-Slave Analogy in Technical Literature."
      author:
         - ins: Ron Eglash
      date: 2007
      seriesinfo: "Technology and Culture, vol. 48 no. 2, 2007, pp. 360-369."
      target: https://doi.org/10.1353/tech.2007.0066

   BrodieGravesGraves:
      title: "Masters, slaves, and infant mortality: Language challenges for technical editing"
      author:
         - ins: Heather Brodie Graves
         - ins: Roger Graves
      date: 1998
      seriesinfo: "Technical Communication Quarterly, 7:4, 389-414"
      target: https://doi.org/10.1080/10572259809364639

   Wyatt:
       title: "Danger! Metaphors at Work in Economics, Geophysiology, and the Internet"
       author:
          - ins: Sally Wyatt
       date: 2004
       seriesinfo: "Science, Technology, and Human Values, Volume: 29 issue: 2, page(s): 242-261"

   Lakoff:
       title: Metaphors We Live By
       author:
          - ins: George Lakoff
          - ins: Mark Johnson
       seriesinfo: U of Chicago P, 1980.

   Orwell:
      title: Politics and the English Language
      author:
         - ins: George Orwell
      date: 1946

   McClelland:
      title: We need better metaphors
      author:
         - ins: J. McClelland
      date: 2011
      target: https://current.workingdirectory.net/posts/2011/master-slave

   UDHR:
     title: The Universal Declaration of Human Rights
     date: 1948
     author:
        - org: United Nations General Assembly
     target: http://www.un.org/en/documents/udhr/

   Fanon:
     title: Black skin, white masks
     date: 1952
     author:
        - ins: F. Fanon

   Jansens:
      title: "I don't believe in PC"
      date: 2008
      author:
         - ins: Bart Jansens
      target: https://www.drupal.org/project/project_issue_file_review/issues/343414#comment-1164514
     
   Python:
      title: "'master-slave' Terminology Was Removed from Python Programming Language"
      date: 2018
      author:
         - ins: Daniel Oberhaus
      target: https://motherboard.vice.com/en_us/article/8x7akv/masterslave-terminology-was-removed-from-python-programming-language

   Django:
      title: "#22667 replaced occurrences of master-slave terminology with leader/follower #2692"
      date: 2014
      author:
         - ins: fcurella
      target: https://github.com/django/django/pull/2692

   Django2:
      title: "comment on #22667 replaced occurrences of master-slave terminology with leader/follower #2692"
      date: 2014
      author:
         - ins: lynncyrin
      target: https://github.com/django/django/pull/2692#issuecomment-44221563

   Wikipedia:
      title: Slavery in the 21st century
      date: 2018
      author:
         - org: Wikipedia
      target: https://en.wikipedia.org/wiki/Talk:Slavery_in_the_21st_century

   Drupal:
      title: "Replace 'master-slave' terminology with 'primary/replica'"
      date: 2014
      author:
         - ins: Xano
      target: https://www.drupal.org/project/drupal/issues/2275877

   Grewal:
      title: "The 'Bad Is Black' Effect"
      date: 2017
      author:
         - ins: D. Grewal
      target: https://www.scientificamerican.com/article/the-bad-is-black-effect/

   socketwench:
      title: "Even in tech, words matter"
      date: 2018
      author:
         - ins: socketwench
      target: https://deninet.com/blog/2018/09/09/even-tech-words-matter
      
   ISC:
      title: "@ISCdotORG reply tweet"
      date: 2017
      author:
         - ins: Internet Systems Consortium
      target: https://twitter.com/ISCdotORG/status/943152507211071489
      
   Github:
      title: "Github to Remove 'Master/Slave' Terminology From its Platform"
      date: June 2020
      author:
         - ins: Kevin Truong 
         - org: VICE
      target: https://www.vice.com/en_us/article/k7qbyv/github-to-remove-masterslave-terminology-from-its-platform
       
   NIST:
      title: "Agency to end use of technology terms such as 'master' and 'slave' over racist associations"
      date: June 2020
      author:
         - ins: Eric Geller
         - org: Politico
      target: https://www.politico.com/news/2020/06/25/agency-ends-use-technology-terms-racist-associations-339880
   
   inclusiveterminology:
      title: "Inclusive terminology in IETF Documents"
      date: August 2020
      author:
         - org: IETF
      target: https://github.com/ietf/terminology
      
   Statement:
      title: IESG Statement on on Inclusive Language
      date: may 2021
      author:
         - org: IESG
      target: https://www.ietf.org/about/groups/iesg/statements/on-inclusive-language/

   in-solidarity-bot:
      title: "Inclusive terminology in IETF Documents"
      date: August 2020
      author:
         - org: IETF
      target: https://github.com/ietf/terminology

--- abstract

There has been extensive discussion in and around the IETF community about the use of technical terminology, which could be interprereted as exclusionary. The document below is published as an artefact of the discussion because it sparked many debates and inspired several actions in the IETF community. This, however, does not say anything about whether the opinions it holds are correct or incorrect. Since the debate about technology, language, and its implications will probably never be finished, we offer this document for reference in future discussions about the topic. 

It is important to note that this is not standard, it does not represent IETF consensus, and should not be misconstrued as anything other than the authors' views. 

--- middle

# Introduction

According to {{RFC7322}}, "The ultimate goal of the RFC publication process is to produce documents that are readable, clear, consistent, and reasonably uniform," and one function of the RFC Editor is to "[c]orrect larger content/clarity issues; flag any unclear passages for author review." Documents that are published as RFCs are first worked on as Internet-Drafts.
 
Given the importance of communication between people developing RFCs, Internet-Drafts (I-D's), and related documents, it is worth considering the effects of terminology that has been identified as exclusionary. This document argues that certain obviously exclusionary terms should be avoided and replaced with alternatives. We propose nothing more than additional care in the choice of language just as care is taken in defining standards and protocols themselves.
 
This document presents arguments for why exclusionary terms should be avoided in Internet-Drafts and RFCs and as an exercise describes the problems introduced by some specific terms and why their proposed alternatives improve technical documentation. The example terms discussed in this document include "master-slave" and "whitelist-blacklist". There is a final section on additional considerations and general action points to address future RFCs and I-D's. Lastly, a summary of recommendations is presented.

# Terminology and Power in Internet-Drafts and RFCs

According to the work of scholar Heather Brodie Graves from 1993, "one goal of the application of rhetorical theory in the technical communication classroom is to assess the appropriateness of particular terms and to evaluate whether these terms will facilitate or hinder the readers’ understanding of the technical material" {{BrodieGravesGraves}}. This implies that in order to effectively communicate the content of I-Ds and RFCs to all readers, it is important for authors to consider the kinds of terms or language conventions that may inadvertently get in the way of effective communication. She continues, "complex and subtle configurations of sexist, racist, or ethnocentric language use in technical documents can derail or interfere with readers’ ability and desire to comprehend and follow important information."

Indeed, problems of language are problems of everyday speech. Racist and sexist language is rampant and similarly counter-productive in other sectors, notably social work {{Burgest}}. The terms "master-slave," treated in detail below are present in other realms of technology, notably "automotive clutch and brake systems, clocks, flip-flop circuits, computer drives, and radio transmitters" {{Eglash}}.

However as noted in the research by Ron Eglash, this seemingly entrenched technical terminology is relatively recent. It is not too late for these terms to be replaced with alternative metaphors that are more accurate, clearer, less distracting, and that do not offend their readers. Language matters and metaphors matter. Indeed, metaphors can be incredibly useful devices to make more human the complex technical concepts presented in RFCs. Metaphors should not be avoided, but rather taken seriously. Renowned linguist George Lakoff argued in 1980 that the ubiquitous use of metaphors in our everyday speech indicates a fundamental instinct to "structure our most basic understandings of experience" {{Lakoff}}. Metaphors structure relationships, and they frame possibilities and impossibilities {{Wyatt}}.

Like Graves, this document recognises the monumental challenge of addressing linguistics and power, and attempts to "promote awareness that may lead to eventual wide-spread change" {{BrodieGravesGraves}} and suggests first steps for actions that may remedy the inadvertent use of undesirable terms'. To that end, the list below is a tersely written set of IETF-specific arguments as to why the RFC Editor should be encouraged to correct other content and clarity issues with respect to exclusionary language and metaphors:

 1. The RFC series is intended to remain online in perpetuity. Societal attitudes to offensive and exclusionary language shift over time in the direction of more empathy, not less.
 2. That exclusionary terms in RFCs are largely hidden from the larger public, or read only by engineers, is no excuse to ignore social-level reactions to the terms. If the terms would be a poor choice for user-facing application features, the terms should be avoided in technical documentation and specifications, too.
 3. At the time of this drafting, the digital technology community has a problem with monoculture. And because the diversity of the technical community is already a problem, a key strategy to breaking monoculture is to ensure that technical documentation is addressed to a wider audience and greater multiplicity of readers.
 4. And yet the technical community already includes members who take offense to these terms. Eradicating the use of exclusionary terminology in official RFCs recognises the presence of and acknowledges the requests from black and brown engineers and from women and gender-non-conforming engineers to avoid the use of exclusionary terminology.

This document does not try to prescribe terminology shifts for any and all language that could be deemed exclusionary. Instead what follow are two examples of specific alternative suggestions to "master-slave" and "white-blacklist" and the rationale for the use of the alternatives. Suggested actions for handling additional considerations are presented in a subsequent section.

## Master-Slave

Master-slave is an offensive and exclusionary metaphor that will and should never become fully detached from history. Aside from being unprofessional and exclusionary it stifled the participation of students whom Eglash interviewed for his research. He asks: "If the master-slave metaphor affected these tough-minded engineers who had the gumption to make it through a technical career back in the days when they may have been the only black persons in their classes, what impact might it have on black students who are debating whether or not to enter science and technology careers at all?" {{Eglash}}

Aside from the arguably most important reason outlined above, these terms are becoming less used and therefore increasingly less compatible as more communities move away from its use (eg {{NIST}}, {{Python}}, {{Drupal}}, {{Github}} and {{Django}}. The usage of 'master' and 'slave' in hardware and software has been halted by the Los Angeles County Office of Affirmative Action, the Django community, the Python community and several other programming languages. This was done because the language is offensive and hurts people in the community {{Django2}}. Root operator Internet Systems Consortium also stopped using the terms {{ISC}}.

In addition to being inappropriate and arcane, the master-slave metaphor is both technically and historically inaccurate. For instance, in DNS the 'slave' is able to refuse zone transfers on the ground that it is malformed. The metaphor is incorrect historically given the most recent centuries during which "the role of the master was to abdicate and the role of the slave was to revolt" {{McClelland}}. Yet in another sense slavery is also not 'just an historic term', whereas freedom from slavery is a human-rights issue {{UDHR}}, it continues to exist in the present {{Wikipedia}}. Furthermore, this term set wasn't revived until recently, after WWII, and after many of the technologies that adopted it were already in use with different terminology {{Eglash}}.

Ultimately master-slave is a poor choice since it is 1) being used less frequently already 2) in a variety of applications 3) to correct perceived exclusionary effects 4) at the request of concerned members of the technical community.

To find alternatives to master-slave, one can look to myriad existing implementations. There are also many other relationships that can be used as metaphors, Eglash's research calls into question the accuracy of the master-slave metaphor. An alternative should be chosen based on the pairing that is most clear in context:

 * Primary-secondary based on authority. See for example {{RFC8499}}.
 * Primary-replica based originality.
 * Active-standby based on state.
 * Writer-reader based on function.

## Blacklist-Whitelist

The metaphorical use of white-black to connote good-evil is exclusive. While master-slave might seem like a more egregious example of racism, white-black is arguably worse because it is more pervasive and therefore more insidious. While recent headlines have decried the technical community's use of master-slave, there is far less discussion about white-black despite its importance. There is even a name for this pervasive language pitfall: the association of white with good and black with evil is known as the "bad is black effect" {{Grewal}}.

Indeed, there is an entire book on the subject, written by renowned authority on race, Frantz Fanon. In his book "Black Skin, White Masks," Fanon makes several persuasive arguments that standard language encodes subconscious in-group, out-group preferences {{Fanon}}.

In the case of blacklist-whitelist in the technical documentation of I-Ds and RFCs, it is entirely a term of art and an arbitrary metaphorical construct with no technical merit. There are scientific uses of black that are related to light-- black holes are black because light cannot escape them. The "dark web" is not counter-related to light; it is a metaphor for evil. Blacklist-whitelist is not a metaphor for lightness or darkness, it is a good-evil metaphor and therefore this trope has significant impact on how people are seen and treated. As we've seen with metaphors, its use is pervasive and, though not necessarily conscious, perceptions get promulgated through culture and repetition.

As with master-slave, we save our technical argument for last, referencing and presenting first the reasons for the use of non-offensive, alternative terminology for the sake of our humanity. Indeed, our technical argument is incredibly succinct: Why use a metaphor when a direct description is both succinct and clear? There can be absolutely no ambiguity if one uses the terms, as suggested below, allow-block rather than white-black.

There are alternatives to this terminology set that vastly improve clarity because they are not even metaphors, they're descriptions. The alternatives proposed here say exactly what they mean.

 * Accept-list and drop-list for threat signaling. See for example {{RFC8612}}, {{RFC8782}}, and {{RFC8783}}).
 * Blocklist-allowlist, deny-allow, exempt-allowlist or block-permit for permissions.

## Other Considerations

As described in the preceding sections, the language used in technical documentation, like all written text, creates and reinforces expectations and stereotypes. We propose nothing more than additional care in the choice of language just as care is taken in defining standards and protocols themselves. The two examples provided above are not the only cases of exclusionary language to be avoided, and many more can be collected. We use this section to broaden the context of other offensive and exclusionary terminologies to encompass additional concerns, why spotting and eradicating problematic terminologies is a valid endeavour for authors and editors of technical documentation and how this might be systematised.

There are many other metaphors present in technical documentation that are "terms of art" but that have no technical basis whatsoever. If any of these metaphors is offensive there is no excuse for its continued use. A term like "man-in-the-middle" is not technically useful. It is not a standard term, not as clear as its alternative "on-path attacker", and should therefore be avoided. When presented with the opportunity to employ the use of metaphors or to unthinkingly repeat terms of art that connote gender or race, authors should simply find a better way to explain themselves. A fun read on the politics of colloquial speech by George Orwell should dissuade any clever author from using tired explanatory metaphors {{Orwell}}.

Gendered pronouns and sexism are common place but easy to spot and replace. Up until recently, strict English grammatists like Orwell decried the use of the neutral pronoun "they". Without a neutral singular pronoun, "he" is assumed as the default singular pronoun when the gender of the person is unknown or ambiguous. However, that has changed, and it is now widely accepted that "they" can be used as a neutral singular pronoun. Since it is unlikely that all implementers and infrastructure operators are of any particular gender, "he" should never be used to refer to a person in I-Ds and RFCs. An author who uses male examples sets male-ness as a standard.

Besides race and gender, our world is full of metaphors rooted in oppression, ableism, and colonialism. Militarised metaphors are also a pervasive problem in language, perhaps even more so in technical communities because of the historical and actual relationship between technology and war.

While it is not our intention to be exhaustive we hope to have made a persuasive case for authors and editors to pay attention to the finer details of metaphor, and the ways power is replicated in technical documentation unless detailed attention is paid. The example terms above "master-slave" and "blacklist-whitelist" are already less common. If the IETF community has learned anything from the debate over the use of these terms, and this document, it is that language matters to us deeply as members of society and as engineers. And because language, and society, change over time, we must approach future concerns with some degree of dispassion when the arguments presented in the first section can be clearly applied.

There is harm in protracted discussion that weighs the validity IETF participants' experiences with exclusionary terminology. The IETF's own discussions surfaced expressions and defense of racist views that pushed away participants and observers. This illustrates the need to, as Graves is cited above as saying, continue to raise awareness within our community for eventual, lasting change on the continued front of struggle against the racists amongst us. Yet we recommend a living stylesheet, rather than repeated RFCs, be used as a mechanism for monitoring exclusionary language in IETF documents {{inclusiveterminology}}.

It is there that we welcome additional examples of terminology that might be avoided through more awareness and thoughtfulness.

# Summary of Recommendations

To summarise, we have outlined some very concrete action points that can be taken by editors, reviewers and authors, both present and future as they develop and publish Internet-Drafts and new RFCs.

Authors can consider to:
  * Replace the exclusionary terms "master-slave" and "blacklist-whitelist" with more accurate alternatives.
  * Read and reflect upon the repository of exclusionary terminology {{inclusiveterminology}}.
  * Reflect on their use of metaphors generally.
  * Consider changing existing exclusionary language in current (reference) implementations {{socketwench}}.
  * Consult the RFC style sheet maintained by the RFC editor and the community that can be found at https://github.com/ietf/terminology .

During the publication process, publishers (such as the RFC Editor) are advised to:
  * Offer alternatives for exclusionary terminology as an important act of correcting larger editorial issues and clarifying technical concepts and
  * Maintain the IETF repository that collects all terms that have been considered and indicate whether they are deemed acceptable, and if not what terms authors should consider instead.
  * Suggest to authors that even when referencing other specifications that have not replaced offensive terminology, the authors could use another term in their document and include a note to say that they have used the new term as a replacement for the term used in the referenced document.

# Epilogue

This document built a compendium of scholarship, activist campaigns, and the will of technologists who had pointed out general and specific issues with technical terms. This sparked a significant discussion in the IETF. Concretely the document’s writing resulted in a statement by the IESG {{Statement}} on on Inclusive Language and its mainstreaming with the {{in-solidarity-bot}}. The authors chose to seek publication of this document as a historical marker of that discussion and as a contribution to social and restorative justice. 

# Further reading

Ford, Heather., Wajcman, Judy. 2017. "‘Anyone can edit’, not everyone does: Wikipedia and the gender gap" Social Studies of Science. ISSN 0306-3127

Grant, Barbara M. 2008. "Master—slave dialogues in humanities supervision" 
Arts and Humanities in Higher Education, Volume: 7 issue: 1, page(s): 9-27 https://doi.org/10.1177/1474022207084880

Miller, Carolyn, R. 1979. "A Humanistic Rationale for Technical Writing" College English, Vol. 40, No. 6, pp. 610-617 

# Security Considerations

Security is dependent on a wide range of actors that are implementing technical documentation. Therefore it is crucial that language is clear, and understood by all that need to implement this documentation. Correct and inclusive language is therefore conducive for secure implementations of technical documentation. 

# IANA Considerations

This document has no actions for IANA.

