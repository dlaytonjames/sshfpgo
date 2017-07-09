# sshfpgo

[![Build Status](https://travis-ci.org/arnested/sshfpgo.svg?branch=master)](https://travis-ci.org/arnested/sshfpgo)
[![release](https://github-release-version.herokuapp.com/github/arnested/sshfpgo/release.svg)](https://github.com/arnested/sshfpgo/releases/latest)
[![Go Report Card](https://goreportcard.com/badge/github.com/arnested/sshfpgo)](https://goreportcard.com/report/github.com/arnested/sshfpgo)

```
$ sshfpgo
NAME:
   sshfpgo - Update SSHFP DNS records

USAGE:
   sshfpgo [global options] command [command options] [arguments...]

AUTHOR:
   Arne Jørgensen <arne@arnested.dk>

COMMANDS:
     dnsimple  Update SSHFP DNS records for DNSimple provider
     help, h   Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --verbose            Verbose output
   --dry-run            Do no updates
   --hostname HOSTNAME  The HOSTNAME to update records for (default: "host.example.com")
   --help, -h           show help
   --version, -v        print the version
```

## DNS providers

### DNSimple

```
$ sshfpgo dnsimple
NAME:
   sshfpgo dnsimple - Update SSHFP DNS records for DNSimple provider

USAGE:
   sshfpgo dnsimple [command options] [arguments...]

OPTIONS:
   --zone ZONE    DNSimple ZONE (default: "example.com")
   --token TOKEN  DNSimple Oauth TOKEN [$DNSIMPLE_TOKEN]
   --sandbox      Run against DNSimples sandbox environment
```
