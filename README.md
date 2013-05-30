Sublime VLT build system
========================

Sublime Text 2 build system for working with Adobe CQ's FileVault tool (vlt)

Installation (OS X)
-------------------
Create a new directory in your Sublime [packages directory](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory):
```
mkdir ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/Vault
```

Copy `Vault.sublime-build` to this dir:
```
cp Vault.sublime-build ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/Vault
```

Usage
-----
This section assumes you have already (syncronized with the repository)[http://dev.day.com/docs/en/crx/current/how_to/how_to_use_the_vlttool.html].

To check in the current file:
`Cmd + B`

To access the other available commands:
`Cmd + Shift + P`
and type `vlt`. Select the command.