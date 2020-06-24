# Contributing to the Kowainik repositories

## :wave: Greetings Traveler!

We are delighted you're reading this, and we appreciate the effort you are
taking to make our projects awesome! :sparkles:

## How to contribute

### :bug: Report bugs or feature request :bulb:

If you discover a bug or have any proposals on how to make this project better
don't hesitate to [create an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue)
in a free format.

> 📝 Please, include all relevant details and provide as much information as possible on the issue.
That would help us to speed up the resolving process.

### Create a PR

We love to receive pull requests from everyone! However, it is usually a good idea
to tell about your intention to work on something under the corresponding
issue, so everyone is aware that you are on it. If there is _no_ such issue — simply
__create a new one__!

> ☝ Pull requests without corresponding issues would require much more effort to understand
and review. It is always better to discuss the problem in the issue and make sure that nobody's
time is going to be wasted on implementing/reviewing irrelevant or unsuitable for the project parts.

To get started with the Pull Request implementation you should first
[fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo),
then clone the repo:

    git clone git@github.com:your-username/project-name.git

Make your changes and consider the following checklist to go through
before submitting your pull request.

### :white_check_mark: Check list

- [ ] New/fixed features work as expected (Bonus points for the new tests).
- [ ] There are no warnings or errors during compilation.
- [ ] `hlint .` output is: _No Hints_ (see [`hlint`][hlint] tool docs).
- [ ] The code is formatted with the [`stylish-haskell`][stylish-tool] tool
      using [stylish-haskell.yaml][stylish] file in the repository.
- [ ] The code style of the files you changed is preserved (for more specific
      details on our style guide check this document: [Kowainik Style Guide][style-guide]).
- [ ] Commit messages are in the proper format.
      Start the first line of the commit with the issue number in square parentheses.

    **_Example:_** `[#42] Upgrade upper bounds of 'base'`

After all above is done commit and push to your fork.
Now you are ready to [submit a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

----------
Thanks for spending your time on reading this contributing guide! :sparkling_heart:

[stylish]: .stylish-haskell.yaml
[stylish-tool]: http://hackage.haskell.org/package/stylish-haskell
[hlint]: http://hackage.haskell.org/package/hlint
[style-guide]: https://github.com/kowainik/org/blob/master/style-guide.md#haskell-style-guide
