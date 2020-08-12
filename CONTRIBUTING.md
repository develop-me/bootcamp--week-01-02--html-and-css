Please use [Git Flow](https://jeffkreeftmeijer.com/git-flow/)

- Make most changes on `develop`
- Only push changes to `master` when the material is ready for students using a `release`
- If you need to make quick changes (e.g. whilst teaching the week) then use a `hotfix`

Generally works out as a `release` per cohort – a week or so before teaching – and maybe a few `hotfix`es whilst teaching.

If doing a `release` for a specific cohort, then please also add a `git tag #<cohort-number>` (e.g. `git tag #17`)

# Versioning

Trying to use a SemVer-ish system for numbering, but it doesn't map so well on to written material:

- patch for little changes/`hotfix`es
- minor for incremental stuff
- major for significant rewrites

---

I'd suggest installing the [git-flow CLI commands](https://github.com/nvie/gitflow) and adding the following aliases to your CLI setup:

```bash
alias feature="git flow feature"
alias release="git flow release"
alias hotfix="git flow hotfix"
```
