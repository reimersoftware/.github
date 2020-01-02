[mail]: mailto:contact@reimer.software
[cla]: https://gist.github.com/heinrichreimer/f0c67749644175724f1c47d4fe53ba7f
[cla-sign]: https://cla-assistant.io/reimersoftware/

# Contributing

*<sup>👍🎉</sup> First off, thanks for taking the time to contribute! <sup>🎉👍</sup>*

We welcome all contributions and we'd like to help you send your first contribution to us.
For that, this is what we recommend:

1. [Look](#look) into the existing issues (or create a new one).
1. [Discuss](#discuss) the possible solution.
1. [Code](#code)!
1. [Test](#test).
1. [Send](#send) a PR.

## Code of Conduct

Help us keep open source projects open and inclusive. Please read and follow our [Code of Conduct](/CODE_OF_CONDUCT.md).

## Look

Take a look at the *existing issues* and linked pull requests: 
perhaps there's one already related to the feature you want to contribute.

Otherwise, *open a new issue*, describing the problem and your suggestion for the solution.  
Be sure to include a *title and clear description*, 
as much relevant information as possible, 
and a way to _reproduce the issue_, if you can.
If possible, use the relevant issue templates to create the issue.

If the bug is a security vulnerability, do **not** open a GitHub issue, and instead [contact us][mail]!

Changes that are purely cosmetic and don't add much to the stability, 
functionality, or testability, will generally not be accepted.


## Discuss

Usually, opening an issue is enough to get a feedback.
If you prefer, send us an [email][mail].

## Code

Once you feel comfortable that the issue has been discussed 
and a general approach is agreed upon,it's time to start coding.

First, *fork* this repository into your own namespace, and then *clone* the forked repository.  
Verify that everything builds, by executing the build command (usually `gradle build`).
It should complete successfully without errors or test failures.

If everything worked, then do your changes as desired. 
Once you are done, run a local build to make sure nothing is broken. 
Ideally, your code should include tests for the bugs you are fixing or for features you are adding. 
If you don't know how to test, it's OK to open the PR with a title saying "WIP" (for Work in Progress).
We can guide you on how to write tests.

## Test

Once your code is considered ready, run all unit tests, including your own tests.
If any test fails, [fix](#discuss) the test issues and [retry](#code).

## Send

Once your code is ready for a review or if you want feedback, 
_open a pull request_ with the patch. 
Ensure the PR description clearly describes the problem and solution. 
Include the relevant issue number if applicable.

If your branch is not ready to be merged for some reason, add "WIP" to the title. 
It is expected that all PRs are passing the continuous integration test.

During the process, we will take a look at your contributions and make comments, 
ask questions and suggest different approaches. 
Even though the reviewer strives to be polite, don't take a possible criticism personally.
After all, we'd really love to get your contribution!

Because of legal reasons, all contributors must [sign][cla-sign] our [Contributor License Agreement][cla].
It's a quick, automated process, we promise! Watch for messages from our CLA bot.

## Thanks!

Open source is a volunteer effort, we strive to support.
We encourage you to pitch in and contribute!
