# Terminal

#Mac

#### Hidden File
```
defaults write com.apple.Finder AppleShowAllFiles true
killall Finder

defaults write com.apple.Finder AppleShowAllFiles false
killall Finder
```

#### ADB Driver
```
brew install android-platform-tools

adb devices
```

#### Mysql
```
/Applications/xampp/xamppfiles/bin/mysql -u root -p
```

#### Finder

[Source](https://macpaw.com/how-to/access-bin-folder-mac)

#### PHP
```
brew unlink php@7.4
brew link php@8.1 --force --overwrite
```

<pre>
<img src="https://github.com/gzeinnumer/Terminal/blob/master/preview/preview1.png" width="300">
</pre>

---

```
Copyright 2022 M. Fadli Zein
```