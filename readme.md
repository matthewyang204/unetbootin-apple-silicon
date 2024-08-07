# Unetbootin For Apple Silicon
This is where I host my Apple Silicon builds of Unetbootin. They also offer higher resolution than the original Intel builds. 

# Caveats
Although these are native builds, the executable within the .app bundle needs to be run with sudo and started from the terminal. A good way to do this is to link the executable to the `/usr/local/bin/`:
```
ln -s /Applications/unetbootin/Contents/MacOS/unetbootin /usr/local/bin/
```
Afterwards, run `sudo unetbootin` from a new terminal to launch the app.