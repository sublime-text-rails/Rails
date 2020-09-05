# Sublime Text 3 - Rails Pack
This package aims to make Sublime Text 3 better than VS Code for Rails development, by providing better code completion and syntax highlighting.

Feel free to contribute by creating issues, and fixes via pull requests, see the contributing guide for more information.

## What This Package Does
The contents of this repo can be used to kill the default Ruby and Rails autocomplete code snippets that ship with Sublime Text, this makes way for a fresh set of completions to be used directly off GitHub, allowing open-source maintainers to keep the code up to date.

- Kills the outdated default Rails snippets.
- Adds new up-to-date Rails code completions.
- Adds new Ruby code completions.
- Adds new ERB code completions.

Unlike the Rails auto-completion used in VS Code, you can't insert ERB tags into a model or controller file by mistake, and better still the Rails completions in this repo are controller or model specific where required, making Visual Studio Code IntelliSense look inferior.

## Usage
- Clone this repo to your desktop.
- Click `Sublime Preferences` and choose `Browse Packages`.
- Drag and drop the freshly cloned reop into the `Packages` folder.

- Repeat the above process with the `Ruby` repo found [here](https://github.com/sublime-text-rails/Ruby).
- Restart Sublime Text.

Because this `Rails` repo and its `Ruby` equilvelent were cloned directly from GitHub and placed in the `Packages` folder you can update using these using typical git version control, creating your own branch, and merging changes from the master back into your custom verion, or simply keep up to date from the master.

## LSP Conflict
If you are using the Sublime LSP with Solargraph, you may find your new completions are buried under the less helpful code suggestions provided by the Language Server, and in some cases, your auto completions do not trigger.

If this is the case, open your LSP settings and disable completions.
