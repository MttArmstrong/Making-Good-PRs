---
title: "Labelling PRs"
teaching: 5
exercises: 5
questions:
- "How do you assign labels to PRs?"
objectives:
- "Learn how to use labels for GitHub PRs."
keypoints:
- "Labelling PRs can help with prioritization and organization."
---

## GitHub Labels

Each new GitHub repository comes with a set of default labels that can be
assigned to issues, pull requests, or discussions.

From [GitHub's official documentation](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels#about-default-labels):

| Label | Description |
| ----- | ----------- |
| `bug`   | Indicates an unexpected problem or unintended behavior |
| `documentation` | Indicates a need for improvements or additions to documentation |
| `duplicate` | Indicates similar issues, pull requests, or discussions |
| `enhancement` | Indicates new feature requests |
| `good first issue` | Indicates a good issue for first-time contributors |
| `help wanted` | Indicates that a maintainer wants help on an issue or pull request |
| `invalid` | Indicates that an issue, pull request, or discussion is no longer relevant |
| `question` | Indicates that an issue, pull request, or discussion needs more information |
| `wontfix` | Indicates that work won't continue on an issue, pull request, or discussion |

These labels can be viewed from the Issues and Pull Requests pages.

![The PR page with the labels option highlighted]({{ page.root }}/fig/prs-labels.png)

## Using Labels

Now that the labels are created, they can be assigned to PRs.

Labels can be applied from the main Pull requests page or within a single PR.

From the main Pull requests page, simply checkmark the PR, hit the "Label"
dropdown, select your preferred label(s), and click outside of the
dropdown.

![Apply Labels from the main Issues page]({{ page.root }}/fig/apply-labels-issue-page.png)

To apply within a single issue, click on the issue to open it. Then you
will see the "Labels" option on the right-hand side.

![Highlighted Labels option within a single issue]({{ page.root }}/fig/label-option-in-issue.png)

Click on "Labels". A dropdown will appear in which you can select or deselect
your preferred label(s).

![Label dropdown within a single issue]({{ page.root }}/fig/label-dropdown-in-issue.png)

> ## Stick the Label
>
> Navigate to [our practice repository's issue page](#).
> 
> * Create a new issue entitled "[YOUR NAME]'s label issue"
> * Add the `discussion` label
>
{:.challenge}


{% include links.md %}

