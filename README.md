[![Build Status](https://travis-ci.org/kennyp/asdf-golang.svg?branch=master)](https://travis-ci.org/kennyp/asdf-golang)

# asdf-golang
golang plugin for [asdf version manager](https://github.com/asdf-vm/asdf)


## Requirements
**Ubuntu 16.04+** `curl`   


## Install

```
asdf plugin-add golang https://github.com/kennyp/asdf-golang.git
```

## Use

Check the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of go.

## When using `go get`

After using `go get` to install a package you need to run `asdf reshim golang` to get any new shims.

## Contributing

Feel free to create an issue or pull request if you find a bug.

## Issues

* Assumes Linux, FreeBSD, or Mac
* Assumes x86_64, i386, i686, armv6l, armv7l or arm64

## License
MIT License
