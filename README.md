# s2aenv - saml2aws version manager

## install

```
sudo git clone https://github.com/briceburg/s2aenv.git /opt/s2aenv
ln -fs /opt/s2aenv/s2aenv /usr/local/bin/
```

(I haven't published a release, so we're cloning from git and symlinking the script to /usr/local/bin/s2aenv)


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

### install the latest version of saml2aws

````
$ s2aenv install latest
```

### install a version particular version

```
$ s2aenv install v2.9.0
```
