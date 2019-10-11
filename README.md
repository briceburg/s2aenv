# s2aenv - saml2aws version manager

## usage

```
s2aenv - saml2aws version manager, without support for .s2aenv hinting.
Usage: s2aenv <command> [<options>]

Commands:
   install <ver|latest> Install (and use) specific version saml2aws
   use <ver|latest>     Switch a version to use
   uninstall <ver>      Uninstall a specific version of saml2aws
   list                 List all installed versions
   list-remote          List all installable versions
```

### list available versions

```
$ s2aenv list-remote
...
v2.16.0
v2.17.0
v2.2.0
v2.3.0
v2.4.0
v2.4.1
v2.4.2
v2.5.0
v2.6.0
v2.6.1
v2.6.2
v2.7.0
v2.8.0
v2.8.1
v2.9.0
```

### install a version

```
$ s2aenv install v2.9.0
```
