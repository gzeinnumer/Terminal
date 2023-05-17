# Terminal

#Mac

#

#### Ipconfig in mac

```
ipconfig getifaddr en0
```

#

#### Enviroment

```
alias mysql=/Applications/XAMPP/bin/mysql
```

```
alias flutter=/Users/mfadlizein/Documents/GitHub/sdk/flutter/bin/flutter
```

```
mysql -v
```
https://zeroesandones.medium.com/how-to-install-python-on-macos-700babeb51f6
```
alias python=/Users/mfadlizein/.pyenv/versions/3.10.1/bin/python
```

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

#### Composer PHP

Composer detected issues in your platform: Your Composer dependencies require a PHP version ">= 8.0.2". You are running 7.4.27.

```
composer install --ignore-platform-reqs
```

#

#### Pods

```
pod init
```

```
pod install
```

#

#### PWD

```
mfadlizein@MacBook-Pro-Zein ~ % code .zprofile
mfadlizein@MacBook-Pro-Zein ~ % cd /Library/Java/JavaVirtualMachines
mfadlizein@MacBook-Pro-Zein JavaVirtualMachines % ls
temurin-17.jdk
mfadlizein@MacBook-Pro-Zein JavaVirtualMachines % cd temurin-17.jdk
mfadlizein@MacBook-Pro-Zein temurin-17.jdk % pwd
/Library/Java/JavaVirtualMachines/temurin-17.jdk
mfadlizein@MacBook-Pro-Zein temurin-17.jdk %
```

<img src="/preview/preview2.png" width="300">

#

#### EXPORT

```
mfadlizein@MacBook-Pro-Zein ~ % code .zprofile
```

<img src="/preview/preview3.png" width="300">


---

```
Copyright 2022 M. Fadli Zein
```
