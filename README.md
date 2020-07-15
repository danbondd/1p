>**NOTE: As most of the features are now built into the official `op` tool, or on the product roadmap, `1p` will not be receiving further updates.**

# 1p

(Unofficial) Wrapper for the [1Password CLI](https://support.1password.com/command-line-getting-started/).

## Installation

- Copy or link the script to your `$PATH`: `ln -sfv /path/to/1p /usr/local/bin/1p`
- Create an alias (optional): `alias op=1p`

## Usage

`1p` works exactly the same as the `op` command. However, it simplifies a few of the commands:

- `1p export`: Export all logins and save to a file.
- `1p get password <account>`: Get password for given account in plain text.
- `1p signin`: Sign in to current saved profile in `$HOME/.op/config`.
