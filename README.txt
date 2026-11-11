STUDENT EXPLORER / THE 2030 ACCELERATION CHALLENGE

PURPOSE
This duplicates the approved global country explorer for students in the course
and adds the U.S. state setting. The global country-only copy and the earlier
simplified student challenge are unchanged. Nothing was published or edited in
GitHub or ThingLink while preparing this package.

STUDENT USE
Select the assigned setting (Country or U.S. state), then the assigned location.
Build on the earlier simulation activities to assess the 2030 acceleration target.
The context accordion switches to the matching course decision factors and
stakeholder roles. The course reference ranges are the same for every location;
there are no added national or state electricity statistics or readiness scores.

Country: Algeria, Brazil, Costa Rica, France, Ireland, Japan, Jordan, Kenya,
Mexico, Morocco, Oman, Pakistan, South Korea, Ukraine, Venezuela, Vietnam.

U.S. state: Colorado, Connecticut, Maryland, New York, South Dakota, Texas,
West Virginia. Both lists are alphabetical and retained from the course apps.

APPROVED EXPERIENCE RETAINED
- The same navy/white colors, type, controls, responsive layout, and source values.
- A separate, initially closed "See examples" accordion; examples fill the
  always-visible customizer for students to adjust counts and MW.
- Mixed AI demand units and multiple units of all 13 energy technology types.
- A live "Scenario at a glance" sidebar at widths of 1,100 pixels and above.
  It follows scrolling alongside inputs and advice. On narrower screens it
  appears above the customizer; a short desktop window can scroll the sidebar.
- The same four-year comparison, generation/storage/hybrid separation, indicative
  investment ranges, calculation details, SMR story, and three advice choices.
- Optional note and Print / Save PDF for the current location, even as a draft.

SAVING
This copy uses its own browser-storage key: ai-readiness-student-explorer-v1.
It does not import or alter drafts from the global app or the earlier student app.
Country and state retain their own selected location, inputs, and advice.
Returning to a location restores its case. Selecting a new location within a
setting carries over that setting's current quantitative inputs with blank advice.
Reset affects only the location currently shown. It preserves the selected setting,
location, and all other cases. Nothing is submitted automatically.
Invalid numeric edits remain visible, but results and saving use the last valid
scenario. Printing labels this explicitly. Selecting a preset or switching
setting/location clears unfinished numeric edits. Browser storage may be blocked
or unavailable for local files; the app can still be used and printed.

MANUAL UPLOAD
Open index.html in a browser to review it. It is a complete, editable, self-contained
app: no external libraries, build step, API, or supporting data fetch is needed.
The JSON source snapshot and text notes are included for review, not runtime use.

For a separate GitHub Pages site, upload index.html to the root of a new repository,
for example Acceleration_Challenge_Student_Explorer. Include the other files if
desired. Keep or configure the usual Pages publishing branch and root folder.
Use the actual published URL GitHub supplies. Do not replace the global version.
Alternatively, upload this index.html in a new student/ folder under an existing
Pages site and link directly to that folder. Keep the other index.html files.

THINGLINK BRANCHES
Use two destinations after manual upload:
- Global users: the existing country-only Acceleration_Challenge_Country_Explorer.
- Course students: this country-and-state Acceleration_Challenge_Student_Explorer.
Inside the student app, students choose the setting and location assigned in the
simulation. They can explore either setting; the app does not require both.
This package does not configure, submit to, or change the ThingLink scenario.

FILES
index.html                  Complete editable app and upload file.
.nojekyll                   Optional static-hosting marker.
course-reference-data.json  Reference inputs and local source hashes.
COURSE-SOURCE-NOTES.txt     Course-only provenance and calculation assumptions.
README.txt                  These upload, use, and branching instructions.

REVIEW
16 automated checks passed for calculation preservation, switching, local saving,
reset, print content, source scope, and preserved files. Browser layout and PDF appearance could not be
visually checked in this environment; review your browser's print preview.
