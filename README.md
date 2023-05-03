Proxy configuration files
=========================

For use with SOCKS5 as provided by [`tailproxy`](https://github.com/gbraad/dotfiles/blob/main/zsh/.local/bin/start-tailproxy) or [`ssh`-based proxy](https://github.com/gbraad/dotfiles/blob/main/zsh/.zshrc.d/alias.zsh) command.


### Usage
To run a server, consider the following:
  * [tailscale-tailwings](https://github.com/spotsnel/tailscale-tailwings), self-contained proxy server for use with tailscale
  * [Dante server](https://github.com/spotsnel-fedora/dante-packages), `dante` and `dante-server` packages needed

Proxy client packages for Fedora/EL are available here:
  * [`socksify`](https://github.com/spotsnel-fedora/dante-packages), part of the `dante` client library
  * [toscks](https://github.com/spotsnel-fedora/tsocks-packages), a transparent SOCKS proxying library


### Related
  * [dotfiles](https://github.com/gbraad/dotfiles)
  * [devenv](https://github.com/gbraad/devenv/)