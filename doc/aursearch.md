# aursearch

## Name

aursearch - Search AUR package names by PCRE pattern

## Synopsis

aursearch [+-Fbqrv} [--] ARGS...

## Description

Search the AUR for packages. The argument is a PCRE pattern which is matched against the AUR.

## Operations

* __-F__ Search for a fixed string instead of a PCRE pattern
* __-b__ Match pkgbase instead of pkgname
* __-q__ Output less
* __-r__ Output JSON from AUR RPC
* __-v__ Output more

## See also

__pcrepattern__(3)

## Authors

Alad Wenter (https://github.com/AladW)