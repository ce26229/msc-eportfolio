# Editing the ePortfolio

## Where content lives

- Home: index.md
- About Me: about.md
- Module list: modules/index.md
- Reusable module template: modules/template.md
- Shared design: _layouts/default.html and assets/style.css
- Website configuration: _config.yml

## Enable GitHub Pages

1. Open the repository.
2. Select Settings, then Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Select main and /(root).
5. Select Save.
6. Wait for deployment, then use the Visit site link provided by GitHub.

The website uses GitHub Pages' built-in Jekyll support. Do not add a .nojekyll file: it would disable the processing required by these pages.

## Edit a page in GitHub

1. Open its Markdown file on the Code tab.
2. Select the pencil icon to edit.
3. Keep the opening --- block intact. It controls the page title and address.
4. Change the text beneath that block.
5. Select Commit changes, describe the change, then save it.
6. Wait for Pages to rebuild and check the published page.

Markdown examples:

# Main heading
## Section heading
**Bold text**
[Link label](https://example.com)

Ask ChatGPT to edit files if you prefer. Review factual claims and reflections before using them for assessment.

## Add a module

Copy modules/template.md to a new file such as modules/confirmed-module-slug.md. Give it a unique title and permalink, for example /modules/confirmed-module-slug/. Replace prompts with verified information. Add its link to modules/index.md using the same relative_url pattern as the existing template link.

## Before public upload

Remove confidential workplace information and private personal details. Check permission to publish group work and feedback. Link academic claims to references; preserve accurate records of any AI assistance required by the assessment.

## Before submission

Practise creating a branch from main using the branch selector on the Code tab. A branch copies the repository state, not just one module. Use a clear name such as submission-module-YYYY-MM-DD.

Check the assessment brief before selecting a submission publishing source. This repository has one Pages site; changing its source branch changes the version shown at that address. Preserve the submission branch and commit, and avoid changing an assessed publication until the university's requirements are clear.

Written documents must follow the university's submission formatting. Browser printing is a convenience and is not a substitute for checking document formatting and page numbering.
