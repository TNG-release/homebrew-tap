# TNG-release Homebrew tap

Homebrew formulae for software released by [TNG Technology Consulting][tng].

## Usage

```sh
brew tap TNG-release/tap
brew install <formula>
```

## Available formulae

| Formula | Description | Source |
| --- | --- | --- |
| [`oh-my-agentic-coder`](Formula/oh-my-agentic-coder.rb) | Sandboxed agent-coding facade with keychain-backed secrets. | [TNG/oh-my-agentic-coder](https://github.com/TNG/oh-my-agentic-coder) |
| [`nono-tng`](Formula/nono-tng.rb) | Capability-based sandbox for running untrusted commands (TNG fork). | [TNG/nono](https://github.com/TNG/nono) |

## Updating

Formulae are pushed automatically by each project's release pipeline
(GoReleaser) on every non-prerelease tag. Do not edit them by hand —
changes will be overwritten on the next release.

```sh
brew update
brew upgrade <formula>
```

## License

Each formula carries the license of its upstream project. The tap
metadata itself is released under the [Apache 2.0 License](LICENSE).

[tng]: https://www.tngtech.com/
