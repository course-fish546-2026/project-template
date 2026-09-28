# notebooks/

Your weekly notebook entries live here, one Quarto file per week. Each entry is that week's deliverable.

## The two files you start with

| File | What it is | What to do with it |
|---|---|---|
| `_template.qmd` | The blank five-section entry, with a pre-push checklist in a comment at the top. | Never edit it directly. Copy it each week to start a new entry. |
| `week00.qmd` | A partly filled-in example for Week 0 (repository and shell setup). | Fill in the blanks (`___`) and use it as your Week 0 entry. |

## Each week

1. Copy the template to a new file named for the week, with a two-digit number:

   ```bash
   cp notebooks/_template.qmd notebooks/week03.qmd
   ```

   In RStudio you can instead open `_template.qmd` and use **File > Save As...** with the new name.
2. Change the `title:` line at the top, then fill in the five sections: analysis, reflection questions, project progress, problems and help needed, and next week.
3. Save tables and figures under `output/weekNN/` and link to them. Write paths relative to the repository root.
4. Render it (the **Render** button in RStudio, or `quarto render notebooks/week03.qmd`). This creates `week03.html` next to the `.qmd`.
5. Commit **both** the `.qmd` and the `.html`, push, and post the commit link on your Project Proposal issue ([how to find it](https://sr320.github.io/course-fish546-2026/how-we-work.html#finding-your-commit-link)).

The full description and rubric are on the course site: [How We Work](https://sr320.github.io/course-fish546-2026/how-we-work.html#the-weekly-notebook-entry).
