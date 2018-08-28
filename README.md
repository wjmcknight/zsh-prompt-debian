# Debian Zsh Prompt

The Debian (original Bash/Dash) prompt for Zsh.

This now comes in two flavours: a modern-ish coloured version and a new
monochromatic version I've dubbed "Drabian". The addition of the monochromatic
version is for when switching between my workstation and server I get a little
more of a visual cue of the differences for the sake of clarity. A nice lack
of a punch of colour keeps me a little more aware of what I'm typing and where.

## Preview

![](https://raw.githubusercontent.com/wjmcknight/zsh-prompt-debian/master/preview.png)

## Installation

- Copy file(s) beginning with `prompt` to `/usr/share/zsh/functions/Prompts`
- Call prompt in your `~/.zshrc` with: `prompt debian` or `prompt drabian`

## Config note

Depending on your installed version of Zsh, you may need to enable color 
support in your `~/.zshrc` config which you can do by adding this:

```bash
autoload -U colors
colors
```

## License

BSD 3-clause "Modified" License: https://opensource.org/licenses/BSD-3-Clause
