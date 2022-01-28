# Contributing

Please note we have a [code of conduct](CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.

## Ways to Contribute

There are a number of ways you can contribute to the project. The major two are:
- Submitting a GitHub issue. This could involve:
    - Logging a bug or undesirable behaviour
    - Recording area of possible improvement
    - Requesting a change or addition of a new feature
- Contributing code/data. Our work is never done, if you have an idea how you could make Londinium better or if you think you 
could generalise it:
    - You can outline the new feature or data in a GitHub issue and send us an email on 
    [citymodelling@arup.com](mailto:citymodelling@arup.com) to let us know you're willing to work on it. We may invite 
    you for a brief rubber-ducking session to go through your idea in more detail. The aim is to mature your idea with 
    one (or more) Londinium developers and to flag any possible blocks or implementation issues to be aware of.
    - Please follow advice below on Contributing Code, working in a branch and the Pull Request process.
    - You may continue to, and are encouraged to, keep in touch and reach out to us throughout your development work.

See this helpful site on [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/) for more ideas
 on how you could contribute. Get in touch with us via email [citymodelling@arup.com](mailto:citymodelling@arup.com).

## Submitting Issues

If you have an idea for an enhancement, a change or addition of new feature or behaviour for Londinium, or a record of a
bug you can communicate this to us in detail through a written account as a GitHub issue on Londinium's
[issues page](https://github.com/arup-group/londinium/issues).
 
A good issue will outline the problem in a full written format. It is helpful to include screenshots. It is also 
helpful to include why you think a new feature would be useful, what problem is it solving and whether there is a 
real-world cases study that would benefit from this improvement.

In case of bugs, please provide the full error message, the OS and information about the environment in which you were
using Londinium. It is also helpful to include a small (if possible) set of data and/or code with which the problem can
be recreated---at the very least, a thorough description of the input data should be included.

See this page on [Creating an issue](https://docs.github.com/en/github/managing-your-work-on-github/creating-an-issue)
on GitHub to learn how to submit an issue.

## Contributing Code - Pull Request Process

If the contribution you want to make includes any code - Python is our main language of choice.

1. All new work is done in a branch taken from the `main` branch, details can be found here:
[feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
2. Ensure your work is covered by unit tests to a decent level of coverage
3. Provide [docstrings](https://www.python.org/dev/peps/pep-0257/) for new Python methods 
4. Perform linting locally by running something like [flake8](https://pypi.org/project/flake8/)
5. Record any dependencies in a `requirements.txt` if applicable
6. Add section in the `README.md` which explains the purpose, and demonstrates usage of your new data/feature
9. Submit your Pull Request (see
[GitHub Docs on Creating a Pull Request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)),
describing the feature, linking to any relevant GitHub issues and requesting review from at least two developers.
(Please take a look at latest commits to find out which developers you should request review from).
10. You may merge your Pull Request once you have the sign-off of two other developers, or if you do not have
permission to do that, please request one of the reviewers to merge it for you.

## Attribution

The Contribution Guide was adapted from [PurpleBooth's Template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).
