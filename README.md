# AMYBO Data Sharing Platform

Our data sharing platform which initially aims to let [Pioreactor](https://pioreactor.com) and [electroPioreactor](https://amy.bo/electropioreactor) users automatically stream data to an open repository.  This should accelerate alternative protein discovery by facilitating collaboration and the development of digital twins.

# STA Scoping

The [page you are currently reading](https://github.com/amy-bo/DSP/edit/main/README.md) is the official Scottish Tech Army scoping document, it supersedes the [original STA word document](https://github.com/Amybo-org/DSP/raw/refs/heads/main/AMYBO-DSP-STA+Project+Scope+Document+V0.4+(6).docx) and going forward, only this repo will be updated.

## Background of the charity

AMYBO ([amy.bo](https://amy.bo)) is a non-profit organisation that aims to develop alternative protein that is so delicious, nutritious and affordable that communities in Scotland and across the world will produce & eat it instead of meat. Once achieved this should:

- lower Scottish (& eventually global) greenhouse gas emissions by >8%
- free >2M hectares of land in Scotland alone for rewilding - reducing biodiversity loss
- reduce diet-related deaths in Scotland by >1,200/annum and eventually end global food crises

To date, we have developed an open source electrobioreactor that will let volunteers cultivate strains of natural Hydrogen Oxidising Bacteria (HOB) to find the best tasting, nutritious and economical strains.

These bioreactors measure the optical density of the culture every 5 seconds so we can determine how quickly the HOB are growing.

## Problem

- To compare the growth of different HOB cultures in what we hope will be thousands of bioreactors, we need to get that data online.
- We also want to give bioreactors away on a ‘free rental’ basis, so people pay nothing as long as they are doing useful experiments. We require an automated system to verify experimental activity.
- Many researchers would like to train AI on bioreactor data, but there is insufficient data available online (LLMs and Google’s AlphaFold were only successful because of the amount of data they could be trained on).

## Current state

- If they remember, people manually upload graphs of their data to [forum.amybo.org](https://forum.amybo.org) or submit pull requests to add experiments to [our docs](https://amybo.org/docs/experiments/)
- Volunteers must buy their own bioreactors
- We currently lack volunteers with both the time and technical expertise to establish the system.

## Scope

- Software on Pioreactor to automatically send standard Pioreactor data and additional experiment data to a data sharing platform
  - The Pioreactor software should if possible be implemented as a [Pioreactor Plugin](https://docs.pioreactor.com/developer-guide/intro-plugins).
  - additional experiment data is listed in [Metadata.md](Metadata.md)
- The data sharing platform collates data from electroPioreactors (scalable to 1000’s)
- Ability for users to select and compare multiple experimental runs including:
  - the ability to graph multiple experimental runs - with x-axis shifting for easy comparison
  - the ability to numerically compare larger groups of experimental runs
- Ability for anyone to download the dataset for analysis (assuming a manual download is easier than an API)
- Training:
  - The system should be fully documented in the software (both front end and code) to ensure that it can be maintained long term by any volunteers.
  - AMYBO can then also produce training videos.

## Goal

- Pioreactors can be set up automatically to stream relevant data to an open source data sharing platform.
- Having all this data on a data sharing platform will allow researchers to collaborate and learn from each other's work, it will allow them to train AI and digital twins on this data and
- It will also allow us to monitor if free-rental bioreactors are being used as intended.
- We would ideally like to have an initial data sharing platform set up by the end of Q1.

## Barriers to Project

- Our constraints to date have been time/ability mismatches and lack of funding to contract out the project.
- Martin has no planned holiday in the next 3 months and works on AMYBO 95% full time.
- We are due to hold a [CARMA Hub project](https://carmahub.co.uk/about-us/pump-priming-projects/#:~:text=Affordable%20Aseptic%20Electro%2DBioreactor%20for%20Reproducible%20Hydrogen%20Oxidising%20Bacteria%20(HOB)%20Research) with Imperial College and Edinburgh University determining the repeatability of a new academic Aseptic electroPioreactor.  Ideally, the platform will be piloted during this project. If not feasible, commencement may be postponed until ~April 2026.

## What conditions exist?

- We will need to lend developers a Pioreactor. We are fully open source - no NDA.
- The AMYBO community can procure/scale up the solution service for medium or long-term use.

## Current/Existing Technology

- The electroPioreactor is detailed [here](https://amy.bo/electropioreactor)
- It is based on the Pioreactor which is thoroughly documented at [docs.pioreactor.com](https://docs.pioreactor.com)
- We have no volunteer database, but can request input from volunteers via [our forum](https://forum.amybo.org) and [YouTube](https://amy.bo/YouTube)

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

- **Organisation main contact**: [Martin Currie](https://martin.aqueum.com)
- **STA contact**: Jean Ferguson 
- **Date**: 28/08/2025  

- **Organisation top stakeholders**:
  - [Martin Currie](https://martin.aqueum.com)
  - [Gerrit Niezen](https://labcrafter.co.uk/pages/about-us)
  - [Cam Davison-Pilon](https://github.com/camdavidsonpilon) (founder of Pioreactor)
