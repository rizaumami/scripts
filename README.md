# scripts
A collection of scripts.

## How to

- Clone this repo

  ```bash
  git clone https://github.com/rizaumami/scripts
  ```

- Edit `~/.bashrc` or `~/.bash_profile` or `~/.bash_login` or `~/.profile` to include `scripts` folder into our PATH. \
For example, if the path to `scripts` folder is `$HOME/Software/scripts`. Insert lines below into one of the files above.

  ```bash
  if [ -d "$HOME/Software/scripts" ]; then
    PATH="$HOME/Software/scripts:$PATH"
  fi
  ```

- Relogin. Or just source the edited file. E.g. if the edited file is `~/.profile`:

  ```bash
  source ~/.profile
  ```

- Profit! Now we can directly call the scripts everywhere whitin terminal.
