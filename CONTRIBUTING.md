# This organization has been deprecated.
Please update your references to the appropriate repository in the [Conforma](https://github.com/conforma) organization.

<strike>
# Contributing

Enterprise Contract welcomes contributions in many forms. [Pull requests](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request) are specifically appreciated and the maintainers will make every effort to assist with any issues in the pull request discussion. Feel free to create a pull request even if you are new to the process. If you need more information, see [this article](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) about how creating a pull request.

## Code of Conduct

Our [company values](https://www.redhat.com/en/about/brand/standards/culture) guide us in our day-to-day interactions and decision-making. Our open source projects are no exception and they will define the standards for how to engage with the project through a [code of conduct](/CODE_OF_CONDUCT.md).

Please, make sure you read both of them before contributing, so you can help us to maintain a healthy community.

## Requesting Support

Before you ask a question, it is best to search for existing issues that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue. It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

* Open an issue.
* Provide as much context as you can about what you’re running into.
* Provide project and platform versions (golang, operator-sdk, etc), depending on what seems relevant.

The community will then take care of the issue as soon as possible.

## Reporting Issues

We use GitHub issues to track bugs and errors. If you run into an issue with the project:

* Open an Issue.
* Explain the behavior you would expect and the actual behavior.
* Please provide as much context as possible and describe the reproduction steps that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.

Once it’s filed:

* The project team will label the issue accordingly.
* A team member will try to reproduce the issue with your provided steps.
  * If there are no reproduction steps or no obvious way to reproduce the issue, the team will ask you for those steps and mark the issue as `needs-reproducer`. Bugs with this tag will not be addressed until they are reproduced.
* If the team is able to reproduce the issue, it will be marked `needs-fix` and left to be implemented by someone. Other labels can be used in addition to better describe the issue or its criticality.

## Requesting Features

Enhancement suggestions are tracked as GitHub issues.

* Suggest a single enhancement per issue.
* Provide a clear and descriptive title for the issue to identify what the specific suggestion is.
* Provide a step-by-step description of the suggested enhancement in as much detail as possible.
* Describe the current behavior, the expected one, and why you expect this behavior.
  * At this point you can also list which alternatives do not work for you.
* Explain why this enhancement would be useful to other users.
  * You may also want to point out the other projects that solved it "better" and could serve as inspiration.

## Submitting Changes

Before contributing code or documentation to this project, make sure you read the following sections.

### Commit message standards

The commit message should contain an overall explanation about the change and the motivation behind it.

In addition to an explanation about the change, please ensure that each commit contains a line similar to one of the following:

|if your commit|use this keyword|value|
|-|-------|-----|
|resolves an issue/ticket|resolves, res, resolved| #123(only for GitHub Issues), PROJ-1234 (any other issue tracker)|
|only references an issue/ticket|ref, refs, references, refers to| #123(only for GitHub Issues), PROJ-1234 (any other issue tracker)|

*Example git commit message*:
```
Fixed the pesky bug.

This commit fixed that pesky bug that we all hated.

resolves: PROJ-1234
Signed-off-by: John Doe <jdoe@example.com>

# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
# Date: Fri Jan 10 00:00:00 2025 -0400
#
# On branch PROJ-1234
```

### Signing Commits

All commits must be signed-off

### Pull Requests

All changes must come from a pull request (PR) and cannot be directly committed. While anyone can engage in activity on a PR, pull requests may only be approved by team members.

Before a pull request can be merged:
* The PR body should contain a line similar to one of the following:
  |if your pull request|use this keyword|value|
  |-|-------|-----|
  |resolves an issue/ticket|resolves, res, resolved| #123(only for GitHub Issues), PROJ-1234 (any other issue tracker)|
  |only references an issue/ticket|ref, refs, references, refers to| #123(only for GitHub Issues), PROJ-1234 (any other issue tracker)|
* The content of the PR has to be relevant to the PR itself
* The contribution must follow the style guidelines of this project
* Multiple commits should be used if the PR is complex and clarity can be improved, but they should still relate to a single topic
* For code contributions, tests have to be added/modified to ensure the code works
* The pull request must be approved by [dev team members](https://github.com/orgs/enterprise-contract/teams/devs):
  * If submitted by a non-team member, the pull request must have at least two approving reviews
  * If submitted by a team member, the pull request must have at least one approving review
  * If the changes are "simple" (e.g. a typo fix), the pull request only needs one approval, regardless of origin. Team members may exercise their best judgement when determining if a PR qualifies as a simple fix.
* The feature branch must be rebased so it contains the latest changes from the target branch
* The CI has to pass successfully
* Every comment has to be addressed and resolved
</strike>