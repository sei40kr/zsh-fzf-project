# zsh-fzf-projects

## Install

```sh
zplugin light sei40kr/zsh-fzf-projects
# you can customize the workspace directories
FZF_PROJECT_WORKSPACE_DIRS=( ~/develop/workspace )
FZF_PROJECT_PROJECT_DIR_MAX_DEPTH=2
FZF_PROJECT_KNOWN_PROJECTS=(
  ~/.dotfiles
  ~/.emacs.d
)
```

## Customization

| Variable                             | Description                                                               |
| :--                                  | :--                                                                       |
| `FZF_PROJECTS_WORKSPACE_DIRS`        | An array containing workspace directories                                 |
| `FZF_PROJECTS_PROJECT_DIR_MAX_DEPTH` | The number of max levels below the workspace directory to search projects |
| `FZF_PROJECTS_KNOWN_PROJECTS`        | An array containing project directories                                   |
| `FZF_DEFAULT_OPTS`                   | Parameters passed to `fzf` (see `fzf --help` for details)                 |
