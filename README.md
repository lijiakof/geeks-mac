# Geeks Mac
How geeks use Mac

## Homeber 包管理器
* 安装
    * `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
* 如何使用
    * brew install git
    * brew list
    * brew upgrade
    * brew uninstall
* cakebrew
* bottles 源替换
    * echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.tuna.tsinghua.edu.cn/homebrew-bottles' >> ~/.bash_profile
    * source ~/.bash_profile

## 软件
* iTerm2
* zsh
    * oh-my-zsh
    * agnoster 字体
* archey
* cheatsheet
* keka
* itsycal
* aerial
* nomachine
* wpsoffice
* iina
* typora
* git
* htop
* tree

## 秘籍
Launchpad 图标大小：
defaults write com.apple.dock springboard-rows -int 7
defaults write com.apple.dock springboard-columns -int 11
defaults write com.apple.dock ResetLaunchPad -bool TRUE;killall Dock