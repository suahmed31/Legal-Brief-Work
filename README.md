# Legal-Brief-Work Introduction
This repository is for developing a framework for legal briefs or case brief. A case brief is a dissection of a judicial opinion -- it contains a written summary of the basic components of that decision. Case briefing helps you acquire the skills of case analysis and legal reasoning. Briefing a case helps you understand it.  

Case briefing aids your memory. Briefs help you remember the cases you read (1) for class discussion, (2) for end-of-semester review for final examinations, and (3) for writing and analyzing legal problems. 

**CaseBriefs** folder contains sample case briefs for indian cases. Case Judgements for each case briefs are stored in **CaseJudgements** folder.

We have used OpenNyAi based BUILD Model to create the Rhetorical Roles (RR). You can find the details about the Rhetorical Role Baseline at the [Git Hub link](https://github.com/Legal-NLP-EkStep/rhetorical-role-baseline). 

Once, we get the RRs, we can now process them further for creating a Case Brief.

# System Overview

This work is build on top of [BUILDNyAI](https://legal-nlp-ekstep.github.io/Competitions/Rhetorical-Role/) model and [OpenNyAI NLP Pipeline](https://github.com/OpenNyAI/Opennyai). The OpenNyAI NLP Pipeline takes a legal Judgement and Produces three types of outputs with the help of three pre-trained models, namely - summarizer, NER and Rhetorical-Roles. 

You can also get all the three types of data (Summary, Name Entities, Rhetorical Roles) using this [WebAPP](https://summarizer-fer6v2lowq-uc.a.run.app/) provided by OpenNyAI. However, copying each rhetorical role is a cumbersome and highly inefficient task. So, we need to install the NLP Pipeline on our local system and then download the models output, in our case rhetorical roles, in JSON format (.

The technical issue with the JSON format in this case is its readability and thereby its analysis. The JSON format of legal text is a complex architecture as mentioned in its [description](https://github.com/Legal-NLP-EkStep/rhetorical-role-baseline). So, we have convert the same in to more efficient format and we choose it to be Comma Separated Values (CSV) format.

# Legal Brief Work

Once, we get the CSV file (You can check the sample CSV


