# ppp

Forked version of ppp with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/ppp.git
* cd ppp
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/ppp.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
