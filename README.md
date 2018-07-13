fatal: Unable to create 'D:/test/eep/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.

delete index.lock
重新add . 
commit -m 'XXX'
就可以了
