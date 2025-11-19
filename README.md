# .github
This is the Organization repo with all default files in it

## Structure
We have a docs directory that holds all the documents related with our work and will help with it.
At first level we have the default template that is used all the time in all repositories PRs.
At the same level we have a directory (PULL_REQUEST_TEMPLATE) that holds all other templates, in there we have different PR templates that can be used by other teams for their PRs (at same level, no need of directories).
Every team can setup its own template/s that have to be placed into the .github (on root path) directory of their repository. If they do that their template will override the default template that is provided on organization level.

In order to use a diffrent PR template than the default one without setting up our own (in our repo) wqe can use a parameterized call that will open a PR window. Example (the parameter is the name of the custom template):

https://github.com/niki-playground/test_argo_repo/compare/main...test?quick_pull=1&template=dev.md
