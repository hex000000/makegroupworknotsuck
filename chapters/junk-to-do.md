### Because I was Learning
I did a slightly different analysis on grid sets 1 and 2, against 3. I need to:

1. Re-assess all grid sets for originality
2. Re-assess grids from 5022 and 5024 for additional characteristics, eg RC EP EI Superficial, Vague or empty.
3. Re-shot all images with consistent look and feel

use RepGrid for role plays where participant roles are randomised.


One of the practical challenges to both students and researchers using the Repertory Grid Technique is the difficulty of large-scale comparison without installing and using the RepPlus software.
The software is easy to install, compatible with Mac, PC, and as a Windows Server instance [RepPlus](repppa00000.shared.sydney.edu.au). The software is available to download from the [RepPlus website](https://pages.cpsc.ucalgary.ca/~gaines/repplus/markdown-4/). It is 32-bit and will not run under the newest Mac OS release 'Catalina'.

With this in mind, I am working on simple workflows to gather and aggregate RepGrid data in ways other than RepPlus, as well as RepPlus.

PDF not available for

- Historical Artifacts as Recreational Resources (pp. 393-416)
From: Recreational Land Use: Perspectives on Its Evolution in Canada
VICTOR A. KONRAD
McGill-Queen's University Press (1982)

- Intergroup Communication on Religion and the Troubles among University Students in Northern Ireland
Maurice Stringer, Olaf Hvattum
The Irish Journal of Education / Iris Eireannach an Oideachais, Vol. 24, No. 2 (Winter, 1990), pp. 48-61
Topics: Catholicism, Protestantism, The Troubles, Questionnaires, Interpersonal interaction, Depth perception, College students, Friendship

- The Applicability of Personal Construct Theory and Repertory Grid in Studies of Tourism Development - A Methodological Evaluation / ישומה של תאורית "המבנה האישי" במחקרי תפיסה של תהליכי פתוח תיירות - הערכה מתודולוגית
עודד גינוסר, יואל מנספלד, Oded Ginosar, Yoel Mansfeld
Horizons in Geography / אופקים בגאוגרפיה‎, No. 37/38 (תשנ"ג - 1993), pp. 35-49

- Performance Issues in U.S.–China Joint Ventures
Gregory E. Osland, S. Tamer Cavusgil
California Management Review, Vol. 38, No. 2 (Winter 1996), pp. 106-130
Topics: Joint ventures, Parent companies, Prices, Government officials, Technology transfer, Consumer goods industries, Financial management, High technology industries, Government performance

- BOOK CHAPTER
The Letter Project – students’ own stories (pp. 163-198)
From: Cultural warfare and trust: Fighting the Mafia in Palermo
CARINA GUNNARSON
Manchester University Press (2008)
Topics: Teachers, Social classes, Warfare, Socioeconomics, Trust, Friendship, Questionnaires, Secondary schools, Peer relations, Classroom environment





"Document variables, which display how often a code exists (their source is acknowledged as “code”) can be transformed into a binary variable by clicking on the  “COnvert to boolean variable” button. After it is transformed the variable will not show, how often a code has been assigned in the document, but if it has been assigned in this document or not."

Selected codes, right-click and   "Transform to document variable".
A column is added for each in the Data Editor window, with the number of codings as an integer.
In the Document Variables List, click the Categorical checkbox.
Click the Convert to Boolean button
Mixed Methods Tab, Activate documents by Variables
Conditions Lex-search-RIS=0 AND Lex-search-RIS=0 -> Creates a saved set
Also found on the Code More.. contextual menu an Invert Activation option.

But now activated, how do I apply a code to them?
Can I do it programmatically through a variable?
Repeat previous actions with Lex-search-NO
Can't use normal coding because no text selected in the Documents

In Data Editor for Document Variables, I can click each of the Lex codes in turn to sort by code. Clicking RIS, then PDF, then NO means that all the documents with the first two codes are at the top/bottom of the list. Can't also show only Activated documents.

Can't select multiple documents. Can't input as in the click the NO box manually. I think I will just have to leave it as a set for now. The purpose is only to double check the search strategy.

What is my purpose?  To see if all the documents that I want to find were found. So I need to go through all those that didn't make the cut to see any parameters I need to change. A new code for those called Lex-MISS

eek! working in backup and know I can't save as... Repeat.

OK have the set re-created, now will work through all uncoded documents searching for educ* in both abstract and PDF. All documents that "should" have been picked up will be coded with Lex-MISS. Sorted by name because sometimes that turns out to be helpful. Immediately helpful because at least the Folder (which contains both RIS and PDF) and author / year are easy to compare.

Start 20191128 20:20
Tried Export Components to Project Files produced a detailed xlsx - I wanted the document titles to keep a record as I checked. Sheet "Coded Segments" column C contained the Code, separating those in the "Other" folder from the Lex-search files. This was accidental but useful.

 Problem was that when I filtered the documents to only show "other", I couldn't then subtotal them on the same page. Remove subtotoals.aha! remembered there's a conditional formatting that colours duplicates. then can I sort by colour? Way too much data, slow to manipulate. Can I export Sets as part of the document system? Nope, not included in the xport/. OK, links export should pick up one document per PDF if I get links just for th ePDFs. Realise it's easier to split into PDF not found and RIS not found, RIS will have extra links like URLs in them.

 Go back to Data Editor - all documents. click by hand NO on everything that's not PDF or RIS. Then I want to repeat the search but without "Psychology" as a stop word and see if I get a comparable list.

 OK Exported variables out to Excel. Use filters to identify documents with 0 in RIS or PDF variable and add a 1 into NO. Tested and 26 found with 1 in PDF and 6 in RIS so correct set. SORT so selection is easier. Reimported. It added some new RIS-specific fields, but looks like it worked to set NO to 1. I changed the variable name to indicate that it denotes those works not found by the first pass of searching.

 Going back and double-checking this document, there were 362 records, one of which will have been the duplicate PDF. So the 361 00 is correct. On checking, I found 32 records that weren't in any of the three sets (my manual intervention clearly failed.) I did this in Excel, but how should I do i in 2020? [now finds 7 RIS, still 26 PDF, NOTIDd1 301; there are 393 named documents]

 Used mixed methods activate by variable with all three AND=0; there are the 60 documents, all EN except one; the PDF uncoded, EN coded. Go to Analysis, summary grid with EN activated to see if any had been "set" coded NOPE none. I think this was just error on my part, still not sure about the odd number of records. But now will code that unfound set and it should then be empty. Not quite accurate to say missed here, but investigation worthwhile and so was review.

 see the T&B spreadhseet logic & strategy tabs




 | Set                                    | Parameters                                                                                                                 | Number |
 |----------------------------------------|----------------------------------------------------------------------------------------------------------------------------|--------|
 | Lex-search-NOTIDd1=1                   | Should be identical, as I added the NOT variable manually                                                                  | 300    |
 | Lex-search-PDFs=0 AND Lex-search-RIS=0 | All documents that did not have either variable = 1 (that is, those not found in the first pass over RIS and PDF documents | 361    |

#### What accounts for the difference?
Export both sets of variables to Excel: /Volumes/eb/Dropbox/Documents/-Fed/Termites-and-Butterflies/Data/RepPlus-Doc-Set-Variables-Compare.xlsx

Sort by RIS_Title, Conditional formatting, format unique values green (those without matching PDF or RIS), then filter by cell colour. 31 unique values in PDF/RIS; 80 unique in the NotIDd1. maybe I need to combine the sheets and then check?


 Now I will re-run the search without psychology in the stop words. It's not there already!

 patient
 patients
 medication
 medicine
 medicines
 clinical
 clinician
 depression
 surgery
 therapy
 psychosis
 psychoses
 disease
 pgi
 schizophrenia
 clinic
 chronic
 med
 nr
 recovery
 depression
 trial
 counsel
 counselling
 child
 children

Difficult to know what's ruling it out so I am going to hand check all the NOTIDd1 and code them, Keeping an eye on what the stoppers are, or whether it's accurate.
I can code with MISS those that should have been found and run a lexical analysis on them.
I can code with anothe NO those that were rightly ignored.
Then I can compare with the Variables-Mod sheet if I think I've missed anything.

When NO coding, selecting enough of the document to make it clear why not.
If MISS and NO together, means should have been picked up for the term but is not relevant to education context. [this not really rigid - be more specific]

Decided the feedback trainer papers that are technical are not included. Many of the Gaines papers were about training feedback systems to train control techs, or generally about the usefulness of computers in Ed. Not RepGrid.Mostly also perceptual motor skills, can group by that on another pass. "human controller" search should get all these.human adaptive controller, feedback training, learning machine,

Realised that the MISSs so far have been Ed but not RepGrid. Reclassify NO to No RepGrid no Ed and MISS to only those with both.

Searching documents by hand for these terms.

Those rightly ignored coded as NO.

So. Those that were not found before, but which contained "educa*" AND "grid" weren't found in some cases because the search parameters specified "repgrid" or "repertory grid".

How do I find them in 2020?
They will all be coded with MISS. Turns out I coded them NotIDd1. Is that bad? It will depend if any of the NO also have this code because they are in the set that wasn't found. Don't think it's a problem.

| Code               | Definition                                                                                                                                                                                                                                                                   |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Lex-search-NO      | does not meet query parameters including having "repertory grid" OR repgrid AND educa*on first pass AND after manual review                                                                                                                                                  |
| Lex-search-NOTIDd1 | not found in RIS or PDFs but DOES meet SOME query parameters including having educa* and "grid" but some have repertory grid or repgrid, so must have stopwords, while others have webgrid or other *grid - manual search was for grid to see extent of this potential issue |
| Lex-search-RIS     | met query parameters on first pass in EN record                                                                                                                                                                                                                              |
| Lex-search-PDFs    | met query parameters on first pass in PDF record                                                                                                                                                                                                                             |

still a bit shaky on these numbers.

realised I am getting codes and variables confused - I had converted the previous codes to variables but not the most recent. Decided just to do the NO as there will only be one of those for each document (one per RIS one per PDF)- can be binarised as before anyway.

1. co to code system
1. select code
1. right click -> transform to document variable
1. select document system
1. Variables menu -> list of document Variables
1. Click the variable, then command-B or the little 101 button to convert


### Analyse these results - how reliable are they for larger data review?
1. Select set
1. Activate all Documents
1. Analysis tab  

It left the original coding intact.



---
so now I'm ready to tidy things up a bit...
Records searched (separate EN and PDF)
Overlap in ES is one more EN than PDF. 63rd gaines 1976
it is because PDF is unavailable:
RPRT
Some notes on the provision of data acquisition, processing and retrieval in the small EDP environment.
Gaines, B. R.
1976
Colchester, UK
Department of Electrical Engineering Science, University of Essex
Whilst the conventional image of EDP computer is as a 'number cruncher' providing large-scale computational resources for a high throughput of numerical calculations, there are an increasing number of small EDP applications whose requirements are primarily those of accurate data acquisition, communication, storage and retrieval, rather than calculation. Even the classical database computations of search, sort and merge, are not dominant in these applications since the prime requirement is simple storage rather than global analysis.
 (Gaines, B. R. - 1976 , Pos. 1-7)
---

back to excel for the summing up


Searched 196 from RepPlus site, I need to know which of those are not NO.

Mixed methods tab -> activate documents by variables - Lex-search-NO =1 -> New set -> sort by name, then manuall highlight PDF? there isn't a document type variable. Well PDF is a variable in the Lex-search-PDF found set, and then I could manually remove the NOTIDd1?

I will do two sets for now.
Lex-search-PDFs=1 = *29 Documents*

and

Lex-search-NOTIDd1=1 AND Lex-search-NO=0 AND Lex-search-PDFs=0
1 removed "grid" only, related to computer programming - hyperverse
1 removed no "grid" at all: Shaw-1979-Personal learning through the comput.pdf (Shaw, M. L. G. - 1979 , Pos. 8) no grid but it is about SOCIOGRIDS and so relevant
Problem with NotIDd1 being both variable and code is that if incorrect can't redo variable easily.

So just for this messy group I will add another code that tells me if it should be yes or should be NO.

SBF - shuld have been found -> educa* & repgrid 'repertory grid' then check stopwords
NFB - should not have been found but know it's relevant.

working htrough set *Lex-search-NOTIDd1=1 AND Lex-search-NO=0* so not found, and not dismissed in the first review

every document in the set should end up with  one of these or a NO.
NO prob won't help so also doing NO review 2








There were x many of these.

Others which did have "repertory grid" & "educa*" must have had stopwords in the them.

There were x of these.
The stopwords most occurring were

This allows me to refine the next, larger, search.

Lots of modelling = coded for later
Look up semantic networks later
Lots of foundational CSCL
Looks like those that were missed had "grid" with a prefix other than rep
"knowledge representation"
"concept maps"
"knowledge acquisition"
"knowledge maps"
Collabor*
agents
rules

peer for PR
intervention for PR



Coding modelling even if no RepGrid for post-review.

To go to the document that a memo is in from the overview, click the row and the document or code will be higlighted in the browser.


## library hell below

at Library today thinking I should apply same search strategies to books & book chapters. how can I get all those stop words into my library search? I'll paste them in one by one. Can only have four paramters. test which are the most effective. With frist four terms, >8000 results.

Limiters are definitely not working, chose sixth down in list at random and a keyword is psychotherapy, which should have been caught by my psycho* NOT. Try psychotherapy in full. It is still in the list. Updated search parameters from Any Field to Subject. No effect.

OK new approach is all those, plus filter subject to only include Repertory Grid Technique, Repertory Grid, Education, Repertory Grid Method, Higher Education. only 2943 results, but still including psychotherapy results. Will have to filter by keyword in 2020 using stopwords there. How doI get the ris out of the Library?

https://sydney.primo.exlibrisgroup.com/discovery/search?query=any,contains,%22repertory%20grid%22,OR&query=any,contains,repgrid,AND&query=sub,contains,education,NOT&query=sub,contains,patient*,NOT&query=sub,contains,psychotherapy,NOT&query=sub,contains,clinic*,NOT&query=sub,contains,counsel*,AND&tab=Everything&search_scope=MyInst_and_CI&sortby=date_a&vid=61USYD_INST:sydney&mfacet=topic,include,Repertory%20Grid%20Technique,1&mfacet=topic,include,Repertory%20Grid,1&mfacet=topic,include,Education,1&mfacet=topic,include,Repertory%20Grid%20Method,1&mfacet=topic,include,Higher%20Education,1&lang=en&mode=advanced&offset=0&pcAvailability=true&came_from=sort

##same search from home resulted in 2935 results!

Search parameters are at /Users/eb/Desktop/Screen Recording 2019-12-03 at 8.06.14 pm.mov
So, 50 max export and no way to limit to books and chapters.
Let's party

stuck on this page https://sydney.primo.exlibrisgroup.com/discovery/search?query=any,contains,%22repertory%20grid%22,OR&query=any,contains,repgrid,AND&query=sub,contains,education,NOT&query=sub,contains,patient*,NOT&query=sub,contains,psychotherapy,NOT&query=sub,contains,clinic*,NOT&query=sub,contains,counsel*,AND&tab=Everything&search_scope=MyInst_and_CI&sortby=date_a&vid=61USYD_INST:sydney&mfacet=topic,include,Repertory%20Grid%20Technique,1&mfacet=topic,include,Repertory%20Grid,1&mfacet=topic,include,Education,1&mfacet=topic,include,Repertory%20Grid%20Method,1&mfacet=topic,include,Higher%20Education,1&lang=en&mode=advanced&offset=900&pcAvailability=true&came_from=sort
only loading 900 to 920. reset

so now the search is only showing 1195 Results
and it;s changed the year dates
when i go back and manually remove the dates I get 2395 results again


trying FF
nightmare emailed support again - nobody there today on chat or phone and no reply.

Tried search this afternoon from home logged in and 1147 results Screen Shot 2019-12-04 at 5.30.45 pm.png

Give up and go back to RepPlus.

(This is a note to myself to table up the participants in the studies - low numbers?)
