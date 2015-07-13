#WHAT?
Vagrant box with Node.js

#How
1. Install [vagrant](http://vagrantup.com/)
2. Download and Install [VirtualBox](http://www.virtualbox.org/)
3. Clone this repo
4. Create a share folder at `~/Projects/MOOC JS`, if you don't need, you can comment the line (`config.vm.synced_folder "~/Projects/MOOC JS", "/MOOC"`) in **Vagrantfile**
5. You need to change the default shell (if you want), you could change in the file `/etc/passwd`. Change your shell with `/bin/zsh`.
  1. You could try with `sudo -u vagrant chsh -s /usr/bin/zsh`
6. Go to the repository and launch the box

> cd [repository]

> vagrant up

> vagrant ssh
