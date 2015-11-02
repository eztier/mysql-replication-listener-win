# mysql-replication-listener-win
MySQL binlog listener fork in C++ patched for Windows

[Reference](https://launchpad.net/mysql-replication-listener)
[Forked Repo](https://github.com/bullsoft/mysql-replication-listener)

###Getting the original source code
```bash
$ bzr branch lp:mysql-replication-listener
```

###Dependencies
* [pthread-win32](https://github.com/GerHobbelt/pthread-win32.git)
* [asio](https://github.com/chriskohlhoff/asio)
* [boost](http://sourceforge.net/projects/boost/files/boost-binaries/)
* [unistd.h](http://stackoverflow.com/questions/341817/is-there-a-replacement-for-unistd-h-for-windows-visual-c)
* [getopt.h](http://www.mit.edu/afs.new/sipb/project/merakidev/include/bits/getopt.h)