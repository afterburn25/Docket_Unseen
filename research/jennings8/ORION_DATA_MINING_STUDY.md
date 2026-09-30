# Jennings 8 — FBI Orion / Academic Data-Mining Analysis

## Why this is important

In 2012–2013, university researchers worked directly with the Jennings Police Task Force and analyzed narrative investigative data from the **FBI-maintained Orion database**.

This is unusually valuable because the study was not built from public news articles or later documentary interviews.

It analyzed material from the actual investigation:
- email correspondence;
- transcribed face-to-face interviews;
- phone-call information;
- other narrative "Information Packages" (IPs).

The 2013 peer-reviewed paper was coauthored by:
- Marco Helbich;
- Julian Hagenauer;
- Michael Leitner;
- **Ricky Edwards**, then-former Jefferson Davis Parish sheriff / key task-force official.

Publication:
**Exploration of unstructured narrative crime reports: an unsupervised neural network and point pattern analysis approach**
Cartography and Geographic Information Science 40(4), 326–336 (2013)
DOI: **10.1080/15230406.2013.779780**

Full paper:
https://www.uni-heidelberg.de/md/chemgeo/geog/lehrstuehle/gis/helbich_etal_2013.pdf

University record:
https://research-portal.uu.nl/en/publications/exploration-of-unstructured-narrative-crime-reports-an-unsupervis/

---

# Dataset

The paper states:
- the Jennings Police Task Force used the FBI **Orion** database;
- Orion stored investigative "Information Packages";
- packages included email, interview transcripts, phone calls and other narrative material;
- the study used **172 IPs related to Necole Guillory**, the eighth victim.

Important:
"Related to Necole" does not mean every package concerns only Necole. The IPs contain names/topics involving other victims and people in the broader investigation.

---

# Analysis method

Researchers:
- converted the narrative records to text;
- used word-frequency / TFIDF methods;
- trained a **self-organizing map (SOM)**;
- grouped similar records into clusters based on textual content;
- mapped geocoded IPs spatially;
- tested whether textual clusters also exhibited geographic relationships.

This was exploratory intelligence analysis, not a forensic proof or suspect-identification algorithm.

---

# Three main textual clusters

The SOM produced three distinct clusters among part of the 172 records:

- **Cluster 1: 17 IPs**
- **Cluster 2: 11 IPs**
- **Cluster 3: 44 IPs**

Other records did not fit cleanly into one of the three distinct clusters.

The paper anonymized private names.

Do not attempt to publicly de-anonymize masked people from context alone.

---

# Kristen Lopez and Brittney Gary relationship

One of the most important published findings:

The terms **"Kristen"** and **"Brittnei"** mapped very near one another in the self-organizing map.

The authors conclude that:

> the criminal investigations concerning Kristen Lopez and Brittney Gary "tended to be closely related."

This is based on similarity in the language/content of actual task-force records.

Analytical significance:
- independently supports a strong connection between the Kristen and Brittney investigative information streams;
- fits their known family/social relationship;
- may indicate shared witnesses, people, events or investigative topics.

It does **not** by itself identify why the cases were related.

Source:
paper pp. 5–6 / lines ~395–399 in parsed copy.

---

# Laconia "Muggy" Brown was different

The word stem for **Laconia** mapped far from Kristen/Brittney.

The paper says this indicates there was "some difference" between the criminal investigation involving Laconia Brown and those involving Kristen/Brittney.

Analytical significance:
- argues against assuming all victim case information formed one homogeneous pattern;
- potentially supports victim-subset / multiple-cluster analysis;
- may mean different witnesses, suspects, geography, or topics.

It does not reveal the reason because confidential names/details were masked.

---

# Other published term relationships

The SOM placed terms corresponding to:
- "sex";
- "boyfriend";
- "blood"

within the same textual cluster, meaning records containing those terms shared content similarities.

These are generic analytical associations and should not be treated as a narrative about a particular victim without the underlying IPs.

---

# Anonymized recurring surnames / names

The paper says:
- one anonymized surname stem ("ln1") appeared frequently because many people with that surname had been interrogated during the Necole investigation;
- this surname stem appeared near the Laconia-related region;
- a different anonymized surname ("ln3") also appeared often;
- "ln3" mapped to the same SOM neuron as **Lafayette** and another anonymized first name.

Critical:
The researchers intentionally masked identities.

Docket Unseen should **not infer or publicly name the masked surnames** without source records confirming them.

The important fact is:
> actual task-force records contained recurring family/name clusters significant enough to emerge independently in text-mining analysis.

---

# Geographic cluster findings

The paper mapped geocoded IPs.

Published findings:
- clusters 1 and 3 were concentrated mostly in/around Jennings;
- a significant share of **cluster 1** IPs appeared near **Lafayette**;
- cluster 3 had fewer Lafayette-area records but a notable concentration around **Lake Charles**;
- cluster 2 was more sparsely distributed.

The statistical analysis found:
- evidence of geographic attraction between clusters 1–2 and 1–3 at distances roughly 0–3 km;
- cluster 2–3 association was significant only over a narrower 2–3 km interval;
- overall, textual similarity and geographic similarity were not simply the same thing.

Analytical significance:
The investigative data appear to contain **distinct information/geography sub-networks**, not one uniform spatial cluster.

---

# Task force reaction

This is the strongest statement in the paper.

The authors say:
- results were presented to the Jennings Task Force;
- the task force confirmed the results contained information **previously unknown** to investigators;
- the findings might provide **new and important clues**.

Because the homicide investigation remained open, the authors said they could not reveal the specific identities/details behind those new clues.

This means a public academic paper confirms:
1. investigators had a large machine-readable intelligence set;
2. external analysis surfaced relationships investigators had not previously recognized;
3. those specific clues remain nonpublic.

---

# What this does to our theory map

## Supports case clustering
Strongly.

The task-force data itself did not behave like one uniform narrative.

Kristen/Brittney appeared closely related.
Laconia appeared different.

This strengthens the need to test **victim subsets** instead of assuming all eight share one identical offender/motive.

## Supports multiple-offender theory?
Only indirectly.

Different information clusters can result from:
- different offenders;
- different witness groups;
- different neighborhoods;
- different phases of one offender's activity;
- different levels of evidence.

It is not proof of multiple killers.

## Supports one-offender theory?
Still possible.

One offender can produce heterogeneous investigative records.

The paper does not reveal whether the hidden relationships pointed to one person or multiple people.

## Supports geographic/local-network theory
Yes.

The records form distinct Jennings/Lafayette/Lake Charles geographic patterns.

---

# Major record opportunity

## The 172 Necole IPs

If even segregable/anonymized versions could be obtained, they could materially change the project.

Potential custodians:
- FBI;
- Jennings Police Department / task force;
- Jefferson Davis Parish Sheriff's Office;
- Louisiana State Police;
- researchers/authors may retain anonymized analytical extracts subject to agreements.

Likely limitation:
Active-investigation, privacy, informant, and law-enforcement exemptions will be substantial.

---

# Request strategy

Do not initially ask for all raw Orion intelligence.

Start with:
1. documents describing the university/task-force research project;
2. data-sharing agreement / memorandum if public;
3. nonconfidential output presented to the task force;
4. figures/maps with masked identities;
5. final presentation/report;
6. records showing how investigators followed up the newly discovered patterns;
7. any now-releasable anonymized or segregable results.

Ask the authors:
- whether a nonconfidential technical report or presentation survives;
- whether anonymized figures/data can be shared;
- whether the task force ever communicated what happened to the new leads;
- whether the whole eight-victim Orion dataset was ever analyzed after the Necole pilot.

---

# Extremely important unanswered question

The 2012 conference paper said that if the Necole analysis proved useful, researchers planned to rerun the analysis on **the entire set of Orion Information Packages**.

We need to determine:

> **Did that full eight-case analysis ever happen?**

If yes, its results could be one of the most important nonpublic analyses in the case.

---

# Documentary value

This belongs in:
- Part 6 — network;
- Part 9 — investigation;
- Part 12 — theories;
- Part 13 — what evidence may still exist.

Possible framing:

> "The task force had so much information that researchers fed 172 reports from Necole's case into a machine-learning system. The analysis found links investigators said they hadn't seen before. Those links have never been publicly identified."

Then clarify:
> "The published research masked names because the murders remained open."

This is compelling without speculating about the hidden identities.


---

# Follow-up publication search — 2026-09-29

A targeted search of later publications by the same researchers has **not identified a verified publication reporting a full all-eight Jennings Orion analysis**.

Important publication-language difference:

## AutoCarto 2012
The conference paper explicitly says:
- only the 172 Necole IPs were analyzed;
- if useful, the authors **planned** to rerun the approach using the entire Orion dataset.

## Peer-reviewed 2013 paper
The final paper confirms:
- the Necole analysis produced new relationships useful to the task force.

But its published future-research section discusses applying/evaluating the method on **collective-surveillance information and solved crime cases from LSU Police**, rather than reporting that the full Jennings dataset had been analyzed.

This does not prove the full Jennings analysis never happened internally.

It means:
> **No published full-eight follow-up has yet been verified.**

A later 2014 publication titled `Building Multi-modal Crime Profiles with Growing Self Organising Maps` appears to be a general criminal-profile/data-mining methodology work by different authors and has not been verified as a Jennings follow-up.

Next step:
See `ORION_RESEARCHER_OUTREACH.md`.


---

# Researcher contact status — 2026-09-29

Verified public contacts:
- Marco Helbich — Utrecht University — **m.helbich@uu.nl**
- Michael Leitner — Louisiana State University — **mleitne@lsu.edu**
- Julian Hagenauer — later 2016 publication lists **j.hagenauer@ioer.de** (recheck before sending)

No outreach has been sent.

The publication search still has **not** identified a verified full-eight Jennings Orion follow-up.

A general 2014 chapter, `Building Multi-modal Crime Profiles with Growing Self Organising Maps`, is by different authors (Yee Ling Boo and Damminda Alahakoon) and should not be treated as the promised Jennings follow-up.

---

# Figure/results clarification from parsed paper text

The current web PDF screenshot service failed on the Heidelberg host, so no new visual interpretation of Figures 3–5 was made.

Only the authors' explicit text is used:
- Cluster 1: 17 IPs.
- Cluster 2: 11 IPs.
- Cluster 3: 44 IPs.
- Other IPs did not map to a distinct cluster.
- Sex, boyfriend, and blood appeared in the same cluster.
- Kristen and Brittnei mapped close together; authors concluded those investigations tended to be closely related.
- Laconia mapped far from them, indicating some difference in that investigation.
- Anonymized last-name stem ln1 appeared frequently because many people with that surname had been interrogated in Necole's investigation; it was closely related to the Laconia region.
- Cluster 3's anonymized ln3 stem mapped with Lafayette and an anonymized first name.
- The three text clusters showed only partial geographic association.
- The Task Force said the analysis revealed previously unknown information / potentially important clues.

Do not infer masked identities from the figure or surrounding public names.