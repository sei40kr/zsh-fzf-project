# zsh-fzf-projects

## Install

```sh
zplugin light sei40kr/zsh-fzf-projects

# see Customization section for details
FZF_PROJECT_WORKSPACE_DIRS=( ~/develop/workspace )
FZF_PROJECT_PROJECT_DIR_MAX_DEPTH=2
FZF_PROJECT_KNOWN_PROJECTS=(
  ~/.dotfiles
  ~/.emacs.d
)
```

## Customization

| Variable                           | Description                                                                                                             |
| :--                                | :--                                                                                                                     |
| `FZF_PROJECTS_WORKSPACE_DIRS`      | An array containing workspace directories.                                                                              |
| `FZF_PROJECTS_WORKSPACE_MAX_DEPTH` | The number of max levels below the workspace directories to search projects.                                            |
| `FZF_PROJECTS_KNOWN_PROJECTS`      | An array containing project directories outside the workspace directories. For example, you can put `~/.dotfiles` here. |
| `FZF_DEFAULT_OPTS`                 | The options to pass to `fzf`. Please see `man fzf` for available options.                                               |

## Similar Projects

- [tmux-per-project-session](https://github.com/sei40kr/tmux-per-project-session) - A project-oriented session manager for tmux.
