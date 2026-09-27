# ShrimpScript's Homebrew tap

```sh
brew install shrimpscript/tap/porthole
portholed setup
```

[Porthole](https://porthole-one.vercel.app) supervises Claude Code on your Mac or Linux
computer from your Android phone, over your own Tailscale network. The formula installs the
release's prebuilt `portholed` (macOS or Linux, Intel or ARM) and links `porthole` beside it;
`portholed setup` starts the background service and adds the approval hook.

`Formula/porthole.rb` is generated at each release by `tools/homebrew-formula.sh` in
[ShrimpScript/porthole](https://github.com/ShrimpScript/porthole); changes belong there.
