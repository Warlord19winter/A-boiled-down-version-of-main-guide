# A-boiled-down-version-of-main-guide
just the code and commands

copy paste the commands in the order that is listed

1: termux-setup-storage

2: termux-change-repo

3: pkg upgrade

4: pkg install x11-repo tur-repo root-repo

5: pkg install curl wget git

6: pkg install xfce4 xfce4-goodies termux-x11-nightly

7: pkg install florence code-oss firefox ark

8: pkg install neofetch xorgproto nano

9: pkg install termux-exec clang inxi

10: pkg install dosbox luanti

11: pkg install mesa-zink virglrenderer-mesa-zink vulkan-loader-android virglrenderer-android   

12: cd $HOME && rm -rf ~/xow64 && wget https://github.com/ar37-rs/xow64-wine/raw/refs/heads/main/xow64 && chmod +x ~/xow64

13: ~/xow64 install

14: termux-x11 :0 -xstartup "dbus-launch --exit-with-session xfce4-session"
