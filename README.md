scripts
=======
My scripts for everyday use.

Currently hosting:

* `gto` - it opens any local remote's GitHub repo in the default browser
* `gtr` - assuming your remote is called `origin` and is a fork, it compares the master repo with the current branch (also opens in the browser)

Both scripts require the `git` gem, so make sure to run `$ [sudo] gem install git` before using them.

Install
=======

There are several ways of using these scripts:

* Copy the desired script(s) to `/usr/local/bin` and make sure that your `$PATH` contains `/usr/local/bin`. If it does not, add this line to your shell configuration dotfile:
`export PATH=$PATH:/usr/local/bin` <br>
* Alternatively, you could create symbolic links for the script(s) in any of your desired locations. (but also make sure that the symlinks' root is included in `$PATH` and **don't** delete the original files)<br>
* **(!)** If you are not sure what the above means, please stop for a second, make yourself a comfortable and read up about [`$PATH` and executables](http://quickleft.com/blog/command-line-tutorials-path), [symbolic links](http://www.nixtutor.com/freebsd/understanding-symbolic-links/), or even peak through the [Bash Guide for Beginners](http://tldp.org/LDP/Bash-Beginners-Guide/html/index.html) before using any of these.

Contribute
=======
Yon can contribute to this repo with any scripts that I will find useful.
