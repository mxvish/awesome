# awesome
Awesome projects

# Contents
<a href="#Internet">Internet</a><br>
-  <a href="#Web-Browser">Web Browser</a><br>
-  <a href="#Chrome-extensions">Chrome extensions</a><br>
-  <a href="#Frontend">Frontend</a><br>
-  <a href="#Web-Server">Web Server</a><br>
-  <a href="#Web-Scraping">Web Scraping</a><br>

<a href="#Multimedia">Multimedia</a><br>
-  <a href="#Audio-Player">Audio Player</a><br>

<a href="#Utilities">Utilities</a><br>
-  <a href="#File-manager">File manager</a><br>
-  <a href="#Terminal-emulator">Terminal emulator</a><br>
-  <a href="#Package-Manager">Package Manager</a><br>
-  <a href="#File-encoding-checker">File encoding checker</a><br>
-  <a href="#Copy-file-contents-to-clipboard">Copy file contents to clipboard</a><br>
-  <a href="#Useful-linux-commands">Useful linux commands</a><br>

<a href="#Documents-and-texts">Documents and texts</a><br>
-  <a href="#Text-Editor">Text Editor</a><br>
-  <a href="#Japanese-Input">Japanese Input</a><br>

<a href="#Others">Others</a><br>
-  <a href="#Programming-language">Programming language</a><br>
-  <a href="#Education">Education</a><br>
-  <a href="#Operating-System">Operating System</a><br>
-  <a href="#Display-Manager">Display Manager</a><br>

<a href="#References">References</a><br>
<a href="#Author">Author</a><br>

## Internet 
### Web Browser
  - [Brave](https://brave.com/) - A privacy oriented web browser and fork of chromium browser 
### Chrome extensions
  - [AHA Music](https://chrome.google.com/webstore/detail/aha-music-song-finder-for/dpacanjfikmhoddligfbehkpomnbgblf) - Song finder for audio playing in the current website(tab)
  - [Audio Only Youtube](https://chrome.google.com/webstore/detail/audio-only-youtube/pkocpiliahoaohbolmkelakpiphnllog) - Hide video on YouTube
  - [Read Aloud](https://chrome.google.com/webstore/detail/read-aloud-a-text-to-spee/hdhinadidafjejdhmfkjgnolgimiaplp) - Learn language for free!
  - [uBlacklist](https://chrome.google.com/webstore/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe) - Hide specific sites from google search result
  - [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) - Best content blocker
  - [Vimium](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb) - Vim keybinding shortcuts for efficient browsing
  - [YouTube Windowed FullScreen](https://chrome.google.com/webstore/detail/youtube-windowed-fullscre/gkkmiofalnjagdcjheckamobghglpdpm) - Always watch video in Full Screen

### Frontend
  - [Tailblocks](https://tailblocks.cc/) - Ready-to-use CSS framework

### Web Server
  - [xampp](https://www.apachefriends.org/index.html) - A development environment with Apache, MariaDB, PHP, and Perl

### Web Scraping
  - [curl](https://curl.se/) - CLI tool to transfer data
  - [html2text](https://github.com/grobian/html2text) - HTML to text converter
  - Usage
    ```sh
    curl -s https://www.google.com | html2text
    ```

## Multimedia
### Audio Player
  - CLI
    - For Fedora(dnf) and Arch(pacman)
      - [mpg123](https://mpg123.de/)
    - For macOS(Homebrew), Ubuntu, Debian based Linux and Raspberry Pi(apt)
      - [mpg321](https://mpg321.sourceforge.net/)
  - GUI
    - [VLC Media Player](https://www.videolan.org/vlc/) - A free media player

## Utilities
### File manager
  - CLI
    - [ranger](https://github.com/ranger/ranger) - A file manager with vim keybindings
  - GUI
    - [thunar](https://github.com/xfce-mirror/thunar) - A lightweight file manager

### Terminal emulator
  - [xfce4-terminal](https://docs.xfce.org/apps/xfce4-terminal/start) - A lightweight and premade terminal

### Package Manager 
  - macOS 
    - [Homebrew](https://brew.sh/) - A fast package manager

### File encoding checker
  - macOS, Linux, and BSD
    - file command
    - usage
      - macOS
      ```sh
      file -I foo.txt
      ```
      - Linux, BSD
      ```sh
      file -i foo.txt
      ```
        - [documentation(Linux and BSD)](https://www.freebsd.org/cgi/man.cgi?query=file&manpath=FreeBSD+13.1-RELEASE+and+Ports)

### Copy file contents to clipboard
  - macOS
    - pbcopy
    - Usage
    ```sh
    pbcopy < foo.txt
    ```
  - Linux
    - [xclip](https://github.com/astrand/xclip) - CLI tool for X11 clipboard
    - Usage
    ```sh
    xclip -sel c < foo.txt
    ```

### Useful linux commands 
  - Check battery percentage
    - ```sh
    cat /sys/class/power_supply/BAT1/capacity
    ```
  - For Ubuntu, Fedora, openSUSE, and Arch
    - (These commands will not work on xfce)
    - Reboot linux without superuser permission
      - ```sh
      systemctl reboot -i
      ```
    - Suspend linux without superuser permission
      - ```sh
      systemctl suspend -i
      ```

## Documents and texts
### Text Editor
  - [Vim](https://www.vim.org/) - Highly productive text editor

### Japanese Input
  - For Windows and macOS
    - [Google Japanese Input](https://www.google.co.jp/ime/)
  - For GNOME(Ubuntu, Fedora)
    - `ibus-mozc`
  - For xfce, Raspberry Pi and i3(openSUSE and Arch)
    - `fcitx-mozc`

## Others
### Programming language
  - [Python](https://www.python.org/) - Good readability
  - [Java](https://www.java.com/en/) - Its WORA(Write Once Run Anywhere) feature is pretty good
  - [Shell Script](https://www.gnu.org/software/bash/) - Widen ability of your programming skills and increase productivity

### Education
  - Free tutorial
    - [w3schools](https://www.w3schools.com/) - Beginner friendly
    - [javatpoint](https://www.javatpoint.com/) - Ready-to-use code examples. Intermediate

### Operating System
  - [Arch Linux](https://archlinux.org/) - A lightweight and extensible linux distro

### Display Manager
  - Linux
    - [xrandr](https://github.com/freedesktop/xorg-xrandr) - CLI tool for adjusting display brightness, location, rotation etc

# References
[List of applications - ArchWiki](https://wiki.archlinux.org/title/List_of_applications)

# Author
- [Kenta Oshima](https://github.com/mxvish) - [Issues](https://github.com/mxvish/awesome/issues) and [PRs](https://github.com/mxvish/awesome/issues) are welcome!
