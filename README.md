Linssen's dotfiles
=============================

Install
-----------------------------

Run this:

    # Clone the repo into the correct directory
    git clone https://github.com/linssen/dotfiles.git ~/.dotfiles
    # Change to that directory
    cd ~/.dotfiles
    # Run the bootstrap script to copy things into the right places
    # IMPORTANT: you should quit Sublime before linking the packages
    script/bootstrap
    # Install all the dependencies
    git submodule init && git submodule update

Thanks
-----------------------------

[Zach Holman](https://github.com/holman) for most of the bootstrap file and
for drilling in [about dotfiles][].

[about dotfiles]: http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)