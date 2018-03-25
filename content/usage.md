+++
title = "Basic Usage"
+++

Run the `help` subcommand to get the full list of available commands.

    exercism help

## Configuration

You need to tell the tool who you are:

    exercism configure --key=YOUR\_API\_KEY

Visit [exercism.io/account/key](http://exercism.io/account/key) to get your api
key.

You can override other configuration options. Run `exercism configure` without
any arguments to see the available options.

## Downloading exercises

You download exercises for a track with the `fetch` command. Replace
`$TRACK_ID` with the ID of the track you are working on, e.g. `python` or
`haskell`.

    $ exercism fetch $TRACK_ID

You can download a specific exercise by specifying the exercise slug, for
example `hello-world` or `food-chain`.

    $ exercism fetch $TRACK_ID $EXERCISE_SLUG

The full list of supported languages can be found at
[exercism.io/languages](http://exercism.io/languages).

## Submitting exercises

To submit an exercise, use the submit command. If you solution has multiple
files then submit them in a single command.

    exercism submit path/to/file1.ext path/to/file2.ext

You only need to submit the code you wrote to solve the exercise, not the test
suite that you were given.
