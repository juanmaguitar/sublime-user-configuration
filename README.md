## Sublime Configuration
This is my Sublime Text 2 user directory. 

### How to install it

1. Clone the repository into the `Packages\User` directory in the path
    + Windows: `C:\Users\<USER_NAME>\AppData\Roaming\Sublime Text 2\Packages` 
    + Mac: `~/Library/Application Support/Sublime Text 2/Packages/User`

            cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
            rm -rf User
            git clone https://github.com/juanmaguitar/sublime-user-configuration.git User

2. Install Package Control

        cd ~/Library/Application\ Support/Sublime\ Text\ 2/Installed\ Packages/
        curl "https://sublime.wbond.net/Package%20Control.sublime-package" -o "Package Control.sublime-package"

3. run `Package Control: Upgrade/Overwrite All Packages`  from the command pallete (`Ctrl+Shift+P`). This will install all the packages.
