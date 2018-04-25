#Q & A
Below you’ll find information you may need to know when planning your data management activities. If your question is not addressed below, please feel free to get in touch at support@arcticdata.io.

### Question: Can I replace data that has already been uploaded and keep the DOI?  

Once you have published your data with the Arctic Data Center, it can still be updated by providing an additional version which can replace the original, while still preserving the original and making it available to anyone who might have cited it. To update your data, return to the data submission tool used to submit it, and provide an update.

**Any** update to a data set qualifies as a **new version** and therefore requires a new DOI. This is because each DOI represents a unique, immutable version, just like for a journal article. DOIs and URLs for previous versions of data sets remain active on the Arctic Data Center (will continue to resolve to the data set landing page for the specific version they are associated with), but a clear message will appear at the top of the page stating that “A newer version of this data set exists” with a hyperlink to the latest version. With this approach, any past uses of a DOI (such as in a publication) will remain functional and will reference the specific version of the data set that was cited, while pointing users to the newest version if one exists.

### Question: Why don't I see the data set that I uploaded to the ADC?  

Possible Answer #1: The data set is still private because we are awaiting your approval to publish it. Please login with your ORCID ID to view private data sets.
Possible Answer #2: The data set is still private and you do not have access because you were not the submitter. If you need access please have the submitter send us a message from his/her email address confirming this, along with your ORCID ID. Once we receive that confirmation we will be happy to grant you permission to view and edit the data set.
Possible Answer #3: The data set is still private and we accidentally failed to grant you access. I apologize for the mistake. I have since updated the access policy. Please let us know if you are still having trouble viewing this data set here: (URL). Remember to login with your ORCID ID.

### Issue: I would like to display multiple geographic coverages for my data set, but the form only accepts one point or bounding box.  
Unfortunately, the current web form does not allow users to input more than one geographic coverage. We are happy to add multiple coverages (maps) for you. Please provide us with the coordinates. Note that next version of the web form will support the addition of multiple locations by users. We anticipate this release in the coming months.

### Issue: I have MANY files to upload (100s or 1000s).

Can you upload the files to a drive we can access, such as G Drive or Dropbox? Alternatively, if you have a publicly accessible FTP you can point us to, we could grab the files from there. If needed, we have a secure FTP you can access. Details are available [here](https://help.nceas.ucsb.edu/remote_file_access). Please access our server at datateam.nceas.ucsb.edu with the username "visitor". Let us know if you would like to use our SFTP and we will send you the password and the path to which directory to upload to.

### Question: May another person (e.g. my student) submit data using my ORCID ID so that it is linked to me?

We recommend instead that the student set up their own ORCID accounts at https://ORCiD.org/register and submit data sets from that account. Submissions are processed by our team and, at that point, we can grant you full rights to the metadata and data files even though another person submitted them.

### Issue: The web form is not cooperating. 
We apologize that you are experiencing difficulties while attempting to submit your data set. We are happy to attempt to troubleshoot this for you. Send us the following inforamtion:

- The operating system (including the version) and browser (with version #) you are using
- The exact step the issue came up
- The error message you received
- Also, please provide us with any screenshots of the error message

### Question: May I submit a non-NSF funded data set?

Yes, you may submit non-NSF-funded Arctic data if you are willing to submit under the licensing terms of the Arctic Data Center (CC-0 or CC-BY), the data are moderately sized (with exact limits open to discussion), and a lot of support time to curate the submission is not required (i.e., you submit a complete metadata record and well formatted, open-source data files).
For larger data sets, we would likely need to charge a one-time archival fee which amortizes the long-term costs of preservation in a single payment. Also, please note that NSF-funded projects take priority when it comes to processing. Information on best practices for data and metadata organization is available [here](https://arcticdata.io/submit/#preparing-data).

### Question: Can I add another data file to an existing submission without having to fill out another metadata form?  

Yes. Navigate to the data set after being sure to login. Then click the green "Edit" button. The form will populate with the already existing metadata so there is no need to fill it out again. Just scroll to the bottom of the form to "Upload Data", click "Choose File", and browse to the data file you wish to add.
Be aware that the DOI will need to change after you add this file (or make any changes to a data set) as, just like for a journal article, a DOI represents a unique and immutable version. The current URL will remain functional, but clearly display a message at the top of that page stating "A newer version of this data set exists" with a link to the latest version.

### Question: Can I add data anytime or is there some deadline associated with the grant, or some other restriction I'm not aware of?   
We are happy to accept your submission any time; however, NSF has stricter policies. For all ARC supported projects, the policies state that "Complete metadata must be submitted... within two years of collection or before the end of the award, whichever comes first. All data and derived data products that are appropriate for submission... must be submitted within two years of collection or before the end of the award, whichever comes first." For all AON projects, "Real-time data must be made publicly available immediately. All data must be submitted... within 6 months of collection, and be fully quality controlled. All data sets and derived data products must be accompanied by a metadata profile and full documentation."

### Question: Can you clarify what constitutes sensitive information (in relation to social science data and whether it needs to be uploaded)?  
Sensitive information includes human subjects data and data that are governed by an Institutional Review Board policy. Data that are ethically or legally sensitive or at risk of decontextualization also constitute sensitive information.

The NSF policy states "NSF realizes that on occasion there are data gathered of a particularly sensitive nature, such as the locations of archaeological sites or nest locations of endangered species. It is not the intention of this policy to reveal such information publicly. Discipline standards, indigenous community cultural rules, and state and federal regulations and laws should be followed for these types of data." The full policies are available [here](https://www.nsf.gov/pubs/2014/nsf14584/nsf14584.htm#grantcond).

### Question: Can I submit data as an Excel file?   
While the Arctic Data Center supports the upload of any data file format, sharing data can be greatly enhanced if you use ubiquitous, easy-to-read formats. For instance, while Microsoft Excel files are commonplace, it is better to export these spreadsheets to Comma Separated Values (CSV) text files, which can be read on any computer without needing to have Microsoft products installed. Data submitted in Excel workbooks will undergo conversion to CSVs by our staff before being made public.

So, yes, you are free to submit an Excel workbook, however we strongly recommend converting each sheet to a CSV. The goal is not only for users to be able to read data files, but to be able to analyze them with software, such as R Studio. Typically, we would extract any plots and include them as separate image files.