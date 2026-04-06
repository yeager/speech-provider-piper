# A Piper Speech Provider

This is a Spiel speech provider for neural TTS models like Piper.

## Swedish custom voices

Custom Swedish voices should be kept separate by speaker identity.

- **Alma** = female voice
- **Axel** = male voice

If you package additional Swedish voices for this provider, keep their metadata and distribution entries separate instead of reusing the same listing.

## Installation

TODO

## Build instructions

```sh
meson setup build
meson compile -C build
```

To run the provider without installing:
```sh
meson devenv -C build
./src/speech-provider-piper
```
