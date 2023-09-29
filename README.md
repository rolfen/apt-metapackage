# apt-metapackage
Metapackage / virtual package utility

## Status
Just started!

## Rationale  
Inspired by [apk add virtual](https://man.archlinux.org/man/apk-add.8.en). Create virtual packages (also know as metapackages) on the fly, to manage manually installed dependencies.

## Suggested Syntax
```
apt-virtual install <package-name> [<package-definition>] [,<package-definition>] ... 
```

```
apt-virtual modify <package-name> add|remove|set <relationship> [<package-definition>] [,<package-definition>] ...
```

```
apt-virtual show <package-name> 
```

Relationships: Depends, Recommends, Suggests, Pre-Depends, Build-Depends, Build-Depends-Indep and Build-Depends-Arch

Export...?

## Disclaimer  
If you break your system using this tool, it's on you!

## Read more  
https://help.ubuntu.com/community/MetaPackages  
https://www.debian.org/doc/debian-policy/ch-relationships.html
