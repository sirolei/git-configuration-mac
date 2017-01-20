# git-configuration-mac
git configuration on mac

# step one
Download the *git-completion.bash* and mv to main directory
```
cd ~
mv Download/git-completion.bash git-completion.bash
```
# step two
Download the *git-prompt.sh* and mv to main directory
```
cd ~
mv Download/git-prompt.sh git-prompt.sh
```
# step three
Download the *bash_profile_course*
```
cd ~
#if :there is a *.bash_profile* already, copy the contents of the *bash_profile_course* and paste to the the end of *.bash_profile*
#else : rename the bash_profile_course to *.bash_profile* and mv to main directory
cd ~
mv Download/bash_profile_course .bash_profile
```
# step four
```
#if you wanna use Sublime for the text editor :
alias subl="/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl"
#if use Sublime for core editor 
git config --global core.editor "'/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl' -n -w"
#config the push
git config --global push.default upstream
#config the conflict
git config --global merge.conflictstyle diff3
```
