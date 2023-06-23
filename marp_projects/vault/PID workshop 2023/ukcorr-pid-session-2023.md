---
marp: true
theme: beamer
paginate: true
size: 16:9
header: PIDs and repositories...
footer: UKCORR webinar - 30 June 2023
title: Marp custom themes
---
<!-- _class: title -->

# PIDs and repositories: experiences & practical issues of implementing DOIs for content
## Perspectives from Strathclyde (Strathprints)


Dr George Macgregor
University of Strathclyde
2023-06-30
https://purl.org/g3om4c

---

# A normal slide

# H1 again
## H2
### H3
- bullet
> quote
```
code
```
text

---
# The 'technical' bit: what are PIDs?
- PID = *persistent identifier* (Doh!)
- PIDs come in many flavours, e.g. DOI, ORCID, RAiD, ROR, etc.
- Provides unique and persistent reference to an entity normally accessible over the Internet
- Enables long-term identification but also 'actionability' because they are formed as URIs
- PIDs usually underpinned by some form of registry which registers new PIDs and resolves them (and contains metadata!) (e.g. DataCite, CrossRef)

---
# The 'soft' bit: things to remember about PIDs
- Technical issues exist *but* persistent identifiers really a 'soft' issue because...

PIDs only persistent:
- while the PID registration service commits to resolving them, and;
- while the organization / publisher commits to updating the registration service (registry)

---
# Strathprints DOI journey...
Using Strathprints as the case study (based on EPrints)
But much of what will be stated applies beyond....

---
# What do you need to begin coining DOIs for content?

- DataCite subscription
- Single subscription but can be used for different DOI prefixes and/or different services
- e.g. [Strathprints](https://strathprints.strath.ac.uk) (research publications & other animals), [STAX](https://stax.strath.ac.uk/) (theses), [KnowledgeBase ](https://pureportal.strath.ac.uk/en/datasets/)(research data), etc.
- Piggyback off research data account...?
---
# Strathprints DOI journey...
DataCite member since circa 2015
Account used for:
- 2015: Research data (different repo)
- 2017: Open grey scholarly literature (Strathprints) - manual DOI minting
- 2018: Research publications (Strathprints) - semi-automatic DOI minting
- 2021: Research publications (Strathprints) - fully automatic DOI minting
---

Example: [https://doi.org/10.17868/strath.00085235](https://doi.org/10.17868/strath.00085235)

---
# When to mint a DOI?



---
# Minting, but not as we know it, Jim...

Important -- there is always an option available to comply, even with DOIs.

DataCite form
Export and import DataCite compliant XML metadata
- 
---
# Things to ponder...

Auto minting?
- [ZORA](https://www.zora.uzh.ch/) - Zurich Open Repository Archive (University of Zurich)
- Example: https://doi.org/10.5167/uzh-224344
![width:900px](zora-screen-1.png)
---
# ...pondering continued
or rules-based minting?
- EPrints DataCite integration enables automatic but conditional DOI minting
- i.e. specific content types
---
# ...pondering extended
or discretionary minting?
- Manually initiated by repository team
- e.g. for RRS/UKRI compliance, overlay journal publication, grey literature, etc.
---
![width:600px](strathprints-screen-2.png)

---
# Other PIDs...
CORE OAI IDs
 
---

# Other compliance options...
Zenodo

 
---

# Possible pain points...
Project data
Integrations with CRIS
'Write protecting' database fields
Other PIDs and enriching the PID graph
Ensuring relational links


 
---
# Title page ad hoc fix

If the title of your presentation is too long and the border intersects with the text underneath, use the following

```html
# Title
<br/>
<!-- empty line here --->
Author's name
University of XYZ
...
```
make sure to leave an empty line below the `<br/>` tag

---
<!-- _class: tinytext -->
# Tinytext class

- use `<!-- _class: tinytext -->` to make some text tiny
- might be useful for References
