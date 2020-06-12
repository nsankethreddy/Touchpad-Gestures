Touchpad Gestures for Linux
============================
A better trackpad experience in Linux using fusuma. Supports multi-finger touch gestures, pinch in and out just like windows track pad.  
  
Credits:  [Kohei Yamada](https://github.com/iberianpig).  


## Steps

- Check if user is a part of the current input group

```sudo gpasswd -a $USER input  ```

- Log in and out after this step.

- Install some necessary tools:

```sudo apt-get install libinput-tools```
```sudo apt-get install xdotool```


- Ruby is required for this to work:

```sudo apt install ruby```

- Then install fusuma

```sudo gem install fusuma  ```


### The config file, by default is located in /var/lib/gems/2.7.0/gems/fusuma-1.10.1/lib/fusuma/config.yml

A config file that mimics Windows-Trackpad features is given as an example in this repository as the ```config.yml``` file. (This file was written for UBUNTU 20.04)

- After changing the config file as required, the program can be started by using ```sudo fusuma```.

To enable it as an startup aplication in ubuntu, go to startup applications and then add a new startup program.
Under the command textbox add just put ```fusuma```.

--------------------------------------------------------------------------------------------------------------
  

For more information refer to: https://github.com/iberianpig/fusuma/

















