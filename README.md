# Tmux configuration files

First ensure that tmux has already been installed.
This setup is inspired by [dreamsofcode-io's setup](https://github.com/dreamsofcode-io/tmux)

To clone on different operating systems

- on Linux and Mac
```sh
git clone https://github.com/chrhjoh/tmux.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

- on Windows (cmd)
```
git clone https://github.com/chrhjoh/tmux.git %userprofile%\AppData\Local\nvim\ 
```

- on Windows (powershell)
```
git clone https://github.com/chrhjoh/tmux.git $env:USERPROFILE\AppData\Local\nvim\ 
```


After installation start tmux

```sh
tmux
```

This then installs the tmux plugin manager (tpm) and other plugins
