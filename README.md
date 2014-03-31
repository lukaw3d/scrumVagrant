Modified vagrant-yeoman
==============

Base from https://github.com/arafalov/vagrant-yeoman.

Basic steps: 

* Install `Vagrant`, `VirtualBox`
* Clone/copy `scrumble` repository into `projects` folder

  * (or adapt Vagrantfile: config.vm.synced_folder)

* vagrant up
* vagrant ssh

```bash
  cd ~/projects/scrumble/scrumbleweb
  sudo npm install
  bower install
  grunt serve
```

