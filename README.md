# About CNSA
CNGB Sequence Archive (CNSA) is a convenient and efficient archiving system of multi-omics data in life science, which provides archiving services for raw sequencing reads and further analyzed results. CNSA follows the international data standards for omics data, and supports online and batch submission of multiple data types such as Project, Sample, Experiment/Run, Assembly, Variation, Metabolism, Single cell, Sequence. Its data submission service can be used as a supplement to the literature publishing process to support early data sharing. CNSA is committed to building a comprehensive and high-quality system for storing, managing and sharing of omics data to provide global researchers with comprehensive data and information resources, so that researchers can access and use them more conveniently, and promote the development of life sciences.

So far, CNSA has archived 2860TB data, 690TB public data, 2410 projects, 372426 samples, 266966 experiments, and 405453 runs.

So far, CNSA has supported 157 articles, 96 magazines, 133 organizations.

Please view the [Statistics](https://db.cngb.org/cnsa/statistic/) for detailed statistics.

# Handbook (simple version)

## Download handbook (simple version)
[CNSA Handbook (simple version in English)](https://db.cngb.org/dc_assets/build/dc_cnsa/handbook/CNSA%20Handbook%20(simple%20version%20in%20English)%20V1.4.pdf)
## Register/Login
Please use the email or mobile number to register/login on the [registration page](https://db.cngb.org/account/signup/?next=%2Fcnsa%2Fsubmit%2F) and fill in the [submitter’s information](https://db.cngb.org/account/login/?next=https%3A%2F%2Fdb.cngb.org%2Fmycngbdb%2Fsubmitter).

## Enter the submission portal
Click “Submit” on the CNSA homepage or click “Submission portal” on the homepage navigation bar to enter the Submission portal page.

## Submit project
### 1. Enter the submission process

Click “Project” on the Submission portal page to enter the submission process.

### 2. Submit project information

Select Data access manner -> fill in the basic information -> fill in the details -> overview -> submit

Notes:

The first step in project submission requires the choice of Data access manner. If you choose "Public" or "Controlled", the release date can refer to the date the article will be published, and the recommendation is later than the date the article will be published.
The information of the article also can be supplemented after the article is published.
After the project is submitted successfully, you can get the CNSA assigned project accession (prefixed with CNP) in “My submission-Project”.
Submit review materials
After the project is submitted successfully, the system will send the “Data Submission Application Form” to your email address. Please send the completed form and the relevant review materials required in the form to the mailbox (bdcro@cngb.org) of CNGB Bioresource Sharing Compliance Center (BSCC) as soon as possible.BSCC will send you an email to confirm the receipt of the complete materials. Please note that it will generally take 3 working days for the material review. After the material review is passed, the data administrator will conduct the project review. If you have questions about the review materials, please contact bdcro@cngb.org.

Submit sample
1. Enter the submission process

Click “Sample” on the Submission portal page to enter the submission process.

2. Submit sample information

If you submit only one sample at a time, we recommend that you choose a single submission method. If you submit multiple samples at a time, we recommend that you choose the batch submission method.

（1）Single submission: Select "Submit a single sample" -> select sample type -> fill in sample attributes -> Fields pass check-> overview -> submit

（2）Batch submission: Select "Submit batch samples" -> Select sample type -> Download template -> Upload completed template -> Template pass check -> Submit

Notes:

Please select the sample type correctly and you can't modify it by yourself after submitting.
The sample name cannot be duplicated.
When filling out the batch template file, please view the related description and field comments first. If some required fields are missing, you can fill in 'not collected', 'not applicable' or 'missing'. If the taxonomy ID or scientific name of the organism is unclear, you can enter the single submission process to search and ensure that the information is correct.
Collection date supports 4 data formats, YYYY, YYYY-MM, YYYY-MM-DD, YYYY-YYYY.
The number of uploaded file lines cannot exceed 2000. If it exceeds 2000, please submit in multiple processes.
After the sample is submitted successfully, you can get the sample accession assigned by CNSA (prefixed by CNS) in “My submission-Sample”.
Submit experiment/run
1. Enter the submission process

Click “Experiment/run” on the Submission portal page to enter the submission process.

2. Submit data files and metadata

If you submit only one experiment/run at a time, we recommend that you choose a single submission method. If you submit multiple experiments/runs at a time, we recommend that you choose the batch submission method. 

（1）Single submission: Select submission type (Submit a single experiment/run) -> Fill in basic information -> Fill in metadata -> Metadata pass check -> Submit data files -> Data files pass check -> Overview ->Submit

（2）Batch submission: Select submission type (Submit batch experiments/runs) ->Upload data files->Download metadata template->Upload completed metadata template->Metadata pass check ->Data files pass check -> submit

Notes:

It is recommended to upload the data files first. All users can upload data via FTP or mail the hard drive.

（1）You just finished uploading after the data is uploaded to the FTP personal directory.

（2）FTP server, username and password can be viewed in the submission process or "My service". Each user has a unique FTP account.

When filling out the batch template file, please view the related instructions and field comments first. One line represents a run. If a sample is associated with multiple data files, please submit them in multiple lines to ensure that the experiment information is consistent and the library name is unique. The file name and MD5 value of each data file are unique.
The number of metadata file lines cannot exceed 2000. If it exceeds 2000, please submit in multiple processes.
After the experiment/run is submitted successfully, you can obtain the accession assigned by CNSA in “My submission- Experiment/run” (Experiment: prefixed with CNX; Run: prefixed with CNR)
Submit assembly
1. Enter the submission process

Click “Assembly” on the Submission portal page to enter the submission process.

2. Submit data files and metadata

If you submit only one assembly at a time, we recommend that you choose a single submission method. If you submit multiple assemblies at a time, we recommend that you choose the batch submission method. 

（1）Single submission: Select submission type (Submit a single assembly) -> Fill in basic information -> Fill in metadata -> Metadata pass check -> Submit data files -> Data files pass check -> Overview ->Submit

（2）Batch submission: Select submission type (Submit batch assemblies)->Upload data files->Download metadata template->Upload completed metadata template->Metadata pass check ->Data files pass check -> submit

Notes:

It is recommended to upload the data files first (currently only supports the FASTA format). All users can upload data via FTP or mail the hard disk.

（1） You just finished uploading after the data is uploaded to the FTP personal directory.

（2） FTP server, username and password can be viewed in the submission process or "My service". Each user has a unique FTP account.

When filling out the batch template file, please view the related instructions and field comments first. One line represents an assembly, ensuring that the assembly name of each assembly is unique, and the file name and MD5 value of each data file are unique.
The number of metadata file lines cannot exceed 2000. If it exceeds 2000, please submit in multiple processes.
After the assembly is submitted successfully, you can get the CNSA assigned assembly accession (prefixed with CNA) in “My submission-Assembly”.
Submit variation
1. Enter the submission process

Click “Variation” on the Submission portal page to enter the submission process.

2. Submit data files and metadata

（1）Submit SNP: Select variation type (SNP) -> Upload data files to ftp-> Download metadata template -> Upload completed metadata template -> Metadata pass check -> Data files pass check -> Submit

（2）Submit SV: Select variant type (SV) -> Upload data files to ftp (optional) -> Download template -> Upload completed template -> Pass check -> Data files pass check (if submitted) ->Submit

（3）Submit CAHV: Select variation type (CAHV)->Download template->Upload completed template-> Pass check->Submit

Notes:

If the selected variation type is SNP, you are advised to first upload the data files (currently only supports VCF format). All users can upload data via FTP or mail the hard disk.

（1） You just finished uploading after the data is uploaded to the FTP personal directory.

（2） FTP server, username and password can be viewed in the submission process or "My service". Each user has a unique FTP account.

When filling out the batch template file, please view the description and field comments first. If you need to upload VCF files, make sure that the file name and MD5 value of each data file are unique.
After the data has been reviewed, you can get the variation accessions (prefixed by varc) assigned by CNSA in “My submission-Variation”.
Submit metabolism
1. Enter the submission process

Click "Metabolism" on the Submission portal page to enter the submission process.

2. Submit data files and metadata

Upload data files-> Download “Descriptions” template -> Upload completed “Descriptions” template -> Add “Assay” ->Download the template of the created “Assay” -> upload the completed “Assay” template ->Metadata pass check -> Data files pass check -> Submit

Notes:

You are advised to first upload the data files. All users can upload data via FTP or mail the hard disk.

（1） You just finished uploading after the data is uploaded to the FTP personal directory.

（2） FTP server, username and password can be viewed in the submission process or "My service". Each user has a unique FTP account.

The "descriptions" information is required, and at least one assay needs to be created. A new assay can be added after the previous assay is uploaded.
The number of lines in each sheet of the metadata file cannot exceed 2000. If it exceeds 2000, please submit in multiple processes.
When filling out the template file, please view the description and field comments first, and make sure that the file name and MD5 value of each data file are unique.
After the data has been reviewed, you can get the metabolism accession (prefixed by METM) assigned by CNSA in “My submission- Metabolism”.
Submit single cell
1. Enter the submission process

Click “Single cell” on the Submission portal page to enter the submission process.

2. Select the associated project accession and fill in the number of cells.

3. Submit data files and metadata

Upload data files-> Download metadata template -> Upload completed metadata template -> Metadata pass check -> Data files pass check -> Submit

Notes:

You are advised to first upload the data files. All users can upload data via FTP or mail the hard disk.

（1） You just finished uploading after the data is uploaded to the FTP personal directory.

（2） FTP server, username and password can be viewed in the submission process or "My service". Each user has a unique FTP account.

The expression matrix file is required, and other file types are optional. If your gene expression files, metadata files, and cluster files need to be grouped, please add the group name to the file name.
The number of lines in each sheet of the metadata file cannot exceed 2000. If it exceeds 2000, please submit in multiple processes.
When filling out the template file, please view the description and field comments first, and make sure that the file name and MD5 value of each data file are unique.
After the data has been reviewed, you can get the metabolism accession (prefixed by CSE) assigned by CNSA in “My submission-Single cell”.
Submit virus sequence
1. Enter the submission process

Click "Virus sequence" on the Submission portal page to enter the submission process.

2. Select the release date of this submission.

3. Submit data files and metadata

Upload data files to ftp-> Download metadata template -> Upload completed metadata template -> Metadata pass check -> Data files pass check -> Submit

Notes:

You are advised to first upload the data files (currently only supports FASTA format). All users can upload data via FTP or mail the hard disk.

（1） You just finished uploading after the data is uploaded to the FTP personal directory.

（2） FTP server, username and password can be viewed in the submission process or "My service". Each user has a unique FTP account.

When filling out the template file, please view the description and field comments first, and make sure that the file name and MD5 value of each data file are unique.
After the data has been reviewed, you can get the virus sequence accessions (prefixed by N_) assigned by CNSA in “My submission-Virus sequence”.
Submit sequence
1. Enter the submission process

Click “Sequence” on the Submission portal page to enter the submission process.

2. Select the release date of this submission.

3. Submit data files and metadata

Upload data files-> Download file list template -> Upload completed file list template -> File list pass check -> Data files pass check -> Submit

Notes:

You are advised to first upload the data files (currently only supports GBFF format). All users can upload data via FTP or mail the hard disk.

（1） You just finished uploading after the data is uploaded to the FTP personal directory.

（2） FTP server, username and password can be viewed in the submission process or "My service". Each user has a unique FTP account.

When filling out the template file, please view the description and field comments first, and make sure that the file name and MD5 value of each data file are unique.
After the data has been reviewed, you can get the virus sequence accessions (prefixed by N_) assigned by CNSA in “My submission-Sequence”.
Memo
1. Data release

The release date can be set in the “Data Management” in the project submission process. Only the date today or within two years after today can be selected. The data will not be made public until the submitted data is reviewed by the reviewer and reaches the release date set by the user. If the data is about to reach the release date, the system will send a reminder email 15 days in advance.

2. Modify and delete

On the "My Submission" page, you can click the "pencil icon"  in the status column to modify. If the status column does not have a "pencil icon" , please send an email to datasubs@cngb.org and indicate the submission ID or data accession and the reason for the modification.

（1）Modify release date

If the status of the project is “Unfinished”, go to “My submission”, and click “pencil icon”  in the project status column to enter the modification process.
If the status of the project is "Processing" or "Processed", you can modify the release date by clicking the date in the release date column or the "pencil icon" .
If the status of the project is “Public” or “Controlled”, the release date cannot be modified by yourself. If you need to make changes, please send an email to datasubs@cngb.org and indicate the project accession and the reason for the change.
（2）Delete submission

If the status is “unfinished”, click the “trash can icon” to delete the submission. If it is in other status, please send an email to datasubs@cngb.org and indicate the submission ID and the reason for the deletion.

3. Data association

The information of the sample will only be triggered after the experiment/run or assembly is submitted; only after the experiment/run or assembly is reviewed and the data is public, all the information associated with the project can be retrieved according to the project accession. Otherwise, the information of the project and sample can only be retrieved separately, and no association will occur.

4. MD5 check

Please fill in the file name and MD5 value of the uploaded data file, and then click "Check", there are maybe four statuses:

（1）Not uploaded: The data file is not uploaded or being uploaded. If you have uploaded the data file, it still shows "Not uploaded". Please click "Check" later.

（2）Calculating: The data file has been uploaded, but the MD5 value of the file has not been calculated or is being calculated. Please click "Check" later.

（3）MD5 mismatch: The MD5 value calculated by the system is inconsistent with the MD5 value you filled in. If the data file is only uploaded a part and in check, the MD5 value calculated by the system will be inconsistent with the one you filled in. Please click "Check" later. If you click "Check" after a long time (such as half an hour), the status still shows "MD5 mismatch", please recalculate and fill in the MD5 of the data file. If the status still shows "MD5 mismatch", please contact datasubs@cngb.org and indicate the file name in the email.

（4）Check finished: The data file has been uploaded and passed the check.

5. View accessions and submitted metadata

On “My submission” page, you can directly view the accession of a single submission, download the batch-submitted attribute files with accessions in the status column, or click on the completed submission ID to view the details.

6. Contact us

If you have any questions, please contact the administrator at datasubs@cngb.org or 0755-33945586.
