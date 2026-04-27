Here are the scripts and supplementary datasets that formed part of our analysis.

Where it is possible to redistribute the source materials, we have kept them.

## Structure

`/`
|---`aux/`
|      |---- `p1.md` - system prompt used for automated extraction by Gemma 4.
|      |---- `p1.schema.json` - JSON schema given to Gemma 4.
|
|---`figs/`            - various figures used throughout our analysis, available as PDFs.
|
|---`p1_to_review/`    - the summary from Gemma 4 for each paper we had accepted.
|
|---`p1_reviewed/`     - the final, human-verified and -modified version of the summaries.
|
|---`papers/`          - the location of where the papers were downloaded to.
|
|---`analysis*.ipynb`  - the constituent steps of our analysis. further information is contained as markdown cells in each notebook.
|
|---`extra/`           - any redistributable extra datasets we used in our analysis.
|
|---`combined.csv`     - Covidence paper list export data combined with validated automated data extraction. 
|
|---`summary_*.md`     - Manually extracted statistics from the studies, and metrics used in all of the studies.
