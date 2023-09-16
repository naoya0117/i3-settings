# plasma-i3-settings
- plasma-i3 session用のi3configファイルです。
- デスクトップマネージャにplasma-i3 sessionを追加する方法については、
https://www.github.com/naoya0117/plasma-i3-kwin_sessions.git を参照してください。

## 使い方
- 必要なパッケージをインストールする
```
sudo pacman -S i3 xcompmgr j4-makeconfig rofi
```
```
git clone https://www.github.com/naoya0117/plasma-i3-settings.git ~/.config/i3
```
mod(win) + shift + r で設定ファイルが読み込まれるはずです。(設定を編集する際は、configを編集するのではなく、config.baseを更新して、```j4-make-config```を行ってください。この設定ファイルでは、j4-make-configのgreenish themeを使用しています。)
- なお、この設定ファイルでは、dmenu_runの変わりにrofiを使用しています。
  rofiの設定ファイルについては、https://www.github.com/naoya0117/dmenu-rofi-settings.git を参照してください。
  
