Proxy configuration files
=========================

For use with SOCKS5 as provided by [`tailproxy`](https://github.com/gbraad/dotfiles/blob/main/zsh/.local/bin/start-tailproxy) or [`ssh`-based proxy](https://github.com/gbraad/dotfiles/blob/main/zsh/.zshrc.d/alias.zsh) command.


### Usage

#### Server
To run a server:
  * [tailscale-tailwings](https://github.com/spotsnel/tailscale-tailwings), self-contained proxy server for use with tailscale
  * [Dante server](https://github.com/spotsnel-fedora/dante-packages), `dante` and `dante-server` packages needed
  * [ssh-based](https://github.com/gbraad/dotfiles/blob/8eeb1ee5f4dd6fddc5351bc47be3e3667ad58811/zsh/.zshrc.d/alias.zsh#L14-L15), using the `-D` option

#### Client
Packages for Fedora/EL:
  * [`socksify`](https://github.com/spotsnel-fedora/dante-packages), part of the `dante` client library
  * [`tsocks`](https://github.com/spotsnel-fedora/tsocks-packages), a transparent SOCKS proxying library

Note: for Debian they are included in the package repository as `dante-client`, and `tsocks`.


### Related
  * [dotfiles](https://github.com/gbraad/dotfiles)
  * [devenv](https://github.com/gbraad/devenv/)
