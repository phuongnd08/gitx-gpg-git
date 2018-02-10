Introduction
============
This is a wrapper to be used with gitx/gitx so that it will sign all
commits

How to use
==========

Download `gitx-gpg-git` and put it somewhere
Add executable permission:
chmod u+x gitx-gpg-git

Then open gitx > Preferences and set Git Executable to gitx-gpg-git

Alternative
===========
I tried [fork!https://git-fork.com/] (and append `no-tty` to `~/.gnupg/gpg.conf`) and it works
without a need for a wrapper.
fork seem to be equally nice compare to gitx (you use `Cmd+Shift+S`
instead of `Cmd+S`)
