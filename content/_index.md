[Exercism](http://exercism.io) is an open source project that aims to give people a way to get from that awkward "Hello, World!" in a new programming language to being fluent and at ease with the basic constructs, idioms and standard library of the language.

The project supports over 40 programming languages, each of which contains numerous small exercises.
You work on the exercises locally, in your own development environment and favorite text editor.
Then you submit your solution to the site, where other participants can discuss the code and suggest improvements, and you iterate until you're happy with the solution and what you've learned.

The Exercism Command-Line Client (CLI) provides the mechanism for fetching and submitting exercises.

## Installing

The CLI is written in Go, but you do not need to install Go (or any other
language) in order to use it.

The recommended installation method is to download the [latest
release](https://github.com/exercism/cli/releases/latest) place the binary in
your `PATH`.

It is also available via Homebrew (`brew install exercism`).

## Upgrading

To upgrade you can either download a new binary from the [latest
release](https://github.com/exercism/cli/releases/latest) page, or
you can use the `upgrade` subcommand:

    exercism upgrade

## Uninstalling

To uninstall the program completely, you need to delete two things:

* the configuration file
* the binary itself

Run `exercism configure` to get the location of the configuration file.  The
binary is wherever you originally put it. On Linux or Mac you can use the
`which` command to figure out where that is:

    which exercism

## Shell Completion Scripts

We have [shell completion scripts available](/scripts) for Bash and Zsh.
