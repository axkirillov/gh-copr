# gh copr
Fuzzy find and checkout GitHub pull requests

inspiration taken from

https://github.com/mloberg/gh-prs

https://github.com/AaronMoat/gh-reviews

this needs fzf

```
brew install fzf
```

install with gh
```
gh extension install axkirillov/gh-copr
```

then, to list all PRs in a repo
```
gh copr
```
or to list only prs that need your review
```
gh copr -r
```
