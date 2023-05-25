# Testing-github-actions

Experimenting with Github Actions
* update version of image with search n'replace github action
* Set default pull request title including issue-id from branch (expect pattern "work/<word>-<digits>". Altso matches branches with any other postfix after issue-id, e.g. "work/ID-55-randomstuff998_". There ID-55 is extracted as jira-id. File: /.github/workflows/get-jira-key-branch.yml
