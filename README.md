
Process for updating website with new models:
- `sad results`
- `sad plot`
- `sad latex_result_table`
- copy over results/plots/website/data.csv to the website repo
- copy over results/plots/website/website_dump.html to the website repo, but delete line 0 and line -1 and also get rid of the css classes on the div
  - replace the relevant bit of sad/results/plots/website/results_table/results_table.tex with sad/results/plots/result_tables/subsets_and_categories.tex (making sure to preserve the custom table column headers)
put this into overleaf, generate, screenshot and save as results_table.png in the website repo


