# Issue Labels for Specifications

When you're using a github repo to store a technical specificaiton, eg a W3C spec, what issue labels should you use?

Here's one suggested set, presented as the issue lables on this repo.

See them at: https://github.com/sandhawke/spec-labels-min/labels?sort=name-asc

Note that the "Commenter ..." and "Postponed" labels are for CLOSED issues, allowing the issues list to function as a Disposition Of Comments report.


## To copy to your repo

1.  Delete all existing labels that you're not using
2.  `npm install -g copy-github-labels-cli`
3.  Get a github access token, with access to your Repos, from https://help.github.com/articles/creating-an-access-token-for-command-line-use/
4. `copy-github-labels -t *your-access-token-here* sandhawke/spec-labels-min *dest-user/dest-repo*`

## FAQ

Q. What about a 'question' label?

A. Questions should be treated as requests to clarify the spec
