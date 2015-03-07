## Sublime Configuration
This is my Sublime Text 2 user directory. 

### How to install it

1. Clone the repository into the `Packages\User` directory in the path
    + Mac: `~/Library/Application Support/Sublime Text 2/Packages/User`
    + Windows: `C:\Users\<USER_NAME>\AppData\Roaming\Sublime Text 2\Packages` 

        cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
        rm -rf User
        git clone https://pahko@github.com/pahko/sublime-text-2-personal-config.git User

2. Install Package Control

        cd ~/Library/Application\ Support/Sublime\ Text\ 2/Installed\ Packages/
        curl "https://sublime.wbond.net/Package%20Control.sublime-package" -o "Package Control.sublime-package"

3. run `Package Control: Upgrade/Overwrite All Packages`  from the command pallete (`Ctrl+Shift+P`). This will install all the packages.
