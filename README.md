# RCWG

Research Culture Working Group

[Portal](https://sainsburywellcomecentre.github.io/RCWG)

[Slack](https://swc-neuro.slack.com/archives/C01CK2NTV32)

# Contributing via GitHub

## Submitting Proposals

- write a draft following the [proposal template](https://github.com/SainsburyWellcomeCentre/S-RCWG/blob/main/_proposals/_proposal_template.md), paying attention to the metadata and the "below summary" comment line.
- go to the [_proposals folder](https://github.com/SainsburyWellcomeCentre/S-RCWG/tree/main/_proposals) and click `add file`. (NB: If a folder does not exist for your subgroup, please submit an issue.)
- paste your draft proposal into the new file
- click the buttons at the bottom to create a branch and submit a pull request
	- name your branch in the format `<your name>-<proposal>-<proposal keyword>`
- submit the pull request so that the group can comment, suggest changes, and approve the request
- you can edit your proposal by switching to your proposal's branch (on the main GitHub page) and editing the proposal file
- if you have any trouble at all, reach out on Slack or submit an issue describing your situation

## Submitting  Minutes

- take the minutes in markdown format (see the template file in the [_minutes folder](https://github.com/SainsburyWellcomeCentre/S-RCWG/tree/main/_minutes) for reference)
- pay careful attention to the file's metadata tags! 
- in the [_minutes folder](https://github.com/SainsburyWellcomeCentre/S-RCWG/tree/main/_minutes), click `add file` and add your minutes. (NB: If a folder does not exist for your subgroup, please submit an issue.)
- name the file using the meeting date in the format `<subgroup_name>_<day>_<month>_<year>` using numbers
- click `commit directly to the main branch` to add the new file


# Contributing as a Developer 

## Testing the Portal Locally
- You'll need a package manager, `ruby`, and `bundler`
- Use your package manager to install [Jekyll](https://jekyllrb.com/docs/installation/) following the steps [here](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll). Don't forget to run `gem install bundler`.
- The `Gemfile` for the project should be fine, just run `bundle update`
- Once you've got everything installed, run `bundle exec jekyll serve` to start a development server at `http://127.0.0.1:4000/`, just go there in your browser.
- If you have issues, try running `bundle update`. If that doesn't work, open an issue or reach out on Slack.
- Changes made to documents should automagically update in your browser, but if you change the `_config.yml` (which you shouldn't) you have to re-run `bundle exec jekyll serve`

## Helpful Jekyll Links

- [posts require specific filenames, collections do not](https://stackoverflow.com/questions/27099427/jekyll-filename-without-date)
