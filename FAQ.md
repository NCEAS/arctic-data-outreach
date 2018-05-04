This draft FAQ is geared at user support. It should be made publicly available on the arcticdata.io site. It is made from actual support tickets, using real questions and real answers.


# Table of Contents
1. [ACADIS legacy accounts and formats](#acadis-legacy-accounts-and-formats)
2. [DOIs](#dois)
3. [Citations and Credit](#citations-and-credit)
4. [ORCiD](#)
5. [Granting Access to collaborators](#granting-access-to-collaborators)
6. [Making Datasets Private and Public](#making-datasets-private-and-public)
7. [File Formats](#file-formats)
8. [Attribute Units](#attribute-units)
9. [Data Abstracts](#data-abstracts)
10. [Methods](#methods)
11. [Metadata](#metadata)

# ACADIS legacy accounts and formats
### Q: I have data under an ACADIS account that I need linked to my new ORCiD account. Can you help me? 
A: We can definitely help link your ACADIS and ORCiD accounts. If you have previously submitted data we can get those linked to your ORCiD profile. Please supply us with your ORCID iD and request this linkage by writing to support@arcticdata.io.  

### Q: I previously submitted data to ACADIS. Now that all the data have been moved I would like to regain editing access to those data packages.  
A: We are aware that the migration of data packages from ACADIS to the Arctic Data Center led to some issues. We apologize for any inconvenience this may have caused you. Please supply us with your ORCID iD and request access by writing to support@arcticdata.io from an email address of the packages' submitter or creator. Also be sure to provide the specific identifiers of the packages.  

# DOIs
### Q: Why is it necessary to mint new DOIs when there is an update to a data package?  
A: We are committed to providing citable datasets to facilitate reproducible science. Each DOI issued by the Arctic Data Center is intended to represent a unique, immutable version of a data package. When data or metadata are changed, we assign a new identifiers to each version, while maintaining the original versions' identifiers. In this way, researchers that want to access the exact version of data files cited in a publication will be able to do so, but will also have access to newer versions. When you open the older version, it will have a clear message displayed on the top “A newer version of this dataset exists”, with a link to the newest version.  
Our approach has been informed by best practices for citing digital research objects, particularly data and software products. Our system is closely aligned with the Force11 Data Citation Principles (https://www.force11.org/group/joint-declaration-data-citation-principles-final) , which, in section 7 recommend that:  
> “Data citations should facilitate identification of, access to, and verification of the specific data that support a claim. Citations or citation metadata should include information about provenance and fixity sufficient to facilitate verifying that the specific time slice, version, and/or granular portion of data retrieved subsequently is the same as was originally cited”.  
In essence, once a data package has been published, it cannot be changed without receiving a new identifier, just as a journal article cannot be changed once it is published. The bottom line for us is that for any new version of a data package, we assign a new identifier so each version (both old and new) can always be cited and accessed without ambiguity as to the content of the package.  

### Q: When will I receive a DOI for my submission?  
A: DOIs are intended for finalized data packages. Once you have provided comprehensive metadata and data that meet NSF submission standards, your submission will be processed in the order in which it was received. Once it is published, we will email you the DOI for your data package. Always prepare and submit metadata and data well ahead of deadlines to avoid delays in approval of final reports to NSF.  

# Citations and Credit
### Q: "I entered (Researcher Name) as the PI, but does that mean that her name will not show up in the citation? As I see it on the page now, it doesn't show her in the citation. I’d like (Researcher Name) to be included on that as well, but I didn’t see a way to list her as both PI and creator.  
A: "Good catch. (Researcher) needs to be listed as a "Creator", in addition to being listed as the "PI", in order to have her name appear in the citation. If you have trouble making this addition we can assist you. Please contact us at support@arcticdata.io.  

# Editing data and metadata once it has been submitted
### Q: I had previously submitted data to the Arctic Data Center (or ACADIS) and I want to edit my data package. Will this affect my DOI?  
A: Be aware that when you make changes to a data package, the new version will receive a new DOI. This way any data citation will refer to a unique and immutable version of the data package. The version with the original DOI will remain on the repository and can be navigated to directly, but only the latest version will be discoverable via a search. Obsoleted versions clearly display a message at the top of their landing pages stating that "A newer version of this dataset exists" with a link to the latest version.  
This is our way of preserving the version chain. Therefore, either DOI you cite will enable the user to find the latest version, but if you would like to be as precise as possible you should cite the identifier for the specific version of interest.  

### Q: I want to update a dataset that already has a DOI, what is the best way to do that?  
A: Usually we would be able to grant you editing permission for data packages, but at present, we are experiencing an issue when users update data sets that already have DOIs. We apologize for the inconvenience. For now, we would prefer that you describe the changes you would like to see made directly in an email to support@arcticdata.io and we will make the updates for you.  

### Q: I was just going through one of my data packages and I noticed that a few changes need to be made. Unlike my other packages I do not see the green "Edit" button on the pne I nned to edit. Can you please help me?
A: Please have an email sent to support@arcticdata.io from an email address of one of the package's creators or from the original submitter.  Tell us who ought to have edit access to the package, being sure to provide their ORCID iDs and the specific identifiers of the package.

### Q: We would like to submit another "child" data package to be nested under a "parent". Do we need to fill out new metadata or can ADC support staff modify them to include the new year's worth of data?  
A: We can make those updates for you. Please email support@arcticdata.io with all the details and to arrange the best way to transfer the data to us.  

### Q: How do I link a new data package to an existing project?  
A: To submit a new dataset, you can just click the 'Submit Data' button on our website and fill out that form. Our team will get in touch and handle linking the dataset to a project based on NSF award number.  

### Q: I would like to upload updated data that are a revised analysis of data that were previously there. What is your procedure for this situation? We would like users to use the newest version, but it is possible that somebody is using the current version on the archive.  
A: Our system supports byte-level versioning. Identifiers and URLs for previous versions of data packages remain active on the Arctic Data Center (continue to resolve to the data package landing page for the specific version they are associated with), but a clear message will appear at the top of the page stating that “A newer version of this dataset exists” with a hyperlink to that latest version. With this approach, any past uses of a DOI (such as in a publication) will remain functional and will reference the specific version of the dataset that was cited, while pointing users to the newest version if one exists. Only the latest version will be discoverable via the user search interface. To revise an existing data package simply visit the landing page, click "Edit", and make your changes. If you do not have access to a data package you wish to update please let us know so we may grant you access.  

### Q: I want to update a dataset that already has a DOI, what is the best way to do that?  
A: Usually we would be able to grant you editing permission for data packages, but at present, we are experiencing an issue when users update data sets that already have DOIs. For now, we would prefer that you describe the changes you would like to see made directly in this email thread and we will make the updates for you.  

### Q: I had previously submitted data to the Arctic Data Center (or ACADIS) and I want to edit my data record. Will this affect my DOI?
A: Be aware that when you make changes to a data package, it will receive a new DOI afterwards. This way any data citation will refer to a preserved and static version of a data package. However, the pacakge with the original DOI will remain on the repository and will clearly display a message at the top of its page stating that "A newer version of this dataset exists" with a link to the updated version.  
This is our way of preserving the revision chain. Therefore, either DOI you cite will enable users to find the most updated version, but if you would like to be as precise as possible please consider waiting until you receive the new DOI after submitting changes.  

### Q: I manage continuous monitoring of a multi-decadal project. Over the years, a few other metadata records have been created and the files associated with them should really be moved and reorganized with other data packages. If these files are moved, is there a way to have the DOI from the old metadata record point or forward to the correct one?
A: For "cleaning up", it is likely best if you tell us the specific changes you would like to make so that we may apply them for you. This is especially true since you would like to move data files and retain a pointer from the old metadata record to the new/ correct one.  

# ORCiD
### Q: I have a question regarding the future use of my account. I will be graduating my program eventually and am currently training a new graduate student to replace me. Can I shift this account into an institutional account or just change the name to something like "XYZ Lab"? This would prevent all future graduate students in our lab from having to each make their own account, and then resubmitting all the data each year.  
A: We could potentially create a group page for the "XYZ Lab", however each contributor would still need to sign in with his/her own ORCiD ID. This is important so that we can track who has edited what and there is accountability and transparency in case of any discrepancies or differences in opinions about what, or how, information ought to be represented.  

# Granting Access to collaborators
### Q: How do I add access for project collaborators to my data package?  
A: Let us know the ORCID iDs of whoever else needs access and we will authorize them from our end. Be sure to send this message to support@articdata.io from an email address of a data package creator and/or submitter.  

# Making Data Packages Private and Public
### Q: I set my data package as private but actually I would like to change it to public. Is is possible to do that?  
A: You will not be able to make the package public, that can only be done from our end. We do not publish data packages until they are finalized. NSF requires that complete metadata be described directly in the metadata record before finalization.  

# File Formats
### Q: I want to provide my raw data, however the data are in a non-proprietary file format. What do you suggest I do?  
A: We appreciate your efforts to archive the raw data. We always strive to do so when those data are in open formats. If providing these data in a non-proprietary format is impractical, are you able to provide processed data in an open format along with a description of the processing? This description could even be to the effect of "we ran the raw data through software X", although more details are always preferred to fewer. By taking the time to convert these to an open format you will vastly improve access to your research.  

### Q: I submitted my Excel spreadsheet, am I done?  
A: Thank you for your recent submission to the NSF Arctic Data Center. We noticed that the data file was submitted in .xlsx format. We recommend conversion of this file into a plain text/csv format in order to facilitate an accurate transfer of information to future researchers and ensure preservation of the data in perpetuity.  

# Large files
### Q: I have large data files, what should I do?  
A: If you have data files that are too large (>25MB) to attach in an email, please let us know and we will provide another method for transferring them to us. Options for large datasets include SFTP or sharing via Google Drive or Dropbox.  

# Submitting Code and Scripts
### Q: What sort of descriptions should I provide for submitting a script?  
A: Please clearly define the following:  
- what the script does
- what the inputs and outputs are
- how the script was verified/tested/trained/calibrated/etc.

# Attribute Units
### Q: I cannot find the unit in your list that appropriately describes my attribute. What should I do?  
A: Believe us, this has happened before. It's very hard to have an exhaustive list that isn't plain exhausting to look through. We recommend you either reach out to our data support team (support@arcticdata.io) to work on a custom unit, or, if you think it's appropriate, you can set your unit as "Other - dimensionless". This works well for counts, percents, concentrations, etc.  

# Data Abstracts
### Q: Does the Arctic Data Center have any guidance for writing my abstract?  
A: We suggest that the abstract be sufficiently descriptive for a general scientific audience. It should provide an overview of the scientific context/ project/ hypotheses, how this data package fits into the larger project, a synopsis of the experimental or sampling design, and a summary of the data contents. If you prefer and it is appropriate, you could add language from the abstract in your NSF Award.  

# Methods
### Q: Does the Arctic Data Center have any guidance for writing my methods?  
A: Please ensure that enough detail is included in your methods so that a reasonable scientist could interpret the study and data for reuse without needing to consult you nor any other resources. NSF requires that a comprehensive methods section is included directly in the metadata record. Article citations are insufficient. We may be able to extract the methods from a journal article for you, but it would be faster and more precise if you did so. Please send a methods section by either updating the submission or sending us the language in an email to support@arcticdata.io.  
