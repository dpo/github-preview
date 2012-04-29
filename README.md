# github-preview

A simple script to generate a HTML preview of a markdown file that is more or
less representative of the way Github will render, e.g., your README.md.

# Installation

    gem install redcarpet
    [[ ! -d ~/bin ]] && mkdir ~/bin
    cp github-preview ~/bin/
    chmod +x ~/bin/github-preview
    [[ ! -d ~/bin/rc ]] && mkdir ~/bin/rc
    cp github-head.html github-foot.html ~/bin/rc

If you are not under OSX, you may need to edit `github-preview` to replace the
`open` command with an appropriate command that will open an `html` file in
your browser.

To preview the present `README.md` file, change to the directory containing the
clone of this git repository and issue the command

    ~/bin/github-preview README.md

# Credits

Clearly, I'm no web developer. I pieced this together from a few other sources.
Most of the credit should go to them. However, it is with this script that I
get the best results.

# Licensing

[![LGPL V3](http://www.gnu.org/graphics/lgplv3-88x31.png)](http://www.gnu.org/licenses/lgpl.html)
