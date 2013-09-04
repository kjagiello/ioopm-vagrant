ioopm-vagrant
=============

Vagrant setup for the IOOPM course at Uppsala University.

Contains
=======

* gcc 4.4.3
* emacs 23.1.1
* pdflatex 
* gdb 7.1
* valgrind 3.6.0
* git 1.7.0.4
* pdflatex 3.1415926-1.40.10

Usage
=======

1. Install Vagrant: http://www.vagrantup.com/.
2. `cd /path/to/repository/vagrant/`
3. `vagrant up`
4. SSH in to the Vagrant box using your favorite SSH-client (port: 22, user: vagrant, password: vagrant).

Notes
=======

* Use `/home/vagrant/ioopm/` as your home directory. Files in that folder will be saved in `/path/to/repository/home` on the host system, which means that they will persist when you destroy the vagrant box.
* `lint` is missing.
