# TaskWarrior Config

Some basic configuration files to make setting up TaskWarrior easier in the future.

## Setup

Installation:
1. Install [TaskWarrior](https://taskwarrior.org/download/)
2. Install [taskWarrior-tui](https://kdheepak.com/taskwarrior-tui/installation/)

1. Download certificates and copy authentication details from [inthe.am](https://inthe.am/getting-started).
2. Copy `.taskrc.sample` to `~/.taskrc` and edit it with the authentication details.
3. Run `task sync init`

Add the following to `.bashrc` or `.zshrc`:

```
alias tt="task sync && taskwarrior-tui"
```
