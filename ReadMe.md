# Attention: I no longer recommend this method. Do use Docker with VS Code Remote Containers instead, as mentioned in the wiki: https://github.com/James-Yu/LaTeX-Workshop/wiki/Install#using-docker

---

Provides Docker shims for LaTeX binaries used by https://github.com/James-Yu/LaTeX-Workshop

Motivation: 
- Easy installation.
- Does not mess with your local files.

I am using this on MacOS, but this should work on unix generally. Windows is not supported currently. Contributions are welcome!

# Setup

- Install Docker for MacOS (https://www.docker.com/community-edition#/download or run `brew cask install docker` if you have `brew`)
- Clone this repository
- Add the `bin` directory to your path
- In VS Code, install the awesome https://github.com/James-Yu/LaTeX-Workshop extension
- Ready! Building, linting, SyncTex, formatting just works!

# Credits

Inspired by https://github.com/James-Yu/LaTeX-Workshop/issues/302
