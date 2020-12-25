# Git-Guide

![Three Trees](./images/three-trees.png)

## restore

```bash
git restore [<options>] [--source=<tree>] [--staged] [--worktree] [--] <pathspec>…​
```

- 파일을 index에서 working directory로 복사한다.

```bash
$ git restore <file>
```

- 파일을 HEAD에서 index로 복사한다.

```bash
$ git restore --staged <file>
```

- 파일을 HEAD에서 index와 working directory로 복사한다.

```bash
$ git restore --source=HEAD --staged --worktree <file>
```

## Line Endings

다음 두 글을 참고한다.

- [Configuring Git to handle line endings](https://docs.github.com/en/free-pro-team@latest/github/using-git/configuring-git-to-handle-line-endings)
- [Mind the End of Your Line](https://adaptivepatchwork.com/2012/03/01/mind-the-end-of-your-line/)
