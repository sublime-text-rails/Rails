# Sublime Text 3 - Rails Pack
This package aims to make Sublime Text 3 better than VS Code for Rails development, by providing better code completion and syntax highlighting.

Feel free to contribute by creating issues, and fixes via pull requests, see the contributing guide for more information.

## What This Package Does
The contents of this repo can be used to kill the default Ruby and Rails autocomplete code snippets that ship with Sublime Text, this makes way for a fresh set of completions to be used directly off GitHub, allowing open-source maintainers to keep the code up to date.

- Kill the outdated default Rails snippets.
- Add new up-to-date Rails completions.
- Add new ERB code completions.

Unlike the Rails auto-completion used in VS Code, you can't insert ERB into a model or controller file, and better still the Rails completions in this repo are controller or model specific where required, making Visual Studio Code IntelliSense look inferior.

## Installation
- Add `Package Control` to Sublime Text.
- Install `PackageResourceViewer`.
- Hit `Command` - `Shift` - `P` Search: `PackageResourceViewer:Extract Package`.
- From the list pick `Rails` and then click `Start Extraction`.
- Next, click `Sublime Preferences` and choose `Browse Packages`.
- Within the `Packages` folder, locate `Rails` and replace the `Snippets` folder with the one from this repo.
- Restart Sublime Text.

## LSP Conflict
If you are using the Sublime LSP with Solargraph, you may find your new completions are buried under the less helpful code suggestions provided by the Language Server, and in some cases, your auto completions do not trigger.

If this is the case, open your LSP settings and disable completions.
