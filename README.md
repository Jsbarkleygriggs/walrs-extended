![walrs logo](https://i.imgur.com/BORMhHc.png){align="right" height="200"}


This is a fork of [walrs](https://github.com/Pixel2175/walrs) with added modularity and handling for remote files for use with [wayvy](https://codeberg.org/J_S_Barkely-Griggs/Wayvy.git).

### walrs

#### Like Pywal, but written in Rust

walrs is a fast, minimalist CLI tool for generating color schemes from
wallpapers. It works the same as pywal but is written in Rust, making it
faster and more efficient. No external dependencies are required ---
just an app to set your wallpaper. If you\'re using pywal, you only need
to replace the \`wal\` command with \`walrs\`. Designed for users who
prefer simplicity and speed. Report issues or bugs on GitHub. Full

## Usage:
see man walrs

## Install
### For general purpose users:
```
$ git clone https://github.com/jsbarkleygriggs/walrs.git
$ cd walrs
$ make install
```
### For Wayvy users:
```
$ git clone https://github.com/jsbarkleygriggs/walrs.git
$ cd walrs
$ make FEATURES="colors" install
```

If ~/.cache/wal/colors is not generated, the script will not fuction properly.
