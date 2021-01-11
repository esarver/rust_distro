# Rust Distro

Arch-base because it is bleeding edge and super lean by default.

## Default Install ##
- **GUI backend:** Wayland
- **Editor:** NeoVim
- **Package Manager:** Cargo (pacman will be available, just in case)
- **Shell:** [ion](https://github.com/redox-os/ion)
- rustup
  - stable
  - nightly

## Apps to Clone ##

### Suckless.org Clones ###
Suckless has a great view of how to create applications: make them simple, small, and hackable. 
All configuration is completed at compile-time, not runtime. 

- [dwm](https://dwm.suckless.org) / [dwl](https://github.com/djpohly/dwl)
- [st](https://st.suckless.org)
  - Maybe just use [alacritty](https://github.com/alacritty/alacritty)
- [surf](https://surf.suckless.org)
  - Servo renderer (maybe the [Servo](https://servo.org) project would be sufficient in and of itself)
  
### Other Apps to Clone ###
- (neo)vim editor
  - No vimscript support
- tmux
  - [tab](https://crates.io/crates/tab) looks like it might be promising and has a [how-to](https://implaustin.hashnode.dev/how-to-write-a-terminal-multiplexer-with-rust-async-and-actors-part-2) guide.
