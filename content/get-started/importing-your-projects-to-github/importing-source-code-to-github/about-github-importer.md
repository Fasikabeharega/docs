---
title: About GitHub Importer
intro: 'If you have source code in Subversion, Mercurial, Team Foundation Version Control (TFVC), or another Git repository, you can move it to GitHub using GitHub Importer.'
redirect_from:
  - /articles/about-github-importer
  - /github/importing-your-projects-to-github/about-github-importer
  - /github/importing-your-projects-to-github/importing-source-code-to-github/about-github-importer
versions:
  fpt: '*'
  ghec: '*'
---
GitHub Importer is a tool that quickly imports source code repositories, including commits and revision history, to GitHub for you.

![Importing a repository gif](/assets/images/help/importer/github-importer.gif)

During an import, depending on the version control system you're importing from, you can authenticate with your remote repository, update commit author attribution, and import repositories with large files (or remove large files if you don't want to use Git Large File Storage).

| Import action | Subversion | Mercurial | TFVC | Git |
|:--------------|:----------:|:---------:|:----------------------:|:---:|
| Authenticate with remote repository | **X** | **X** | **X** | **X** |
| [Update commit author attribution](/get-started/importing-your-projects-to-github/importing-source-code-to-github/updating-commit-author-attribution-with-github-importer) | **X** | **X** | **X** | |
| Move large files to [Git Large File Storage](/repositories/working-with-files/managing-large-files/about-git-large-file-storage) | **X** | **X** | **X** | |
| Remove large files from your repository | **X** | **X** | **X** | |

## Further reading

- "[Importing a repository with GitHub Importer](/get-started/importing-your-projects-to-github/importing-source-code-to-github/importing-a-repository-with-github-importer)"
- "[Updating commit author attribution with GitHub Importer](/get-started/importing-your-projects-to-github/importing-source-code-to-github/updating-commit-author-attribution-with-github-importer)"
- "[Importing a Git repository using the command line](/get-started/importing-your-projects-to-github/importing-source-code-to-github/importing-a-git-repository-using-the-command-line)"
- "[Source code migration tools](/get-started/importing-your-projects-to-github/importing-source-code-to-github/source-code-migration-tools)"
