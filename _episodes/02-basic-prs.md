---
title: "Basic Pull Requests"
teaching: 10
exercises: 5
questions:
- "How do you open a PR?"
- "How do you interact with a PR?"
- "How do you close a PR?"
objectives:
- "Become familiar with basic actions on GitHub Pull Requests"
keypoints:
- "New PRs can be opened in a repository from a branch or a fork."
- "Text on PRs use Markdown styling for formatting."
- "A user can interact with PRs in multiple ways: commenting, mentioning others, linking to other issues and pull requests, and more."
---

## Open a PR

A PR cannot be opened without some changes to be incorporated. For this example,
we will use the `branch` and `merge` workflow; however, another common method
is the `fork`, `branch`, and `merge` method (see the
[Reference page]({{ page.root }}/reference.html) for more details).

> ## Multiple Paths Available
> We will do the rest of this lesson through the GUI; however, all of these
> steps can be done via command line and your preferred text editor.
> Do whatever feels right for you!
{:.callout}

### Make a Change

First we will make a change to a file in our repository. We click on the
preferred file in the repository and hit the "Edit" pencil in the top-right
corner.

![File edit button highlight]({{ page.root }}/fig/prs-edit-file.png)

Once the file is edited to our satisfaction, we click "Commit changes...",
which pops up a dialog box asking us to fill in the commit message.

![Commit changes pop-up dialog]({{ page.root }}/fig/prs-commit-dialog.png)

Rather than committing directly to the main branch, we will instead make a
new branch with the changes.

![Commit changes/new branch pop-up dialog]({{ page.root }}/fig/prs-new-branch-dialog.png)

GitHub will autopopulate a branch name for us. We can choose to keep it or
change it.

Once we click "Commit changes," the page will load the "Open a pull request"
page with our commit message as the title.

![Open a pull request page reloaded]({{ page.root }}/fig/prs-new-pr-default.png)

A new PR has several parts:

- _Title_: This will display on the main "Pull request" page.
- _Write_: This is an open area for the details of the PR. GitHub support Markdown formatting.
- _Preview_: This will preview the Markdown-rendered version of the details.

To open the issue, click the "Create pull request" button.

![Newly opened PR with proposed changes]({{ page.root }}/fig/prs-new-pr-view.png)

## Interact with a PR

## Close a PR

{% include links.md %}

