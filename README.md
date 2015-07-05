# media-dotfiles

I'm using RichiH/vcsh for dotfile management.

## Dependencies
Currently the following arch packages are used:
- [mopidy](https://aur.archlinux.org/packages/mopidy/) as an MPD implementation
- [mopidy-spotify](https://aur.archlinux.org/packages/mopidy-spotify/) for spotify integration
- [mpd](https://www.archlinux.org/packages/?name=mpd) the plain MPD for listening w/o spotify
- [ncmpcpp](https://www.archlinux.org/packages/?name=ncmpcpp) as an MPD client
- [mpv](https://www.archlinux.org/packages/?name=mpv) as a video player

## How to use
```
# Install dependencies
yaourt -S vcsh mopidy mopidy-spotify mpd ncmpcpp mpv

# Clone  
vcsh clone git@github.com:deiwin/media-dotfiles.git media
```
