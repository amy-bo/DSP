# AMYBO Data Sharing Platform

Our data sharing platform which initially aims to let [Pioreactor](https://pioreactor.com) and [electroPioreactor](https://amy.bo/electropioreactor) users automatically stream data to an open repository.  This should accelerate alternative protein discovery by facilitating collaboration and the development of digital twins.

# STA Scoping

The [original STA word document is available here](https://github.com/Amybo-org/DSP/raw/refs/heads/main/AMYBO-DSP-STA+Project+Scope+Document+V0.4+(6).docx)

## Background of the charity

AMYBO ([amy.bo](https://amy.bo)) is a non-profit organisation that is developing alternative protein that is so delicious, nutritious and affordable that communities in Scotland and across the world will produce & eat it instead of meat. We project this will:

- lower Scottish (& eventually global) greenhouse gas emissions by 8%
- free >2M hectares of land in Scotland alone for rewilding - to halt biodiversity loss
- reduce diet-related deaths in Scotland by >1,200/annum and eventually end global food crises

We have developed an open source electrobioreactor that will let volunteers cultivate strains of natural Hydrogen Oxidising Bacteria (HOB) to find the best tasting, healthy and economical strains.

These bioreactors measure the optical density of the culture every 5 seconds so we can determine how quickly the HOB are growing.

## Problem

- In order to compare the growth of different HOB cultures in what we hope will be thousands of bioreactors, we need to get that data online.

- We also want to give bioreactors away on a ‘free rental’ basis, so people pay nothing as long as they are doing useful experiments. We need an automated means of determining if this is happening.

- We (and many others) would like to train AI on bioreactor data, but there is insufficient data available online (LLMs and Google’s AlphaFold were only successful because of the amount of data they could be trained on).

## Current state

- If they remember, people manually upload graphs of their data to [forum.amybo.org](https://forum.amybo.org)
- Volunteers have to buy their own bioreactors
- We have volunteers, but none have both the time and ability to set this system up.

## Existing Tech

- The electroPioreactor is detailed [here](https://amy.bo/electropioreactor)

- It is based on the Pioreactor which is thoroughly documented at [docs.pioreactor.com](https://docs.pioreactor.com)

## Scope

- Software on Pioreactor to automatically send standard data plus a number of additional text user-inputs to a data sharing platform
- The data sharing platform collates data from electroPioreactors (scaleable to 1000’s)
- Ability for anyone to download the dataset for analysis (assuming a manual download is easier than an API)
- Training: It would be great to document the system both in the software and via training videos to ensure that it can be maintained long term by any volunteers.

## Goal

- Pioreactors can be set up automatically to stream relevant data to an open source data sharing platform.

- Having all this data on a data sharing platform will allow researchers to collaborate and learn from each other's work, it will allow them to train AI and digital twins on this data and

- It will also allow us to monitor if free-rental bioreactors are being used as intended.

- We would like to have an initial data sharing platform set up by the end of Q1.

## Barriers to Project

- Our constraints to date have been time/ability mismatches and lack of funding to contract out the project.

- Martin has no planned holiday in the next 3 months, and works on AMYBO 95% full time.

## What conditions exist?

- We will need to lend developers a Pioreactor. We are fully open source - no NDA.

- The AMYBO community is in a position to procure/scale up the solution service for medium or long-term use – Prof Joshua Pearce of [uwo.ca](https://uwo.ca) offered to fund 10 electroPioreactors with $100k in kind academic support for a pilot trial, with hopefully 100 electroPioreactors to follow if successful.

## Current Technology

The Pioreactor software should if possible be implemented as a [Pioreactor Plugin](https://docs.pioreactor.com/developer-guide/intro-plugins).
We have not started development of the Data Sharing Platform other than opening a [public repo](https://github.com/Amybo-org/DSP).


## Technology

### Charity details

- **Website URL**: [amy.bo](https://amy.bo)
- **Website platform**: Docsy (Hugo) with [amy.bo/forum](https://amy.bo/forum) using self-hosted Discourse
- **URL provider**: Cloudflare & nic.bo
- **Email platform**: Google Workspace
- **Facebook page**: NA, but we use [YouTube](https://www.youtube.com/@AMYBO)
- **LinkedIn**: [linkedin.com/company/amybo](https://linkedin.com/company/amybo)
- **Twitter handle**: [x.com/martin_currie](https://x.com/martin_currie) – not sensible to set up amybo Twitter 

## Useful Documents

- [amy.bo/forum](https://amy.bo/forum)
- [amy.bo/docs](https://amy.bo/docs)
- [amy.bo/repo](https://amy.bo/repo)

## Marketing Permissions

We are happy for STA to acknowledge the work we are doing with us and would possibly be open to future joint marketing activities.  

---

**Organisation main contact**: Martin Currie  
**STA contact**: Name here  
**Date**: 08/01/2025  

**Organisation top stakeholders**: Martin Currie, Gerrit Niezen, Cam Davison-Pilon (founder of Pioreactor who will likely be helpful via [forum.pioreactor.com](https://forum.pioreactor.com))
