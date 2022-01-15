# Git setup

```bash
# Your Identity
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"

# Your Editor
git config --global core.editor "vim --nofork"
git config --global core.editor "code --wait"

# Your default branch name
git config --global init.defaultBranch main

# Rebase branches on top of the fetched branch in "git pull"
git config --global pull.rebase true

# Checking Settings
git config --list --show-scope --show-origin
```

## Git Credential

```bash
$ git config --global credential.helper 'cache --timeout=86400'

# Git Credential Manager for WSL & GitHub
$ git config --global credential.helper "/mnt/c/bin/Git/mingw64/libexec/git-core/git-credential-manager-core.exe"
```

---

## References

- [Git - First-Time Git Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
- [Version Control in Visual Studio Code](https://code.visualstudio.com/docs/editor/versioncontrol)
- [GitCredentialManager/git-credential-manager](https://github.com/GitCredentialManager/git-credential-manager)
- [Git - gitcredentials Documentation](https://git-scm.com/docs/gitcredentials)
- [Git - git-credential-cache Documentation](https://git-scm.com/docs/git-credential-cache)
- [cli/cli: GitHub’s official command line tool](https://github.com/cli/cli)
- [GitHub CLI | Take GitHub to the command line](https://cli.github.com/)
- [GitHub Documentation](https://docs.github.com/en)
- [The GitHub Blog | Updates, ideas, and inspiration from GitHub to help developers build and design software.](https://github.blog/)
- [Git Credential Manager Core: Building a universal authentication experience | The GitHub Blog](https://github.blog/2020-07-02-git-credential-manager-core-building-a-universal-authentication-experience/)
- [Token authentication requirements for Git operations | The GitHub Blog](https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/)
