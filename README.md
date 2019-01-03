# VSC-Trials
## (Overview of) My Trials in Setting Visual Studio Code for C++ learning 


The initial idea was to use VSC in Windows for C++ (re)learning, with as little as possible installations and/or configurations.
Of course this got out of control :-)

So I tried to make some "how-to" articles inspired by my hardships.

* [Part 1 - Windows 10, MSYS / MinGW](https://github.com/Adrian-LL/vscode-cpp-windows) 
  * The initial idea. I tried MinGW, settled for MSYS2 (that, of course included MinGW).
* [Part 2 - Windows + WSL](https://github.com/Adrian-LL/vscode-cpp-win-wsl)
  * I tried to use WSL tools (i.e. gcc / g++ and so on) instead of MinGW with VSC running in Windows
* [Part 3 - Installing VSC as graphical application under WSL, console and (unfortunate) conclusions](https://github.com/Adrian-LL/vscode-cpp-wsl-graphical-apps)
  * Tried to install `code` inside WSL (actually not tried, but managed). Working with it is altogether another story.
  * There are some personal considerations about using a better console and X Server
  * `sublime-text` works!
  
## Other things
### Good versions of configuration files for Ubuntu (i.e not WSL):
* tasks.json
* launch.json

### Work In Progress:
* tasks for Clang++
* launch for lldb (somehat working)

**To be updated ...**
