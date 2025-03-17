# Eko Docs & Help Files

This repository hosts independent documents and pages for Eko, such as, help files, FAQ sections, public policy documents, etc.

## Built with Jekyll Now

**Jekyll** is a static site generator that's perfect for GitHub hosted blogs ([Jekyll Repository](https://github.com/jekyll/jekyll))

**Jekyll Now** makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup ([Jekyll Now Repository](https://github.com/barryclark/jekyll-now)).

## Quick Start

### Step 1) Customize and view this site

Change site name, description, avatar and many other options by editing the _config.yml file. You can easily turn on Google Analytics tracking, Disqus commenting and social icons here too.

Making a change to _config.yml (or any file in your repository) will force GitHub Pages to rebuild the site with jekyll. The rebuilt site will be viewable a few seconds later at <https://ekoindia.github.io/empages> - if not, give it ten minutes as GitHub suggests and it'll appear soon

> There are 3 different ways that you can make changes to the blog's files:

> 1. Edit files here within this repository in the browser at GitHub.com (shown below).
> 2. Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io). It's optimized for use with Jekyll making markdown editing, writing drafts, and uploading images really easy.
> 3. Clone down this repository and make updates locally, then push them to GitHub.

![_config.yml](/images/config.png "_config.yml")

### Step 2) Publish the first blog post

Edit `/_posts/2014-3-3-Hello-World.md` to publish the first blog post. This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

![First Post](/images/first-post.png "First Post")

> You can add additional posts in the browser on GitHub.com too! Just hit the + icon in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: year-month-day-title.md

## Local Development

1. Install Ruby
   1. On Linux: `sudo apt-get install ruby-full`
   2. On Windows: Download RubyInstaller from [rubyinstaller.org](https://rubyinstaller.org/)
   3. On MacOS: `brew install ruby` (requires [Homebrew](https://brew.sh/)) and then add `export PATH="/usr/local/opt/ruby/bin:$PATH"` to your `.bash_profile` or `.zshrc` file.
2. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
3. Start the application locally with the following command: `jekyll serve`
4. View your website at: http://127.0.0.1:4000/empages
5. Commit any changes and push everything to the develop branch of this GitHub user repository. After the changes are accepted and merged into master, GitHub Pages will then rebuild and serve your website.

