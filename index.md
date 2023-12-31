# Install mkdocs

- ### [Git and GitHub learning resources](https://docs.github.com/en/get-started/quickstart/git-and-github-learning-resources)

- ### [GitHub Account](https://docs.github.com/en/get-started/quickstart/creating-an-account-on-github)

- ### [Create A Repo](https://docs.github.com/en/get-started/quickstart/create-a-repo)

--- 

# Material for MkDocs

- ## [Install Material for MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/)

- ## [Reference](https://squidfunk.github.io/mkdocs-material/reference/)

Shell commands

```zsh
rad Dev
mkdir stage2townhome
git clone https://github.com/JohnTelford/stage2townhomege2.git stage2
pip install mkdocs-material
mkdocs new .
```
### Version

Show the currently installed version with:

```zsh
pip show mkdocs-material
```
---

## netlify Deploy

``` zsh

mkdocs build
netlify deploy 
────────────────────────────────────────────────────────────────

❯ Version
  @netlify/build 29.31.0

❯ Flags
  deployId: 6571282d5f20252035fff64b
  open: false
  prod: true
  prodIfUnlocked: false
  skipFunctionsCache: false

❯ Current directory
  /Volumes/Dev/stage2townhome

❯ Config file
  No config file was defined: using default values.

❯ Context
- Finished uploading blobs to deploy store
- Finished hashing 
- CDN requesting 0 files
- Finished uploading 0 assets
- Deploy is live!

Build logs:        https://app.netlify.com/sites/stage2townhome/deploys/6571282d5f20252035fff64b
Function logs:     https://app.netlify.com/sites/stage2townhome/functions
Unique deploy URL: https://6571282d5f20252035fff64b--stage2townhome.netlify.app
Website URL:       https://stage2townhome.com

```

# [Visual Studio Code](https://code.visualstudio.com/)

Visual Studio Code, also commonly referred to as VS Code, is a source-code editor developed by Microsoft for Windows, Linux and macOS. Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git. Users can change the theme, keyboard shortcuts, preferences, and install extensions that add functionality.