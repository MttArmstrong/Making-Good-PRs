---
title: "Code Reviews"
teaching: 10
exercises: 5
questions:
- "How do you add reviews to a PR?"
- "How do you address requested changes?"
objectives:
- "Become familiar with the code review process on GitHub."
keypoints:
- "Code reviews are integrated into GitHub Pull requests."
- "Reviewers can approve, request changes, or simply add comments as part of the review process."
---

## Request a Review

Requesting a review can be done within a PR. Click on a PR, then click on 
"Reviewers" on the right-hand side. Here you can type in and select
reviewers for your PR.

![Reviewers menu on a Pull Request]({{ page.root }}/fig/prs-reviewers.png){:width="40%"}

> ## No reviewers?
> At this point, likely no reviewers will appear. You can only directly request
> reviews from "Collaborators" on your repository.
> [Read more about GitHub Collaborators](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository).
{:.callout}

## Add a Review

To add a review to a PR, navigate to the PR in question and click on "Files
changed."

![PR page with files changed highlighted]({{ page.root }}/fig/prs-files-changed.png){:width="60%"}

Within this page, when you hover over a line of text, a `+` button will appear
to the left.

![PR add comment plus symbol for reviews]({{ page.root }}/fig/prs-add-comment-line.png){:width="50%"}

Click on the `+` button to add a comment to that line.

![Adding a review comment to line 6]({{ page.root }}/fig/prs-comment-line-6.png){:width="60%"}

At this point, you can "Cancel", "Add single comment", or "Start a review." If
you click "Add single comment", the comment will be added without rendering
a review decision. If you click "Start a review", this will "start" a review.

> ## Can you see it yet?
> At this point, no one can see your review. It is "Pending" until you finish
> all of your comments.
{:.callout}

Once you have finished adding all of the comments, you will need to press the
"Review changes" button.

![Files changed page with review button highlighted]({{ page.root }}/fig/prs-review-changes-button.png){:width="75%"}

You will see three options: "Comment", "Approve", or "Request changes."

> ## Greyed out options?
> Are you following along on your own PR? You might notice that you cannot
> approve or request changes. This is because you are the author! GitHub
> doesn't allow authors to do either of these actions.
{:.callout}

> ## Let's Review
>
> Partner up with another participant and navigate to their practice repository.
> Add a few comments to one of their PRs and submit the review, requesting changes.
>
{:.challenge}

## Address a Review

Review comments can be viewed in the "Conversation" tab as well as in the
"Files changed" tab. 

![PR review comments on Conversation tab]({{ page.root }}/fig/prs-review-convo-page.png){:width="75%"}

![PR review comments on Files changed tab]({{ page.root }}/fig/prs-review-files-changed-page.png){:width="75%"}

Incorporating requested changes can be done via command line or through the
GitHub GUI. Once addressed and pushed, you can resolved the different conversations
and re-request a review.

> ## Fix It
>
> Address the changes your partner requested and re-request a review from them.
>
{:.challenge}

And that’s all, folks! You now know much more about GitHub Pull Requests.

{% include links.md %}

