---
title: "Arctic Data Submission Guidelines"
date: May 8, 2018
output:
  html_document: default
---

## Introduction

Datasets from NSF Office of Polar Programs supported research are required to deposit metadata files, full datasets, and derived data products, in a long-lived and publicly accessible archive. Specific requirements for various Office of Polar Programs programs can be found [here](https://www.nsf.gov/pubs/2016/nsf16055/nsf16055.jsp). The Arctic Data Center (ADC) at http://arcticdata.io was created with funding from the NSF to assist with compliance of these requirements by providing a long-lived and publicly accessible archive for Arctic Sciences data and metadata. At a minimum, all Arctic supported datasets must be submitted to the ADC. 

The following documentation provides guidelines to assist with submission of data and metadata to the ADC. If you have additional questions please see the [Q and A](https://arcticdata.io/q-and-a/) section of the ADC website, or contact support@arcticdata.io; a member of the ADC data team will respond promptly.


## File Orgainization Guidelines

In order to optimally document and share a project's output, good data file management is necessary. Some resources for best practices for managing data files can be found at [here](https://www.dataone.org/best-practices) or [here](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/0012-9623-90.2.205). The following are a few guidelines that are encouraged for file organization for projects that plan to submit to the ADC. Following these guidelines should help ensure a project's outputs are easy to access and understand.

- All files should have short descriptive names.
- No file name should contain spaces (dashes “-” or underscores “_” should be used alternatively).
- All files should be stored in open-source, ubiquitous, and easy-to-read file formats (see [File Format Guidelines](#file-format-guidelines)).
- Tabular data should be submitted in a long (versus wide) format if possible. Long file formats will make documentation of attributes as well as access of the data much easier.
- For models/scripts, all files necessary to run the code should be included and organized in a manner that makes running the code as simple as possible. If outside dependencies (software, hardware, or otherwise) are needed to run code which cannot be submitted to the ADC, details of these dependencies should be made clear within the metadata description of the code files as well as within the methods metadata. 

## File Format Guidelines

The ADC primarily supports the upload of open-source, ubiquitous, and easy-to-read file formats. Examples of such formats are Comma Separated Values (CSV) files, text (TXT) files, PNG, JPEG or TIFF image files, R or Python scripts, and netCDF files among many others.
For projects that plan to submit to the ADC, it is strongly advised to incorporate plans for creating open-source files from the initial stages of project development (i.e. within the data management plan of the project proposal). If work with any proprietary data formats such as Excel workbooks or MATLAB files is deemed necessary, plans should be made early on to transform all data stored in these formats into open-source formats before submission to the ADC. If for any reason it is determined that certain files created in a project must be submitted in a proprietary format, the ADC may request an explanation before publishing the files.

- For tabular data, it is advised to use common file formats such as CSV or TXT.
- For image files, it is advised to use common file formats such as PNG, JPEG, TIFF, etc.
- For GIS files, it is acceptable to submit ESRI files.
- For MATLAB or other matrix-based programs, it is advised to use netCDF (an open binary format).
- NetCDF is also encouraged for many files due to the ability to organize and document files in such a format. See [here](https://www.unidata.ucar.edu/software/netcdf/docs/index.html) for more information about netCDF files.

## Metadata Guidelines

The ADC primarily stores metadata using the [Ecological Metadata Language (EML)](https://knb.ecoinformatics.org/#external//emlparser/docs/eml-2.1.1/index.html). Transformation of plain text metadata documentation into an EML format for archiving will be done automatically when submitting through the ADC website. It is advised for projects that plan to submit to the ADC that complete plain text metadata records be readily available before submission. Accordingly, plans to create and store metadata records should be made during the initial stages of project development (i.e. within the data management plan of the project proposal)

The goal of metadata is to document a project's output so that a reasonable scientist will be able to understand and use all the components of the output without any outside consultation. The following components represent a non-exhaustive list of components typically expected within metadata records submitted to the ADC.

- A descriptive title that includes the topic, geographic location, dates, and if applicable, the scale of the data.
- A descriptive dataset abstract that provides a brief overview that summarizes the specific contents and purpose of the dataset.
- Funding information (typically the NSF award number).
- A list of all people associated with dataset with at least one person acting as a creator and one person acting as a contact (these can be the same person). See the [Identification Guidelines](#identification-guidelines) for more information about listing people within ADC metadata records.
- Full records of field and laboratory sampling times and locations. 
- Full records of taxonomic coverage within the dataset (if applicable). 
- Full descriptions of field and laboratory sample collection methods.
- Full descriptions of field and laboratory sample processing methods.
- Full descriptions of any hardware and software used (including make, model, and version where applicable). 
- Full attribute/variable information for all data (see [Metadata Guidelines for Tabular Data](#metadata-guidelines-for-tabular-data)).
- Quality control procedures.
- Relevant explanations for why the particular components detailed above were chosen for the project.

Additional guidance for specific metadata cases is included below.

### Metadata Guidelines for Tabular Data

For datasets with tabular data (e.g. CSV data), submitted metadata should contain the following components for **every** attribute (attributes are also sometimes called variables and in tabular data are arranged in either columns or rows). Note, storage of data in a long versus wide format will allow for much more succinct metadata (see [File Orgainization Guidelines](#file-organization-guidelines). Also note, tabular data stored within structured formats such as zip, netCDF, or ESRI spatial files should comply with these guidelines. 

- A name (often the column or row header in the file).
- A definition.
- Missing value codes for missing data and explanations for those codes.
- For all numeric data, unit information is needed.
- For all date-time data, a date-time format is needed (e.g. "YYYY-MM-DD")
- For all text data, if the text is constrained to a list of patterns or codes (e.g. a phone number would be constrained to a certain pattern and abbreviations for site locations may be constrained to a list of codes) full descriptions for all patterns/codes are needed.

### Metadata Guidelines for Software

For datasets with software (including models), submitted metadata should contain the following components amoung others.

- Version information.
- Licensing information.
- A list of software/hardware used in development.
- A list of software/hardware dependencies needed to run the software.
- Information detailing source data for models.
- Any mathematical/physical explanations needed to understand models.
- Any methods used to evaluate models.

## Identification Guidelines
The ADC utilizes [ORCiDs](https://orcid.org/) to identify individuals associated with each dataset. When submitting to the ADC an ORCiD will be required for the designated creator of each dataset. ORCiDs are not required for all associated parties (contacts, additional creators, etc.) but are strongly encouraged so that proper identification and attribution can be given. Additionally, access to edit each dataset will granted to individuals using ORCiDs. Therefore, it is advised that a plan to create (in not already created) and record ORCiDs for each individual involved with the project be created during the initial stages of project development (i.e. within the data management plan of the project proposal).

## Publication Policy
The ADC provides a long-lived and publicly accessible system that is free for users to obtain data and metadata files. Complete submissions to the ADC meet [the requirements set by the The Office of Polar Programs](https://www.nsf.gov/pubs/2016/nsf16055/nsf16055.jsp) that require that metadata files, full datasets, and derived data products be deposited in a long-lived and publicly accessible archive. 

Submission of datasets to the ADC is free for all NSF Arctic Sciences funded projects. Non NSF funded may be permitted to submit to the ADC but may be subject to a one-time processing fee dependent on the size and processing needs of the dataset. Additionally, non NSF funded projects must contain Arctic Sciences related data to be published by the ADC.

The ADC publicly releases datasets once all metadata files, full datasets, and derived data products have been submitted and compiled. In the typical submission process, users will submit data to the ADC through the [ADC website](https://arcticdata.io/catalog/#share) (see [Alternative Submission Methods](#alternative-submission-methods) or [Submission Support](#submission-support) if needed). Then, the ADC data team will review the dataset. If the data team discovers any issues with the initial submission, the data team will work with the submitter to resolve the issues as quickly as possible. It is advised to submit datasets well before deadlines. Depending on the complexity of the dataset and the quality of the initial submission, the review process can take anywhere from a few hours to several weeks. Long processing times generally occur when initial submissions have incomplete metadata and/or poorly organized files. Compliance with the guidelines detailed here should ensure quick processing times. Well organized and complete datasets can be published within four working hours. After the review process, each dataset will be given a unique Digital Object Identifier (DOI) that will assist with attribution and discovery.	

## Licensing and Data Distribution Policy

All data and metadata published to the ADC will be released under either the CC-0 Public Domain Dedication or the Creative Commons Attribution 4.0 International License (CC BY), with the potential exception of social science data that have certain sensitivities related to privacy or confidentiality. In cases where legal (e.g., contractual) or ethical (e.g., human subjects) restrictions to data sharing exist, requests to restrict data publication must be made in advance and in writing and are subject to the approval of NSF, who will ensure compliance with all federal, university, and Institutional Review Board policies on the use of restricted data.	

## Alternative Submission Methods

Most users submit to the ADC through the [ADC website](https://arcticdata.io/catalog/#share). However, there are several alternative tools to submit datasets to the ADC.

- Users can submit data inside an R workflow using the [dataone R package](https://github.com/DataONEorg/rdataone).
- Users can submit data inside a MATLAB workflow using the [Matlab DataONE library](https://github.com/DataONEorg/matlab-dataone).
- In addition to our web and data tools shown above, the Arctic Data Center provides the ability to access and submit data via the [DataONE REST API](https://arcticdata.io/catalog/#api). This allows the community to use many programming languages to add data and metadata to the repository, search for and access data, and automate any process that might otherwise be highly time consuming. Most useful to groups with repetitive tasks to perform, such as submitting many data files of the same type, the REST API can be a real time saver.

## Submission Support

If for whatever reason support with a submission is needed, contact support@arcticdata.io and an ADC data team member will respond promptly.

If you have a large volume of files to submit or the total size of your data is too large to upload via the web form, please first submit your complete dataset description (metadata) through the ADC website and then write to support@arcticdata.io to arrange another method for the data transfer. The data team has multiple options for transferring large amounts of data, including via Google Drive or our SFTP.



