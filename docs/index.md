# Minio Client

mc - Minio Client for S3 Compatible Object Storage released under [Apache license v2](./LICENSE).

## Install

```
# go get github.com/minio-io/mc
```

## Usage

### Commands
```
NAME:
   mc - Minio Client for object storage and filesystems

USAGE:
   mc [global flags] command [command flags] [arguments...]

VERSION:
   9b3f0a923efd39cd98487c08b761dbd0

BUILD:
   2015-04-28 11:59:38.77226527 -0700 PDT

COMMANDS:
   ls		List files and objects
   cp		Copy objects and files from multiple sources single destination
   sync		Copies files and objects from single source to multiple destinations
   cat		Concantenate objects or files to standard output
   mb		Make a bucker or a folder
   access	Set permissions [public, private, readonly] for buckets and folders.
   config	Generate configuration "/home/harsha/.mc/config.json" file.
   update	Check for new software updates

GLOBAL FLAGS:
   --theme "minimal"	Choose a console theme from this list [*minimal*, nocolor, white]
   --debug		Enable HTTP tracing
   --quiet, -q		Supress chatty console output
   --retry "5"		Number of retry count
   --version, -v	print the version

```

## Contribute

[Contribute to mc](./contributing.md)

### Supported platforms

| Name  | Supported |
| ------------- | ------------- |
| Linux  | Yes  |
| Windows | Yes |
| Mac OSX | Yes |

### Supported architectures

| Arch | Supported |
| ------------- | ------------- |
| x86-64 | Yes |