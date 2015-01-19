# media-dotfiles

I'm using RichiH/vcsh for dotfile management.

## Dependencies
Currently the following arch packages are used:
- [mopidy](https://aur.archlinux.org/packages/mopidy/) as an MPD implementation
- [mopidy-spotify](https://aur.archlinux.org/packages/mopidy-spotify/) for spotify integration
- [ncmpcpp](https://www.archlinux.org/packages/?name=ncmpcpp) as an MPD client

## How to use
```
# Install dependencies
yaourt -S mopidy mopidy-spotify ncmpcpp

# Clone  
vcsh clone git@github.com:deiwin/media-dotfiles.git media
```
