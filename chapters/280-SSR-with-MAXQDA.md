# Methodology
## Using MAXQDA for a systematic scoping review

Using a Qualitative Data Analysis application along with a bibliographic database means that a single source set of data can be collected and categorised in a way that preserves the connection between bibliographic record and full text, while at the same time allowing both qualitiative and quantitative data analysis of document variables and user-added or automatic coding.

As the systematic aspect of the review should be replicable {Arksey, 2005 #7;Peters, 2015 #5}, keeping each set of documents separate during the early stages of the process allows repeat review. This is more likely in a scoping review as iterative refinement of protocol occurs {Peters, 2015 #5}, when the full range of data is not  initially known {Arksey, 2005 #7;Peters, 2015 #5}.

A full description of the search sequence and terms is available in the Literature Review Method chapter. All results were saved to source-specific EndNote Library. Where full-text was available, these were attached to the bibliographic record and the filename changed to consistently be author-year-title. This is important because in MAXQDA this is how you will identify the documents in the document list.

There are arguments to be made both for creating a coding system prior to importing documents to MAXQDA and for allowing codes to emerge from the content of the documents themselves. As I had begun the project with a different focus, I had a legacy code set that I did not remove. Its development was a thorough and deliberate endeavour and it will be useful in the broader, non-scoping, Literature Review.

While MAXQDA does allow import/export of documents, codes and variables, there are technical affordances in creating a blank project file, then saving a copy of this with the name of the data set you are about to import if you want to use a pre-determined coding system. However, for a scoping review, the codes may take several sets of documents to develop as different sources introduce new nuances that must be accommodated.

Like EndNote, MAXQDA does not recommend storing your project or associated files in a networked or cloud-linked folder such as Dropbox. This necessitates an organised approach to file and folder locations as both applications have dependencies and default behaviour that they prefer. I found it helpful to keep a list of the locations as I was transferring both sets of data between two computers. (Example at /Users/eb/Dropbox/Documents/-Fed/Termites-and-Butterflies/Documents/File_Locations.xlsx)

I decided that for each application, I would create a projects folder in the local computer's  Applications folder as the path on both Macs will be a stable location. For each EN and 2020, there is a titled folder in the Applications folder of each Mac, containing:
- the application
- necessary support files
- a sub-folder with option-f extension containing current project files.

Then, in Dropbox, for each applicaiton an an "_Exchange"_ folder, which contains the sub-folder, which will be copied from the current and to the next current device as needed, and back again.

### Workflow

1. Work on local machine, save Library/Project in specified folder.
1. Copy folder to an Exchange folder on Dropbox.
1. Copy folder from that Exchange folder to next local machine (the Plus version allows installation on two computers).
1. When finished, copy back to Exchange and repeat from step 1 on other computer

It's REALLY important to note that once documents (or videos, or audio) are imported to MAXQDA they can't be modified, only coded and annotated. Quality Assurance should be carried out at each stage to avoid multiple versions of a document with different details.

The next set of files to export from EN should be a small, exploratory set, with procedure replicable as part of the SSR. I began with the output from epistemonikos as it had a small number of files but more than one.

### EndNote preparation
1. Export results from database as .RIS
1. Import to EndNote (doesn't have to be a new Library at this point)
1. Check that all abstracts are in place in EndNote (so they come into MAXQDA, particularly important if no full-text)
1. Find full text if possible
1. Rename attachments author-date-titles
1. Copy the records to new library, eg <EN-epistemonikos.enl> (this ensures that the renamed PDFs are in a folder unique to this library - important for MAXQDA import later)
1. Select all documents and Export as .RIS (RefMan output option, will have a .txt extension on filename)

### MAXQDA import
1. Import > Reference Manager Data > Import from EndNote to import both the "References" and References> Attachments.
*Leave the 'external' box unchecked, so the original PDFs will stay in the EndNote PDF folder and still be accessible within EN but won't show your coding in EN.*
2. (optional) I moved the PDFs (Attachments) into the RIS (References) folder which I retitled epistemonikos so all documents were co-located and the relationship between reference and document was easy to identify.

#### Mistakes happen
After some technical issues related to Mac-only MAXQDA installations, I needed to replace an already-coded PDF that had become embedded in the project with a linked PDF to be consistent with the others.

From a Library specifically created just for this addition to the project, I used **Teamwork> Teamwork Export: Data Exchange file write** to create an exchange file with the two documents (RIS & PDF) of this specific paper.

I then opened the destination project and used **Teamwork> Teamwork Import: reading from Exchange file data**. It asked whether I wanted to import the RIS as new, and wanting to retain the original, I unchecked that box, and it recognises the PDF as the name is identical so correctly replaces it, confirming 22 codes and 8 coded segments. Next. Overwrite existing segment boundaries with imported ones? yes. Other options are inner bounds, outer bounds and keep existing. 52 variables? not sure that I might want to delete those. Import.

Automatically creates a backup prior to Merge.

#### Technical points to note, potentially only Mac
a. Always start with an empty project file saved as the name of the import you're about to do so the PDFs don't get duplicated.
Saving a copy duplicates the PDFs internally
b. When you want to replace previously coded documents, create a project with those files, then use Export / Import to retain the coding.

### Reviewing the Documents

For content analysis of any data type, there is a balance between breadth and detail, and you will need to select what is relevant to you and what is simply background. MAXQDA Dictio's stop list feature {VERBI Software, 2019 #7616} allows you to exclude terms from analysis either by manually entering them into the system or by uploading text files. More details about how you might do this is below.

For text document reading and review, while prior versions of MAXQDA required you to manually convert each PDF to text to make it searchable, the 2020 update searches PDF text provided it has been created using a text editor or has been though a character recognition process. It is still important to develop a search strategy you will use consistently, in order for your work to be replicable. MAXQDA2020's Lexical Search feature {VERBI Software, 2018 #7617} allows you to save complex boolean searches that can be applied in other projects. More information about creating a search strategy is below.

__Too detailed? make available somewhere else?__

#### Creating a "stop list"

Depending on the purpose of your review, you could create either a pre-developed list of terms to exclude (for example, if you definitely didn't want analysis to include the words "random" or "trial" as data). For an exploratory review like mine, you might chose a data-driven approach to identifying terms within this set of records which could be useful to limit results in future searches and provide cleaner data for analysis. An example of this is below.

##### Example of data-driven stop list development

MAXQDA2020 offers one set of pre-configured stop list words in English, principally "definite and indefinite articles, conjunctions, or numerals". {VERBI Software, 2019 #7616}. Even though these lists had been uploaded, the clouds and tables showed that several variations were still included. To remedy this, I used the application's interface to manually add words already established as stop words (for example, "a", "the" and "did") to the stop list. This is appropriate to use for my review, but is not adequate to exclude the range of clinical or therapeutic contexts which are not relevant to higher education learning, teaching and research, particularly for databases with large output sets such as PSYCHINFO.

Once I had uploaded the additional stop word list to MAXQDA2020, I re-ran the word frequency analysis to check that the result foregrounded more relevant terms, such as "self", "group", and "cognitive". While these terms may be found in a clinical context, they are also potentially relevant to educational research and could not be excluded at this stage of the review.

My next step was to work through the frequency table line by line, and develop a custom stop list based on my research aim - to provide a benchmark of how RepGrid has been operationalised in education, preferably higher education. By the 100th row of the frequency output, variations on the previous terms were frequent and I concluded it was likely I had reached saturation of these terms, at least for this data set.

After reviewing these 100 terms, I then broke them down into categories, and determined those that may be too relevant to exclude. The data from this is at Table N.

| possessives | articles | conjunctions | generic research words | tech  | other   | numbers  | clinical terms from epistemonikos-all | add to specific stop list just for RepGrid terms | retained       | reason                                                                |
|-------------|----------|--------------|------------------------|-------|---------|----------|---------------------------------------|--------------------------------------------------|----------------|-----------------------------------------------------------------------|
| their       | the      | and          | found                  | https | yes     | one      | patient                               |                                                  | self           | PCP foundation                                                        |
| our         |          | of           | research               | http  | had     | two      | patients                              |                                                  | heart          | may be used in another context, but add to stop if continual clinical |
|             |          | also         | reported               | doi   | using   | three    | medication                            |                                                  | adherence      | difficult to contextualise                                            |
|             |          | for          | measures               | www   | to      | four     | medicine                              |                                                  | belief/s       | PCP foundation                                                        |
|             |          | with         | used                   | com   | related | five     | medicines                             |                                                  | grid           | RepGrid                                                               |
|             |          |              | review                 |       | life    | six      | clinical                              |                                                  | group          | important for my context                                              |
|             |          |              | results                |       | in      | seven    | clinician                             |                                                  | study          | difficult to contextualise                                            |
|             |          |              | people                 |       | non     | eight    | depression                            |                                                  | failure        | difficult to contextualise                                            |
|             |          |              | data                   |       | years   | nine     | surgery                               | constructs                                       |                | PCP foundation                                                        |
|             |          |              | compare                |       | would   | ten      | therapy                               | elements                                         |                | PCP foundation                                                        |
|             |          |              | compares               |       | there   | twenty   | psychosis                             |                                                  | treatment      | may be used in another context, but add to stop if continual clinical |
|             |          |              | compared               |       | weight  | thirty   | psychoses                             | personal                                         |                | PCP foundation                                                        |
|             |          |              | analysis               |       | aqlq    | forty    | disease                               |                                                  | score/s        | difficult to contextualise                                            |
|             |          |              | outcome                |       | did     | fifty    | pgi                                   |                                                  | adherent       | difficult to contextualise                                            |
|             |          |              | based                  |       | use     | sixty    | schizophrenia                         |                                                  | individual/s   | difficult to contextualise                                            |
|             |          |              | studies                |       | used    | seventy  | clin                                  |                                                  | cognitive      | difficult to contextualise                                            |
|             |          |              | study                  |       | seiqol  | eighty   | chronic                               |                                                  | subject/s      | may be used in another context, but add to stop if continual clinical |
|             |          |              | journal                |       | na      | ninety   | med                                   |                                                  | care           | difficult to contextualise                                            |
|             |          |              | sample                 |       | new     | hundred  | nr                                    |                                                  | generated      | difficult to contextualise                                            |
|             |          |              | et                     |       | age     | thousand | recovery                              |                                                  | health         | difficult to contextualise                                            |
|             |          |              | al                     |       | time    | million  | depression                            | technique                                        |                | PCP foundation                                                        |
|             |          |              |                        |       | could   | number   | trial                                 |                                                  | months         | difficult to contextualise                                            |
|             |          |              |                        |       | were    | numbers  |                                       |                                                  | quality        | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | scale          | PCP foundation                                                        |
|             |          |              |                        |       |         |          |                                       |                                                  | control/s      | may be used in another context, but add to stop if continual clinical |
|             |          |              |                        |       |         |          |                                       |                                                  | identity       | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | mean           | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | activities     | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | fluid          | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | social         | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | management     | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       | rgt                                              |                | PCP foundation                                                        |
|             |          |              |                        |       |         |          |                                       |                                                  | mars           | may be used in another context, but add to stop if continual clinical |
|             |          |              |                        |       |         |          |                                       |                                                  | â              | impossible to contextualise                                           |
|             |          |              |                        |       |         |          |                                       | elicited                                         |                | PCP foundation                                                        |
|             |          |              |                        |       |         |          |                                       |                                                  | important      | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | intervention   | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | necessity      | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | water          | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | affect         | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | higher         | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | positive       | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | significant/ly | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | different      | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | behavioural    | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | overall        | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | perception/s   | PCP foundation                                                        |
|             |          |              |                        |       |         |          |                                       | psychology                                       |                | PCP foundation - but not looking to focus on this.                    |
|             |          |              |                        |       |         |          |                                       |                                                  | statements     | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | change/s       | difficult to contextualise                                            |
|             |          |              |                        |       |         |          |                                       |                                                  | concern/s      | difficult to contextualise                                            |



#### Creating a search strategy

Depending on the purpose of your review, you may have a pre-developed search strategy such as "random control trial" AND "breast cancer". Again, for an exploratory review, a data-driven approach can provide insights into how a search might be most effective.


##### Example of data-driven search strategy

For me, the next step was to search for anything in the set that was relevant to my research aim. The stop word lists are not applicable to the Lexical Search function in MAXQDA, so I used the list to develop a search strategy for exclusion, while looking for the terms "educa*" (to avoid finding variations of reduc*), and "repertory grid" or "repgrid" or "grid". The lexical search parameters I used are at Table N.

| Lexical search parameters |                |
|------|------------------------|
| ALL: | educa*                 |
| ANY: | "repertory grid" repgrid |
| NOT: | patient                |
|      | patients               |
|      | medication             |
|      | medicine               |
|      | medicines              |
|      | clinical               |
|      | clinician              |
|      | depression             |
|      | surgery                |
|      | therapy                |
|      | psychosis              |
|      | psychoses              |
|      | disease                |
|      | pgi                    |
|      | schizophrenia          |
|      | clinic                 |
|      | chronic                |
|      | med                    |
|      | nr                     |
|      | recovery               |
|      | depression             |
|      | trial                  |
|      | counsel                |
|      | counselling            |
|      | child                  |
|      | children               |

__end too detailed?__



## Refining your results

Once you run this search, the subset of records that match the search parameters will display in a _Results_ window. At this point, you can review the context of each hit by clicking the **Detailed list of search hits** button. In the first result found, for example, the full sentence is displayed: "Exploring beliefs about heart failure treatment in adherent patients: use of the repertory grid technique". This shows me it is not the setting I am searching for. I can then select enough text in the document (usually the abstract) to make it clear why I am not including it, and then code it to show it is not to be included in the reported output.

Where the result is relevant to context, use a code to categorise where the document belongs in your search. These codes can later be converted to variables for analytical purposes (for example, count how many documents the search terms are in as opposed to how many times the search string occurs).

Figure 1 shows an example of coding applied from the Setting, Research and Something Else categories. This document does meet the criteria for inclusion in the review.

/Volumes/eb/Dropbox/Documents/-Fed/Termites-and-Butterflies/Analysis Files/code-assignment-example-APlus.png

Technical note - this record also has the Autocoded segments that all RIS records do. You can turn these off to display selected codes by Activating those codes first, then right-clicking the coding strip, checking _Only Activated Codes_, then **OK**.

A useful method for double-checking your coding if you have a search strategy is to select the code you want to check, then right-click to activate all documents containing that code. Then use a Lexical Search to search only those documents for terms that should be included or excluded. For example, I wanted to double check that I had manually reviewed all records that would not have been found because they contained "child*", and added the "Higher Education" code if it should be applied.

Alternatively, use the Code Matrix Browser to display a table of all (or activated) documents and codes.

Each time I updated the EN Libary, I could re-import th RIS to add only new or updated records in 2020.

Trying to get only the additional attachments in to 2020, so have exported those as a Library and will then do a new project and then export for merge,
Trying to get only the additional attachments in to 2020, so have exported only those EN records with an attachment to a new .RIS file, so the Library PDF folder in place. Then created a new library with just those documents. Then exported a teamwork mex from that project.  Then imported that to Termites-ALL. I took screen shots of "not identical" and some are eplacing files in other database folders. Does this matter? The count in PQ will be accurate, as will those in other folders, provided I do the count on just the PDFs + fulltext needed. Realised needed to save to new Library before export to find attachments. Re-do. Then coded new files in 2020.

When I finish getting all th ful-texts, it's better to import the first EN into the second, so it deletes the non-attachment records.

With the really big datasets (>1000), need to chunk Lexical search into smaller sets of activated documents to avoid crashing.

When coding, its helpful to use the citation for the FTR code, but if you want to be able to search effectively, you need to apply the codes to a single segment rather than to the variables.

## If you do want to use 2020 for interaction Analysis
# Importing transcripts
For non-timestamp transcrips from otter.ai, select all the times, and apply para style. Then search for the ^p in that para style and replace with "#^pSpeaker: ". Then ^p^p -> " #"
