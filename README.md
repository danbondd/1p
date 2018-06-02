# 1p

(Unofficial) Wrapper for the [1Password CLI](https://support.1password.com/command-line-getting-started/).

## Installation

- Copy the script to your `$PATH`: `cp ./1p /usr/local/bin`
- Create an alias: `alias op=1p`

## Usage

`1p` works exactly the same as the `op` command. However, it simplifies a few of the commands:

- `op get item <account>`: Get password for given account in plain text.
- `op generate`: Create a random 32 bit password.
- `op signin`: Sign in to current saved profile in `$HOME/.op/config`.
