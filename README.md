# mac-packages

Repository of exported packages using Brew. Can be used to automate installing software on a new MacOS install.

## Requirements

- [Brew](https://brew.sh/)

The Brewfile was generated by running:

`brew bundle dump --file=./Brewfile`

## Usage

`brew bundle --file=./Brewfile`

It is also recommended to install xcode command line tools:

`xcode-select --install`