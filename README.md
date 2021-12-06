gh-gitignore
---

Generate .gitignore files from GitHub CLI (`gh`) with language search.

## Dependencies:
- Required:
  - [curl](https://curl.se/download.html)
- Optional (only for languages search)
  - [jq](https://stedolan.github.io/jq/)
  - [fzf](https://github.com/junegunn/fzf)

## Installation

Install dependencies first, then:

```sh
gh extension install roziscoding/gh-ignore
```

## Usage

To specify the languages in one command:

```sh
gh ignore <language>,<language>,<language>
```

To see a list of languages and select between them with `fzf`

```sh
gh ignore
```
