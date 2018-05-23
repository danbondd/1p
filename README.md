# 1p

(Unofficial) Wrapper for the [1Password CLI](https://support.1password.com/command-line-getting-started/).

## Installation

- Copy the script to your `$PATH`: `cp ./1p /usr/local/bin`
- Create an alias: `alias op=1p`

## Usage

`1p` works exactly the same as the `op` command. However, by default it pretty prints the JSON output.

### 1p Subcommands

- `1p get password <account>`: Get password for given account in plain text.
- `1p create password`: Create a random 32 bit password.
