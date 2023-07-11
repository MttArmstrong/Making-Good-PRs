---
title: "Basic Pull Requests"
teaching: 10
exercises: 5
questions:
- "How do you open a PR?"
- "How do you interact with a PR?"
- "How do you merge a PR?"
objectives:
- "Become familiar with basic actions on GitHub Pull Requests"
keypoints:
- "New PRs can be opened in a repository from a branch or a fork."
- "Text on PRs use Markdown styling for formatting."
- "A user can interact with PRs in multiple ways: commenting, assigning reviewers, linking to other issues and pull requests, and more."
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

![File edit button highlight]({{ page.root }}/fig/prs-edit-file.png){:width="75%"}

Once the file is edited to our satisfaction, we click "Commit changes...",
which pops up a dialog box asking us to fill in the commit message.

![Commit changes pop-up dialog]({{ page.root }}/fig/prs-commit-dialog.png){:width="50%"}

Rather than committing directly to the main branch, we will instead make a
new branch with the changes.

![Commit changes/new branch pop-up dialog]({{ page.root }}/fig/prs-new-branch-dialog.png){:width="60%"}

GitHub will autopopulate a branch name for us. We can choose to keep it or
change it.

### Make a PR

Once we click "Commit changes," the page will load the "Open a pull request"
page with our commit message as the title.

![Open a pull request page reloaded]({{ page.root }}/fig/prs-new-pr-default.png){:width="75%"}

A new PR has several parts:

- _Title_: This will display on the main "Pull request" page.
- _Write_: This is an open area for the details of the PR. GitHub support Markdown formatting.
- _Preview_: This will preview the Markdown-rendered version of the details.

To open the issue, click the "Create pull request" button.

![Newly opened PR with proposed changes]({{ page.root }}/fig/prs-new-pr-view.png){:width="75%"}

> ## Open a New PR
>
> Navigate to your practice repository.
> 
> * Make a change to your `README.md` file
> * Commit the changes to a new branch
> * Put a basic title and details
> * Create the PR
>
{:.challenge}

## Interact with a PR

There are many interactions available on an open PR.

The most basic interaction is adding a comment. This is
how you can interact with the PR author, the assignee, and others who
have commented on or subscribed to the PR.

Simply click in the comment box at the bottom of the PR, type whatever
you'd like, and click "Comment."

![Add a comment to a PR]({{ page.root }}/fig/add-pr-comment.png){:width="75%"}

Another useful feature for GitHub is linking Issues and PRs. This is actually
very simple. In the PR's description or in a comment, mention the relevant
Issue using `#` and the Issue number.

![Link a PR to an Issue]({{ page.root }}/fig/link-pr-to-issue.png){:width="60%"}

This will create a link to the Issue.

![Link to the Issue]({{ page.root }}/fig/linked-issue.png){:width="60%"}

You can also edit the information in the right-hand column.

![Information block with reviewers, assignees, labels, projects]({{ page.root }}/fig/prs-right-hand-column.png){:width="40%"}

We will cover the following options:

| Options | Purpose |
| ------- | ------- |
| Reviewers | Assign reviewer(s) to look over your proposed changes. |
| Assignees | Add assignee(s) who are responsible for incorporating proposed changes. |
| Labels | Assign label(s) to categorize the PR. |

> ## Assignment Time
>
> Navigate to your PR from the previous exercise.
> 
> * Add yourself as the `Assignee`
> * Mention one of your open Issues
>
{:.challenge}

## Merge a PR

We are done with these changes. We have completed the work on it, had our
discussion, and now we are ready to merge the changes.

> ## Wait, what about review?
> Nobody reviewed our changes, so do we really want to merge? In a real-case
> scenario, *no*! We will cover more about reviewing later, though, so we
> are going to skip it for now.
{:.callout}

Merging a PR is quite simple - just click the "Merge pull request" button.

![A simple merge with our exercise PR]({{ page.root }}/fig/merge-pr-no-review.png){:width="50%"}

The dropdown on the "Merge pull request" shows several options:

![Merge PR dropdown with three options]({{ page.root }}/fig/merge-pr-options.png){:width="50%"}

We will not cover all of these options here, but read more about them in
[GitHub's official documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request#merging-a-pull-request).

When you click the "Merge pull request" button, a new dialog box appears,
prompting for the commit message. Once you have made the preferred edits,
click "Confirm merge."

![Confirm merge dialog box]({{ page.root }}/fig/confirm-merge-dialog.png){:width="75%"}

The changes have been incorporated back into the `main` branch.

> ## Time to Merge
>
> Navigate to your PR from the previous exercises.
> 
> * Click "Merge pull request"
> * Modify the merge message
> * Merge!
>
{:.challenge}

You now know the basic actions you can take on a GitHub Pull Request!

{% include links.md %}

