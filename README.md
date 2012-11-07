Linssen's dotfiles
=============================

Install
-----------------------------

Run this:

    git clone https://github.com/linssen/dotfiles.git ~/.dotfiles
    cd ~/.dotfiles
    rake install
    git submodule init && git submodule update

That will symlink the appropriate files in `.dotfiles` to your home directory as well as installing all the various required repos for configurations and bundles.

Thanks
-----------------------------

[Zach Holman](https://github.com/holman) for the Rakefile and for drilling in [about dotfiles](http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/).
