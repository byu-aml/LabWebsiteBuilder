# BYU AML Lab Website

The website was built using GitHub pages, Jekyll and the very cool *Minimal Mistakes* theme (with minor tweaks) from [Michael Rose](http://twitter.com/mmistakes). Take a look at the [Minimal Mistakes website](http://mmistakes.github.io/minimal-mistakes) for detailed instructions about creating your own website using this theme.

## To create and add to this website please:
1. Clone the repository.
2. Install Ruby on your system if you haven't already (see details [here](https://www.ruby-lang.org/en/documentation/installation/)) or check by running `ruby -v`
3. Go inside this repo `cd LabWebsiteBuilder` and initialize the website submodule `git submodule init`.
4. Make your changes to the source code (mostly in the `*.md` files) and run `bash deploy_to_pages.sh` to build the site and transfer the files to the github pages site.  Note that we cannot just upload this repository automatically since github pages doesn't support `jekyll-scholar` our automatic citation builder.

