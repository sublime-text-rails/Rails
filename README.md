# Sublime Text 3 - Rails Pack
Makes Sublime Text 3 better than VS Code for rails development.

## How?
This reop allows you to:

- Kills the outdated default Rails snippets.
- Adds new up-to-date Rails completions.
- Adds new ERB code completions.

Unlike the Rails auto-completions in VS Code, you can't insert ERB into a model file, better still our completions provide model and controller specific completions.

## Installation
- Add `Package Control` to Sublime Text.
- Install `PackageResourceViewer`.
- Hit `Command` - `Shift` - `P` Search: `PackageResourceViewer:Extract Package`.
- From the list pick `Rails` and then click `Start Extraction`.
- Next, click `Sublime Preferences` and choose `Browse Packages`.
- Within the `Packages` folder, locate `Rails` and replace the `Snippets` folder with the one from this repo.
- Restart Sublime Text.

## My LSP Completions Gets In The Way

If you are using the Sublime LSP with Solargraph, you may find your new completions are buried under the less helpful code suggestions provided by the Language Server, and in some cases, your auto completions do not trigger.

If this is the case, open your LSP settings and disable completions.
