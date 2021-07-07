# Working With GitHub CLI 
Notes on working with the GitHub CLI, and some useful commands. Complete manual can be found here: 
[GH CLI Manual](https://cli.github.com/manual/)

## Issues: Example Commands
[GH CLI Manual: Issues](https://cli.github.com/manual/gh_issue)

```
$ gh issue list
$ gh issue create --label bug
$ gh issue view --web
```
## Pull Requests: Working With GH Pull Requests
[GH CLI Manual: Pull Requests](https://cli.github.com/manual/gh_pr)

```
$ gh pr checkout 353
$ gh pr create --fill
$ gh pr view --web
$ gh pr merge [<number> | <url> | <branch>] [flags]
```