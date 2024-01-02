# [plasma-i3-config](https://github.com/naoya0117/plasma-i3-config)
- plasma-i3 session用のi3configファイルです。
- デスクトップマネージャにplasma-i3 sessionを追加する方法については、
[plasma-i3-kwin_session](https://www.github.com/naoya0117/plasma-i3-kwin_sessions.git) を参照してください。

## 使い方
- 必要なパッケージをインストールする
```
sudo pacman -S i3 xcompmgr j4-makeconfig rofi i3blocks
```
```
git clone https://www.github.com/naoya0117/plasma-i3_config.git ~/.config/i3
```
mod(win) + shift + r で設定ファイルが読み込まれるはずです。
- 設定を編集する際は、configを編集するのではなく、config.baseを更新して、```j4-make-config```を行ってください。mod + shirt + R によってi3 configファイルを更新します。この設定ファイルでは、j4-make-configのgreenish themeを使用しています。
- このi3 configファイルでは、dmenu_runの変わりにrofiを使用しています。
  rofiの設定ファイルについては、[dmenu-rofi_config](https://www.github.com/naoya0117/dmenu-rofi_config.git) を参照してください。
- このi3 configファイルでは、i3 statusの代わりにi3blocksを使用しています。[i3blocks-contrib](https://github.com/vivien/i3blocks-contrib) を参考にi3 blocksを設定するか、i3statusをインストールし、 ~/.config/i3/config.base のbarブロック中のi3blocksをi3statusに書き換えてください" ## Links
- Repository: [https://github.com/naoya0117/qemu-scripts](https://github.com/naoya0117/qemu-scripts)
- Github: [https://github.com/naoya0117](https://github.com/naoya0117)
- Blog: [https://naoya0117.com](https://naoya0117.com)
