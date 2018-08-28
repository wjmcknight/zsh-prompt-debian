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

### System wide

```console
git clone https://github.com/wjmcknight/zsh-prompt-debian.git
sudo cp zsh-prompt-debian/prompt_* /usr/share/zsh/functions/Prompts
```

### Per user

```console
git clone https://github.com/wjmcknight/zsh-prompt-debian.git
mkdir ~/.zprompts
cp zsh-prompt-debian/prompt_* ~/.zprompts
```

## Configuration

### System wide

Simply add the following to `~/.zshrc`:

```bash
prompt debian
```

or:

```bash
prompt drabian
```

### Per user

First, you'll want to add this at or near the top of your `~/.zshrc`:

```bash
fpath=( "$HOME/.zprompts" $fpath )
```

Next, call the prompt with:

```bash
prompt debian
```

or:

```bash
prompt drabian
```

## Config note

Depending on your installed version of Zsh, you may need to enable color 
support in your `~/.zshrc` config which you can do by adding this:

```bash
autoload -U colors
colors
```

## License

BSD 3-clause "Modified" License: https://opensource.org/licenses/BSD-3-Clause
