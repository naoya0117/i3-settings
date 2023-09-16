# plasma-i3-config
- plasma-i3 session用のi3configファイルです。
- デスクトップマネージャにplasma-i3 sessionを追加する方法については、
https://www.github.com/naoya0117/plasma-i3-kwin_sessions.git を参照してください。

## 使い方
- 必要なパッケージをインストールする
```
sudo pacman -S i3 xcompmgr j4-makeconfig rofi i3blocks
```
```
git clone https://www.github.com/naoya0117/plasma-i3-settings.git ~/.config/i3
```
mod(win) + shift + r で設定ファイルが読み込まれるはずです。(設定を編集する際は、configを編集するのではなく、config.baseを更新して、```j4-make-config```を行ってください。この設定ファイルでは、j4-make-configのgreenish themeを使用しています。)
- このi3 configファイルでは、dmenu_runの変わりにrofiを使用しています。
  rofiの設定ファイルについては、https://www.github.com/naoya0117/dmenu-rofi-settings.git を参照してください。
- このi3 configファイルでは、i3 statusの代わりにi3blocksを使用しています。https://github.com/vivien/i3blocks-contrib を参考にi3 blocksを設定するか、i3statusをインストールし、 ~/.config/i3/config.base のbarブロック中のi3blocksをi3statusに書き換えてください。
