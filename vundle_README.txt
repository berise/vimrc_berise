=== vim plugin. Vundle ===
1. see vundle for windows installation 
 https://github.com/VundleVim/Vundle.vim/wiki/Vundle-for-Windows

2.  run clone_vundle.bat
run accompanied clone_vundle.bat
 - git must be installed
 - curl might be installed 

----------- clone_vundle.bat ---------------
cd %USERPROFILE%
git clone https://github.com/gmarik/Vundle.vim.git %USERPROFILE%/.vim/bundle/Vundle.vim
--------------------------------------------

3. config vim
 Include _vimrc_berise to _vimrc

add following text to your .vimrc (see _gvimrc)
so YOUR_PATH/_vimrc_berise


4. open vim and install plugins
open ex-mode and press i

-------------
:PluginList
i
-------------

5. Better life with vim
 - if you want make your life more easier then add following text to your favorite tool

 - total commander F4 Edit command
   Edit & View
    gvim.exe --servername berise --remote-tab-silent 
