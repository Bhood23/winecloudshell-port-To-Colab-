# winecloudshell-port-To-Colab Originaly Made By @raspduino
Install wine on Google Colab, together with winetricks, xfce4, and VNC through ngrok
Thanks To @raspduino For The Og Repo And Telling Me to 
Have !bash wcs.sh instead of !./wcs.sh 

# I want to install it now!
[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://shell.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https%3A%2F%2Fgithub.com%2Fraspiduino%2Fwinecloudshell&cloudshell_git_branch=main&cloudshell_tutorial=README.md)

# How to run it?

```
!sudo apt install git wget
!wget https://raw.githubusercontent.com/Bhood23/winecloudshell-port-To-Colab-/Pls-Don't-Use/wcs.sh
!chmod +x wcs.sh
!bash wcs.sh
```

It will prompt you some questions, so prepare for that, and look carefully for the prompt, especially before the long xfce log appear (you might miss that, for sure) :)

# Note
Each time you choose to set `WINEPREFIX` to `/tmp/wineprefix`, it will append a new line

```
!export WINEPREFIX=/tmp/wineprefix
```

to your `~/.bashrc`.

So your `.bashrc` will be longer :)

# License
[MIT License](https://github.com/raspiduino/winecloudshell/blob/main/LICENSE)

The script's author is not responsible to any damage caused by the script itself or by user's actions.
