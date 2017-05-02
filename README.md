# Debian Zsh Prompt

The Debian (original Bash or Dash) prompt for Zsh.

### Installation:
- Copy prompt_debian_setup to /usr/share/zsh/functions/Prompts
- Call prompt in your ~/.zshrc with: ```prompt debian```

### Config note:

Depending on your installed version of Zsh, you may need to enable color 
support in your ~/.zshrc config which you can do by adding this:

    autoload -U colors
    colors
