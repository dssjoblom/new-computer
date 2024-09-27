Things to do when setting up a new computer. This is for my personal
use, but I figured this might be interesting to others as well, so
making this repository public.

OS: Ubuntu Linux (22/24)

# Copy important configurations from GitHub

`sudo apt-get install git`

`git clone https://github.com/dssjoblom/dotfiles.git`

`cd dotfiles`

`cp .zshrc ~/`

`cp .emacs.el ~/`

`cp -R elisp/ ~/elisp`

# Switch to ZSH

`sudo apt-get install zsh`

`chsh -s /bin/zsh`

Reboot the system.

# Set up a firewall

`sudo ufw enable`

This is a useful future-proofing safeguard even if you are initially
only planning to use the computer in a local network inaccessible to
the public.

# Set up networking

 * Configure DNS to point to Pi-hole server in local network.
 * Configure HTTP proxy to point to Privoxy server in local network.

This can be done in several ways, I have usually used the Ubuntu
Settings GUI.

# Install Chrome

Hated by many, I still think this is the best browser. Download from
<https://www.google.com/chrome/>.

# Install Emacs

Install latest Emacs from Ubuntu Snap.

# Tweak UI

 * change keybindings for navigating between workspaces via Settings
   -> Keyboard -> Keyboard Shortcuts

 * change number of workspaces via Settings -> Multitasking ->
   Workspaces
