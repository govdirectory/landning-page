# Contributing to Govdirectory

🙇‍♀️ Thank you for contributing!

We love issues and pull requests from everyone.
If you're not comfortable with those features of GitHub, you can also just [start a discussion](https://github.com/govdirectory/website/discussions).

## Direction

When contributing, it might be helpful to know what we want this tool to be.
We have defined our **vision** as:

>Our vision is a world where people are empowered to engage with their government to ensure responsive, inclusive, participatory and representative decision-making at all levels.

and we also have set a **mission** to:

>We will enable a community powered directory where the online presence of every public organization is easily findable, queryable and trustworthy.

We hope that will help you contribute meaningfully.
As a more detailed help, and to see what we already have planned, checkout our [roadmap](https://github.com/orgs/govdirectory/projects/2) and [milestones](https://github.com/govdirectory/website/milestones).

## Problems, suggestions and questions in issues

Please help development by reporting problems, suggesting changes and asking questions.
To do this, you can [create a GitHub issue](https://help.github.com/articles/creating-an-issue/) for this project in the [GitHub Issues for the website](https://github.com/govdirectory/website/issues/new).

In particular, we use the tags [good first issue](https://github.com/govdirectory/website/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) so that you can see where you can start and [help wanted](https://github.com/govdirectory/website/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) where we still need input.

You don't need to change any of our code or documentation to be a contributor!

## Documentation and code in pull requests

If you want to add to the documentation or code of one of our projects you should make a pull request.

If you never used GitHub, get up to speed with one of the great free interactive courses in the [GitHub learning lab](https://lab.github.com/) on working with GitHub and working with MarkDown, the syntax this project's documentation is in.

This project is [licensed CC-0](LICENSE.md), which essentially means that the project, along with your contributions is in the public domain in whatever jurisdiction possible, and everyone can do whatever they want with it.

### 1. Make your changes

In this project we use branches for changes and don't usually commit direct to the main branch.
When you've forked this repository, please make sure to create a feature branch.

Add your changes in commits [with a message that explains them](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message).
Document choices or decisions you make in the commit message, this will enable everyone to be informed of your choices in the future.

If you are adding code, make sure you've added and updated the relevant documentation and tests before you submit your pull request.
Make sure to write tests that show the behavior of the newly added or changed code.

For icons, we are using the libraries [Maki](https://labs.mapbox.com/maki-icons/) and [Temaki](https://ideditor.github.io/temaki/docs/) for a consistent style. If you can't find a usable icon in those sets, try to emulate their style or find other icons similar to it.

### 2. Pull request

When submitting the pull request, please accompany it with a description of the problem you are trying to solve and the issue numbers that this pull request fixes.

### 3. Improve

All contributions have to be reviewed by someone.

It could be that your contribution can be merged immediately by a maintainer.
However, usually, a new pull request needs some improvements before it can be merged.
Other contributors (or helper robots) might have feedback.
If this is the case the reviewing maintainer will help you improve your documentation and code.

If your documentation and code have passed human review, it is merged.

## Improving data on Wikidata

You can also help the project by improving data about public agencies on [Wikidata](https://wikidata.org).
Here is what we know that we need right now:

1. Add all public agencies. You can start with the ones in you country. Public agencies are notable so you don't need to worry about that. Please add sources and/or external identifiers so that it is possible to verify their existence.
2. Make sure it's possible to differentiate active agencies in contrast to historic agencies in a query.
3. Add basic properties like country (P17) and which administrative level they are on (state, regional, local etc.). How this is modeled may vary by country. If possible add what type of agency it is (like environmental protection or taxes).
4. Add the online platforms you can find for them. Common ones are YouTube channel (P2397), Facebook (P2013), Twitter (P2002), Instagram (P2003) and LinkedIn (P4264). These are also the one that is shown with icons in the directory. But others that they are active on (that have properties in Wikidata) are also good to add and they will show on the institution page.

## Add a country in the interface

If the data of a country is of high quality it can be added to the directory.
The guide [Add a country](ADD_A_COUNTRY.MD) gives instructions for how that is done.

## Feedback

You can also help by [telling us](https://github.com/govdirectory/website/discussions) how you would like to use a resource like this.
