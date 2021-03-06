# Terminal

#Mac

#### Hidden File
```
defaults write com.apple.Finder AppleShowAllFiles true
```
```
killall Finder
```
```
defaults write com.apple.Finder AppleShowAllFiles false
```
```
killall Finder
```

#### ADB Driver
```
brew install android-platform-tools
```
```
adb devices
```

#### Mysql
```
/Applications/xampp/xamppfiles/bin/mysql -u root -p
```
```
mysql -u [user] -p [database_name] < [filename].sql
```
```
https://github.com/mydumper/mydumper
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
```
```
brew install shivammathur/php/php@7.2
```

<pre>
<img src="https://github.com/gzeinnumer/Terminal/blob/master/preview/preview1.png" width="300">
</pre>

hellotech.com/guide/for/how-to-change-where-screenshots-are-saved-on-mac

#
#### Putty On Mac

https://www.youtube.com/watch?v=EdngKcoTnF0&ab_channel=OpenGovHub

#
#### Ipconfig in mac
```
ipconfig getifaddr en0
```

#
#### Composer PHP

Composer detected issues in your platform: Your Composer dependencies require a PHP version ">= 8.0.2". You are running 7.4.27.
```
composer install --ignore-platform-reqs
```

---

```
Copyright 2022 M. Fadli Zein
```