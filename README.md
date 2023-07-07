# CEOS OpenSearch

# Best Practice Document

# Version 1. 3

### CEOS Document

### [CEOS-OPENSEARCH-BP-V1. 3 ]


# Revision History

```
Date Version Sections affected Changes
```
2014 - 12 - 17 1.0(draft) All Draft release for public comment period

2015 - 05 - 29 1.0 All Official release

2015 - 06 - 10 1.0.1 CEOS-BP- 007 Changed to recommend startIndex over startPage in CEOS-BP-
007

2016 - 01 - 13 1.1 D1 All Conversion from Google Doc to MS-Word using styles to generate
Table of content, list of figures and list of tables.
Appendix added listing open issues for which agreement is still
needed.
Use of "param:" namespace prefix made consistent in several
examples.

Section 1.4 Section revised to strengthen applicability of OGC specifications
(as per WGISS-40 MoM §4.3.1.4).

Section 1.4.3 Section with namespace prefix mappings added to remove
ambiguity about meaning of namespace prefixes used in the
normative part (and its examples) of the text, e.g. meaning of "dc:"
in CEOS-BP- 011.

Section 2.2 Third bullet added to CEOS-BP-002 to indicate how
inconsistencies between <Url> template and <Parameter>
elements should be handled.

Section 2.2.1 Section "Free Text Keyword" about CEOS-BP-002 expanded to
also apply to other parameters than "searchTerms" (e.g.
eo:platform), and propose the same mechanism to define
expected behavior of wildcards in search parameters
(eo:platform="SPOT*") to cover the corresponding point in (as per
WGISS-40 MoM §4.3.1.4).
Reworded to also cover mechanism proposed in CEOS-DG- 005
which existed in the text (as an example), but was not identified as
a separate requirement.

Section 2.2.2 CEOS-DG-006 added as a requirement.

Section 2.2.3 CEOS-BP-101 added (Query element in OSDD).


```
Date Version Sections affected Changes
```
Section 2.2.3 CEOS-BP-004 updated to clarify which requirements are to be
met before a server can advertise to be CEOS OpenSearch Best
Practice compliant.

Section 2.3 Expected behavior specified when count=0, which is allowed by
the specification (CEOS-BP-005B).

Section 2.3 Guidance added for search parameter name to be used when
searching by satellite name (CEOS-BP- 005 C). Guidance for
search parameter value in case of satellite name added.

Section 2.3 CEOS-DG-007B added derived from original CEOS-DG-007.

Section 2.3 CEOS-DG-014 added, but split in 014B and 014B to clarify how
fixed part of URL corresponding to "keys" of optional parameters
should be handled.

Section 2.3 Sentence added after CEOS-BP-009 to clarify that use of "." as
separator is not normative.

Section 2.4 CEOS-DG- 018 added (rel="first", ...).

Section 2.4 CEOS-BP-012B added. Use of rel="via" in Atom feed to indicate
provenance of search results in case of syndication/aggregation.

Section 2.4 CEOS-DG-020 (Minimum Bounding Rectangle) added as optional
(nice-to-have).

Section 2.4 CEOS-BP-014 updated to clarify representation of multi-polygon
and multi-* footprints with GeoRSS GML.

Section 2.4 CEOS-BP-015B added with guidance on how to return multiple
quicklook/browse images corresponding to a single granule.

Section 2.4 CEOS-BP-016 (rel="enclosure") reworded to clarify that it applies
to granule level searches only.

Section 2.4 CEOS-DG-021 added (dc:date).

Section 2.4 CEOS-DG-022 (atom:link types) and CEOS-DG-022B added
(type attribute). CEOS-BP-012 split in two separate requirements
CEOS-BP-012A and CEOS-BP-012C for "metadata" and
"documentation".


```
Date Version Sections affected Changes
```
2016 - 01 - 28 1.1 D 2 Table 3 Reference to RFC 6906 ("profile" Link), INSPIRE Guidance
document and schema.org added.

Section 2.2.1 Info URI scheme used in "href" attribute to refer to "masked"
relation identifier as Info URI are valid URI as per
[http://www.ietf.org/rfc/rfc4452.txt.](http://www.ietf.org/rfc/rfc4452.txt.)

Section 2.4 CEOS-BP-016B added (data access with multiple files), compliant
with [INSPIRE] TG Requirement 32.
CEOS-BP-010: wording simplified.

Annex C Subsections C1 and C2 created and JSON-LD example added.

Internal ESA review comments (Email 21/01/2016 01:20)
resolved:

All Typos corrected.

Section 1.3 ADV-1: Subsection "Document terms and definitions" added.

Section 1.4.1 ADV-4: [OpenSearch] moved to top of table.
ADV-6: "encodings" replaced by "metadata model".

Section 2.2.3 ADV-9: Note added referring to NASA CWIC-SMART automated
test tool which rely on a similar convention.
ADV-11: Issue added about possible support for multiple
conformance levels and different encoding, for discussion with the
group.

Section 2.3 Wording of CEOS-BP-005 updated ("shall").

Section 2.4 Wording of CEOS-BP-011 updated ("shall").

Section 2.4 ADV-17: Link type attribute (CEOS-DG-022B) made mandatory.
Reference to [INSPIRE] Technical Guidance Req. 30 added.

2016 - 03 - 08 1.1 D3 Agreed review comments discussed at teleconf 2 March 2016
integrated.

All JGA-01: resto2 to be replaced with resto in URLs.

Section 2.4 NASA-7: update CEOS-DG- 018 to allow for both "prev" and
"previous" and add proposed responses for border cases.

Section 2.2.1 NASA-8: Issue 2 – "href attributes should be URI" removed.


```
Date Version Sections affected Changes
```
Section 2.2.3 NASA-9: CEOS-BP- 101 - Remove Note 4 and add caveat to use
"best example".

Section 2.4 NASA-10: downgrade requirement CEOS-DG- 0 22B to
recommended. Note 9 removed and converted into explanatory
text.

Section 2.2.3 CWIC-1: CEOS-BP-004 updated with three compliance levels and
"Issue 5" removed.

Section 2.4 CWIC-3: CEOS-BP-015B updated. Added possibility of rel=icon"
and reword text about attribute unique combination.

2016 - 04 - 18 1.1 D4 Finalisation after WGISS-41 on 14th – 17 th March

Table of Content Updated

Section 2 Table 6 updated with renumbered requirements

Section 2.1 CEOS-DG- 005 renumbered as CEOS-BP-002B

Section 2.2.2 CEOS-DG- 006 renumbered as CEOS-BP-002C

Section 2.2.3 CEOS-BP- 101 renumbered as CEOS-BP-003B

Section 2.3 CEOS-DG-007B renumbered as CEOS-BP-005D

Section 2.3 CEOS-DG-014A renumbered as CEOS-BP-005E

Section 2.3 CEOS-DG-014B renumbered as CEOS-BP- 005 F

Section 2.4 CEOS-DG- 018 renumbered as CEOS-BP-011B

Section 2.4 CEOS-DG- 022 renumbered as CEOS-BP-012D

Section 2.4 CEOS-DG-022B renumbered as CEOS-BP-012E

Section 2.4 CEOS-DG- 021 renumbered as CEOS-BP-013B

Section 2.4 CEOS-DG- 020 renumbered as CEOS-BP-014E

2016 - 05 - 24 1.1 Comments received on version 1.1D4 resolved:

Section 2 CWIC-3: Typo in Table 6 corrected.


```
Date Version Sections affected Changes
```
Section 2.4: CEOS-
BP-011B

```
CWIC-2: equivalence of startIndex and startPage in href attribute
explained and startPage example added.
```
Section 3.2.4.1 CWIC-1: Info for IDN/CWIC updated from "O" to "G".

Section 3.2.8 CWIC-1: Info for CWIC updated to indicate support for startIndex.

2016 - 10 - 14 1.1.1 All OGC 13-026r5 replaced by OGC 13-026r8 which was approved
by OGC in August 2016.

Table 4 Editorial: prefixes corrected to start with lower case character
instead of uppercase.

Table 7 Media types aligned with section 8.2.2 of [OGC 13-026r8]

CEOS-BP-015B scheme attribute of media:category in example updated as per
[OGC 13-026r8].

2017 - 06 - 13 1.2 All Comments received on version 1.1.1 text resolved

CEOS-BP-004B New recommended requirement to specify indexOffset/pageOffset
values

CEOS-BP-014E Order of georss:box values specified.

CEOS-BP-009B New Optional requirements added about “Handling unsupported
request parameter”

2020 - 11 - 12 1.3 Section 2.2.
Changed section 2.2.3 to “Temporal range” and added CEOS-BP-
00 2D

CEOS-BP- 00 2D New recommended requirement for specifying temporal range

Section 2.2.4 Section 2.2.3 renumbered to Section 2.2.

Table 6 Updated Table 6 – List of Best Practices to include CEOS-BP-
00 2D

CEOS-BP- 003 Updated BP to include a new recommended attribute regarding

#### service level search query URL


## Table of Contents





- 1 INTRODUCTION
   - 1.1 PURPOSE OF THE DOCUMENT
   - 1.2 PROJECT MEMBERS
   - 1.3 TERMINOLOGY
      - Document terms and definitions
      - Terminology referring to data granularity
      - CWIC (CEOS WGISS Integrated Catalog)
      - CEOS IDN (CEOS International Directory Network)
      - FedEO (Federated Earth Observation Missions)
      - OGC (Open Geospatial Consortium)
   - 1.4 SPECIFICATIONS AND REFERENCES
      - 1.4.1 Applicable Documents
      - 1.4.2 Reference Documents
      - 1.4.3 Namespace prefix conventions
   - 1.5 WHAT IS OPENSEARCH?
      - Discovery
      - Description of Service
      - Search
      - Search Response
- 2 CEOS OPENSEARCH BEST PRACTICES
   - 2.1 TWO STEP SEARCH
      - CEOS-BP- 001 - Support of two step search [Recommended]
   - 2.2 OSDD
      - CEOS-BP- 002 - Support of OpenSearch Parameter Extension (Draft 2) [Recommended]
      - 2.2.1 Free Text Keyword
      - CEOS-BP-002B – Free text parameters [Recommended]
      - 2.2.2 Geometry
      - CEOS-BP-002C – Advertising supported geometry types [Requirement]
      - 2.2.3 Temporal range
      - CEOS-BP-002D – Specify temporal range [Recommended]
      - 2.2.4 Other requirements
      - CEOS-BP- 003 - rel attribute of the URL in OSDD [Recommended]
      - CEOS-BP-003B – Query element in OSDD [Recommended]
      - CEOS-BP- 004 - CEOS OpenSearch Best Practice identifier [Recommended]
   - 2.3 SEARCH REQUEST
      - CEOS-BP- 005 - Supported search parameters [Requirement]
      - EOS-BP-005B - Search with count=0 [Optional]
      - CEOS-BP-005C - Search with satellite name [Optional]
      - CEOS-BP-005D – Client identification [Recommended]
      - CEOS-BP-005E – Preserving URL template parameters [Requirement]
      - CEOS-BP-005F – Optional template parameters [Requirement]
      - CEOS-BP- 006 - Multi-words for searchTerms [Recommended]
      - CEOS-BP- 007 - Use of startIndex over startPage [Recommended]
      - CEOS-BP- 008 - Search with geo:name [Recommended]
      - CEOS-BP- 009 - Output encoding format in search URL [Optional]
      - CEOS-BP-009B – Handling unsupported request parameter [Optional]
   - 2.4 SEARCH RESPONSE
      - CEOS-BP- 010 - Output encoding format support [Requirement]
      - CEOS-BP- 011 - Support of dc:identifier in search response to allow for search-by-ID [Requirement]
      - CEOS-BP-011B – Result set navigation [Recommended]
      - CEOS-BP- 012 - Metadata representation in search response [Recommended]
      - CEOS-BP-012B – Provenance information [Optional]
      - CEOS-BP-012C – Reference to documentation [Recommended]
      - CEOS-BP-012D – Relation attribute values [Recommended]
      - CEOS-BP-012E – Link type attribute [Recommended]
      - CEOS-BP- 013 - atom:summary [Recommended]
      - CEOS-BP-013B – Dublin Core date [Recommended]
      - CEOS-BP- 014 - GeoRSS [Recommended]
      - CEOS-BP-014B – GeoRSS multi-polygon footprint [Recommended]
      - CEOS-BP-014C – GeoRSS multi-point footprint [Recommended]
      - CEOS-BP-014D – GeoRSS multi-line footprint [Recommended]
      - CEOS-BP-014E – Minimum-bounding rectangle [Optional]
      - CEOS-BP- 015 - Browse image [Recommended]
      - CEOS-BP-015B – Multiple browse images [Optional]
      - CEOS-BP- 016 - Data access [Recommended]
      - CEOS-BP-016B - Data access to multiple files [Optional]
      - CEOS-BP-016C - Data access for data download and order [Optional]
   - 2.5 EXCEPTIONS
      - CEOS-BP- 017 - Exception codes [Recommended]
   - 2.6 FUTURE DISCUSSIONS
- 3 CLOSER LOOK ON IMPLEMENTATIONS
   - 3.1 BASICS
      - 3.1.1 OSDD URL
         - 3.1.1.1 Collection Level
         - 3.1.1.2 Granule Level (examples)
      - 3.1.2 Search URL
         - 3.1.2.1 Collection Level
         - 3.1.2.2 Granule Level (examples)
      - 3.1.3 Documents
   - 3.2 REMARKABLE PRACTICES
      - 3.2.1 OSDD
         - 3.2.1.1 Support of parameter extension
         - 3.2.1.2 Support of Explain operation (SRU)
      - 3.2.2 Output encoding format in a search URL
      - 3.2.3 Support of 2 step search
      - 3.2.4 Search Parameters
         - 3.2.4.1 Supported Search Parameters
      - 3.2.5 Supported output format
      - 3.2.6 Output schema support
      - 3.2.7 Free Keyword notation (searchTerms)
      - 3.2. 8 Pagination
      - 3.2.9 Search Result
         - 3.2.9.1 Browse
         - 3.2.9.2 Thumbnail
         - 3.2.9.3 Mask Image
         - 3.2.9.4 Metadata
         - 3.2.9.5 Documentation
         - 3.2.9.6 Data
      - 3.2.10 Error Handling
         - 3.2.10.1 Exception Status Code (4xx, 5xx)
- ANNEX A: LIST OF OPENSEARCH ENDPOINTS
- ANNEX B: EXAMPLES
   - B1. OSDD (COLLECTION LEVEL)
      - IDN/CWIC
      - FedEO
      - CNES
- ANNEX C: SEARCH-ENGINE-FRIENDLY CATALOG
   - C1. USING MICRODATA
   - C2. USING JSON-LD
- Figure 1: CEOS OpenSearch List of Figures
- Figure 2: EO satellite data granularity
- Figure 3: OpenSearch client-server interaction
- Figure 4: 2 Step Search Diagram
- Figure 5: Referencing Metadata and Documentation
- Table 1 – Terminology mapping for collections and granules List of Tables
- Table 2 – List of applicable specifications
- Table 3 – List of reference documents
- Table 4 – List of namespace prefix mappings
- Table 5 – List of additional namespace prefix mappings
- Table 6 – List of best practices
- Table 7 – MIME types for metadata formats
- Table 8 – Relation attribute values


## 1 INTRODUCTION

This document provides server implementation best practices for EO OpenSearch search
services that allow for standardized and harmonized access to metadata and data for CEOS
agencies, including CWIC and FedEO.

```
Figure 1 : CEOS OpenSearch
```
### 1.1 PURPOSE OF THE DOCUMENT

The purpose of this document is to achieve the following

```
● Promote the use of the OpenSearch standard as a means of data discovery for Earth Data
providers
● Define the expectations and requirements of candidate OpenSearch implementations
● Remove ambiguity in implementation where possible
● Facilitate the aggregation of results between disparate Earth Data providers via
OpenSearch common standards
● Allow for clients to access search engines via an OpenSearch Description Document
(OSDD) with no a priori knowledge of the interface
● Facilitate smooth integration between related OpenSearch implementations, such as a
dataset resource collection that refers to granule resource collections from another
provider
```

### 1.2 PROJECT MEMBERS

This document has been developed by the CEOS OpenSearch Project Team of the Committee
on Earth Observation Satellites (CEOS) Working Group on Information Systems and Services
(WGISS).

The project team members are listed below.

```
JAXA Yoshiyuki Kudo
Satoko Miura
CNES Jérôme Gasperi
Richard Moreno
ESA Pier Giorgio Marchetti
Giuseppe Troina
Yves Coene
Philippe Mougnaud
Andrea Della Vecchia
NASA Andrew Mitchell
Yonsook Enloe
Doug Newman
Christopher Lynnes
NOAA Martin Yapur
Kenneth McDonald
CCMEO Patrick King
```
### 1.3 TERMINOLOGY

#### Document terms and definitions

The word "shall" (not "must") is the verb form used to indicate a requirement to be strictly followed
to conform to this standard.

#### Terminology referring to data granularity

Earth observation (EO) satellite data usually falls into two types in the context of granularity -
collection and granule.

**_Granule_**


A granule is the finest granularity of data that can be independently managed. A granule usually
matches the individual file of EO satellite data.

**_Collection_**

A collection is an aggregation of granules sharing the same product specification. A collection
typically corresponds to the series of products derived from data acquired by a sensor on board
a satellite and having the same mode of operation.

## Figure 2: EO satellite data granularity

Table 1 shows how agencies use different terminology when referring to these two granularities.

```
Terminology
(Fig 2)
```
```
ISO terms
(i.e. ISO19115-2)
```
```
Agency dependent terminology
```
```
collection dataset series collection (CNES, NASA)
dataset (JAXA)
dataset series (ESA)
product (JAXA)
```
```
granule dataset dataset (ESA)
granule (NASA)
product (ESA, CNES)
scene (JAXA)
```
```
Table 1 – Terminology mapping for collections and granules
```

```
Since the agencies share the common notion of this two level hierarchy, the difference does not
adversely affect the harmonization effort of this activity.
The terminology “collection” and “granule” - are used throughout this document.
```
#### CWIC (CEOS WGISS Integrated Catalog)

```
The Working Group on Information Systems and Services is a subsidiary body supporting the
Committee on Earth Observing Satellites (CEOS). WGISS promotes collaboration in the
development of systems and services that manage and supply these observatory data.
```
#### CEOS IDN (CEOS International Directory Network)

```
An international effort developed to assist researchers in locating information on available
collections and services. The directory is sponsored as a service to the Earth science community.
```
#### FedEO (Federated Earth Observation Missions)

```
FedEO provides interoperable access, following ISO/OGC interface guidelines, to Earth
Observation metadata.
```
#### OGC (Open Geospatial Consortium)

```
OGC is an international industry consortium of private companies, government agencies and
universities participating in a consensus process to develop publicly available interface standards.
```
### 1.4 SPECIFICATIONS AND REFERENCES

#### 1.4.1 Applicable Documents

```
OpenSearch implementations within CEOS shall comply with a number of specifications.
Conformance to these specifications helps achieve consistent level of implementation across
CEOS agencies and systems. Those specifications are enumerated in Table 2
```
```
Acronym Title Reference Issue
```
[OpenSearch] OpenSearch Specification,
1.1, Draft 5

```
http://www.opensearch.org/Specification
s/OpenSearch/1.1/Draft_
```
```
1.1 Draft 5
```
###### [OGC 10-

032r8]

```
OpenSearch Geo and Time
extensions
```
```
https://portal.opengeospatial.org/files/?ar
tifact_id=
```
```
r8, 14/04/
```

###### [OGC 13-

026r 8 ]

```
OpenSearch Extension for
Earth Observation Products
```
```
http://docs.opengeospatial.org/is/13-
026r8/13-026r8.html
```
```
r 8 , 06 /0 7 /201 6.
```
[Param] OpenSearch Parameter
Extension – 1.0 Draft 2

```
http://www.opensearch.org/Specification
s/OpenSearch/Extensions/Parameter/1.
0/Draft_
```
```
1.0 Draft 2
```
[Relevance] OpenSearch Relevance
Extension

```
http://www.opensearch.org/Specification
s/OpenSearch/Extensions/Relevance/1.
0/Draft_
```
```
1.0 Draft 1
```
[Atom] Atom syndication format IETF RFC4287,
[http://tools.ietf.org/html/rfc](http://tools.ietf.org/html/rfc)

## Table 2 – List of applicable specifications

```
The Geo and Time extensions [OGC 10-032r8] specify a series of query parameters that can be
used to geographically and temporally constrain search results. Parameters include: bounding
box, geometry, and start/end of a temporal extent. It also defines a set of response elements to
be used to express geographical and temporal context in the search results.
The extension for EO Products [OGC 13-026r 8 ] defines query parameters that allow the filtering
of search results with the fields that are unique to EO products, e.g. platform (satellite), sensor,
processing center, etc. The OpenSearch query parameters defined in this document are aligned
with O&M EO Profile [OGC 10-157r4] that describes EO products metadata.
The OpenSearch Parameter Extension [Param] sets rules to describe valid range and entries for
query parameters in OSDD. This extension is not an OGC standard.
Reading these specifications may require understanding of the following related specification as
well.
● O&M EOP Profile [OGC 10-157r4]
```
```
The O&M (Observations and Measurements) EO Profile [OGC 10-157r4] defines the metadata
model required to describe metadata of Earth Observation (EO) data. The underlying O&M
standard (ISO 19156 and OGC 10- 025 r1) defines a conceptual schema encoding for
observations, and for features involved in sampling when making observations.
```
#### 1.4.2 Reference Documents

```
Reference documentations are as follows.
```

```
Acronym Title Reference Issue
```
[OGC 10-
157r4]

```
Earth Observation Profile
of Observations and
Measurements
```
```
http://docs.opengeospatial.org/is/10-
157r4/10-157r4.html
```
```
r4.
```
[FedEO-CPG] FedEO Client Partner
Guide

###### PDGS-FEDEO-SPB-ICD- 15 - 1174 ,

```
https://wiki.services.eoportal.org/tiki-
download_wiki_attachment.php?attId=
065
```
```
Issue 1.1,
22/12/
```
[CWIC-OBP] CWIC OpenSearch Best
Practices

```
https://wiki.earthdata.nasa.gov/downloa
d/attachments/28541363/CWIC%20Ope
n%20Search%20Best%20Practices.doc
x?version=3&modificationDate=
6508686&api=v
```
[CWIC-ODPG] CWIC OpenSearch Data
Partner Guide

```
http://ceos.org/document_management/
Working_Groups/WGISS/Projects/CWIC
/OpenSearch/CWIC_OpenSearch_Data
```
- Partner-Guide.doc

[CWIC-OCPG] CWIC OpenSearch Client
Partner Guide

```
http://ceos.org/document_management/
Working_Groups/WGISS/Projects/CWIC
/OpenSearch/CWIC_OpenSearch_Clien
t-Guide.doc
```
[Referrer] OpenSearch Referrer
Extension

```
http://www.opensearch.org/Specification
s/OpenSearch/Extensions/Referrer/1.
```
```
Issue 1.0 Draft 1
```
[RFC6906] RFC 6906, The "profile"
Link Relation Type

```
https://tools.ietf.org/html/rfc
```
[INSPIRE] Technical Guidance for
the implementation of
INSPIRE Download
Services.

```
http://inspire.ec.europa.eu/documents/N
etwork_Services/Technical_Guidance_
Download_Services_v3.1.pdf
```
```
Issue 3.1,
09/08/
```
[schema.org] Getting started with
schema.org

```
https://schema.org/docs/gs.html
```
## Table 3 – List of reference documents

#### 1.4.3 Namespace prefix conventions

```
Namespace prefixes used in the requirements section and corresponding examples in current
document map to the namespaces according to the mappings defined in [OGC 10-032r8] and
[OGC 13-026r 8 ]. The prefixes are not normative and are merely chosen for convenience; they
```

may appear in examples without being formally declared, and have no semantic significance. The
namespaces to which the prefixes correspond are normative, however.

```
Prefix Namespace URI Specification
atom http://www.w3.org/2005/Atom The Atom Syndication Format
Common 1.0 – RFC- 4287
dc http://purl.org/dc/elements/1.1/ Namespace Policy for the DCMIa
eo http://a9.com/-
/opensearch/extensions/eo/1.0/
```
```
OpenSearch Extension for EO
```
```
geo http://a9.com/-
/opensearch/extensions/geo/1.0/
```
```
OpenSearch Geo Extension
```
```
georss http://www.georss.org/georss GeoRSS Specification
gml http://www.opengis.net/gml GML specification
os http://a9.com/-
/spec/opensearch/1.1/
```
```
OpenSearch 1.1 Specification
```
```
time http://a9.com/-
/opensearch/extensions/time/1.0/
```
```
OpenSearch Time Extension
```
```
a See <http://dublincore.org/documents/dcmi-namespace/>.
```
## Table 4 – List of namespace prefix mappings

The following namespace prefixes are used as well.

```
Prefix Namespace URI Specification
param http://a9.com/-
/spec/opensearch/extensions/para
meters/1.0/
```
```
[Param]
```
```
referrer http://www.opensearch.org/Specifi
cations/OpenSearch/Extensions/R
eferrer/1.
```
```
[Referrer]
```
## Table 5 – List of additional namespace prefix mappings


### 1.5 WHAT IS OPENSEARCH?

OpenSearch is a collection of simple formats for the sharing of search results.

The OpenSearch specification defines a descriptor document (OSDD) format that can be used to
describe a search engine so that it can be used by search client applications.

The OpenSearch response elements can be used to extend existing syndication formats, such
as RSS and Atom, with the extra metadata needed to return search results. Figure 3 shows a
diagram of client and server interaction of OpenSearch.

## Figure 3: OpenSearch client-server interaction


#### Discovery

A client can learn of support for an OpenSearch service by looking at the html header of a server’s
web page. A link element with a rel attribute equal to “search” shows the location of the OSDD in
the value of “href” attribute as shown below.

```
<html>
<head>
<link rel="search"
type="application/opensearchdescription+xml"
title="Foo Search Engine“
href="http://foo.ceos.org/xxx/description.xml"> ... URL to OSDD
```
#### Description of Service

The client uses the OSDD to learn about the OpenSearch API of the server. The OSDD contains
parameterized URL templates that indicate how the search client should make search requests.
The URL template can be repeated for each combination of relation and search result output
format that the service supports.

```
<OpenSearchDescription
xmlns="http://a9.com/-/spec/opensearch/1.1/"
xmlns:os="http://a9.com/-/spec/opensearch/1.1/"
xmlns:atom="http://www.w3.org/2005/Atom"
xmlns:time="http://a9.com/-/opensearch/extensions/time/1.0/"
xmlns:geo="http://a9.com/-/opensearch/extensions/geo/1.0/"
xmlns:eo="http://a9.com/-/opensearch/extensions/eo/1.0/"
xmlns:param="http://a9.com/-/spec/opensearch/extensions/parameters/1.0/"
xmlns:dc="http://purl.org/dc/elements/1.1/">
...
<description>This service is ...</description>
...
<Url type="application/atom+xml" rel=”results”
template="http://...search/atom?q={searchTerms}&ts={time:start}&te={time:end
}"/>
<Query role="example" searchTerms=”water"
```

```
time:start="2012- 04 - 01"
time:end="2012- 06 - 30”/>
```
```
</OpenSearchDescription>
```
#### Search

A client constructs the request URL by replacing each {xxx} in the URL template with a value. It
then sends that request to the server using HTTP GET. For example:

```
<Url type="text/html"
template="http://...search?q={searchTerms}&ts={time:start}&te={time:end?}/>
```
can be used to construct a url as follows,

```
http://...search?q=water&ts=2012- 04 - 01&te=2012- 06 - 30
```
Optional template parameters are described with a "?" such as {xxx?} and can be left empty or
removed.

#### Search Response

OpenSearch doesn’t define or require any specific encoding format for the search response.
Instead, it defines a set of search-related metadata elements which can be inserted into existing
encoding formats. Typically, list-based XML syndication formats - such as RSS 2.0 and Atom 1.0

- are used.

The OpenSearch response elements include:

```
totalResults: number of total results
startIndex: index number corresponding to the first entry item returned
itemsPerPage: number of results returned
Query: search query to get the same search response
```
Below is an example of a search response in Atom, to the free keyword search “water”.

Notice the three OpenSearch elements appear inside the feed element.

```
<feed xmlns=http://www.w3.org/2005/Atom
xmlns:os=”http://a9.com/-/spec/opensearch/1.1/”>
```

<title>OpenSearch response to” water”</title>

<id>http://example.ceos.org/search?q=water</id>

<author><name>Taro Yamada</name></author>

**<os:totalResults>231</os:totalResults>**

**<os:startIndex>51</os:startIndex>**

**<os:itemsPerPage>50</os:itemsPerPage>**

<os:Query role=”request” searchTerms=”water” time:start=”2012- 04 - 01”
time:end=”2012- 06 - 30” />

<entry>

<title>Water Resource Management Guideline</title>

<id>http://aaa.ceos.org/waterResource/guideline/v001</id>

<link href=”http://aaa.ceos.org/waterResource/guideline/v001“/>

</entry>

<entry>

...

</entry>

<entry>

...

</entry>

<entry>

...

</entry>

</feed>


## 2 CEOS OPENSEARCH BEST PRACTICES

```
This chapter goes through best practices that have been derived from OpenSearch server
implementations at CEOS agencies and projects.
The list of best practices are summarized in the table below.
```
```
ID Category Title Requirement
Level
```
CEOS-BP- 001 Two step search Support of two step search Recommended

CEOS-BP- 002 OSDD Support of OpenSearch Parameter
Extension (Draft 2)

```
Recommended
```
CEOS-BP-002B Free Text Keyword Free text parameters Recommended

CEOS-BP-002C Geometry Advertising supported geometry types Requirement

CEOS-BP-002D Temporal range Specify temporal range Recommended

CEOS-BP- 003 rel attribute of the URL in OSDD Recommended

CEOS-BP-003B Query element in OSDD Recommended

CEOS-BP- 004 BP Compliance
Declaration

```
CEOS OpenSearch Best Practice
identifier
```
```
Recommended
```
CEOS-BP-004B indexOffset/pageOffset attribute of the
URL in OSDD [Recommended]

```
Recommended
```
CEOS-BP- 005 Search Request Supported search parameters Requirement

CEOS-BP-005B Search with count=0 Optional

CEOS-BP-005C Search with satellite name Optional

CEOS-BP-005D Client identification Recommended

CEOS-BP-005E Preserving URL template parameters Requirement

CEOS-BP-005F Optional template parameters Requirement

CEOS-BP- 006 Multi-words for searchTerms Recommended

CEOS-BP- 007 Use of startIndex over startPage Recommended

CEOS-BP- 008 Search with geo:name Recommended

CEOS-BP- 009 Output encoding format in search URL Optional

CEOS-BP-009B Handling unsupported request parameter Optional

CEOS-BP- 010 Search Response Output encoding format support (atom) Requirement


CEOS-BP- 011 Support of dc:identifier in search response
to allow for search-by-ID

```
Requirement
```
CEOS-BP-011B Result set navigation Recommended

CEOS-BP- 012 Metadata representation in search
response

```
Recommended
```
CEOS-BP-012B Provenance information Optional

CEOS-BP-012C Reference to documentation Recommended

CEOS-BP-012D Relation attribute values Recommended

CEOS-BP-012E Link type attribute Recommended

CEOS-BP- 013 atom:summary Recommended

CEOS-BP-013B Dublin Core date Recommended

CEOS-BP- 014 GeoRSS Recommended

CEOS-BP-014B GeoRSS multi-polygon footprint Recommended

CEOS-BP-014C GeoRSS multi-point footprint Recommended

CEOS-BP-014D GeoRSS multi-line footprint Recommended

CEOS-BP-014E Minimum-bounding rectangle Optional

CEOS-BP- 015 Browse Image Recommended

CEOS-BP-015B Multiple browse images Optional

CEOS-BP- 016 Data access Recommended

CEOS-BP-016B (^) Data access to multiple files Optional
CEOS-BP- 017 Exceptions Exception codes Recommended

## Table 6 – List of best practices

### 2.1 TWO STEP SEARCH

#### CEOS-BP- 001 - Support of two step search [Recommended]

```
One serious hurdle to overcome in searching for data is the great number of data items to account
for in responses, as well as the expected number of successful “hits” for a query. In ordinary web
searches, the searcher is usually looking for a small number of web pages or documents.
Relevance ranking typically does a good job of presenting these successful hits near the top of
the returned list, followed by single point-and-click retrievals. However, when searching for Earth
science data covering large time periods or spatial areas, a user will often specify a set of
```

constraints to find an appropriate data collection together with space-time criteria for files within
that data collection. Often, the precision of the data collections returned for the search is low, with
many spurious hits. However, the space-time precision of the files is often quite high: that is, the
user truly wants to use all the data files of a desirable data collection set that fall within the space-
time region of interest. Thus, searching for all data satisfying both dataset content and space-time
region at the same time can produce a great many spurious hits, i.e., all the files for data
collections that are _not_ desired.

The 2-step search consists of a collection level search and the subsequent granule level search
(or file-level search) as Figure 4 shows.

## Figure 4: 2 Step Search Diagram

In order to provide a well-defined search path from a collection of interest to granules associated
with that collection, we advocate the use of two-step searching leveraging the following:

1. Link elements of relation search (rel=’search’) within collection entries. These links point
    to a granule-level OSDD specific to the collection entry


2. Granule level OSDDs that can be tailored to a specific collection

The key requirement of this approach is an identifier that both the collection and granule resource
understand as uniquely describing the collection.

The advantages of this approach are as follows:

```
● A client can navigate from dataset to granule with only an understanding of the
OpenSearch specification
● A server can link between datasets and granules using any set of unique identifiers they
choose. For example, identifier plus version
● It allows the client to determine what search parameters are available to the user at the
granule level using the OSDD
```
For example, a collection level search result looks something like this:

```
<feed>
...
<entry>
<title>Collection A</title>
<link rel=”search” type=”application/opensearchdescription+xml”
href=”http://foo.ceos.org/search/osdd.xml?collectionId=collection_a” />
...
</entry>
```
```
<entry>
<title>Collection B</title>
<link rel=”search” type=”application/opensearchdescription+xml”
href=”http://foo.ceos.org/search/osdd.xml?collectionId=collection_b” />
...
</entry>
...
</feed>
```
The value of href attribute of the link element with the rel attribute equal to “search”, in this case,
_[http://foo.ceos.org/search/osdd.xml](http://foo.ceos.org/search/osdd.xml)_ ?collectionId=collection_a, for the collection A, is the URL to


the OSDD specific to collection A.

Looking for the OSDD in each result entry, a client can be directed to URL template(s) usable for
the collection’s granule level search.

The URL template for the granule search contains a search parameter dedicated to the specific
collection, which is hard-coded and not meant to be replaced by the client when constructing a
query.

E.g.

```
<Url type="application/atom+xml" rel=”results”
template="http://../search/collection.atom?collectionId=collection_a&q={sear
chTerms}&ts={time:start}&te={time:end}&bbox={geo:box}>
```
Notice “collection_a” is not enclosed in braces.

### 2.2 OSDD

#### CEOS-BP- 002 - Support of OpenSearch Parameter Extension (Draft 2) [Recommended]

The Parameter Extension explicitly advertises the valid values and ranges of search parameters.
Thus, it reduces the risk of ambiguity and error.

CEOS recommends the support of the OpenSearch Parameter Extension with the following
constraints:

```
1) “value” attributes should always be set to facilitate the client task (i.e. avoid to parse the
<Url> templates)
2) other attributes (i.e. “minimum”, “maximum”) and options elements should be provided
only when it makes sense
3) In case of inconsistency^1 between the Parameter extension annotations and the <Url>
template in the OSDD, the <Url> template prevails.
```
(^1) Examples of "inconsistencies" are when the <Url> template includes a parameter for which no
<param:Parameter> is specified or when a search parameter is mandatory or optional in the
<Url> template, but the corresponding <param:Parameter> element does not have a
corresponding "minimum" or "maximum" attribute or such attributes with contradicting values.


#### 2.2.1 Free Text Keyword

#### CEOS-BP-002B – Free text parameters [Recommended]

For conveying the server’s support of free text keyword searches (e.g. searchTerms), the server
should declare adherence to a specific, existing standard within the parameter definition using
the Parameter Extension and an Atom link referring to a profile [RFC6906].

See below for an example.

```
<param:Parameter name="q" value=”{searchTerms}”>
<atom:link rel="profile"
href=”http://lucene.apache.org/core/2_9_4/queryparsersyntax.html”
title="This parameter follows the Lucene free text search implementations"
/>
</param:Parameter>
```
This tells a client to refer to the href link for the notation rule of free text keyword searches (q) the
server complies with. In this case, Apache Lucene is used.

A similar convention can be used by an OpenSearch server to advertise its support for relational
modifiers (e.g. wild cards such as "*" or "?"). The OpenSearch specifications (in contrast to the
more elaborate OASIS SearchRetrieve specifications^2 ), do not specify the expected behavior of
a server in such cases. To allow clients to know whether a string passed as a parameter value
can contain wild cards or relational operators, the Parameter extension can be used.

In the example below, the server advertises its support for the "masked" relation modifier defined
at the URL provided. This allows a client to pass eo:platform parameters with wild cards such as
"SPOT*" and receive hits for SPOT-4, SPOT-5.

```
<param:Parameter name="platform" value=”{eo:platform}”>
<atom:link rel="profile" href=”info:srw/cql-context-set/1/cql-
v2.0#masked” title="This parameter supports wild cards" />
</param:Parameter>
```
In the example below, the server explicitly states that is does not support the "masked" relation
modifier (i.e. wildcards) for the eo:platform search parameter.

(^2) OASIS SearchRetrieve specifications (available at [http://docs.oasis-open.org/search-](http://docs.oasis-open.org/search-)
ws/searchRetrieve/v1.0/os/part5-cql/searchRetrieve-v1.0-os-part5-cql.html) use the notion of context-sets
defining different kinds of relation modifiers. An example context set with useful conventions is
info:srw/cql-context-set/1/cql-v2. 0 which defines the "masked" and "unmasked" modifiers.


```
<param:Parameter name="platform" value=”{eo:platform}”>
<atom:link rel="profile" href=”info:srw/cql-context-set/1/cql-
v2.0#unmasked” title="This parameter does not support wild cards" />
</param:Parameter>
```
#### 2.2.2 Geometry

For conveying the server’s support condition of a geometry (geo:geometry) parameter, the server
should declare adherence to a specific, existing standard within the parameter definition using
the Parameter Extension.

#### CEOS-BP-002C – Advertising supported geometry types [Requirement]

An OpenSearch server with {geo:geometry} search capabilities shall advertise supported
geometry types with the Parameter extension and via Atom links referring to geometry type
profiles.

```
<param:Parameter name="geometry" value=”{geo:geometry}”>
<atom:link rel="profile" href=”http://www.opengis.net/wkt/LINESTRING”
title="This service accepts WKT LineStrings"/>
<atom:link rel="profile" href=”http://www.opengis.net/wkt/POINT”
title="This service accepts WKT Point"/>
<atom:link rel="profile" href=”http://www.opengis.net/wkt/POLYGON”
title="This service accepts WKT Polygons"/>
<atom:link rel="profile"
href=”http://www.opengis.net/wkt/MULTILINESTRING” title="This service
accepts WKT Multi-LineStrings"/>
<atom:link rel="profile" href=”http://www.opengis.net/wkt/MULTIPOINT”
title="This service accepts WKT Multi-Point"/>
<atom:link rel="profile" href=”http://www.opengis.net/wkt/MULTIPOLYGON”
title="This service accepts WKT Multi-Polygons"/>
</param:Parameter>
```
This explains that a server supports point, line and polygon among other geometry types, and the
convention can be found in the value of href.


#### 2.2.3 Temporal range

An OpenSearch API implementation may need to convey a maximum range for a temporal
search filter. It can specify that constraint in the OSDD using the parameter element using one
of the {time:start and time:end} parameters : the option to define a relativeTo and maxPeriod
attribute to one of these parameters allows the server to communicate to an OpenSearch client
a maximum termporal range. The range is defined such that the relativeTo attribute will name
the other corresponding temporal parameter or vice versa, and such that the maxPeriod
attribute is defined as a string value consistent with ISO_8601 duration
(https://www.iso.org/standard/40874.html). This construct is only useful when the two
parameters in question (the parameter that defines maxPeriod and the parameter it is
relativeTo) describe points in time as per the OpenSearch time extension.

#### CEOS-BP-002D – Specify temporal range [Recommended]

```
<Parameter xmlns:time="http://a9.com/-/opensearch/extensions/time/1.0/"
name="start"
value="{time:start}"
pattern="[0-9]{4}-[0-9]{2}-[0-9]{2}T[0-9]{2}:[0-9]{2}:[0-9]{2}(\.[0-
9]+)?(Z|[\+\-][0-9]{2}:[0-9]{2})"
/>
```
```
<Parameter xmlns:time="http://a9.com/-/opensearch/extensions/time/1.0/"
name="end"
value="{time:end}"
maxPeriod="P6M"
relativeTo="{time:start}"
pattern="[0-9]{4}-[0-9]{2}-[0-9]{2}T[0-9]{2}:[0-9]{2}:[0-9]{2}(\.[0-
9]+)?(Z|[\+\-][0-9]{2}:[0-9]{2})" />
```
#### 2.2.4 Other requirements

#### CEOS-BP- 003 - rel attribute of the URL in OSDD [Recommended]

CEOS recommends the use of rel attribute of Url element in OSDD in the following manner^3.

```
● rel=”collection” to advertise collection level search query URL
```
(^3) As per [http://www.ietf.org/rfc/rfc6573.txt.](http://www.ietf.org/rfc/rfc6573.txt.)


```
● rel=”results” (default) to mean granule level search query URL
● rel=”service” to mean service level search query URL
```
If rel attribute is not specified, it is assumed that its value is “results”.

#### CEOS-BP-003B – Query element in OSDD [Recommended]

For testability purposes, CEOS recommends that an OSDD should at least contain one Query
element of role ‘example’ when presenting an Atom response which returns representative
results.

In case the OSDD contains multiple <Url> templates or <Url> templates for both collection and
granule level search, the Query element shall refer to a collection level search with Atom
response.

In case the OSDD contains only <Url> templates for collection level search, the Query element
shall refer to a collection level search with Atom response. In case the OSDD contains only <Url>
templates for granule level search, the Query element shall refer to a granule level search with
Atom response.

Implementers are recommended to include a search query example which will return a response
with the largest possible set of features, e.g. quick look images, access to data etc.

#### CEOS-BP- 004 - CEOS OpenSearch Best Practice identifier [Recommended]

CEOS recommends adding a string (as defined below) indicating the server conformance level in
the <Tags> element of the OSDD. This can be used by an OpenSearch client to detect which
requirements level the server conforms to.

- CEOS-OS-BP-V1.1/L1: Compliant with all server requirements labeled as [Requirement]
    in Table 6 of the current specification.
- CEOS-OS-BP-V1.1/L2: Compliant with all server requirements labeled as [Requirement]
    and [Recommended] in Table 6 of the current specification.
- CEOS-OS-BP-V1.1/L3: Compliant with all server requirements labeled as [Requirement],
    [Recommended] and [Optional] in Table 6 of the current specification.

#### CEOS-BP- 00 4B - indexOffset/pageOffset attribute of the URL in OSDD

#### [Recommended]

CEOS recommends the use of indexOffset/pageOffset attribute of URL element in OSDD in the
following manner:

- indexOffset=”0/1” to advertise the offset of startIndex
- pageOffset=”0/1” to advertise the offset of startPage


### 2.3 SEARCH REQUEST

#### CEOS-BP- 005 - Supported search parameters [Requirement]

OpenSearch Geo and Time extension [OGC 10-032r8] gives a list of fundamental search
parameters sufficient to constrain a search by time and space. The OpenSearch Extension for
EO Products [OGC 13-026r 8 ] complements it with optional parameters specific to EO data.

From these specifications, an OpenSearch CEOS implementation shall support the following
minimum set of search parameters for both “collection” and “granule” levels:

```
● count
● searchTerms (optional for “granule level” search)
● startIndex or startPage
● geo:uid
● geo:box
● time:start
● time:end
```
Note regarding the {geo:geometry} parameter : the option of polygon in the geometry parameter
raises practical issues with HTTP GET requests. Polygons can contain an arbitrary number of
vertices which, when expressed as a constraint in a HTTP GET request, may exceed the URL
length limits of some HTTP servers. This would suggest that HTTP POST should also be
supported in some instances. However, this is not recommended since it would 1) add an
unwanted degree of complexity to the specification and 2) using POST to request data would
violate a RESTful implementation - POST should be used to “create” a resource on the server not
to get a “resource”. As a consequence CEOS recommends the use of HTTP GET only for search
request with appropriate HTTP error message (i.e. HTTP 414) when URI is too long.

#### EOS-BP-005B - Search with count=0 [Optional]

The count parameter shall support non-negative values according to [OpenSearch]. OpenSearch
servers shall return a search response without Atom entries when count=0 is specified the
request, but preserve other information in the search response (Atom feed) such as
os:totalResults.

#### CEOS-BP-005C - Search with satellite name [Optional]

OpenSearch servers supporting collection (or granule) searches based on satellite name are
recommended to pass the satellite name via the {eo:platform} search parameter defined in [OGC
13 - 026r 8 ].

To avoid name mismatches (e.g. "SPOT 5" versus "SPOT5" versus "SPOT-5" or "SEASAT 1"
versus "Seasat"), implementations are encouraged to support names as defined in the SKOS


description of satellite and missions is in the Global Change Master Directory (See skos:prefLabel
of the platform as defined in [http://gcmdservices.gsfc.nasa.gov/static/kms/platforms/platforms.rdf).](http://gcmdservices.gsfc.nasa.gov/static/kms/platforms/platforms.rdf).)

#### CEOS-BP-005D – Client identification [Recommended]

OpenSearch servers wishing to identify clients via a client-supplied identifier (e.g. for purposes of
server-side metrics generation) shall request this information through the {referrer:source}^4
OpenSearch parameter or a non-variable search parameter in the URL template.

```
<Url type="application/atom+xml"
template="http://...search?q={searchTerms}&clientId={referrer:source}/>
```
Consequently, if a client abides by the contract of the URL template in the example above, all
queries to the API will contain the clientId parameter.

#### CEOS-BP-005E – Preserving URL template parameters [Requirement]

OpenSearch clients shall preserve any non-variable search parameters given to them by the URL
template in the OSDD for building a search request.

The actual search request shall correspond to the URL template retrieved from the OSDD with
mandatory OpenSearch parameters replaced by an actual value and optional parameters (i.e.
with "?") replaced by an empty string or the key/value pairs of optional parameters removed.

For example: considering the URL template below, with a non-variable parameters (collectionId
and clientId) and optional parameter {time:end?}.

```
<Url type="application/atom+xml"
template="http://...search?
collectionId=collection_a&q={searchTerms}&ts={time:start}&te={time:end?}&cli
entId=foo/>
```
Applying the above URL template, clients can make the following valid request:

```
http://...search?collectionId=collection_a&q=water&ts=2012- 04 - 01&te=2012- 06 -
30&clientId=foo
```
#### CEOS-BP-005F – Optional template parameters [Requirement]

OpenSearch servers shall treat the following as equivalent,

(^4) [http://www.opensearch.org/Specifications/OpenSearch/Extensions/Referrer/1.0](http://www.opensearch.org/Specifications/OpenSearch/Extensions/Referrer/1.0)


- Values of optional parameter that are empty (i.e. the key is present but the value is absent)
- key/value pairs of optional parameters that are removed (i.e. both key and value are
    absent).

E.g. The optional parameter {time:end?} can be left empty or the actual parameter "te=" can be
removed also.

For example, with optional parameter left empty the request would be thus,

```
http://...search?collectionId=collection_a&q=water&ts=2012- 04 -
01&te=&clientId=foo
```
With optional parameter removed.

```
http://...search?collectionId=collection_a&q=water&ts=2012- 04 -
01 &clientId=foo
```
In all cases, the non-variable part of the URL template (i.e.
[http://...search?collectionId=collection_a&clientId=foo)](http://...search?collectionId=collection_a&clientId=foo)) is present.

Note: The use of a mandatory clientId parameter is a typical use case for such non-variable URL
component.

#### CEOS-BP- 006 - Multi-words for searchTerms [Recommended]

OpenSearch specifications do not define or suggest any convention for the notation of multiple
keywords used in searchTerms parameter. However, consistent notation rules for expressing a
phrase and logical operators are important from a user’s (i.e. client’s) perspective.

For example, what is the right way to make a phrasal search for “air temperature”? One can
imagine a client could be bewildered with an enormous results hits when the query was interpreted
as “air OR temperature” at the server, for example.

The parameter extension can partially resolve this by advertising the rules of searchTerms
construction in the OSDD. (See section 2.2.1 for details)

Without the parameter extension, the following interpretation is the default.

```
● white space-delimited words not enclosed in double quote “ “ represents logical AND
(e.g.) q=air temperature : air AND temperature
```
```
● whitespace delimited words enclosed in double quote “ “ represents phrasal search
(e.g.) q="air temperature" : “air temperature” in one phrase
```

```
Note the examples are not URL encoded.
```
#### CEOS-BP- 007 - Use of startIndex over startPage [Recommended]

The OpenSearch specification allows the use of either startIndex and startPage for pagination
control.

We recommend using startIndex over startPage. The reason for this is that startPage is not
defined in the OpenSearch specification as a valid response element whereas startIndex is.
Although this is probably an oversight, adherence to specification is essential in Best Practices.

startIndex should take precedence when both startPage and startIndex are supplied in a search
request by a client.

#### CEOS-BP- 008 - Search with geo:name [Recommended]

We recommend supporting geo:name and optionally, geo:radius. If geo:name is supported but
geo:radius is not, it is recommended that the search be interpreted as a point search.

The geo:name can be resolved by Gazetteer. The most common one used by CEOS agencies is
geonames.org (http://api.geonames.org/searchJSON).

When a server supports geo:radius the default value should be specified in the OSDD within the
“title” attribute of the corresponding Parameter element (example below)

```
<param:Parameter name="radius" value="{geo:radius}" title="Expressed in
meters. Default value is 10000"/>
```
#### CEOS-BP- 009 - Output encoding format in search URL [Optional]

CEOS recommends the specification of encoding format by resource extension in the search
URL. While the "type" attribute of the URL element identifies the encoding format supported by a
service, specification within the url itself allows for greater usability (bookmarking for example)

```
http://foo.ceos.org/search/collection .atom ?collectionId=Landsat_8&amp;startP
age=1&amp;count=10&amp;timeStart=&amp;timeEnd=&amp;geoBox=
```
Implementations can apply the resource extension using a different separator as well. The use of
"." is not normative. The example below is using the resource extension mechanism, with a "/" as
separator.

```
http://foo.ceos.org/ATS_NR__2P /atom ?count=10
```

#### CEOS-BP-009B – Handling unsupported request parameter [Optional]

To find relevant responses and alleviate some frustration for clients who may not always check
the OSDD before formulating a query, a server or gateway shall ignore the unsupported request
parameters and process the query as if they were not present. The server, to report about the
considered search parameters, should return an <os:Query role="request" ../> element with only
the parameters taken into account.

### 2.4 SEARCH RESPONSE

#### CEOS-BP- 010 - Output encoding format support [Requirement]

CEOS OpenSearch implementations shall support Atom [Atom] as a mandatory format, as
required by OpenSearch Geo and Time Extension [OGC 10 - 032r8.

#### CEOS-BP- 011 - Support of dc:identifier in search response to allow for search-by-ID [Requirement]

The dc:identifier element in the search result shall allow navigating from search results to a single
entry inside these results using the OpenSearch parameter {geo:uid} as described in [OGC 10-
032r8].

This makes the following use cases possible,

```
● Put a link on a Web site pointing to a single (OpenSearch) catalog item (using a URL) to
illustrate a particular event (e.g. an earthquake in the Himalaya)
● The ability to bookmark and retrieve a single item
```
#### CEOS-BP-011B – Result set navigation [Recommended]

CEOS OpenSearch implementations should provide navigation links for the first (rel="first"),
previous (rel="prev" or "previous"), current (rel="self"), next (rel="next") and last pages (i.e.
rel="last") of a result set (if applicable) using the rel attribute as defined in [OGC 10-032r8] and
[RFC5988]^5 and shown below.

The table below indicates which navigation links should be included in a result set for a number
of border cases.

```
Use cases rel="first" rel="previous"
or rel="prev"
```
```
rel="self" rel="next" rel="last"
```
```
First page of
result set
```
```
Yes No Yes Yes (if not
last page)
```
```
Yes
```
(^5) [OGC 10-032r8] only mentions "self", "prev", "previous", "next". "last" and "first" are defined in RFC5988.


```
Middle pages
of result set
```
```
Yes Yes Yes Yes Yes
```
```
Last page of
result set
```
```
Yes Yes (if not first
page)
```
```
Yes No Yes
```
```
Empty result
set
```
```
No No Yes No No
```
E.g.

```
<feed>
...
<os:totalResults>55</os:totalResults>
<os:itemsPerPage>10</os:itemsPerPage>
<os:startIndex>31</os:startIndex>
```
```
<link href="foo.gov/opensearch/datasets.atom?
startIndex=1&numberOfResults=10" rel="first" type="application/atom+xml"/>
<link href="foo.gov/opensearch/datasets.atom?
startIndex=21&numberOfResults=10" rel="prev" type="application/atom+xml"/>
<link href="foo.gov/opensearch/datasets.atom?
startIndex=31&numberOfResults=10" rel="self" type="application/atom+xml"/>
<link href="foo.gov/opensearch/datasets.atom?
startIndex=41&numberOfResults=10" rel="next" type="application/atom+xml"/>
<link href="foo.gov/opensearch/datasets.atom?
startIndex=51&numberOfResults=10" rel="last" type="application/atom+xml"/>
...
</feed>
```
The structure of href attribute of the Atom:link is irrelevant to the client as long as the semantic
(e.g. next set of results) is preserved by the link returned by the server. The client is not supposed
to "parse" the URL returned by the server. The server can thus return a link to, for example, the
next page of the result set using a link with startIndex (i.e. startIndex=41) or an equivalent link
with startPage (i.e. startPage=5).

The example below using startPage is equivalent to the previous example using startIndex.


```
<feed>
```
```
<os:totalResults>55</os:totalResults>
<os:itemsPerPage>10</os:itemsPerPage>
<os:startIndex>31</os:startIndex>
```
```
<link href="foo.gov/opensearch/datasets.atom?
startPage=1&numberOfResults=10" rel="first" type="application/atom+xml"/>
<link href="foo.gov/opensearch/datasets.atom?
startPage=3&numberOfResults=10" rel="prev" type="application/atom+xml"/>
<link href="foo.gov/opensearch/datasets.atom?
startPage=4&numberOfResults=10" rel="self" type="application/atom+xml"/>
<link href="foo.gov/opensearch/datasets.atom?
startPage=5&numberOfResults=10" rel="next" type="application/atom+xml"/>
<link href="foo.gov/opensearch/datasets.atom?
startPage=6&numberOfResults=10" rel="last" type="application/atom+xml"/>
```
```
</feed>
```
#### CEOS-BP- 012 - Metadata representation in search response [Recommended]

Although the Atom format allows any foreign (or user-defined) elements to be included and
OpenSearch Extension for EO Products [OGC 13-026r 8 ] along with O&M EOP Profile [OGC 10-
157r4] suggests many options for metadata fields, CEOS OpenSearch implementations are
encouraged to rely on atom:link@rel="alternate" or atom:link@rel=”via” for detailed
representation of the metadata. (The “via” relation should be preferred to convey the authoritative
resource or the source of the information from where the atom:entry is made.)

#### CEOS-BP-012B – Provenance information [Optional]

CEOS OpenSearch implementations using syndication/aggregation of results provided by third-
party catalogs are recommended^6 to include provenance information (at Atom Feed) level using
an atom:link element with rel=”via” and an href attribute referring to the original result set.

The above is only applicable if the original result set is accessible through an HTTP URL.

(^6) See [http://www.openarchives.org/rs/1.0/resourcesync#RePub.](http://www.openarchives.org/rs/1.0/resourcesync#RePub.)


#### CEOS-BP-012C – Reference to documentation [Recommended]

In the same context, atom:link@rel="describedby" should be used to reference to the
documentation (a file with human-readable information about the resource).

## Figure 5: Referencing Metadata and Documentation

For example,

```
<link rel=”alternate” href=”http://foo.ceos.org/foo/dataset_abc.xml”
type=”application/vnd.iso.19139+xml”/>
<link rel=”describedby” href=”http://foo.ceos.org/foo/dataset_abc.html”
type=”text/html”/>
```
Table 7 defines the MIME types to be used to reference various metadata formats.

```
Metadata format MIME Type
```
```
ISO 19139 application/vnd.iso.19139+xml
```
```
ISO 19139- 2 application/vnd.iso.19139-2+xml
```
```
ISO 19115- 3 application/vnd.iso.19115-3+xml
```
```
OGC 10-157r3
application/gml+xml;profile=http://www.opengis.net/spec/EOMPOM/1. 0
```
```
OGC 10-157r4 application/gml+xml;profile=http://www.opengis.net/spec/EOMPOM/1.1
```

```
Dublin core^7 application/xml
```
```
Markdown text/x-markdown
```
## Table 7 – MIME types for metadata formats

#### CEOS-BP-012D – Relation attribute values [Recommended]

```
CEOS OpenSearch implementations are recommended to use the following relation attribute
values when describing artifacts associated with a resource (Atom entry):
```
## Table 8 – Relation attribute values

#### CEOS-BP-012E – Link type attribute [Recommended]

```
CEOS OpenSearch implementations shall specify the media (MIME) type of the artifact
associated with a resource by specifying the "type" attribute of the Atom link element^9.
This requirement allows a client to determine which resource type a HATEOAS Atom link refers
to. E.g. a "describedby" link may point to a human readable representation or to an ISO 19139
service metadata file of the INSPIRE Download service. Clients can make this distinction by
checking the media type provided in the "type" attribute.
```
(^7) According to the XML schema [http://www.loc.gov/standards/sru/recordSchemas/dc-schema.xsd](http://www.loc.gov/standards/sru/recordSchemas/dc-schema.xsd)
(^8) The "type" attribute of the Atom link shall determine whether the resource is human-readable.
(^9) This requirement ensures compliance with TG Requirement 30 in [INSPIRE].
**Artifact Definition Relation See also Example**
Metadata file with (usually) structured information about
corresponding data files
alternate or via (^) CEOS-BP- 012 <link href="foo.xml"
rel="alternate"/>
Browse image of the data typically used for making data
request decisions
icon
CEOS-BP- 015 <link
href="sample.gif"
rel="icon"/>
Documentation file with (human-readable^8 )^ information about the
resource
describedby (^) CEOS-BP-012C <link href="foo.pdf"
rel="describedby"/>
Data link representing a data file or other science data
resource; may be large in size
enclosure
CEOS-BP- 016 <link href="foo.hdf"
rel="enclosure"/>
OSDD link to an OpenSearch^ Description Document; useful
for recursive searching
search
CEOS-BP- 001 <link href=”osdd.xml”
rel=”search”/>


#### CEOS-BP- 013 - atom:summary [Recommended]

The default value for atom:summary is “text” - i.e. if MIME type is not specified then the client
should assume that it is of type “text”. Otherwise MIME type should be specified according to
Table 7. Summaries of type ‘text/html”, should be correctly escaped. We recommend that CEOS
OpenSearch implementations have “useful” information in the actual metadata and not only in
atom:summary. The canonical source of information should be described in the metadata
(atom:link or feed/entry) and not in the atom:summary.

#### CEOS-BP-013B – Dublin Core date [Recommended]

For representing temporal extents of entries in the search result, we recommend you use a Dublin
Core date (dc:date) element as per [OGC 10-032r8] for representing either,

- A single date
- A single date-time
- A date-time range
- An open-ended date-time range

#### CEOS-BP- 014 - GeoRSS [Recommended]

For representing geographical extent in GeoRSS in the search result, we recommend (when
applicable) using “GeoRSS Simple” over “GeoRSS GML”.

When not applicable (e.g. footprint made of multiple polygons), “GeoRSS GML” (i.e.
<georss:where>) should be used (even though the strict application of GeoRSS GML does not
allow representing a multi-polygon. Only allows four simple GML root elements to appear under
georss:where.See [http://www.georss.org/xml/1.0/georss.xsd](http://www.georss.org/xml/1.0/georss.xsd) for further information.

#### CEOS-BP-014B – GeoRSS multi-polygon footprint [Recommended]

For representing geographical extent consisting of a multiple polygons in GeoRSS in the search
result, it is recommended to use “GeoRSS GML” with a <gml:MultiSurface> element containing
multiple <gml:Polygon> elements.

E.g.

```
<georss:where>
<gml:MultiSurface gml:id="MULSF01" srsName="EPSG:4326">
<gml:surfaceMembers>
<gml:Polygon xmlns:gml="http://www.opengis.net/gml" gml:id="POLN1004F1">
<gml:exterior>
<gml:LinearRing>
<gml:posList srsDimension="2">42.80386 7.22599 51.65319 4.44298 58.690876
```

1.600294 63.93042 -1.190491 69.113703 -5.017015 72.515489 -8.589162
75.839731 -13.639094 79. 017327 - 21.416325 80.505193 -27.095671 81.875982 -
34.701757 83.060111 -45.048111 83.947141 -58.914241 84.394294 -76.114221
84.297169 -94.390703 83.680793 -110.571486 82.675037 -123.155644 81.415609 -
132.447313 79.997781 -139.300653 78.479783 -144.461335 76.896266 -148.453273
73.608796 -154.206101 71.926502 -156.353166 68.5144 -159.740891 65.059909 -
162.325304 61.577619 -164.395098 56.319203 -166.882324 51.031772 -168.896467
35.062954 -173.502794 5.86342 - 180 - 21.10288 -180 7.040615 -173.900731
23.088247 - 16 9.974902 37.250369 -165.628752 47.742935 -161.263581 52.917102

- 158.434729 56.325915 -156.176491 59.690156 -153.507183 62.993884 -
150.281098 67.778891 -143.898159 70.79027 -138.083214 72.21513 -134.50441
74.827617 -125.523104 76.967397 -113.376084 78.37118 7 - 97.57291 78.705462 -
88.558317 78.760132 -79.236134 78.034898 -61.41943 77.302514 -53.606223
75.280825 -40.766619 72.742141 -31.245854 69.880667 -24.184437 66.815004 -
18.828798 63.615602 -14.64938 58.654358 -9.850203 53.567708 -6.203163
48.399967 -3.299028 41.425982 -0.178961 42.80386 7.22599</gml:posList>

</gml:LinearRing>

</gml:exterior>

</gml:Polygon>

<gml:Polygon xmlns:gml="http://www.opengis.net/gml" gml:id="POLN1004F2">

<gml:exterior>

<gml:LinearRing>

<gml:posList srsDimension="2">5.86342 180 -13.180367 175.749402 -27.402929
172.044313 -37.983457 168.635021 -46.70575 165.032035 -53.583872 161.287771

- 60.31448 156.214145 -65.198574 150.919337 -68.325776 146.238267 -69.833011
143.408601 -72.68634 136.414694 -74.003946 132.064691 -76.316313 121.114386
- 77.994851 106.595877 -78.752838 88.93359 -78.408579 70.635228 -77.840638
62.263658 -76.073449 48.176348 -73.70415 37.605582 -70.955567 29.784574 -
68.833389 25.410055 -71.395897 10.531073 -73.798945 13.549547 -77.064662
19.409287 -78.635454 23.484612 -80.138583 28.76103 -81.53812 35.77544 -
82.773822 45.282798 -83.747956 58.115927 -84.324346 74.475206 -84.379346
92.704855 -83.89886 109.640667 -82.992149 123.200212 -81.799327 133.306555 -
80.426659 140.749386 -78.940803 146.321501 -77.381562 150.602066 -75.7729 14
153.979897 -72.461612 158.973041 -67.361744 163.939913 -60.437968 168.253072
- 51.682985 171.934458 -39.323454 175.681849 -21.10288 180 5.86342
180</gml:posList>

</gml:LinearRing></gml:exterior>

</gml:Polygon>

</gml:surfaceMembers>

</gml:MultiSurface>

</georss:where>


#### CEOS-BP-014C – GeoRSS multi-point footprint [Recommended]

For representing geographical extent consisting of a multiple points in GeoRSS in the search
result, it is recommended to use “GeoRSS GML” with a <gml:MultiPoint> element containing
multiple <gml:Point> elements.

E.g.

```
<georss:where>
<gml:MultiPoint gml:id="MULTIPOINTN10051">
<gml:pointMember xmlns:gml="http://www.opengis.net/gml">
<gml:Point gml:id="POINTN100511">
<gml:pos srsDimension="2">49.695066 -136.337212</gml:pos>
</gml:Point>
</gml:pointMember>
<gml:pointMember xmlns:gml="http://www.opengis.net/gml">
<gml:Point gml:id="POINTN100512">
<gml:pos srsDimension="2">49.699539 -136.322377</gml:pos>
</gml:Point>
</gml:pointMember>
</gml:MultiPoint>
</georss:where>
```
#### CEOS-BP-014D – GeoRSS multi-line footprint [Recommended]

For representing geographical extent consisting of a multiple lines in GeoRSS in the search result,
it is recommended to use “GeoRSS GML” with a <gml:MultiGeometry> element containing
multiple <gml:LineString> elements.

E.g.

```
<georss:where>
<gml:MultiGeometry gml:id="MULGN10051">
<gml:geometryMembers>
<gml:LineString xmlns:gml="http://www.opengis.net/gml" gml:id="IDLSN100511">
<gml:posList srsDimension="2">-34.7796 102.055 -39.7836 100.515 -44.2692
98.9729 -48.3553 97.3886 -51.9754 95.7923 -55.3822 94.068 -58.412 92. 2924 -
61.1428 90.4304 -63.6322 88.4441 -65.8898 86.3242 -67.9982 83.9763 -69.8558
```
(^10) E.g. applicable for observations by the ENVISAT GOMOS (spectrometer) sensor.
(^11) E.g. applicable for observations by the ENVISAT RA2 (altimeter) sensor.


```
81.5103 -71.5184 78.8761 -73.0474 75.9704 -74.3819 72.9188 -75.614 69.5145 -
76.7237 65.7785 -77.9708 60.4664 -79.0444 54.4087 -79.9152 47.7539 -80.6
40.4392 -81.1113 32.2753 -81.4307 23.3304 -81.5365 14.3493 -81.4318 5.02661
```
- 81.1431 -3.30081 -80.6707 -11.1964 -80.0251 -18.4329 -79.2102 -24.9842 -
78.226 -30.8705 -77.0688 -36.1379 -75.7236 -40.8685 -74.1629 -45.1503 -
73.2589 -47.2138 -72.3029 -49.1436 -71.2517 -51.0222 -70.1403 - 52.7826 -
68.9422 -54.4681 -67.6573 -56.0757 -66.3226 -57.5657 -64.8832 -59.0038 -
63.3576 -60.3703 -61.7367 -61.6756 -59.9729 -62.9543 -58.1039 -64.1764 -
54.0024 -66.4875 -49.3644 -68.6552 -44.8535 -70.4491 -39.7916 -72.203 -
34.1674 -73.9239 -27.8413 -75. 6594 - 21.7536 -77.1911 -14.7287 -78.8462
10.7406 -84.4874 20.603 -86.7673 30.2014 -89.2029 38.2408 -91.5353 42.4808 -
92.9324 46.3141 -94.3356 49.8689 -95.7931 53.1354 -97.306 56.143 -98.8914
58.8823 -100.545 61.3447 -102.255 63.6636 -104.118 66.1536 -106.482 68.3495
- 108.991 70.3257 -111.72 72.0557 -114.616 73.5855 -117.724 74.9991 -121.234
76.2585 -125.092 77.3546 -129.258 78.3368 -133.933 79.1907 -139.099 79.9051
- 144.681 80.502 -150.861 80.9664 -157.523 81.2974 -164.657 81.4918 -172.36
81.5337 -180</gml:posList>
</gml:LineString>
<gml:LineString xmlns:gml="http://www.opengis.net/gml/3.2"
gml:id="IDLSN100512">
<gml:posList srsDimension="2">81.5337 180 81.4334 172.547 81.1894 165.185
80.8255 158.488 80.3222 152.047 79.7197 146.336 78.9612 140.832 78.0981
13 5.945 77.1125 131.509 76.0023 127.49 74.7475 123.806 73.3589 120.476
71.7874 117.381 70.0151 114.507 68.0696 111.896 65.832 109.403 63.451
107.187 61.3014 105.475 58.5991 103.615 55.742 101.919 52.7419 100.365
49.454 98.8658 45.7702 97.3789 41.7777 95.9426 37.3975 94.5253 29.3939
92.238 19.8126 89.8302 10.317 87.6446 -13.1049 82.4689 -24.0868 79.8694 -
33.8473 77.2688 -38.0684 76.0048 - 42.0022 74.718</gml:posList>
</gml:LineString>
</gml:geometryMembers>
</gml:MultiGeometry>
</georss:where>

#### CEOS-BP-014E – Minimum-bounding rectangle [Optional]

CEOS OpenSearch implementations should render spatial extents using a minimum-bounding
rectangle (MBR) with a <georss:box> element in addition to the native more accurate
representation of that extent with GeoRSS Simple or GeoRSS GML. The value of the georss:box
element must be an array of length 4 (two lat/long pairs), with the southwesterly point followed by
the northeasterly point.

Note that clients can distinguish the MBR from the native extent as georss:box is not to be used
for representing a native spatial extent. The MBR shall envelop, with the minimum bounding box
area, the EO acquisitions footprints, represented with GeoRSS Simple or GeoRSS GML.


#### CEOS-BP- 015 - Browse image [Recommended]

We recommend that CEOS OpenSearch implementations provide a URL to the granule’s browse
image when available, by either atom:link@rel=”icon” or Media RSS (e.g.
media:content/media:Category=QUICKLOOK).

#### CEOS-BP-015B – Multiple browse images [Optional]

We recommend that CEOS OpenSearch provide the URLs to the granule's browse images when
available, by either including multiple atom:link@rel=”icon” or including multiple Media RSS
<media:group> elements.

In case Media RSS is used, then <media:group> elements should only group <media:content>
elements which are representations of the same content. Therefore, it is recommended in this
case to provide the URL to the browse images via multiple <media:group> elements as defined
in [OGC 13-026r 8 ], when a single granule has multiple browse images (See also multi-polygon
footprint).

E.g.

```
<feed xmlns="http://www.w3.org/2005/Atom
xmlns:media="http://search.yahoo.com/mrss/" ...>
...
<entry>
...
<media:group>
<media:content
url="http://foo.ceos.org/browse/ABC/2012/08/01/PASS_ABC_210671_3_32488_1.jpg
" type="image/jpeg" medium="image">
<media:category
scheme="http://www.opengis.net/spec/EOMPOM/1. 1 ">QUICKLOOK</media:category>
</media:content>
</media:group>
<media:group>
<media:content
url="http://foo.ceos.org/browse/ABC/2012/08/01/PASS_ABC_210671_3_32488_2.jpg
" type="image/jpeg" medium="image">
<media:category
scheme="http://www.opengis.net/spec/EOMPOM/1. 1 ">QUICKLOOK</media:category>
</media:content>
</media:group>
```

```
</entry>
```
#### CEOS-BP- 016 - Data access [Recommended]

We recommend CEOS OpenSearch implementations use Atom link elements with an attribute of
rel=”enclosure” and a MIME type attribute type=”xxx” for embedding data access URLs in granule
level search responses.

The above data access URL should also be applied in case multiple files are available for data
access through a single .ZIP file or via a Metalink^12 file. If multiple physical files cannot be grouped
however, the mechanism below can be used instead.

#### CEOS-BP-016B - Data access to multiple files [Optional]

When data access to a granule in a granule search response is to be provided in multiple physical
files, each file should be linked to via a separate Atom link element. Each of these links should
have an attribute rel=”section” along with a MIME type attribute type=”xxx” for embedding the data
access URL to each file^13.

#### CEOS-BP-016C - Data access for data download and order [Optional]

CEOS recommends the use of type attribute value to further distinguish data order link and data
download link:

```
● For data order link: set the value of type attribute as “text/html”
Example of <link> with granule order URL:
<link rel="enclosure" type="text/html" title="" href=""/>
● For data download link: set the value of type attribute with the appropriate MIME type
which is compatible with downloadable dataset format.
Example of <link> with granule download URL:
<link rel="enclosure" type="application/binary" title=" " href=""/>
```
### 2.5 EXCEPTIONS

#### CEOS-BP- 017 - Exception codes [Recommended]

OpenSearch Geo and Time Extensions [OGC 10-032r8] recommends the use of HTTP status
codes as following, 4xx for client errors, and 5xx for server errors.

(^12) https://tools.ietf.org/html/rfc5854
(^13) This requirement is equivalent to TG Requirement 32 in [INSPIRE].


● 400 Bad Request: The request has an invalid syntax (i.e. badly formatted geometry)
● 413 Request Entity Too Large: The request originates too many returnable hits
● 415 Unsupported media type: Media type in the request is not available or valid.
● 5 00 Internal Server Error: Default code for the server side for an execution error.
● 501 Not Implemented: When requesting an unimplemented feature
(e.g. relation operator not supported).
● 503 Service Unavailable: When the search service is temporarily not available
(due to overload or other reasons).
● 504 Gateway Timeout: When the search engine is a broker or aggregator to other services
that fail to produce an answer within a giving time frame.
CEOS OpenSearch implementations are recommended to support these codes.

### 2.6 FUTURE DISCUSSIONS

Future discussion topics include the following.

```
● Sorting, ranking / relevance score
● Aggregation of multiple source results at client side
● Recommended Schema.org itemtype/itemprop to be used for granule metadata and
collection metadata
```

## 3 CLOSER LOOK ON IMPLEMENTATIONS

This chapter shows comparison among implementations: CWIC, FedEO, and CNES. (other
implementations may be added in the future)

### 3.1 BASICS

#### 3.1.1 OSDD URL

##### 3.1.1.1 Collection Level

```
IDN/CWIC https://cmr.earthdata.nasa.gov/opensearch/collections/descriptor_documen
t.xml?clientId=<your client id here>
```
```
FedEO http://fedeo.esa.int/opensearch/description.xml (rel=”collection”)
```
```
CNES http://theia.cnes.fr/resto/api/collections/describe.xml
```
##### 3.1.1.2 Granule Level (examples)

```
IDN/CWIC http://cwic.wgiss.ceos.org/opensearch/datasets/osdd.xml?clientId=cwicClie
nt
http://cwic.wgiss.ceos.org/opensearch/datasets/Landsat_8/osdd.xml?clientI
d=cwicClient
```
```
FedEO Option 1 (specific)
http://fedeo.esa.int/opensearch/description.xml?parentIdentifier={dataset-
id}
Option 2 (general)
http://fedeo.esa.int/opensearch/description.xml (rel=”results” - default)
Example 1
http://fedeo.esa.int/opensearch/description.xml?parentIdentifier=EOP%3A
VITO%3AVGT_S10
Example 2:
http://fedeo.esa.int/opensearch/description.xml?parentIdentifier=MIR_SC_
F0_
```
```
CNES http://theia.cnes.fr/resto/api/collections/{collection}/describe.xml
```
```
where {collection} should be replaced by the name of the collection (e.g.
Landsat)
```

#### 3.1.2 Search URL

##### 3.1.2.1 Collection Level

```
IDN/CWIC https://cmr.earthdata.nasa.gov/opensearch/collections.atom?keyword=Lan
dsat_8&clientId=cswOpenSearchDoc
```
```
FedEO http://fedeo.esa.int/opensearch/request/?httpAccept=application/atom%2B
xml&query=landsat
```
```
Note: parentIdentifier=EOP:ESA:FEDEO is default value for
EOP:ESA:FEDEO ”parentIdentifier” and can be added to request above.
application/atom+xml is the default value for the httpAccept parameter.
```
```
CNES http://theia.cnes.fr/resto/api/collections/search.atom?q=Landsat
```
##### 3.1.2.2 Granule Level (examples)

```
IDN/CWIC http://cwic.wgiss.ceos.org/opensearch/granules.atom?datasetId=Landsat_8&start
Page=1&count=1&timeStart=2017- 01 - 01T00:00:00Z&timeEnd=2017- 02 -
24T23:59:59Z&clientId=foo
```
```
FedEO http://fedeo.esa.int/opensearch/request/?httpAccept=application%2Fatom%2Bxml
&parentIdentifier=EOP%3ASPOT%3AMULTISPECTRAL_10m&startRecord=1&st
artDate=2013- 09 - 13T00%3A00%3A00Z&endDate=2013- 09 -
16T10%3A00%3A59Z&instrumentShortName=HRGNb1&bbox=3.7110010147094
98%2C44.549828243256%2C22.617251014709005%2C52.987328243256
```
```
CNES http://theia.cnes.fr/resto/api/collections/Landsat/search.atom?lang=en&q=images
%20acquired%20in%20may%202013%20over%20Paris
```
#### 3.1.3 Documents

```
IDN/CWIC CWIC Client Partner Guide (OpenSearch) v0.9
CWIC Data Partner’s Guide (OpenSearch) v0.9
CWIC Software Exception Handling v1.2
```
```
FedEO FEDEO Client Partner Guide (v1. 1 ) [FedEO-CPG]
```
```
CNES http://github.com/jjrom/resto
```

### 3.2 REMARKABLE PRACTICES

#### 3.2.1 OSDD

##### 3.2.1.1 Support of parameter extension

###### IDN/CWIC YES

```
Note: Recommended attributes are “name”, “value”, “title”.
“uiDisplay” will be an optional attribute in the future.
```
```
FedEO YES
```
```
CNES YES
```
##### 3.2.1.2 Support of Explain operation (SRU)

The Explain document (from the OASIS SearchRetrieve standard) provides additional metadata
about the search endpoint, the parameters accepted by the search endpoint and the possible
response schemas. If fulfils a similar role as an OGC Capabilities document.

```
IDN/CWIC NO
```
```
FedEO YES
```
```
CNES NO
```
#### 3.2.2 Output encoding format in a search URL

```
IDN/CWIC resource extension (e.g. description.atom) and content negotiation
```
```
FedEO a search parameter (httpAccept). This search parameter is borrowed from
the OASIS SearchRetrieve (and SRU) standard.
```
```
Note : Other ways i.e. content-negotiation using HTTP header (httpAccept)
and resource extension will be supported in the future. Q2 2015)
```
```
CNES resource extension (e.g. search.atom) and content negotiation
```
#### 3.2.3 Support of 2 step search

###### IDN/CWIC YES


```
FedEO YES
```
```
CNES YES
```
#### 3.2.4 Search Parameters

##### 3.2.4.1 Supported Search Parameters

C : Supported in Collection Level search parameter,

G : Supported in Granule Level search parameter

Superscript : M : Mandatory, O : Optional, 1 : dependent on subsidiary catalog

Namespaces prefixes : Table 2 of OGC 10-032r8 and Table2 of OGC 13-026r 8.

```
Search Parameters IDN/CWIC FedEO CNES
count CG C G
searchTerms C CG^1 CG
startIndex G C CG
startPage G CG CG
dc:publisher C
dc:subject CG^1
dc:title C^1
dc:type C^1
time:start CG CG G
time:end CG CG G
geo:box CG CG G
geo:geometry
geo:lat CG G
geo:lon CG G
geo:name CG G
geo:radius CG G
geo:uid CG G
eo:acquisitionStation C^1 G^1
```

```
Search Parameters IDN/CWIC FedEO CNES
```
eo:acquisitionType G^1

eo:acquisitionSubType G^1

eo:antennaLookDirection G^1

eo:archivingCenter G^1

eo:cloudCover G^1 G

eo:completionTimeFrom
AscendingNode

###### G^1

eo:compositeType G^1

eo:dopplerFrequency G^1

eo:frame G^1

eo:illuminationAzimuthAngle G^1

eo:illuminationElevationAngle G^1

eo:imageQualityDegradation G^1

eo:incidenceAngleVariation G^1

eo:instrument CG^1 G

eo:maximumIncidenceAngle G^1

eo:minimumIncidenceAngle G^1

eo:orbitDirection G^1

eo:orbitNumber C^1 G^1 G

eo:orbitType G^1

eo:organisationName C G

eo:parentIdentifier G (datasetId) CG^1

eo:platformSerialIdentifier G^1

eo:platform CG^1 G

eo:polarisationChannels G^1

eo:polarisationMode G^1

eo:processingCenter C^1 G^1

eo:processingLevel G^1 G

eo:processorName G^1


```
Search Parameters IDN/CWIC FedEO CNES
eo:productionStatus G^1
eo:productType CG^1 G
eo:resolution G^1 G
eo:sensorType G^1
eo:sensorMode G^1
eo:snowCover G^1 G
eo:startTimeFromAscendingNode G^1
eo:swathIdentifier G^1
eo:track C^1
semantic:classifiedAs C
sru:recordSchema CG
```
#### 3.2.5 Supported output format

```
IDN/CWIC ATOM, RSS^1 , HTML^1 [1] IDN only
```
```
FedEO ATOM, RSS^1 , SRU^1 , RDF/XML^1 , JSON-LD^2 , Turtle^2 , HTML^2 [1] depends on
data partner [2] not advertised in operational environment.
```
```
CNES ATOM, GeoJSON, HTML
```
#### 3.2.6 Output schema support

###### IDN/CWIC NO

```
FedEO YES (dc, iso, O&M EOP v1.0 and v1.1)
```
```
CNES NO
```
#### 3.2.7 Free Keyword notation (searchTerms)

```
IDN/CWIC Conveyed by Parameter Extension (Parameter/link@rel=“profile”)
```
```
FedEO whitespace for AND double quote for phrase
```

```
CNES Natural language queries (e.g. “images over Paris between may and june
2013”)
```
#### 3.2. 8 Pagination

```
IDN startPage, count
```
```
CWIC startIndex, startPage, count
```
```
FedEO startIndex, startPage, count
```
```
CNES startIndex, startPage, count
```
#### 3.2.9 Search Result

##### 3.2.9.1 Browse

```
IDN/CWIC link@rel=”icon”
```
```
FedEO link@rel=“icon”
also supports
Media RSS notation (use of media:content/media:Category=QUICKLOOK)
```
```
CNES link@rel=”icon”
also supports
Media RSS notation (use of media:content/media:Category=QUICKLOOK)
```
##### 3.2.9.2 Thumbnail

###### IDN/CWIC N/A

```
FedEO Media RSS notation (use of media:content/media:Category=THUMBNAIL)
```
```
CNES Media RSS notation (use of media:content/media:Category=THUMBNAIL)
```
##### 3.2.9.3 Mask Image

###### IDN/CWIC N/A

```
FedEO Media RSS notation (use of media:content/media:Category=MASK)
```
```
CNES N/A
```

##### 3.2.9.4 Metadata

```
IDN/CWIC link@rel=”via”
```
```
FedEO link@rel=”alternate” or link@rel=”via”
```
```
CNES link@rel=”via”
```
##### 3.2.9.5 Documentation

```
IDN/CWIC link@rel=”describedBy”
```
```
FedEO link@rel=”describedBy”
```
```
CNES N/A
```
##### 3.2.9.6 Data

```
IDN/CWIC link@rel=”enclosure”
```
```
FedEO link@rel=”enclosure”
```
```
CNES link@rel=”enclosure”
```
#### 3.2.10 Error Handling

##### 3.2.10.1 Exception Status Code (4xx, 5xx)

```
IDN/CWIC Compliant with OGC OpenSearch [OGC 10-032r8]
```
```
FedEO Compliant with OGC OpenSearch [OGC 10-032r8] and OGC OWS
Common [OGC 06-121]
```
```
CNES Compliant with OGC OpenSearch [OGC 10-032r8]
```

## ANNEX A: LIST OF OPENSEARCH ENDPOINTS

```
This appendix shows OpenSearch endpoints of CEOS agency catalogs.
```
```
FedEO :
http://fedeo.esa.int/opensearch/description.xml
CWIC:
http://cwic.wgiss.ceos.org/opensearch/datasets/osdd.xml?clientId=<your client id here>
IDN:
https://cmr.earthdata.nasa.gov/opensearch/collections/descriptor_document.xml?clientId=<your
client id here>
CNES:
http://theia.cnes.fr/api/collections/describe.xml
```

## ANNEX B: EXAMPLES

```
This appendix contains example code snippets from CEOS agencies’ implementations.
```
### B1. OSDD (COLLECTION LEVEL)

#### IDN/CWIC

```
https://cmr.earthdata.nasa.gov/opensearch/collections/descriptor_document.xm
l?clientId=<your client id here>
```
#### FedEO

```
http://fedeo.esa.int/opensearch/description.xml
```
#### CNES

```
http://theia.cnes.fr/resto/api/collections/describe.xml
```

## ANNEX C: SEARCH-ENGINE-FRIENDLY CATALOG

```
This appendix gives some hint to make a catalog Search-Engine-Friendly with schema.org
Only Atom format is required as an output format response. However, for implementations that
support also HTML as an output format, it is recommended to use schema.org within the provided
HTML response.
Additionally there are numerous ways in which that HTML can be designed to make it visible to
search engines and, therefore, a searcher interested in earth science data.
Schema.org provides a means to expose datasets in search engine results that is explicitly geared
towards earth science datasets (https://schema.org/Dataset). Implementers can mark up their
HTML in a manner that allows crawlers to index their data in terms of a variety of parameters
including spatial and temporal extent. The following subsections illustrate the use of the
schema.org vocabulary along with microdata and JSON-LD. For more information, please refer
to [schema.org].
```
### C1. USING MICRODATA

```
For example:
```
```
<li itemscope itemtype='http://schema.org/Dataset' >
<span itemprop='alternateName' >doi:10.3334/ORNLDAAC/1</span>
<span itemprop='version' >1</span>
<span itemprop='provider' >ORNL_DAAC</span>
<div itemprop='description' >ABSTRACT: USGS 15 minute stream flow data for
Kings Creek on the Konza Prairie</div>
<span itemprop='temporal' >2000- 01 - 01T00:00:00Z/</span>
<span itemprop='spatial' >-55.0 -180.0 90.0 180.0</span>
</li>
```
```
And another example :
```
```
<ul class='results' itemscope itemtype='http://schema.org/DataCatalog' >
<li class="dataset" itemscope itemtype='http://schema.org/Dataset' >
<h2 itemprop='name' >15 Minute Stream Flow Data: USGS (FIFE)</h2>
<span class="uid">C179003030-ORNL_DAAC</span>
<div class='dataset-identification'><span>Dataset Information:</span>
<div class='tuple' >Short name: <span class='value short_name'
```

**itemprop='alternateName'** >doi:10.3334/ORNLDAAC/1</span></div>

<div class='tuple' >Version ID: <span class='value version_id'
**itemprop='version'** >1</span></div>

<div class='tuple' >Data center: <span class='value data_center'
**itemprop='provider'** >ORNL_DAAC</span></div>

</div>

<span><div class='temporal'><span>Temporal extent:</span><div
class='tuple'>Start: <span class='start value'>1984- 12 -
25T00:00:00.000Z</span></div><div class='tuple'>Stop: <span class='stop
value'>1988- 03 - 04T00:00:00.000Z</span></div></div></span>

<span class='temporal schema_org' **itemprop='temporalCoverage'** >1984- 12 -
25T00:00:00.000Z/1988- 03 - 04T00:00:00.000Z</span>

<span><div class='spatial'><span>Spatial extent:</span><div
class='tuple'>Bounding box: <span class='spatial-value value'>39.1 -96.6
39.1 -96.6</span></div><div class='tuple'>Point: <span class='spatial-value
value'>39.1 -96.6</div></span></div></span>

<span class='spatial schema_org' **itemprop='spatialCoverage'** >39.1 -96.6
39.1 -96.6</span>

<div class='dataset-identification'><span>Description:</span>

<div class='tuple description' **itemprop='description'** >ABSTRACT: USGS
15 minute stream flow data for Kings Creek on the Konza Prairie</div>

</div>

<div>

<span class='link-title'>Links:</span>

<ul class='links'>

<li><a class='dataset_link' href="http://daac.ornl.gov/cgi-
bin/dsviewer.pl?ds_id=1" **itemprop='url'** >Data link</a></li>

<li><a class='dataset_link'
href="http://daac.ornl.gov/FIFE/guides/15_min_strm_flow.html" **itemprop='url'**
>USGS 15 minute stream flow data for Kings Creek on the Konza Prairie (VIEW
RELATED INFORMATION)</a></li>

<li><a class='dataset_link'
href="http://gcmd.nasa.gov/getdif.htm?FIFE_STRM_15M" **itemprop='url'**
>doi:10.3334/ORNLDAAC/1</a></li>

<li><a class='dataset_link'
href="https://api.echo.nasa.gov:443/catalog-
rest/echo_catalog/datasets/C179003030-ORNL_DAAC.xml" **itemprop='url'** >Product
metadata</a></li>

</ul>


</div>

<div class="granule-search">

<a
href="/opensearch/granules?clientId=our_html_ui&amp;dataCenter=ORNL_DAAC&amp
;dataset_cursor=1&amp;dataset_id=15+Minute+Stream+Flow+Data%3A+USGS+%28FIFE%
29&amp;dataset_number_of_results=10&amp;shortName=doi%3A10.3334%2FORNLDAAC%2
F1&amp;spatial_type=bbox

&amp;versionId=1"><span class="ui-state-default ui-corner-all open-search-
button">Granule Search</span></a>

</div>

</li>


### C2. USING JSON-LD

For example

```
<html>
```
```
<head>
<title>Search Results</title>
<script type="application/ld+json">
{
"@context" : "http://schema.org",
"@type" : "Dataset",
"name" : "SeaSat L-Band SAR Level-1 Ellipsoid Geocoded Precision Image
(SEA_GEC_1P)",
"alternateName" : "SEA_GEC_1P",
"description" : "The SEA_GEC_1P product is generated by geocoding of data
processed to the SEA_PRI_1P product specification. Products are generated in
UTM map coordinates, with output pixel spacing at 12.5 metres. Geocoding is
undertaken on the approximation that all image points lie on the surface of
the WGS84 ellipsoid adjusted for a local representative vertical datum. It
should be noted that mapping distortions will occur as a consequence of
terrain relief.",
"provider" : {
"@type" : "Organization",
"name" : "ESA/ESRIN",
"address" : {
"@type" : "PostalAddress"
},
"email" : "eohelp@eo.esa.int"
},
"publisher" : {
"@type" : "Organization",
"name" : "ESA/ESRIN",
"address" : {
"@type" : "PostalAddress"
},
"email" : "eohelp@eo.esa.int"
},
"dateModified" : "1978- 07 - 13T00:00:00Z",
"keywords" : "FedEO, ESA LDS, ocean, coast, snow, ice, land, Science
Keywords > Earth Science > Spectral/Engineering > Visible Wavelengths >
Visible Imagery, Science Keywords > Earth Science > Terrestrial Hydrosphere
> Snow/Ice > Ice Extent, SEASAT 1, SAR",
"temporalCoverage" : "1978- 07 - 13/1978- 10 - 10",
"spatialCoverage" : {
"@type" : "Place",
"geo" : {
"@type" : "GeoShape",
"polygon" : "-10.0 -125.0 70.0 -125.0 70.0 20.0 -10.0 20.0 -10.0 -125.0"
}
}
}
</script>
</head>
</html>
```

