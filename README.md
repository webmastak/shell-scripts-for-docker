# Shell scripts for Docker

Shell scripts utilit for Docker

![scrinshot 1](https://github.com/webmastak/shell-scripts-for-docker/blob/master/1.png)
![scrinshot 2](https://github.com/webmastak/shell-scripts-for-docker/blob/master/2.png)
![scrinshot 3](https://github.com/webmastak/shell-scripts-for-docker/blob/master/3.png)
![scrinshot 4](https://github.com/webmastak/shell-scripts-for-docker/blob/master/4.png)


## Dependencies

  * Have dependence `zenity`
  * For Gnome [quicklaunch](https://extensions.gnome.org/extension/37/quicklaunch)


## Install

In the **docker-utilit** script, in variable **TERMINAL** replace **gnome-terminal** the one you set by default.
 
And if you do not have **zsh** then in variables **SHELL** and **TERMINAL** replace **zsh** with **bash**.

In the launch shortcut file `docker-utilit.desktop` replace `Icon=docker-symbolic` and `Name[en]=Docker Utilit` with your own.

* `git clone git: //github.com/webmastak/shell-scripts-for-docker`
* `cd shell-scripts-for-docker`
* `cp ~/shell-scripts-for-docker/local/bin/docker-utilit ~/.local/bin/docker-utilit`
* For Gnome `cp ~/shell-scripts-for-docker/local/share/gnome-shell/quicklaunch/docker-utilit.desktop ~/.local/share/gnome-shell/quicklaunch/docker-utilit.desktop`
* For Gnome `Alt+F2 restart shell`
* `enjoy`


## Usage

Usage: `docker-utilit [options]`

Options:
*	`-h,  --help`  shows this help
*	`-r,  --run`   run container
*	`-rc, --rmc`   delete container
*	`-ri, --rmi`   delete image
*	`-p,  --pull`  pull image


## Contributing

* Fork it (<https://github.com/webmastak/shell-scripts-for-docker/fork>)
* Create your feature branch (`git checkout -b my-new-feature`)
* Commit your changes (`git commit -am 'Add some feature'`)
* Push to the branch (`git push origin my-new-feature`)
* Create a new Pull Request


## Contributors

- [webmastak](https://github.com/webmastak) - creator and maintainer

