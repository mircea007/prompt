# My Bash Prompt
My custom bash prompt
## Install
You can get the prompt by downloading the script (or the repo) and source-ing it from your `.bashrc`.
## Screenshots
![Screenshot](http://github.com/007-Hacked/prompt/screenshot.png "screenshot")
## Configuration
You can configure the prompt by editing the `prompt_main()` function in the script.
To exclude something comment the coresponding line (add a `#` at the begining of the line).
To put something back uncomment it.

Say, for example, if I wanted to exclude the git component i would comment the line
```
  prompt_git
```
So it would then become
```
  #prompt_git
```
## License
This script is licensed under the **GNU General Public License v3.0**
