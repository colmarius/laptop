## Laptop

Laptop is a script to set up my OS X laptop for web development. Forked from [thoughtbot/laptop](https://github.com/thoughtbot/laptop).

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages based on what is already installed on the machine.

## Requirements

* [OS X Mavericks (10.9)](https://itunes.apple.com/us/app/os-x-mavericks/id675248567)
* [OS X Yosemite (10.10)](https://www.apple.com/osx/)

## Install

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/colmarius/laptop/master/mac
less mac
sh mac 2>&1 | tee ~/laptop.log
```

## Debugging

Your last Laptop run will be saved to `~/laptop.log`. Read through it to see if
you can debug the issue yourself.

## What it sets up

* [Bundler] for managing Ruby libraries
* [Chruby] for managing versions of Ruby
* [Elastic Search] for implementing full-text search solution
* [Exuberant Ctags] for indexing files for vim tab completion
* [Foreman] for managing web processes
* [Heroku Toolbelt] for interacting with the Heroku API
* [Homebrew] for managing operating system libraries
* [Hub] for interacting with the GitHub API
* [ImageMagick] for cropping and resizing images
* [Mongo] for storing nosql data
* [Node.js] and [NPM], for running apps and installing JavaScript packages
* [Postgres] for storing relational data
* [Qt] for headless JavaScript testing via Capybara Webkit
* [Redis] for storing key-value data
* [Ruby Install] for installing Rubies
* [Ruby] stable for writing general-purpose code
* [Selecta] for quick navigation to projects
* [The Silver Searcher] for finding things in files
* [Tmux] for saving project state and switching between projects
* [Zsh] as your shell

[Bundler]: http://bundler.io/
[Chruby]: https://github.com/postmodern/chruby
[Elastic Search]: https://www.elastic.co/
[Exuberant Ctags]: http://ctags.sourceforge.net/
[Foreman]: https://github.com/ddollar/foreman
[Heroku Toolbelt]: https://toolbelt.heroku.com/
[Homebrew]: http://brew.sh/
[Hub]: https://github.com/github/hub
[ImageMagick]: http://www.imagemagick.org/
[Mongo]: https://www.mongodb.org/
[Node.js]: http://nodejs.org/
[NPM]: https://www.npmjs.org/
[Postgres]: http://www.postgresql.org/
[Qt]: http://qt-project.org/
[Redis]: http://redis.io/
[Ruby Install]: https://github.com/postmodern/ruby-install
[Ruby]: https://www.ruby-lang.org/en/
[Selecta]: https://github.com/garybernhardt/selecta
[The Silver Searcher]: https://github.com/ggreer/the_silver_searcher
[Tmux]: http://tmux.sourceforge.net/
[Zsh]: http://www.zsh.org/

It should take less than 15 minutes to install (depends on your machine).

## Contributing

Edit the `mac` file.
Document in the `README.md` file.
Follow shell style guidelines by using [ShellCheck] and [Syntastic].

```sh
brew install shellcheck
```

[ShellCheck]: http://www.shellcheck.net/about.html
[Syntastic]: https://github.com/scrooloose/syntastic

Thank you, [contributors]!

[contributors]: https://github.com/thoughtbot/laptop/graphs/contributors

## License

Laptop is © 2011-2015 thoughtbot, inc.
It is free software,
and may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: LICENSE
