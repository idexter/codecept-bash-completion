# codecept-bash-completion
Bash Autocomplete for Codeception testing framework
Actual for [Codeception 2.0.11](https://github.com/Codeception/Codeception/releases/tag/2.0.11)

Original: https://github.com/Mediahero/Codeception/blob/1.8/codecept_complete.sh

Thanks to https://github.com/kuntashov

Script can autocomplete Codeception commands, options, suites(as dirs) and files in suites.

## Installation

First `bash-completion` must be installed in your operation system.
Codeception must be available via `codecept` or `codeception` command

### Ubuntu/Debian

Run commands
```
sudo wget https://raw.githubusercontent.com/DexterHD/codecept-bash-completion/master/src/codecept -O /etc/bash_completion.d/codecept
sudo chmod +x /etc/bash_completion.d/codecept
```
Restart shell

### OS X

You must have `homebrew` package manager installed first.
Run commands
```
brew install wget bash-completion
wget https://raw.githubusercontent.com/DexterHD/codecept-bash-completion/master/src/codecept -O /usr/local/etc/bash_completion.d/codecept
chmod +x /usr/local/etc/bash_completion.d/codecept
```
Restart shell

##License

This software is licensed using the MIT License. The license is provided in the source code repository.