# What

Shortcut tool for Toolbox (https://containertoolbx.org/) that can associate diretories with a toolbox. 

# Install

```
pip install --user toolbox-dir
```

# Usage
```
Usage: tb [OPTIONS] COMMAND [ARGS]...

  Shortcut tool for Toolbox (https://containertoolbx.org/) that can associated
  diretories with a toolbox.

  Features, Feedback, and Bugs: https://github.com/bostrt/toolbox-dir

Options:
  --podman-url TEXT  URL to access Podman service  [default:
                     unix:///run/user/1000/podman/podman.sock]
  -h, --help         Show this message and exit.

Commands:
  add    Link a directory to Toolbox container
  enter  Enter a linked toolbox for a directory
  list   List all toolbox/directory links
  rm     Remove link for directory
```

# Demo

[![asciicast](https://asciinema.org/a/ND7jdq9U1HUF9jp00dqNTQBij.svg)](https://asciinema.org/a/ND7jdq9U1HUF9jp00dqNTQBij)
