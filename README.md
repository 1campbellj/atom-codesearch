# Atom CodeSearch

Super-fast search for code using Google CodeSearch

# Installation

1. install this package
2. install and configure Go
3. download and build Google CodeSearch

Something like this:

```
export GOROOT=/usr/local/go
export GOPATH=$HOME/go

go get github.com/google/codesearch/cmd/{cindex,csearch}
```

# Usage

Mac: <kbd>cmd-alt-shift-F</kbd>  
Windows, Linux: <kbd>ctrl-alt-shift-F</kbd>

# Commands

### Code Search: Toggle

Open *Find with CodeSearch* window

### Code Search: Reindex

Reindex current project

### Code Search: Purge Index

Purge index for current project (e.g., when there are some strange problems with it)