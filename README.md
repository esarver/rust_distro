# Rust Distro

Arch-base because it is bleeding edge and super lean by default.

## Default Install ##
- **GUI backend:** Wayland
- **Editor:** NeoVim
- **Package Manager:** Cargo (pacman will be available, just in case)
- **Shell:** [ion](https://github.com/redox-os/ion)
- **Browser:** [Servo](https://servo.org)
- **Terminal Emulator:** [alacritty](https://github.com/alacritty/alacritty)
- **Terminal Multiplexer:** [tab](https://crates.io/crates/tab)
- git
- lldb
- Rust toolchain:
  - rust-analyzer
  - rustup
    - stable
    - nightly

## Apps to Clone ##

### Suckless.org Clones ###
Suckless has a great view of how to create applications: make them simple, small, and hackable. 
All configuration is completed at compile-time, not runtime. It might be fun to try to copy that 
mindset with the applications provided in this distro which could slowly replace other default 
applications.

- [dwm](https://dwm.suckless.org) / [dwl](https://github.com/djpohly/dwl)
  - look at [Swot](https://hg.sr.ht/~icefox/swot) for a rust implementation of [tinywl](https://github.com/swaywm/wlroots/blob/master/tinywl/tinywl.c)
  - A good [writeup about Swot](https://wiki.alopex.li/WritingAWaylandCompositorInRust)
- [st](https://st.suckless.org)
- [surf](https://surf.suckless.org)
  
### Other Apps to Clone ###
- (neo)vim editor
  - No vimscript support
- tmux
  - [tab](https://crates.io/crates/tab) looks like it might be promising and has a [how-to](https://implaustin.hashnode.dev/how-to-write-a-terminal-multiplexer-with-rust-async-and-actors-part-2) guide.
