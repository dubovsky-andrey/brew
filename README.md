# Install programs using brew

```
tmpfile="$(mktemp)"
curl -fsSL https://raw.githubusercontent.com/dubovsky-andrey/brew/main/Brewfile -o "$tmpfile" && mv "$tmpfile" /tmp/Brewfile
brew bundle --file=/tmp/Brewfile
```


# Create brew dump

```
brew bundle dump --force 
```
