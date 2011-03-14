MOZTMP
======

Firefox is not the fastest browser on earth. But some issues can be resolved by moving its files to a RAM-disk. This ensures that all the cache and stuff can be directly served from RAM and firefox does not need to access the harddisks.


Things to have in mind before using it
--------------------------------------

- Firefox' directories can be quite huge. Only use this script if you can spare 100-200MB of RAM.
- This script creates a backup copy. But if your computer is not able to make a normal shutdown (e.g. some crash), all things done in the session is lost (it's only in RAM - remember?).
- This script is written for and tested only on Gentoo Linux with OpenRC. It should work on any other OpenRC-system though (are there any others?).

Install
-------

Installation is easy: Download the files and put them in /etc/init.d/ and /etc/conf.d/ respectively. Do not forget to change the conf.d/moztmp file to fit your needs.
