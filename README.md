# homebrew-apksim

Homebrew tap for [apksim](https://github.com/aglose/apksim): it runs unmodified Android APKs on an Apple Silicon Mac as one process, with no VM.

```bash
brew tap aglose/apksim
brew trust aglose/apksim    # Homebrew 7 loads casks only from taps you trust
brew install apksim
apksim app.apk
```

`Casks/apksim.rb` is written by apksim's release workflow each time a release is published; don't edit it here.
