# Homebrew tap for KubeTective

This tap exists so KubeTective installs with a single command:

```sh
brew install gledilami/kubetective/kubetective
```

Homebrew finds this repository automatically because its name starts with
`homebrew-`. The formula installs two binaries:

- `kubetective`, the investigation engine CLI
- `kubectl-investigate`, the kubectl plugin (`kubectl investigate <resource>`)

The formula is a copy of `Formula/kubetective.rb` from the main repository
[github.com/GlediLami/kubetective](https://github.com/GlediLami/kubetective),
kept in sync at each release (see the release steps there).
