# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test go-versioninfo https://github.com/ngyewch/go-versioninfo-plugin.git "go-versioninfo version"
```

Tests are automatically run in GitHub Actions on push and PR.
