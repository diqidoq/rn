# rn
rn - a simple recursive shell file rename and text replace command.

## How to install
Simply clone the Github repository (or download it) and move or symlink the executable files inside bin/ to your command line tools folder. Common is the username/bin or /usr/local/bin folder. Or create one if you don't have one. Make sure this bin folder is added to your PATH and the command executables are set as executables with ```chmod u+x```. If you are new to this read about executable scripts and how to access them on your machine. Seach engines are full of tutorials on this. Using sym links has the advantage of using updated versions automatically on each git pull or new clone.

### Example installation 
If your executables folder would be under yourusername/bin and your default shell is bash, then the install commands what look like this:

```
cd userfolder
git clone git@github.com:diqidoq/rn.git
ln -s ~/rn/bin/* ~/bin/
chmod u+x ~/bin/*
source ~/.bashrc
```  
