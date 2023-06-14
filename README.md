# Script for Git Bash
If you want to remove `MINGW64` word on the Git Bash, you can use this script to replace the original script.
Follow the steps belong using Git Bash.

## Start

### Open Git Bash
`Run as Administrator`


### Clone the repository 
~~~
git clone https://github.com/MMuslimAbdulJ/Gitbash-Remove-MINGW64.git
~~~


### Backup the original script
~~~
mv /c/Program\ Files/Git/etc/profile.d/git-prompt.sh /c/Program\ Files/Git/etc/profile.d/git-prompt.sh.bak
~~~


### Copy the script (final step)
~~~
cp Gitbash-Remove-MINGW64/git-prompt.sh /c/Program\ Files/Git/etc/profile.d/
~~~


## If you miss to see the `MINGW64` (Back to default script)
~~~
rm -rf /c/Program\ Files/Git/etc/profile.d/git-prompt.sh
mv /c/Program\ Files/Git/etc/profile.d/git-prompt.sh.bak /c/Program\ Files/Git/etc/profile.d/git-prompt.sh
~~~
