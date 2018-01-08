# .mac
Macセットアップ手順
1. Homebrew のインストール
``` shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
2. Homebrew cask のインストール
```
brew tap caskroom/cask
```
3. Homebrew の更新
```
brew update
```
4. Homebrew の検証
```
brew doctor
```
5. その他 のインストール
```
brew cask install karabiner-elements
brew cask install appcleaner
brew cask install the-unarchiver
brew cask install clipy
brew cask install google-chrome
brew cask install visual-studio-code
brew cask install google-japanese-ime
brew cask install microsoft-office
brew cask install vlc
brew cask install iterm2
brew cask install maczip4win
brew cask install docker
brew cask install kitematic
brew cask install sql-operations-studio
brew cask install github
brew install node
# brew cask install kindle
# brew cask install dmmbookviewer
# brew cask install firealpaca
# brew cask install bettertouchtool
# brew cask install alfred
```

6. mas のインストール
```
brew install mas
```

7. MacStore のインストール
```
mas install 539883307       # LINE
mas install 557168941       # Tweetbot
```

7. 後始末
```
brew cask cleanup
brew cleanup
```
