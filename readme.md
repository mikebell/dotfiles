# Mikes Tool Setup

A list of tools and config that I use on Arch, MacOS and Ubuntu/WSL.

## Should this be a dotfile repo?

Probably, but it's a pain to keep OS specific customisations in check per machine.

## Should I automate it?

Yes, if anyone has a way of writing once deploying to multiple OSs then I'm all for it. Making sure 3 different flavours of OS are in sync isn't easy though.

## Applications

* [Kitty](https://sw.kovidgoyal.net/kitty/) - MacOS and Arch
* Windows Terminal - Win 11
* VS Code (move to [VS Codium](https://vscodium.com/))

## CLI Stuff

* tmux
* [tpm](https://github.com/tmux-plugins/tpm)
  * tmux nord theme
  * tmux yank
* [oh-my-zsh](https://ohmyz.sh/)
  * candy theme
* [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
* [aws cli](https://aws.amazon.com/cli/)
* [kubectl](https://kubernetes.io/docs/tasks/tools/#kubectl)
* [kind](https://kubernetes.io/docs/tasks/tools/#kind)
* [kube-ps1](https://github.com/jonmosco/kube-ps1)
* [k9s](https://k9scli.io/)
* [stern](https://github.com/stern/stern)
* [helm](https://helm.sh/docs/intro/install/)
* jq/yq
* [tfenv](https://github.com/tfutils/tfenv)

## Aliases

```
alias tf="terraform"
alias k="kubectl"
```

## Dotfiles

* `.tmux.conf` - my default setup for tmux
