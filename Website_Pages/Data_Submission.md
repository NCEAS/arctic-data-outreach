---
title: "Arctic Data Submission Guidelines"
date: June 4, 2018
output:
  html_document: default
---
# Data Submission Guidelines

- [Introduction](#introduction)
    - [Who Must Submit?](#who-must-submit)
- [Organizing Your Data](#organizing-your-data)
    - [What is a Data Package?](#what-is-a-data-package)
    - [File Organization Guidelines](#file-organization-guidelines)
    - [File Format Guidelines](#file-format-guidelines)
    - [Metadata Guidelines](#metadata-guidelines)
    - [Guidelines for Large Data Packages](#guidelines-for-large-data-packages)
- [The Submission Process](#the-submission-process)
    - [Identification Guidelines](#identification-guidelines)
    - [Licensing and Data Distribution](#licensing-and-data-distribution)
    - [Publication](#publication)
    - [Submission Tools](#submission-tools)
- [Submission Support](#submission-support)

## Introduction

The NSF Office of Polar Programs requires that metadata, full datasets, and derived data products be deposited in a long-lived and publicly accessible archive. Specific requirements for various Office of Polar Programs programs can be found in the [NSF Dear Colleague Letter #16055](https://www.nsf.gov/pubs/2016/nsf16055/nsf16055.jsp). The Arctic Data Center at http://arcticdata.io was created with funding from NSF to assist with compliance of these requirements by providing a long-lived and publicly accessible archive for Arctic Sciences Section (ARC) data and metadata. At a minimum, metadata describing ARC-supported data packages must be submitted to the Arctic Data Center. 

The following documentation provides guidelines to assist with submission of [data packages](#what-is-a-data-package) to the Arctic Data Center. If you have additional questions please see the [Q and A](https://arcticdata.io/q-and-a/) section of the Center's website, or contact support@arcticdata.io and a member of the Arctic Data Center support team will respond promptly.

### Who Must Submit?

Data from ARC-supported scientific research should be deposited in [long-lived and publicly-available archives](/preservation) appropriate for the specific type of data collected (by default, the NSF supported [Arctic Data Center](/) at [http://arcticdata.io](http://arcticdata.io), or others where appropriate). Metadata for projects, regardless of where they are archived, should be submitted to this Arctic Data Center for centralized access and discoverability.

For all ARC supported projects, see the [NSF ARC-programs data policy](http://www.nsf.gov/pubs/2014/nsf14584/nsf14584.htm#grantcond), which includes the following conditions:

- Complete metadata must be submitted to a national data center or another long-lived, publicly accessible archive within two years of collection or before the end of the award, whichever comes first.
- All data and derived data products that are appropriate for submission (see exceptions below), must be submitted within two years of collection or before the end of the award, whichever comes first.

For all ARC supported Arctic Observing Network projects, NSF also requires:

- Real-time data must be made publicly available immediately. If there is any question about what constitutes real-time data, please contact the appropriate NSF program officer.
- All data must be submitted to a national data center or another long-lived publicly accessible archive **within 6 months of collection**, and be fully quality controlled.
- All data sets and derived data products must be accompanied by a metadata profile and full documentation that allows the data to be properly interpreted and used by other researchers.

For sensitive social science data:

- NSF policies include special exceptions for Arctic Social Sciences awards and other awards that contain sensitive data, including human subjects data and data that are governed by an Institutional Review Board policy. These special conditions exist for sharing social science data that are ethically or legally sensitive or at risk of decontextualization.
- In these cases, NSF has requested that a metadata record be created that documents non-sensitive aspects of the project and data, including the title, contact information for the data set creators and contacts, and an abstract and methods description summarizing the data collection methodologies that does not include any sensitive information or data.
- Please let us know when submitting your record that your data contain sensitive information so that we can adjust our review process accordingly.
- Please contact your NSF Program Manager if you have questions about what to submit or what is required for any particular award.

Please write to [support@arcticdata.io](mailto:support@arcticdata.io) with any questions or for clarifications, and we will help to clarify these policies to the best of our ability. Ultimately, NSF makes the final policy decisions on these data submissions.

## Organizing Your Data

### What is a Data Package?

The Arctic Data Center primarily archives data packages. Data packages on the Arctic Data Center are simply defined as a collection of related data and metadata files. On the Arctic Data Center, each data package should contain, when possible, all of the relevant data and metadata from a specific research project (or sub-project/project component).

Depending on the size of a research project, multiple data packages may be associated with a single research project. For example, if a research project consists of field sampling at several distinct sites or over several distinct sampling seasons, each site/season may have its own unique data package. When submitting to the Arctic Data Center, it is up to the best judgement of the submitting researcher how his/her research should be grouped. If multiple data packages are needed for a research project, they can be made by individually going through the [Arctic Data Center website submission tool](https://arcticdata.io/catalog/#share) for each subset. After submitting multiple data packages, the support team (support@arcticdata.io) can help nest related data packages together. See [here](https://arcticdata.io/catalog/#view/urn:uuid:46789d94-7c12-4d9f-9e62-7f90f7918219) for an example of how nested data packages render on the website.

### File Organization Guidelines

In order to optimally document and share a project's output, quality data file management is necessary. Some resources for best practices for managing data files can be found [here](https://www.dataone.org/best-practices) and [here](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/0012-9623-90.2.205). The following are a few guidelines that are encouraged for file organization for projects that plan to submit to the Arctic Data Center. Following these guidelines should help ensure a project's outputs are easy to access and understand.

- All files should have short, descriptive names.
- Only letters, numbers, hyphens ("-"), and underscores ("\_")
should be used in file names. Always avoid using spaces and specialized ASCII characters when naming files.
- All files should be stored in open, ubiquitous, and easy-to-read file formats (see [File Format Guidelines](#file-format-guidelines)).
- Tabular data should be submitted in a long (versus wide) format if possible. Long file formats will make documentation of attributes (variables), as well as access to the data, much easier.
- For models/scripts, all files necessary to run the code should be included and organized in a manner that makes running the code as accessible as possible. If outside dependencies (software, hardware, or otherwise) are needed to run code which cannot be submitted to the Arctic Data Center, details of these dependencies should be made clear within the metadata description of the code files as well as within the method's metadata. For large models see [Guidelines for Large Models](#guidelines-for-large-models).

### File Format Guidelines

The Arctic Data Center primarily supports and encourages the upload of open, ubiquitous, and easy-to-read file formats. Examples of such formats are Comma Separated Values (CSV) files, text (TXT) files, PNG, JPEG or TIFF image files, R or Python scripts, and NetCDF files, among many others.
For projects that plan to submit to the Arctic Data Center, we strongly advise researchers to incorporate plans for creating files using open data formats from the initial stages of project development (i.e. within the data management plan of the project proposal). If work with any proprietary data formats such as Excel workbooks or MATLAB files is necessary, researchers should make plans early on to transform all data stored in these formats into open data formats before submission to the Arctic Data Center. If for any reason that certain files created in a project must be submitted in a proprietary format, the Center may request an explanation before publishing the files.

- For tabular data, we advise researchers to use common file formats such as CSV or TXT.
- For image files, we advise researchers to use common file formats such as PNG, JPEG, TIFF, etc.
- For GIS files, it is acceptable to submit the de-facto standard ESRI shapefiles, or GeoJSON files.
- For MATLAB or other matrix-based programs, we advise researchers to export NetCDF files (an open binary format).
- We encourage researchers to use the NetCDF format when large numbers of uniform matrices or arrays are being archived. See [here](https://www.unidata.ucar.edu/software/netcdf/docs/index.html) for more information about NetCDF files.
- For transparency and ease of automated parsing, we advise researchers to upload files individually as opposed to zipped archives.  The exception to this guideline is when ubiquitous software expects zipped formats and where the co-existence of the files is required, such as in shapefiles.

### Metadata Guidelines

The Arctic Data Center primarily stores metadata in a structured, XML-based files. Transformation of plain text documentation into a structured metadata format for archiving is done automatically when submitting through the [Arctic Data Center website](https://arcticdata.io/catalog/#share). Prior to submitting documentation to the Arctic Data Center, we advise projects to create complete, plain text metadata records. Ideally, plans to create and store metadata records should be made during the initial stages of project development (i.e. within the data management plan of the project proposal).

The goal of metadata is to document a project's output so that a reasonable scientist will be able to understand and use all the components of the output without any outside consultation. The following components represent a non-exhaustive list of components typically expected within metadata records submitted to the Arctic Data Center:

- A descriptive title that includes the topic, geographic location, dates, and, if applicable, the scale of the data.
- A descriptive data package abstract that provides a brief overview summarizing the specific contents and purpose of the data package.
- Funding information (typically the NSF award number).
- A list of all people or organizations associated with the data package with at least one person or organization acting as a creator and one acting as a contact (these can be the same). See the [Identification Guidelines](#identification-guidelines) for more information about listing people within Arctic Data Center metadata records.
- Full records of field and laboratory sampling times and locations, including a geographic description interpretable by a general scientific audience. 
- Full records of taxonomic coverage within the data package (if applicable). 
- Full descriptions of field and laboratory sample collection methods.
- Full descriptions of field and laboratory sample processing methods.
- Full descriptions of any hardware and software used (including make, model, and version where applicable). 
- Full attribute/variable information for all data (see [Metadata Guidelines for Tabular Data](#metadata-guidelines-for-tabular-data)).
- Quality control procedures.
- Relevant explanations for why the particular components detailed above were chosen for the project.

Additional guidance for specific metadata cases is included below.

#### Metadata Guidelines for Tabular and Spatial Data

Submitted metadata should contain detailed metadata for **every** attribute collected. 

Attributes in tabular data (e.g. age, sex, length (ASL) of fish encoded in CSV) are also referred to as variables and are arranged in either columns or rows. Note that storage of data in a long versus wide format will allow for more succinct metadata (see [File Organization Guidelines](#file-organization-guidelines).

In spatial vector data (e.g. lake features encoded in a shapefile), attributes describe a feature characteristic (e.g. lake area). In spatial raster data, the attribute of interest is encoded as a cell value for a given location (e.g. AVHRR Sea Surface Temperature (SST) encoded in a NetCDF matrix). 

The following components are needed to describe each attribute:

- A name (often the column or row header in the file). Like file names, only letters, numbers, hyphens (“-“), and underscores (“\_”) should be used in attribute names. Always avoid using spaces and specialized ASCII characters when naming attributes.
- A complete definition. The definition should fully clarify the measurement to a broad scientific audience. For example, a definition like "%C" may always be interpreted within a certain discipline in a uniform way. However, it might always be interpreted within another certain discipline in a different uniform way. A full technical definition such as "percent soil carbon by dry soil mass" helps to limit possible confusion.
- Any missing value codes along with explanations for those codes.
- For all numeric data, unit information is needed.
- For all date-time data, a date-time format is needed (e.g. "YYYY-MM-DD").
- For all spatial data, the spatial reference system details are needed.
- For text data, full descriptions for all patterns/codes are needed if the text is constrained to a list of patterns or codes (e.g. a phone number would be constrained to a certain pattern and abbreviations for site locations may be constrained to a list of codes). 

#### Metadata Guidelines for Software

For data packages with software (including models), submitted metadata should contain the following components, among others:

- Instructions on how to use the software.
- Version information.
- Licensing information.
- A list of software/hardware used in development.
- A list of software/hardware dependencies needed to run the software.
- Information detailing source data for models.
- Any mathematical/physical explanations needed to understand models.
- Any methods used to evaluate models.

## Guidelines for Large Data Packages

The Arctic Data Center does not have data package or file size limitations for NSF funded projects. Many multi-terabyte data packages have been archived on the Arctic Data Center. In most cases, all data and metadata relevant to each project should be archived regardless of total file size (note, non-NSF funded projects may be subject to a one-time processing fee depending on the total data package size). The [Arctic Data Center website](https://arcticdata.io/catalog/#share) can handle the upload of multiple large files simultaneously. However, researchers with slow internet connections or those that experience any trouble uploading any file through the website should contact the Arctic Data Center support team at support@arcticdata.io. The Arctic Data Center support team has many options to upload large data packages when connection speed is limited or files are exceptionally large.
 
### Guidelines for Large Models

Models with extensive outputs are a case where data package sizes can become substantially large. In general, we advise researchers to archive the model output if it is relevant to the project. That being stated, sometimes model output can be regenerated from archived input data and model code. Accordingly, depending on the specifics of a project, it may be reasonable to archive only the code and model inputs as well as a clear workflow on how to recompute the model output (rather than the output itself).  However, if re-running the model would require prohibitive amounts of compute cycles or other resources (such as access to specialized or expensive software or hardware), then we recommend researchers to archive the output, especially if the output is a valuable data package that others may want to analyze and use in their own work. For example, many climate model outputs are difficult for the average scientist to recompute but are valuable for a myriad of downstream uses. Additionally, some models are stochastic and the interpretation of subsequent products depends on specific model runs. In these (and most related cases) archival of model outputs is recommended.

## The Submission Process

### Identification Guidelines

The Arctic Data Center [ORCID iDs](https://orcid.org/) to identify individuals associated with each data package. When submitting to the Arctic Data Center, an ORCiD is required for the submitter of each data package. ORCiDs are not required for all associated parties (contacts, additional creators, etc.), but are strongly encouraged, especially for the primary creator, so that proper identification and attribution can be given. Additionally, access to edit each data package can only be granted to individuals using ORCiDs. Therefore, we advise researchers to [register](https://orcid.org/register/) and record ORCID iDs for each individual involved with the project during the initial stages of project development (i.e. within the data management plan of the project proposal).

### Licensing and Data Distribution

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

All data and metadata will be released under either the [CC-0 Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/) or the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/), with the potential exception of social science data that have certain sensitivities related to privacy or confidentiality. In cases where legal (e.g., contractual) or ethical (e.g., human subjects) restrictions to data sharing exist, requests to restrict data publication must be requested in advance and in writing and are subject to the approval of the NSF, who will ensure compliance with all federal, university, and Institutional Review Board policies on the use of restricted data. As a repository dedicated to helping researchers increase collaboration and the pace of science, this repository needs certain rights to copy, store, and redistribute data and metadata. By uploading data, metadata, and any other content to the Arctic Data Center, users warrant that they own any rights to the content and are authorized to do so under copyright or any other right that might pertain to the content. [Data and facts themselves are not covered under copyright](http://www.bitlaw.com/copyright/database.html) in the US and most countries, since facts in and of themselves are not eligible for copyright. That said, some associated metadata and some particular compilations of data could potentially be covered by copyright in some jurisdictions. **By uploading content, users grant the Arctic Data Center repository and UCSB all rights needed to copy, store, redistribute, and share data, metadata, and any other content. By marking content as publicly available, users grant the Arctic Data Center repository, UCSB, and any other users the right to copy the content and redistribute it to the public without restriction under the terms of the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/) license or the [CC-0 Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/), depending on which users choose at the time of upload.**

### Publication

The Arctic Data Center provides a long-lived and publicly accessible system that is free for other researchers to obtain data and metadata files. Complete submissions to the Center meet [the requirements set by The Office of Polar Programs](https://www.nsf.gov/pubs/2016/nsf16055/nsf16055.jsp) which require that metadata files, full datasets, and derived data products be deposited in a long-lived and publicly accessible archive. 

Submission of data packages to the Arctic Data Center is free for all NSF ARC-funded projects. data packages from projects funded by sources that do not include NSF are permitted to submit to the Center but may be subject to a one-time processing fee, depending on the size and processing needs of the data package. Additionally, data packages from projects not funded by NSF ought to cover Arctic science-relevant research to be published on the Arctic Data Center. Please note that submissions of NSF-funded data packages are prioritized in our processing queue. 

The Arctic Data Center publicly releases data packages once complete data packages have been submitted and compiled. In the typical submission process, researchers will submit data to the Arctic Data Center through the [Arctic Data Center website](https://arcticdata.io/catalog/#share) (see [Alternative Submission Methods](#alternative-submission-methods) or [Submission Support](#submission-support) if needed). Then, the Center's support team will review the data package. If the support team discovers any issues with the initial submission, the data team will work with the submitter to resolve the issues as quickly as possible (we primarily correspond via emails from support@arcticdata.io to the email address registered with the submitter's ORCID iD). **We advise researchers to submit data packages well before deadlines.** For most ARC-funded projects, all data and metadata submissions are due within two years of collection or before the end of the award, whichever comes first. The data submission deadline is stricter for Arctic Observing Network (AON) projects, with real-time data needed to be made publicly available immediately and all data required to be fully quality controlled and submitted within 6 months of collection. Please see below for the [submission requirement exceptions](#licensing-and-data-distribution-policy) for sensitive social science data.

Depending on the complexity of the data package and the quality of the initial submission, the review process can take anywhere from a few hours to several weeks. Long processing times generally occur when initial submissions have incomplete metadata and/or poorly organized files and/or the submitter is not responsive to follow-up emails. Compliance with the guidelines detailed here should ensure quick processing times. Well organized and complete data packages can potentially be published within one business day. After the review process, each data package will be given a unique Digital Object Identifier (DOI) that will assist with attribution and discovery. The DOI is registered with [DataCite](http://www.datacite.org/) using the [EZID](http://ezid.cdlib.org/) service, and will be discoverable through multiple data citation networks, including [DataONE](http://dataone.org/) and others.

![about-doi](https://arcticdata.io/wp-content/uploads/about-doi.png)Once the data package is published with the Arctic Data Center, it can still be editied and updated with new data or metadata. Additionally, the original data and metadata will remain archived and available to anyone who might have cited it. Updates to data and metadata can be made by clicking the green "Edit" button on the website of any data package (researchers will need to log in and have edit access to see the green button).

Each data package DOI represents a unique, immutable version, just like for a journal article. Therefore, **Any** update to a data package qualifies as a **new version** and therefore requires a new DOI. DOIs and URLs for previous versions of data packages remain active on the Arctic Data Center (i.e. they will continue to resolve to the dataset landing page for the specific version they are associated with), but a clear message will appear at the top of the page stating that “A newer version of this data package exists” with a hyperlink to the latest version. With this approach, any past uses of a DOI (such as in a publication) will remain functional and will reference the specific version of the data package that was cited, while pointing researchers to the newest version if one exists.

[Learn more about DOIs](http://www.doi.org/driven_by_doi/DOI_Marketing_Brochure.pdf)

### Submission Tools
![The Arctic Data Center simple online submission form.](https://arcticdata.io/wp-content/uploads/registry-screenshot.png)</br>
Most researchers submit to the Arctic Data Center through the [Arctic Data Center website](https://arcticdata.io/catalog/#share). However, there are several alternative tools to submit data packages to the Center.

![The DataONE R package.](https://arcticdata.io/wp-content/uploads/R-logo.png)</br>
Researchers can also submit data inside an R workflow using the [dataone R package](https://github.com/DataONEorg/rdataone).

![The DataONE MATLAB library](https://arcticdata.io/wp-content/uploads/matlab.png)</br>
Researchers can also submit data inside a MATLAB workflow using the [Matlab DataONE library](https://github.com/DataONEorg/matlab-dataone).

### Developers: REST API

In addition to the web and data tools shown above, the Arctic Data Center provides the ability to access and submit data via the [DataONE REST API](/catalog/#api). This allows the community to use many programming languages to add data and metadata to the repository, search for and access data, and automate any process that might otherwise be highly time consuming. Most useful to groups with repetitive tasks to perform, such as submitting many data files of the same type, the REST API can be a real time saver. For more details, please contact us at [support@arcticdata.io](mailto:support@arcticdata.io).
 
 The Arctic Data Center currently encodes metadata in the [Ecological Metadata Language (EML)](https://knb.ecoinformatics.org/#external//emlparser/docs/eml-2.1.1/index.html). 

## Submission Support

If, for whatever reason, support with a submission is needed, contact support@arcticdata.io and an Arctic Data Center support team member will respond promptly.

If you have a large volume of files to submit or the total size of your data is too large to upload via the web form, please first submit your complete data package description (metadata) through the Arctic Data Center website and then write to support@arcticdata.io to arrange another method for the data transfer. The support team has multiple options for transferring large amounts of data, including via Google Drive or our SFTP service. 
