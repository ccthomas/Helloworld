# Setup guides

## Mac
### Show all files
From Finder
- CMD + SHIFT + .

From Temrinal 
1. `sudo nano ~/.bash_profile`
2. 
   ```
   alias showFiles='defaults write com.apple.finder AppleShowAllFiles YES; killall Finder /System/Library/CoreServices/Finder.app'
   alias hideFiles='defaults write com.apple.finder AppleShowAllFiles NO; killall Finder /System/Library/CoreServices/Finder.app'
   ```
3. CTRL + O
4. CTRL + X
5. `source ~/.bash_profile`

## Oh My Zsh
https://ohmyz.sh
1. https://github.com/robbyrussell/oh-my-zsh/
