# ubuntu 安裝 zsh + oh my zsh 筆記

1.[安裝 zsh](http://josephj.com/entry.php?id=314)  

```
1.從 Repository 安裝
#sudo apt-get install zsh
2.更換 Shell
#chsh -s /bin/zsh
```
2.[安裝 oh my zsh](https://github.com/robbyrussell/oh-my-zsh)

```
#curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
```
3.[變更 theme](https://github.com/robbyrussell/oh-my-zsh/wiki/themes)

```
變更 theme 為 agnoster
#sudo vi ~/.zshrc
找到 ZSH_THEME 設定為 agnoster
```
4.例外狀況，如果有出現 ？ 或沒有正常顯示，至 [https://gist.github.com/agnoster/3712874](https://gist.github.com/agnoster/3712874) 更新 agnoster 的 theme 內容

```
#sudo vi ~/.oh-my-zsh/themes/agnoster.zsh-theme
接著將內容替換掉，done
```


Symbol              |powerline      |vim-powerline     |
--------------------|---------------|------------------|
separator.left      |'' (\ue0b0)  |'⮀' (\u2b80)     |
separator.right     |'' (\ue0b2)  |'⮂' (\u2b82)     |
subseparator.left   |'' (\ue0b1)  |'⮁' (\u2b81)     |
subseparator.right  |'' (\ue0b3)  |'⮃' (\u2b83)     |
branch symbol       |'' (\ue0a0)  |'⭠' (\u2b60)     |
readonly symbol     |'' (\ue0a2)  |'⭤' (\u2b64)     |
linecolumn symbol   |'' (\ue0a1)  |'⭡' (\u2b81)     |
