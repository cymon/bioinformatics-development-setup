### How to set up a development environment for Visual Studio Code

[Install VSCode][vscode]

[vscode]: https://code.visualstudio.com/docs/setup/linux

Go to extensions (CTL+Shift+X) and add:

- Black:
  Format Python code with black
- Ruff:
  A Visual Studio Code extension with support for the Ruff linter
- Codeium:
  The modern coding superpower, free AI code acceleration plugin for your favorite languages
- Git Extension Pack:
  Popular Visual Studio Code extensions for Git
- Git History:
  View git log, file history, compare branches or commits
- GitHub Repositories:
  Remotely browse and edit any GitHub repository
- GitLens:
  Supercharge Git within VS Code

Change the default code formatter:
go to setting (CTL+,)
search for `default code formatter`; change to "black"
search for `auto save`; change to "On Focus Change"
