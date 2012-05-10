reuse-ssh-agent
===============

This is my take on the idea described by
[elertric monk](http://www.electricmonk.nl/log/2012/04/24/re-use-existing-ssh-agent-cygwin-et-al/):

Use an existing ssh-agent when there is one or start a new one.

### Setup:
* Get the file
* Change “`&lt;user name&gt;`” to your user name.
* `mkdir ~/.ssh/agent`
* `chmod 700 ~/.ssh/agent`
* Just keep the file and source it when you feel like it
* Or insert it into your `.tchrc`
* Then just `ssh-add` your keys once per boot.
