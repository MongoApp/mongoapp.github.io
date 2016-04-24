---
layout: index
title: the easiest way to run MongoDB on the Mac
---

### What is this?

Mongo.app is status bar application that runs MongoDB. Application contains MongoDB binaries and command line tools.

### Installation

Unzip archive, copy Mongo.app to /Application folder and double-click.

### Command Line Tools/ Configure your `$PATH`:

Mongo.app includes standard command line tools. If you want to use them, you must configure the `$PATH` variable.

If you are using **bash** (default shell on OS X) or **zsh**, add the following line to `~/.bash_profile` or `~/.zshrc` file respectively:

```bash
export PATH=$PATH://Applications/MongoDB.app/Contents/Resources/Vendor/mongodb
```

If you're using the **fish** shell, add the following to your `config.fish` (normally located at `~/.config/fish/config.fish`):

```bash
set PATH /Applications/MongoDB.app/Contents/Resources/Vendor/mongodb $PATH
```

You can now check if the path is set up correctly by typing `which mongo`.


### Contribute & Support

If you have an issue requests, or you find a bug, you can easily report them on [GitHub Issues](https://github.com/mongoapp/mongoapp/issues).

If you want to fix bug or create new feature, just fork Mongo.app, make changes and create a pull request.
List of TODOs you can find at [GitHub](https://github.com/mongoapp/mongoapp/). Furthermore, you can create support documentation.

You can ask any question at [@TheMongoApp](https://twitter.com/TheMongoApp) on Twitter.

### License

The source code for Mongo.app is released under the [Creative Commons License](http://creativecommons.org/licenses/by-nc-sa/3.0/).

The app also includes MongoDB binaries that covered under the same license.
For more information please see the GitHub page.

### Credits

Mongo.app is created and maintained by [Pavel Kozlov](http://pkozlov.ru/).

Inspired by [Postgres.app](http://postgresapp.com/).
