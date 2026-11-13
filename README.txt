THE 2030 ACCELERATION CHALLENGE — DOCUMENT REVISION

UPLOAD
Extract this ZIP and replace index.html in Student_Acceleration_Challenge with this index.html.
Keep the existing repository name and Pages settings. No build step is needed.
The app is self-contained; the other files are supporting notes and references.
No live repository, published website, or ThingLink scenario was changed.

FACULTY CHANGES
- Deleted the orientation, requested header sentence, and Leadership’s target label.
- Added a prominent December 31, 2030 target near the header prompt.
- Replaced the former summary sidebar, examples, customizer, conditional-timing
  switch, calculation explainers, resource section, and multi-question advice
  flow with an earlier-decisions / revised-2030 dashboard.
- Kept both challenge story cards and the final target-credibility question.
- Spelled out small modular reactor and removed the milestone accordion.
- Added a compact MW comparison above the dashboard and retained Copy summary
  of responses and Print / Save PDF with matching current-location results.

EARLIER DECISIONS AND SAVING
Enter the earlier AI counts/MW, energy choices/quantities, final schedule and
final cost from saved course summaries. The final schedule/cost fields are
learner-entered records and are kept separate from calculated course ranges.
Other course apps do not transfer their entries automatically. A saved scenario
from the previous version of this same Acceleration app can be restored as the
left-side starting point when its browser storage is accessible. Confirm it.
The previous storage key is read but never overwritten. Revised comparisons use
a separate version-2 key. Each location, and both settings in the Student app,
keeps independent entries. A new location starts blank, with no example loaded.
Storage can be blocked in an embed or private browser; saving failures are shown.
Copy or print before leaving. No responses are sent automatically.

2030 TIMING RULE
The simulation starts in January 2027 and allows four years to December 31, 2030.
Only energy technologies with maxYears <= 4 appear in the revised selector.
The full course range must fit; there is no earliest-timing override. Existing
technology ranges are unchanged, including small modular reactor at 4–7 years.
The fictional 2027 design-certification milestone does not shorten that range.
All supplied AI course horizons exceed four years: Low 5–10, Medium 10–15,
High 15–20 years. Consequently no new AI level is offered on the revised side.
The app explicitly explains this result, rather than reporting a smaller MW
choice as new AI readiness deliverable by 2030. Counts alone cannot establish
readiness. The user still makes the final target-credibility judgment.

CALCULATION SCOPE
AI MW = sum(count × MW each). Generation, standalone storage, and the unsplit
solar/storage category remain separate. The power strip compares earlier AI
demand with generation selected for 2030; it is not a dependable supply balance.
Energy investment adds quantity × lower/upper course cost endpoints as an
indicative scenario, not a factual linear scaling claim. The energy schedule
uses the longest selected lower and upper bounds, assuming overlapping work.
No outside data, annual electricity cost, or combined AI/energy cost was added.
Invalid numeric edits are excluded; copies and print identify last valid inputs.

SOURCE
Read-only snapshot of tpicker/Student_Acceleration_Challenge/index.html.
Git blob SHA: 97e98e8df9b5c8504722e41afdcb6e3bed2c4f43
SHA-256 of frozen source: f8c53974e4f2fd337353c0647c6b2f7b4368997ebc10360e279e9c98f79742c2
The published app’s course values and original stylesheet blocks are preserved.
Layout changes follow the faculty document; no new palette was introduced.

FILES
index.html                Self-contained, editable app for manual upload.
.nojekyll                 Optional static-hosting marker.
course-reference-data.json Course input snapshot used by this revision.
README.txt                Instructions, limits, and source provenance.

VERIFICATION
Automated checks cover the timing filter, AI horizon limit, MW/cost/schedule
math, copy and manual fallback, print data, saved-work restoration, invalid edits,
reset, accessible labels, and separation by location. Browser layout and PDF
appearance were not visually inspected in this environment.
