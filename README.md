# S-RCWG
Science Research Culture Working Group (S-RCWG)

[homepage](https://sainsburywellcomecentre.github.io/S-RCWG)

# How to Submit a Proposal
- Clone this repository on your local machine, make a branch titled `proposal-<short proposal name>` using `git branch <branch name>`
- Check out the [template](proposal_template.md) and write your proposal in a Markdown document following those guidelines
- Put your proposal in the `_proposals` folder
- Don't modify anything else on this branch
- Submit a pull request on GitHub for this branch

# How to Write Meeting Minutes
- Find the `_minutes` folder on GitHub
- Add a new file and follow the format of previous meetings
- Commit this new file

OR (if you want to be fancy)

- Clone the repository
- Make a new Markdown file in the `_minutes` folder
- Write up the minutes following previous meetings' format
- `git add <minute file>`, `git commit -m <Your short commit message>` and `git push`

# How to Develop the Portal Locally

- Download [Jekyll](https://jekyllrb.com/docs/installation/) following the steps [here](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll). You'll need a package manager, `ruby`, and `bundler`. Don't forget to run `gem install bundler`.
- Once you've got everything installed, run `bundle exec jekyll serve` to start a development server at `http://127.0.0.1:4000/`, just go there in your browser.
- If you have issues, try running `bundle update`. If that doesn't work, open an issue or reach out on Slack.
- Changes made to documents should automagically update in your browser.

## Helpful Jekyll Links

- [posts require specific filenames, collections do not](https://stackoverflow.com/questions/27099427/jekyll-filename-without-date)