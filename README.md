# Sublime Text - Rails Pack
This package improves Rails code completions in Sublime Text 3

Feel free to contribute by creating issues, and fixes via pull requests, see the contributing guide for more information.

## What This Package Does
The contents of this repo can be used to kill the default Rails auto complete code snippets that ship with Sublime Text, this makes way for a fresh set of completions to be used directly from GitHub, allowing open-source maintainers to keep the code up-to-date as changes occur.

- Kills the outdated default Rails snippets.
- Adds new Rails code completions.
- Adds new Ruby code completions.
- Adds modern ERB code completions.

## Smart Code Completions
- Where relevant code completions are ERB, model, controller, and database specific.
- Using the tab key to auto complete, then tab again to cycle through preset tab locations for cursor positions and highlighting variables that should be customized.
- Multi point editing on completions.


## Usage
- Clone this repo to your desktop.
- Click `Sublime Preferences` and choose `Browse Packages`.
- Drag and drop the freshly cloned reop into the `Packages` folder.
- Repeat the above process with the `Ruby` repo found [here](https://github.com/sublime-text-rails/Ruby).
- If you are running Solargraph through the Language Server disable "completion" in LSP setting.
- Restart Sublime Text.

## Upgrading & Customizing
Because this `Rails` repo and its `Ruby` equivalent were cloned directly from GitHub and placed in the `Packages` folder you can update using these using typical git version control, fork your own branch, and merging changes from the master back into your custom version, or simply keep up to date from the master.
