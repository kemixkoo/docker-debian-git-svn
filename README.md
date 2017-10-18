# Debian Git SVN Image

Based on debian:buster-slim


# Installed Version

git, version 2.11.0

svn, version 1.9.5 (r1770682)

nano, version 2.7.4


# Usage

```
docker run --rm kemixkoo/debian-git-svn
```
By default, will display the version of git, svn, nano.


# Custom

## Git

Customize the gitconfig via volume (-v):

```
docker run -v ~/.gitconfig:/root/.gitconfig kemixkoo/debian-git-svn
```


# Building

```
docker build -t kemixkoo/debian-git-svn .
```
