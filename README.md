# HamWaver

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![pypi](https://img.shields.io/pypi/v/ggwave.svg)](https://pypi.org/project/ggwave/)
[![npm](https://img.shields.io/npm/v/ggwave.svg)](https://www.npmjs.com/package/ggwave/)

HamWaver - 
 A fork of ggerganov's ggwave library and util to make it a bit more friendly for Ham Radio users. 
 All the hard work and thanks goes to Georgi Gerganov for their work on this great project. 
 <p>
Matt VK2FLY




<a href="https://user-images.githubusercontent.com/1991296/161401690-013023ba-1d21-4fb7-8d7f-9953f51c1e5b.mp4"><img width="100%" src="https://user-images.githubusercontent.com/1991296/109401710-d7d3d880-7958-11eb-9b7e-364be0b4cf55.gif"></img></a>

<a href="https://youtu.be/Zcgf77T71QM"><img width="100%" src="media/waver-preview1.gif"></img></a>


## Details

This project is very beta and is currently under test among a small group of operators. As such the doco is fairly slim. See the original project at https://github.com/ggerganov/ggwave for other info. 

If you would like to test with us and you are in Sydney Give me a call on VK2RBV - Note that I will likely be pushing code many times a day  until I get some of the initital features tested. 


## Building

### Dependencies for SDL-based examples

    [Ubuntu]
    $ sudo apt install libsdl2-dev

    [Mac OS with brew]
    $ brew install sdl2

    [MSYS2]
    $ pacman -S git cmake make mingw-w64-x86_64-dlfcn mingw-w64-x86_64-gcc mingw-w64-x86_64-SDL2

### Linux, Mac, Windows (MSYS2)

```bash
# build
git clone https://github.com/mattaperkins/HamWaver --recursive
cd ggwave && mkdir build && cd build
cmake ..
make

```
### running
```
./bin/waver
```
Then go into the cogs menu at the top left and enter your callsign. (note right now there is no way to save the callisgn so it must be re-entered after restarting the app) 
<p>Other settings can be left at their defaults. 


[license]: ./LICENSE
