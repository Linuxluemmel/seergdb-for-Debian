Would you like to use a nice looking GUI for gdb with Debian 12 ? 

If your answer is yes, use seergdb !
Of course, there are a few other frontends like ddd (that looks ugly ...) 
prior to install over dpkg  you have to do ...  
install all other deb files needed.

apt-get update

apt-get install gdb libqt6core6 libqt6charts6 libqt6printsupport6 

dpkg -i dpkg -i seergdb-2.4_amd64.deb 

Ready ...
