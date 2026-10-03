Gathered from all over the internet, A non-exhaustive opinionated Awesome list by me; for me.

```shell
if (sad) {
  sad.stop(); beAwesome()
}
```

<br/>


## Windows Setup

### Package Managers

[Chocolatey](https://chocolatey.org/install): The OG package manager for Windows for installing dev tools and apps.

[WinGet](https://github.com/microsoft/winget-cli): The official Windows package manager from Microsoft.
```powershell
# Install WinGet.
Add-AppxPackage https://aka.ms/getwinget

# Check version
winget --version

# Install Chocolatey
winget install -e --id Chocolatey.Chocolatey
```

### Core CLI Tools

[BusyBox](https://frippery.org/busybox/): A bundle of popular Unix command-line tools for Windows.
```powershell
winget install -e --id frippery.busybox-w32
busybox --install
```

[GNU Core Utilities](https://gnuwin32.sourceforge.net/packages/coreutils.htm): Core Unix utilities like `ls`, `cp`, `rm`, and `grep` for Windows.
```powershell
winget install -e --id GnuWin32.CoreUtils
```

[Git for Windows](https://gitforwindows.org/): Git + Git Bash for a more Unix-like terminal experience.
```powershell
winget install --id Git.Git -e
```

[Nano](https://github.com/okibcn/nano-for-windows): A simple terminal text editor.
```powershell
winget install -e --id Nano.Nano
```

[NTop](https://github.com/gsass1/NTop): An `htop`-style system monitor with vi keybindings.
```powershell
winget install -e --id gsass1.NTop
```

### Utilities & Productivity

[Everything](https://www.voidtools.com/): Fast file search for Windows.
```powershell
winget install -e --id voidtools.Everything
```

[Flow Launcher](https://www.flowlauncher.com/): Fast application launcher and productivity tool.
```powershell
winget install -e --id Flow.Launcher
```

[File Converter](https://fileconverters.com/): Batch convert media files.
```powershell
winget install -e --id FileConverter.FileConverter
```

[Attribute Changer](https://www.petges.lu/): Modify timestamps and file attributes.
```powershell
sudo choco install attributechanger
```

### Fun / Media / Tools

[Opera Neon](https://www.opera.com/browsers/neon): A futuristic browser concept.
```powershell
winget install -e --id Opera.OperaNeon
```
<br/>

[fastfetch](https://github.com/fastfetch-cli/fastfetch): A modern system info tool for the terminal.
```powershell
winget install -e --id fastfetch.fastfetch
```
<br/>

[MPC-HC](https://mpc-hc.org/): Lightweight media player for Windows.
```powershell
winget install -e --id MPC-HC.MPC-HC
```
<br/>

[K-Lite Codec Pack](https://codecguide.com/): Full codec support for media playback.
```powershell
winget install -e --id CodecGuide.K-LiteCodecPack.Full
```
<br/>

[VLC](https://www.videolan.org/vlc/): Free and open-source multimedia player.
```powershell
winget install -e --id VideoLAN.VLC
```
<br/>

[Cloudflare WARP](https://www.cloudflare.com/zero-trust/products/warp/): Secure networking and privacy protection.
```powershell
winget install -e --id Cloudflare.WARP
```
<br/>

[Inkscape](https://inkscape.org/): Vector graphics editor.
```powershell
winget install -e --id Inkscape.Inkscape
```
<br/>

[Typora](https://typora.io/): Minimal Markdown editor.
```powershell
winget install -e --id typora.typora
```
<br/>

[File Converter](https://fileconverters.com/): Batch file conversion tool.
```powershell
winget install -e --id FileConverter.FileConverter
```
<br/>

[osquery](https://osquery.io/): Query OS data like a database.
```powershell
winget install -e --id osquery.osquery
```
<br/>

[yt-dlp](https://github.com/yt-dlp/yt-dlp): Command-line video downloader.
```powershell
winget install -e --id yt-dlp.yt-dlp
```
<br/>

[Avidemux](https://avidemux.sourceforge.net/): Free video editor and transcoder.
```powershell
winget install -e --id Avidemux.Avidemux
```
<br/>

[AOMEI Partition Assistant](https://www.diskpart.com/): Disk partitioning and management utility.
```powershell
winget install -e --id AOMEI.PartitionAssistant
```
<br/>

[LocalWP](https://localwp.com/): Local WordPress development environment.
```powershell
winget install -e --id LocalWP.LocalWP
```
<br/>

[Stretchly](https://hovancik.net/stretchly/): Break reminder to avoid burnout.
```powershell
winget install -e --id stretchly.Stretchly
```
<br/>

[FFmpeg](https://www.ffmpeg.org/): Audio/video processing framework.
```powershell
winget install -e --id Gyan.Dev.FFmpeg
```
<br/>

[Wget](https://www.gnu.org/software/wget/): Command-line web downloader.
```powershell
winget install -e --id GnuWin32.Wget
```
<br/>

[Postman](https://www.postman.com/): API development and testing platform.
```powershell
winget install -e --id Postman.Postman
```

<br/>
<br/>

## MacOS Setup

### Package Managers

[Homebrew](https://brew.sh/): The package manager for macOS, used to install most CLI tools and desktop apps.
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Core CLI Tools

[Git](https://git-scm.com/): Version control for repositories and collaboration.
```bash
brew install git
```

[BusyBox](https://busybox.net/): Common Unix utilities on macOS when you want a portable CLI stack.
```bash
brew install busybox
```

[GNU Core Utilities](https://www.gnu.org/software/coreutils/): More Unix-like versions of standard tools.
```bash
brew install coreutils
```

[Nano](https://www.nano-editor.org/): A lightweight terminal-based text editor.
```bash
brew install nano
```

[Htop](https://htop.dev/): Process monitor with a more Unix-like feel.
```bash
brew install htop
```

[Wget](https://www.gnu.org/software/wget/): Command-line downloader.
```bash
brew install wget
```

[FFmpeg](https://www.ffmpeg.org/): Audio/video processing toolkit.
```bash
brew install ffmpeg
```

[yt-dlp](https://github.com/yt-dlp/yt-dlp): Command-line video downloader.
```bash
brew install yt-dlp
```

[fastfetch](https://github.com/fastfetch-cli/fastfetch): A sleek system-info utility for the terminal.
```bash
brew install fastfetch
```

### Utilities & Productivity

[Raycast](https://www.raycast.com/): Fast app launcher and productivity tool for macOS.
```bash
brew install --cask raycast
```

[Alfred](https://www.alfredapp.com/): Alternative launcher and automation tool.
```bash
brew install --cask alfred
```

[GitHub Desktop](https://desktop.github.com/): GUI client for Git.
```bash
brew install --cask github
```

### Fun / Media / Tools

[IINA](https://iina.io/): A macOS-native media player with good playback support.
```bash
brew install --cask iina
```

[VLC](https://www.videolan.org/vlc/): Free and open-source multimedia player.
```bash
brew install --cask vlc
```

[Cloudflare WARP](https://www.cloudflare.com/zero-trust/products/warp/): Secure networking and privacy protection.
```bash
brew install --cask cloudflare-warp
```

[Inkscape](https://inkscape.org/): Vector graphics editor.
```bash
brew install --cask inkscape
```

[Typora](https://typora.io/): Minimal Markdown editor.
```bash
brew install --cask typora
```

[osquery](https://osquery.io/): Query your OS like a database.
```bash
brew install osquery
```

[LocalWP](https://localwp.com/): Local WordPress development environment.
```bash
brew install --cask local
```

[Stretchly](https://hovancik.net/stretchly/): Break reminder to avoid burnout.
```bash
brew install --cask stretchly
```

[Postman](https://www.postman.com/): API development and testing platform.
```bash
brew install --cask postman
```

<br/>
<br/>

## Browser (Chrome) Setup

<br/>
<br/>

## Python

<br/>
<br/>


## Data Science 

<br/>
<br/>


## Javascript

<br/>
<br/>


## Docker, Kubernetes, Infra++

<br/>
<br/>


<div align="center">
  <h1></h1>
  <h3> Curated with <b>❤️</b> by<b>〈 RA 〉</b></h3>
</div>
