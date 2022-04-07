# ghcopr
Fuzzy find and checkout GitHub pull requests

inspiration taken from
https://github.com/mloberg/gh-prs
https://github.com/AaronMoat/gh-reviews

I added a -a flag to list prs that need my review

this needs fzf
```
brew install fzf
```

```
gh extension install axkirillov/gh-copr
```

then 
```
gh copr
```
or to see prs that need your review
```
gh copr -r
```
