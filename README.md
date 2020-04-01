## Installing New Package
Add a new submodule and then add to .vimrc

    $ git submodule add https://github.com/<package repo>.git bundle/<package name>

### Black

To get Black to work, must have vim 7+ with Python3 support. 

Install Python3 using Homebrew's default version. Install vim with Homebrew

    $ brew install python vim

Add aliases in your bash profile to use the Homebrew installed version

    $ alias python=/usr/local/bin/python3
    $ alias pip=/usr/local/bin/pip3

Make sure you use the Homebrew vim not Mac vim

    $ brew link vim

