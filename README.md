# ghcopr
Fuzzy find and checkout GitHub pull requests

this is based on
https://github.com/mloberg/gh-prs

I added a -a flag to list prs that need my review

this needs fzf and gomplate
```
brew install fzf gomplate
```

```
gh extension install axkirillov/gh-prs
```

then 
```
gh copr
```
or
```
gh copr -a
```
