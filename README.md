# DEPRECATED. Use golangci-lint instead

To replicate the behavior of this library using modern tools, use the following formatting
config in `.golangci.yml`:

```
...
formatters:
  enable:
    - gci
  settings:
    gci:
      custom-order: true
      sections:
        - standard
        - default
        - prefix(your.local/path)
...
```

# Importsort

This is a fork of repository - https://github.com/aristanetworks/goarista/tree/master/cmd/importsort

## Quick start

```bash
$ go get -u github.com/lcd1232/importsort
```
