---
title: 'Characterization of Potential Drug Treatments for COVID-19 using Twitter'
tags:
  - COVID-19
  - Machine Learning
  - Twitter
authors:
  - name: Ramya Tekumalla
    orcid: 0000-0002-1606-4856
    affiliation: 1
  - name: Juan M Banda
    orcid: 0000-0001-8499-824X
    affiliation: 1
affiliations:
 - name: Georgia State University, Atlanta, Georgia, USA
   index: 1
date: 22 May 2020
bibliography: paper.bib
---

# Abstract

Since the classification of COVID-19 as a global pandemic, there have been many attempts to treat and contain the virus. Although there is no specific antiviral treatment recommended for COVID-19, there are several drugs that can potentially help with symptoms. In this work, we mined a large twitter dataset of 280 million tweets of COVID-19 chatter to identify discourse around potential treatments. While seemingly a straightforward task, due to the informal nature of language use in Twitter, we demonstrate the need of machine learning methods to aid in this task. By applying these methods we are able to recover almost 21% additional data than with traditional methods.

# Introduction 

The World Health Organization (WHO) defines the Coronavirus disease (COVID-19) as an infectious disease caused by a newly discovered coronavirus and declared it a pandemic on March 11, 2020 [@WorldHealthOrganization]. As of May 11, 2020, 4,148,034 cases were confirmed worldwide with 284,124 deaths and 1,428,161 cases recovered. Social media platforms like Twitter and Reddit contain an abundance of text data that can be utilized for research. Over the last decade, Twitter has proven to be a valuable resource during disasters for many-to-many crisis communication [@Earle:2010] [@Zou:2018] [@Alam:2018]. Recently, Several works [@Gao:2020] [@Lu:2020] [@Sanders:2020]  have provided insights on the treatment options and drug usages for COVID-19. 

We utilized the largest available COVID-19 dataset [@Banda:2020] curated using a Social Media Mining Toolkit [@Tekumalla:2020]. This dataset consists of tweets related to COVID-19 from January 1, 2020. Version 9 was utilized for our experiments since it was the latest version at the time of experiments. We annotated ~283 million tweets using the drug dictionary [@Tekumalla:2019] compiled from RxNorm [@NationalLibraryofMedicine:2008] with 19,643 terms and validated in [@Tekumalla:2019] and [@TekumallaandBanda:2020]. 
