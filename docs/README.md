| Status | Version | Maturity | Normative level |
|:-------------|:------------------|:------|:-------|
|  <span style="background-color:gold">Work in progress</span> | v0.5 | draft | ikke normert/skal ikke normeres |

Status and maturity level explained.

## Status

The status of the product indicates where in the release cycle the product is at the moment of publication.  

 <span style="background-color:gold">Work in progress</span>  

~~~md
<span style="background-color:gold">Work in progress</span>
~~~

<span style="background-color:BlueViolet">Prerelease</span>  

~~~md
<span style="background-color:BlueViolet">Prerelease</span> 
~~~

<span style="background-color:LimeGreen">Release</span>  

~~~md
<span style="background-color:LimeGreen">Release</span>
~~~

<span style="background-color:CornflowerBlue">Normative</span>  

~~~md
<span style="background-color:CornflowerBlue">Normative</span>
~~~

<span style="background-color:OrangeRed">Deprecated</span>  

~~~md
<span style="background-color:OrangeRed">Deprecated</span>  
~~~

| Status | Description |
|:-------------|:------------------|
| <span style="background-color:gold">Work in progress</span>   | Product is in active development, COULD indicate planned normative level of the finished product |
| Prerelease | Prerelease version of the published product, SHOULD have version number and proposed normative level of the finished product |
| Release | A release version of the product, metadata MUST indicate normative level and version number |
| Normative | Normative version published by e-helse, metadata MUST indicate normative level and version number |
| Deprecated | A deprecated version of the product, SHOULD have version number and proposed normative level of the finished product, if the product is superceded by a new product this hould be indicated by the documentation |

## Maturity level

Each part/artifact of a publication can have different maturity based on the level and types of review it has been subject to.

| Maturity | Description |
|:-------------|:------------------|
| 1-draft | untested draft not yet ready for review |
| 2-review | draft ready for review |
| 3-test | reviewed draft ready for testing (when applicable) |
| 4-mature | Mature part of the publication, this part has undergone necessary QA for release publication |
| 5-normative | Normative part of the publication, this part has undergone formal normative process and is considered a normative part of the publication |

## Use of metadata

All pages publicly available from Direktoratet for e-helse's GitHub should indicate maturity and status of the publicly available documentation. The status should be indicated with at table on the top of each page, just like what is shown on the top of this one. The markdown code for the metadata table should look like this:
~~~md
| Status | Version | Maturity | Normative level |
|:-------------|:------------------|:------|:-------|
|  <span style="background-color:gold">Work in progress</span> | v0.5 | draft | ikke normert/skal ikke normeres |
~~~