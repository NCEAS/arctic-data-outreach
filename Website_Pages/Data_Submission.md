#Data Submission

[Who must submit?](#who-must-submit?)<br/>
[Submission Guidelines](#submission-guidelines)<br/>
[Terms of Use: Licensing and Data Distribution](#license)<br/>
[Preparing data and metadata](#preparing-data)<br/>
[Publishing with a DOI](#publishing)<br/>
[Data Submission Tools](#tools)<br/>
[Developers: REST API](#rest)<br/>

### Who must submit?

Data sets from ARC-supported scientific research should be deposited in [long-lived and publicly-available archives](/preservation) appropriate for the specific type of data collected (by default, the NSF supported [Arctic Data Center](/) at [http://arcticdata.io](http://arcticdata.io), or others where appropriate). Metadata for projects, regardless of where they are archived, should be submitted to this Arctic Data Center for centralized access and discoverability.

For all ARC supported projects, see the [NSF ARC-programs data policy](http://www.nsf.gov/pubs/2014/nsf14584/nsf14584.htm#grantcond), which includes the following conditions:

*   Complete metadata must be submitted to a national data center or another long-lived, publicly accessible archive within two years of collection or before the end of the award, whichever comes first.
*   All data and derived data products that are appropriate for submission (see exceptions below), must be submitted within two years of collection or before the end of the award, whichever comes first.

For all ARC supported Arctic Observing Network projects, NSF also requires:

*   Real-time data must be made publicly available immediately. If there is any question about what constitutes real-time data, please contact the appropriate NSF program officer.
*   All data must be submitted to a national data center or another long-lived publicly accessible archive **within 6 months of collection**, and be fully quality controlled.
*   All data sets and derived data products must be accompanied by a metadata profile and full documentation that allows the data to be properly interpreted and used by other researchers.

For sensitive social science data:

*   NSF policies include special exceptions for Arctic Social Sciences awards and other awards that contain sensitive data, including human subjects data and data that are governed by an Institutional Review Board policy. These special conditions exist for sharing social science data that are ethically or legally sensitive or at risk of decontextualization.
*   In these cases, NSF has requested that a metadata record be created that documents non-sensitive aspects of the project and data, including the title, contact information for the data set creators and contacts, and an abstract and methods description summarizing the data collection methodologies that does not include any sensitive information or data.
*   Please let us know when submitting your record that your data contain sensitive information so that we can adjust our review process accordingly.
*   Please contact your NSF Program Manager if you have questions about what to submit or what is required for any particular award.

Please write to [support@arcticdata.io](mailto:support@arcticdata.io) with any questions or for clarifications, and we will help to clarify these policies to the best of our ability. Ultimately, NSF makes the final policy decisions on these data submissions.

### Terms of Use: Licensing and Data Distribution

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

All data and metadata will be released under either the [CC-0 Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/) or the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/), with the potential exception of social science data that have certain sensitivities related to privacy or confidentiality. In cases where legal (e.g., contractual) or ethical (e.g., human subjects) restrictions to data sharing exist, requests to restrict data publication must be requested in advance and in writing and are subject to the approval of the NSF, who will ensure compliance with all federal, university, and Institutional Review Board policies on the use of restricted data. As a repository dedicated to helping researchers increase collaboration and the pace of science, this repository needs certain rights to copy, store, and redistribute data and metadata. By uploading data, metadata, and any other content to this repository, you warrant that you own any rights to the content and are authorized to do so under copyright or any other right that might pertain to the content. [Data and facts themselves are not covered under copyright](http://www.bitlaw.com/copyright/database.html) in the US and most countries, since facts in and of themselves are not eligible for copyright. That said, some associated metadata and some particular compilations of data could potentially be covered by copyright in some jurisdictions. **By uploading content, you grant this repository and UCSB all rights needed to copy, store, redistribute, and share data, metadata, and any other content. By marking content as publicly available, you grant this repository, UCSB, and any other users the right to copy the content and redistribute it to the public without restriction under the terms of the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/) license or the [CC-0 Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/), depending on which you choose at the time of upload.**

### Preparing data and metadata

To prepare for upload, it’s good to have your files in order. You might want to take a look at some [best practices](http://www.dataone.org/best-practices) for [managing your data files](http://onlinelibrary.wiley.com/doi/10.1890/0012-9623-90.2.205/full). For a given project, perhaps you have 6 data files, and one document that describes the methods that you used to collect or analyze your data. Collect these files into a single directory, and name them with short but descriptive names. Try to avoid spaces in your file names, but rather use dashes “-” or underscores “_”.

##### Use any file format.

![about-fileformats](https://arcticdata.io/wp-content/uploads/about-fileformats.png)

Credit: Blugraphic.com

While the Arctic Data Center supports the upload of any data file format, sharing data can be greatly enhanced if you use ubiquitous, easy-to-read formats. For instance, while **Microsoft** **Excel** files are commonplace, it’s better to export these spreadsheets to Comma Separated Values (CSV) text files, which can be read on any computer without having Microsoft products installed. Data submitted in Excel workbooks will undergo conversion to CSVs by our staff before being made public. Other proprietary formats will also be converted to plain-text formats when possible.

For **image** files, use common formats like PNG, JPEG, TIFF, etc. Most all browsers can handle these.

**GIS data** can be exported to ESRI shapefiles, and data created in Matlab or other matrix-based programs can be exported as [NetCDF](http://www.unidata.ucar.edu/software/netcdf/) (an open binary format).

Finally, gather together metadata that describes your data, including information about the name and identity of the data, the geospatial coordinates where it was collected, when it was collected, and by whom. For people, you’ll want to have their names and contact information, and an ORCID identifier for them. You’ll want to have a good complete set of text describing the methods used to collect the data, as well as experimental design and sampling layouts. Finally, you’ll need the data files themselves. Once you’ve gathered this information, choose a data submission tool and get started!

### Publishing with a DOI

Once data have been submitted to the Arctic Data Center, our metadata staff will review and provide suggestions for improvement. Once everything is set, we will make the data publicly accessible and publish it with a DOI. This will allow you and other researchers to cite the data set directly in NSF reports, publications, and other venues. The DOI is registered with [DataCite](http://www.datacite.org/) using the [EZID](http://ezid.cdlib.org/) service, and will be discoverable through multiple data citation networks, including [DataONE](http://dataone.org/) and others.

![about-doi](https://arcticdata.io/wp-content/uploads/about-doi.png)Once you have published your data with the Arctic Data Center, it can still be updated by providing an additional version which can replace the original, while still preserving the original and making it available to anyone who might have cited it. To update your data, return to the data submission tool used to submit it, and provide an update.

**Any** update to a data set qualifies as a **new version** and therefore requires a new DOI. This is because each DOI represents a unique, immutable version, just like for a journal article. DOIs and URLs for previous versions of data sets remain active on the Arctic Data Center (will continue to resolve to the dataset landing page for the specific version they are associated with), but a clear message will appear at the top of the page stating that “A newer version of this dataset exists” with a hyperlink to the latest version. With this approach, any past uses of a DOI (such as in a publication) will remain functional and will reference the specific version of the dataset that was cited, while pointing users to the newest version if one exists.

[Learn more about DOIs](http://www.doi.org/driven_by_doi/DOI_Marketing_Brochure.pdf)

### Data Submission Tools

#### On the web

![Submit data on the Arctic Data Center website using a simple online form.](https://arcticdata.io/wp-content/uploads/registry-screenshot.png)

Submit data on the Arctic Data Center website using a [simple online form](https://arcticdata.io/catalog#share).

#### In R

![Submit data inside your R workflow using the DataONE R package.](https://arcticdata.io/wp-content/uploads/R-logo.png)

Submit data inside your R workflow using the [dataone R package](https://github.com/DataONEorg/rdataone).

#### In Matlab

![Submit data directly in your Matlab workflow using the DataONE library](https://arcticdata.io/wp-content/uploads/matlab.png)

Submit data directly in your Matlab workflow using the [Matlab DataONE library](https://github.com/DataONEorg/matlab-dataone)

### Developers: REST API

In addition to our web and data tools shown above, the Arctic Data Center provides the ability to access and submit data via the [DataONE REST API](/catalog/#api). This allows the community to use many programming languages to add data and metadata to the repository, search for and access data, and automate any process that might otherwise be highly time consuming. Most useful to groups with repetitive tasks to perform, such as submitting many data files of the same type, the REST API can be a real time saver. For more details, please contact us at [support@arcticdata.io](mailto:support@arcticdata.io).

If you have a large volume of files to submit or the total size of your data is too large to upload via the web form, please submit your complete data set description (metadata) and write to [support@arcticdata.io](mailto:support@arcticdata.io) to arrange another method for data transfer. We have multiple options for transferring large amounts of data, including via Google Drive or our SFTP.

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

### Terms of Use: Licensing and Data Distribution

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

All data and metadata will be released under either the [CC-0 Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/) or the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/), with the potential exception of social science data that have certain sensitivities related to privacy or confidentiality. In cases where legal (e.g., contractual) or ethical (e.g., human subjects) restrictions to data sharing exist, requests to restrict data publication must be requested in advance and in writing and are subject to the approval of the NSF, who will ensure compliance with all federal, university, and Institutional Review Board policies on the use of restricted data. As a repository dedicated to helping researchers increase collaboration and the pace of science, this repository needs certain rights to copy, store, and redistribute data and metadata. By uploading data, metadata, and any other content to this repository, you warrant that you own any rights to the content and are authorized to do so under copyright or any other right that might pertain to the content. [Data and facts themselves are not covered under copyright](http://www.bitlaw.com/copyright/database.html) in the US and most countries, since facts in and of themselves are not eligible for copyright. That said, some associated metadata and some particular compilations of data could potentially be covered by copyright in some jurisdictions. **By uploading content, you grant this repository and UCSB all rights needed to copy, store, redistribute, and share data, metadata, and any other content. By marking content as publicly available, you grant this repository, UCSB, and any other users the right to copy the content and redistribute it to the public without restriction under the terms of the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/) license or the [CC-0 Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/), depending on which you choose at the time of upload.**

### Preparing data and metadata

To prepare for upload, it’s good to have your files in order. You might want to take a look at some [best practices](http://www.dataone.org/best-practices) for [managing your data files](http://onlinelibrary.wiley.com/doi/10.1890/0012-9623-90.2.205/full). For a given project, perhaps you have 6 data files, and one document that describes the methods that you used to collect or analyze your data. Collect these files into a single directory, and name them with short but descriptive names. Try to avoid spaces in your file names, but rather use dashes “-” or underscores “_”.

##### Use any file format.

![about-fileformats](https://arcticdata.io/wp-content/uploads/about-fileformats.png)

Credit: Blugraphic.com

While the Arctic Data Center supports the upload of any data file format, sharing data can be greatly enhanced if you use ubiquitous, easy-to-read formats. For instance, while **Microsoft** **Excel** files are commonplace, it’s better to export these spreadsheets to Comma Separated Values (CSV) text files, which can be read on any computer without having Microsoft products installed. Data submitted in Excel workbooks will undergo conversion to CSVs by our staff before being made public. Other proprietary formats will also be converted to plain-text formats when possible.

For **image** files, use common formats like PNG, JPEG, TIFF, etc. Most all browsers can handle these.

**GIS data** can be exported to ESRI shapefiles, and data created in Matlab or other matrix-based programs can be exported as [NetCDF](http://www.unidata.ucar.edu/software/netcdf/) (an open binary format).

Finally, gather together metadata that describes your data, including information about the name and identity of the data, the geospatial coordinates where it was collected, when it was collected, and by whom. For people, you’ll want to have their names and contact information, and an ORCID identifier for them. You’ll want to have a good complete set of text describing the methods used to collect the data, as well as experimental design and sampling layouts. Finally, you’ll need the data files themselves. Once you’ve gathered this information, choose a data submission tool and get started!

### Publishing with a DOI

Once data have been submitted to the Arctic Data Center, our metadata staff will review and provide suggestions for improvement. Once everything is set, we will make the data publicly accessible and publish it with a DOI. This will allow you and other researchers to cite the data set directly in NSF reports, publications, and other venues. The DOI is registered with [DataCite](http://www.datacite.org/) using the [EZID](http://ezid.cdlib.org/) service, and will be discoverable through multiple data citation networks, including [DataONE](http://dataone.org/) and others.

![about-doi](https://arcticdata.io/wp-content/uploads/about-doi.png)Once you have published your data with the Arctic Data Center, it can still be updated by providing an additional version which can replace the original, while still preserving the original and making it available to anyone who might have cited it. To update your data, return to the data submission tool used to submit it, and provide an update.

**Any** update to a data set qualifies as a **new version** and therefore requires a new DOI. This is because each DOI represents a unique, immutable version, just like for a journal article. DOIs and URLs for previous versions of data sets remain active on the Arctic Data Center (will continue to resolve to the dataset landing page for the specific version they are associated with), but a clear message will appear at the top of the page stating that “A newer version of this dataset exists” with a hyperlink to the latest version. With this approach, any past uses of a DOI (such as in a publication) will remain functional and will reference the specific version of the dataset that was cited, while pointing users to the newest version if one exists.

[Learn more about DOIs](http://www.doi.org/driven_by_doi/DOI_Marketing_Brochure.pdf)

### Data Submission Tools

#### On the web

![Submit data on the Arctic Data Center website using a simple online form.](https://arcticdata.io/wp-content/uploads/registry-screenshot.png)

Submit data on the Arctic Data Center website using a [simple online form](https://arcticdata.io/catalog#share).

#### In R

![Submit data inside your R workflow using the DataONE R package.](https://arcticdata.io/wp-content/uploads/R-logo.png)

Submit data inside your R workflow using the [dataone R package](https://github.com/DataONEorg/rdataone).

#### In Matlab

![Submit data directly in your Matlab workflow using the DataONE library](https://arcticdata.io/wp-content/uploads/matlab.png)

Submit data directly in your Matlab workflow using the [Matlab DataONE library](https://github.com/DataONEorg/matlab-dataone)

### Developers: REST API

In addition to our web and data tools shown above, the Arctic Data Center provides the ability to access and submit data via the [DataONE REST API](/catalog/#api). This allows the community to use many programming languages to add data and metadata to the repository, search for and access data, and automate any process that might otherwise be highly time consuming. Most useful to groups with repetitive tasks to perform, such as submitting many data files of the same type, the REST API can be a real time saver. For more details, please contact us at [support@arcticdata.io](mailto:support@arcticdata.io).

If you have a large volume of files to submit or the total size of your data is too large to upload via the web form, please submit your complete data set description (metadata) and write to [support@arcticdata.io](mailto:support@arcticdata.io) to arrange another method for data transfer. We have multiple options for transferring large amounts of data, including via Google Drive or our SFTP.