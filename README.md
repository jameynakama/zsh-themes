zsh-themes
==========

I store my ZSH themes here. COOL. To use them (I recommend it), put them in your themes directory and set your
ZSH_THEME environment variable to the name of the thing, without the extension. Or be smarter and put it in your
~/.zshrc.

    $ git clone git@github.com:jameydeorio/zsh-themes.git
    $ cd zsh-themes
    $ cp rainbow-summer.zsh-theme $ZSH/themes
    $ echo 'ZSH_THEME="rainbow-summer"' >> ~/.zshrc
    $ source ~/.zshrc
    $ echo "My daily life just got a lot nicer!"