# Configuration files for local development.


## Features

- Gnu Readline configurations  
   - [ ] Add .inputrc.
   - [ ] Enable vi mode to prompt.
   - [ ] Add different cursors on different modes.
- Bash configurations.
   - [x] Add .bashrc.
   - [ ] Aliases: Add aliases.
   - [ ] Prompt: Configure PS1 prompt.
   - [ ] Prompt: Enable 'vi mode'.
   - [ ] Completions: Add Git bash-completion.
   - [ ] Completions: Add AWS CLI bash-completion.
   - [ ] Scripts: Start default tmux session if not started.
- Vim configurations.
   -  [ ] Add .vimrc
   -  [ ] Install visual theme.
   -  [ ] Spelling: Enable spelling in code files.
   -  [ ] Setup: Prevent word wrap.
   -  [ ] Setup: Prevent swap files.
   -  [ ] Setup: Enable code-completion in command line.
   -  [ ] Setup: Show cursor line.
   -  [ ] Setup: Show different cursor chars in insert and normal mode.
   -  [ ] Setup: Install and setup CoC Plugin for code completion, formating, language server and navigation.
   -  [ ] Setup: Enable Utf-8.
   -  [ ] Search for caps only if caps in search string.
   -  [ ] Search: highlight search result.
   -  [ ] Search: Search for filenames in repository.
   -  [ ] Search: Search for files containing pattern.
   -  [ ] Search: Show matches while searching.
   -  [ ] Search: Goto definition.
   -  [ ] Search: Goto type-definition.
   -  [ ] Search: Goto implementation.
   -  [ ] Search: Goto references.
   -  [ ] Indentation: Convert tab to 4 spaces.
   -  [ ] Indentation: Show actual tab chars.
   -  [ ] Startup: Reset cursor.
   -  [ ] Startup: Goto last edit position when file was saved.
   -  [ ] Statusline: Show git branch.
   -  [ ] Statusline: Show Filename.
   -  [ ] Statusline: Show if file is edited since open.
   -  [ ] Statusline: Show cursor position percentage to total number of lines.
   -  [ ] Statusline: Show row and column.
   -  [ ] Statusline: Show CoC info.
- Tmux configurations.
   - [ ] Add .tmux.conf
- Installation Script.
   -  [ ] Add 'install'
   -  [ ] Add install instructions to 'README.md'
   -  [ ] Ensure Git installed.
   -  [ ] Ensure Tmux installed.
   -  [ ] Ensure NeoVim installed.
   -  [ ] Ensure AG installed.
   -  [ ] Ensure FZF installed.
   -  [ ] Clone repository.
   -  [ ] Make symlinks to user home for .bashrc.
   -  [ ] Make symlinks to user home for .vimrc.
   -  [ ] Run PluginInstall in vim.
   -  [ ] Make symlinks to user home for .tmux.conf.
   -  [ ] Make symlinks to user home for .insertrc.

## Conventions

Do...
- use Conventional Commits messages before push.
- update this 'README.md' for every feature change in a new commit.
- use 55 chars of comment chars to structure each configuration file headline.
- use 3 returns before each headline if not the first.
- use GitFlow.
- use pull requests.
- use FF merge strategy on pull requests.

```
eg. if '#' is the comment char.



#######################################################
# Headline
#######################################################

#  Comment
some configuration

#  Comment
some configuration
some configuration

```
