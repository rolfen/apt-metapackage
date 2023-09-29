# apt-metapackage
Metapackage utility

## Status
Just started!

## Rationale  
Inspired by [apk add virtual](https://man.archlinux.org/man/apk-add.8.en). Create virtual packages (also know as metapackages) on the fly, to manage manually installed dependencies.

## Suggested Syntax
```
apt-metapackage create <package-name> [install] [package-definition], [package-definition] ...
```

```
apt-metapackage modify <package-name> add|remove|set <relationship> [package-definition], [package-definition] ...
```

```
apt-metapackage show <package-name> 
```

Relationships: Depends, Recommends, Suggests, Pre-Depends, Build-Depends, Build-Depends-Indep and Build-Depends-Arch

## Disclaimer  
If you create fake packages that provide real dependencies and break your system, don't blame me!

## Read more  
https://help.ubuntu.com/community/MetaPackages  
https://www.debian.org/doc/debian-policy/ch-relationships.html
