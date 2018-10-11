# 1p

(Unofficial) Wrapper for the [1Password CLI](https://support.1password.com/command-line-getting-started/).

## Installation

- Copy/link the script to your `$PATH`: `ln -sfv /path/to/1p /usr/local/bin/1p`
- Create an alias: `alias op=1p`

## Usage

`1p` works exactly the same as the `op` command. However, it simplifies a few of the commands:

- `op export`: Export all logins and save to a file.
- `op get password <account>`: Get password for given account in plain text.
- `op generate`: Create a random 32 byte password.
- `op signin`: Sign in to current saved profile in `$HOME/.op/config`.
