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
    script/bootstrap
    # Install all the dependencies
    git submodule init && git submodule update

Thanks
-----------------------------

[Zach Holman](https://github.com/holman) for the Rakefile and for drilling in [about dotfiles](http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/).
