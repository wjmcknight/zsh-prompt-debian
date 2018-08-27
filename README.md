# Debian Zsh Prompt

The Debian (original Bash or Dash) prompt for Zsh.

This now comes in two flavours: a modern-ish coloured version and a new 
monochrome version I've dubbed "Drabian". The addition of the monochrome version
is because when switching between my workstation and server prompts the
hostname itself isn't enough for me to not occasionally get confused. A nice
lack of a punch of colour keeps me a little more aware of what I'm typing and
to where.

### Installation:
- Copy file(s) beginning with `prompt` to /usr/share/zsh/functions/Prompts
- Call prompt in your ~/.zshrc with: `prompt debian` or `prompt drabian`

### Config note:

Depending on your installed version of Zsh, you may need to enable color 
support in your ~/.zshrc config which you can do by adding this:

```console
autoload -U colors
colors
```
