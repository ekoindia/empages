# Eko Docs & Help Files

This repository hosts independent documents and pages for Eko, such as, help files, FAQ sections, public policy documents, etc.

## Built with Jekyll Now

**Jekyll** is a static site generator that's perfect for GitHub hosted blogs ([Jekyll Repository](https://github.com/jekyll/jekyll))

**Jekyll Now** makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup ([Jekyll Now Repository](https://github.com/barryclark/jekyll-now)).


## Local Development

1. Install Ruby
   1. On Linux: `sudo apt-get install ruby-full`
   2. On Windows: Download RubyInstaller from [rubyinstaller.org](https://rubyinstaller.org/)
   3. On MacOS: `brew install ruby` (requires [Homebrew](https://brew.sh/)) and then add `export PATH="/usr/local/opt/ruby/bin:$PATH"` to your `.bash_profile` or `.zshrc` file.
2. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
3. **Start the application locally** with the following command: `jekyll serve`
4. **View your website at:** http://127.0.0.1:4000/empages
5. Commit any changes and push everything to the develop branch of this GitHub user repository. After the changes are accepted and merged into master, GitHub Pages will then rebuild and serve your website.

