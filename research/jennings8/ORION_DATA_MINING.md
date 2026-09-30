# Jennings 8 — Orion / FBI Lead-Database Data-Mining Study

## Why this source matters

A peer-reviewed 2013 paper analyzed **172 "Information Packages" (IPs)** from the Jennings homicide investigation using the FBI-maintained Orion database.

This is unusual because it gives a documented window into:
- the task force's internal lead-management data;
- witness/interview/email/phone-call records;
- how leads clustered by content and geography;
- information the task force itself said was previously unknown.

The study does **not** identify a killer in public.

---

## Citation

Marco Helbich, Julian Hagenauer, Michael Leitner, Ricky Edwards.

**"Exploration of unstructured narrative crime reports: an unsupervised neural network and point pattern analysis approach."**

Cartography and Geographic Information Science, 40(4), 326–336 (2013).

DOI:
10.1080/15230406.2013.779780

Open PDF:
https://www.uni-heidelberg.de/md/chemgeo/geog/lehrstuehle/gis/helbich_etal_2013.pdf

Utrecht research portal:
https://research-portal.uu.nl/en/publications/exploration-of-unstructured-narrative-crime-reports-an-unsupervis

Important:
**Ricky Edwards is a coauthor.**
That ties the paper directly to the sheriff/task-force leadership rather than making it an outside speculative study.

---

# Data source

The paper says the Jennings task force used the FBI's **Orion** database to store "Information Packages" consisting of:

- email correspondence;
- transcribed face-to-face interviews;
- phone calls;
- witness/public tips;
- geographic coordinates associated with people/locations.

For the study:
- only **172 IPs related to Necole Guillory** were analyzed;
- personal names and addresses were masked in the published paper for confidentiality;
- the authors said the entire case contained more IPs and suggested future analysis of all victims.

This means the public internet contains only a small fraction of the actual lead data.

---

# Task-force assumption at the time

The paper says the task force assigned to the series **assumed the homicides were linked to the same perpetrator**.

This is historically important.

It helps distinguish:
- the task force's working model in 2012–13;
- later Sheriff Ivy Woods statements that not all eight were officially classified as homicides / proven linked;
- Ethan Brown's later multiple-offender theory.

The academic analysis was therefore performed inside a **common-offender investigative framework**.

---

# Three textual clusters

The self-organizing-map analysis identified three distinct clusters within the 172 Necole-related IPs.

Cluster sizes reported:
- **Cluster 1:** 17 IPs
- **Cluster 2:** 11 IPs
- **Cluster 3:** 44 IPs

Other IPs did not map cleanly into the three distinct clusters.

The paper does not publish the identities behind anonymized person codes.

---

# Important public relationship findings

## Kristen Lopez ↔ Brittney Gary

The authors observed:
- "Kristen" and "Brittnei" mapped near one another in the self-organizing map;
- they concluded that the criminal investigations concerning Kristen and Brittney **tended to be closely related**.

This is a potentially important computational finding because it emerges from the task-force lead corpus, not merely from family relationship information.

Possible reasons could include:
- family relationship;
- overlapping witnesses;
- overlapping suspects;
- shared locations;
- shared lead narratives.

The public paper does not reveal which.

**Do not overinterpret.**

---

## Laconia Brown appears different

The paper says:
- "Laconia" mapped far away from Kristen/Brittney;
- this indicated some difference in how the Laconia investigation related to the others inside the Necole lead corpus.

Again, the paper does not explain the substantive reason.

This may be analytically important when testing:
- one-offender vs multiple-offender models;
- witness/informant clusters;
- suspect clusters.

---

# Anonymized person clusters

## Cluster 1

The highest-weight term was an anonymized last name: **ln1**.

The paper says:
- many interrogations involved different people sharing that last name;
- ln1 was closely related to "laconia" in the map.

Possible significance:
A particular family/surname may have been central to Necole-related leads and also connected analytically to Muggy/Laconia.

Because the authors masked the name:
**Docket Unseen must not guess who ln1 represents.**

---

## Cluster 3

Important terms included:
- anonymized first name **fn1**;
- anonymized last name **ln3**;
- "sex";
- "piec" / piece;
- "prepar";
- another anonymized first name fn2.

The paper says:
- ln3 appeared frequently in the criminal investigation;
- ln3 mapped to the same neuron as "Lafayette" and fn2.

This suggests a recurring surname/person cluster tied in some way to Lafayette-area information.

Again:
**identity is confidential in the paper and must not be reverse-engineered by guesswork.**

---

# Other terms visible in the data

The paper's word cloud / preprocessing tables show recurring terms including:
- investigations;
- person;
- lead;
- vehicle;
- truck;
- DNA;
- detective;
- deputy;
- interview;
- license;
- evidence;
- Lafayette;
- Lake Charles;
- GMC;
- Chevrolet Impala;
- Louisiana State Police Crime Lab;
- sex;
- boyfriend;
- blood.

These terms establish categories present in the lead corpus, not conclusions.

---

# Geographic cluster findings

The three text-derived clusters had different spatial distributions.

The authors reported:
- clusters 1 and 3 were mostly in/around Jennings;
- a significant portion of Cluster 1 was near Lafayette;
- Cluster 3 had relatively more IP locations around Lake Charles;
- Cluster 2 was more sparsely distributed.

Spatial statistics found:
- some significant short-distance attraction among cluster pairs;
- but overall the three clusters were **not strongly co-located geographically**.

Meaning:
similar narrative/lead content did not necessarily correspond to the same physical geography.

This could support the idea that the investigation contained multiple distinct lead networks.

It does **not** prove multiple offenders.

---

# Task force reaction

The authors state that:
- results were presented to the Jennings Task Force;
- the task force confirmed the information was previously unknown;
- it might provide **"new and important clues"**;
- specifics could not be disclosed because the homicide investigation was still open.

This is one of the strongest public indications that a structured analysis produced lead relationships that were **not previously recognized manually**.

---

# Analytical implications for Docket Unseen

## 1. The internal lead database is richer than the public case narrative

We know 172 IPs existed for Necole alone.

Therefore:
- public news articles represent only a fraction of the investigation;
- the current sheriff may possess thousands of lead/interview records.

## 2. Kristen/Brittney linkage is independently supported by lead-data structure

Their relationship is not only familial/social; their investigative records clustered close together.

We still need to learn why.

## 3. Muggy/Laconia may belong to a different lead cluster

This supports testing subset models instead of forcing all cases into one pattern.

## 4. Anonymous surnames may be highly central

At least two anonymized surname clusters were frequent enough to dominate parts of the analysis.

This makes the underlying unmasked mapping a potentially high-value law-enforcement artifact.

---

# What the study does NOT tell us

It does not publicly reveal:
- identities behind ln1 / ln3 / fn1 / fn2;
- which IPs were credible;
- whether a cluster pointed to a suspect;
- whether the clues were followed;
- whether the analysis produced arrests/searches;
- whether the analysis was repeated across all eight victims;
- whether current investigators still use the findings.

---

# Records / research targets created by this study

## FBI / JDPSO

Request or inquire about:
1. existence/current preservation of Orion Jennings 8 IPs;
2. total number of IPs across all eight victims;
3. whether the 2013 data-mining output remains in the case file;
4. whether all-eight-victim analysis was ever completed;
5. whether the three cluster findings were acted upon;
6. whether modern investigators have re-run text/network analysis on the entire corpus.

Public release may be denied because the cases remain open.

---

# Prior FBI FOIA requests

FBI FOIA logs show at least:

### 2019
FOIA no. **1442165**
Subject: **Jeff Davis 8**
Opened: 07/17/2019

### 2022
FOIA no. **1560355**
Subject: **Jennings 8/Jeff Davis 8**
Opened: 09/16/2022

These numbers should be referenced in a new request asking whether previously processed releasable material can be reproduced or whether the same search set can be requested.

Sources:
FBI Vault FOIA logs.

---

# Academic-author inquiry opportunity

Possible inquiry to:
- Marco Helbich
- Julian Hagenauer
- Michael Leitner

Ask only for nonconfidential/public material:
- supplemental figures;
- de-identified cluster descriptions;
- whether all-victim analysis was ever completed;
- whether a follow-up paper exists;
- whether task-force feedback was documented in nonconfidential correspondence;
- whether the anonymization key remains exclusively with law enforcement.

Do not ask researchers to reveal protected names from an open homicide investigation.

---

# Relationship to our solvability analysis

This study materially strengthens the idea that modern computational analysis of the complete case corpus could be useful.

If the current JDPSO has:
- thousands of pages of new reports;
- old Orion/IP material;
- modern OCR/text embedding/network tools;

then a comprehensive re-analysis could compare:
- person co-occurrence;
- vehicle mentions;
- addresses;
- phone numbers;
- family names;
- lead credibility;
- geography;
- victim subsets;
- time.

Docket Unseen can discuss this method conceptually without pretending we possess the protected lead data.

---

# Documentary use

This could be a very strong Part 13 / investigative-method segment.

Visual:
- 172 document nodes;
- three clusters;
- anonymized names;
- map split toward Jennings/Lafayette/Lake Charles;
- Kristen/Brittney nodes close together;
- Laconia separated.

Narration concept:
> "Years before today's AI tools, researchers fed 172 task-force leads from Necole Guillory's case into an unsupervised neural network. It found relationships investigators said they hadn't recognized before. The public was never told what those clues were."

Then clearly state:
> "The names were deliberately masked because the case was—and remains—open."
