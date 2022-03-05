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
```
mysql -u [user] -p [database_name] < [filename].sql
```

#### Finder

[Source](https://macpaw.com/how-to/access-bin-folder-mac)

#### PHP
```
brew unlink php@7.4
```
```
brew link php@8.1 --force --overwrite
```

#### PHP 7.2
```
brew tap shivammathur/php
brew install shivammathur/php/php@7.2
```

<pre>
<img src="https://github.com/gzeinnumer/Terminal/blob/master/preview/preview1.png" width="300">
</pre>

---

```
Copyright 2022 M. Fadli Zein
```