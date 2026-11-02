# kvz Homebrew tap

Homebrew formulae for [kvz](https://github.com/kvz-platform/kvz), native macOS
Kubernetes.

```sh
brew install kvz-platform/tap/kvz
```

kvz needs an Apple Silicon Mac running macOS 26 or later. The formula installs
a signed and notarized `kvz` binary and the pod kernel.

Upgrade with `brew upgrade kvz`.

## How this tap is updated

`Formula/kvz.rb` is written by the kvz release pipeline from
[`packaging/homebrew/kvz.rb.tmpl`](https://github.com/kvz-platform/kvz/blob/main/packaging/homebrew/kvz.rb.tmpl).
Please send changes there, not here.
