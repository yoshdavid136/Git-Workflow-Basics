# Git-Workflow-Basics
i-need-help-conflict


This Is the line I am going to be changing. I am changing the line with this sentence.

Jon, David, and Tristan is this group.
This assignment was learning the basics of Git and GitHub, along with hooking up the SSH key. Each team member made individual commits to their own file and pulled and synched changes from teammates, and created branches and opened pull requests a review, as well as making and fixing a merge conflict. We learned the Git push and pull aren't just there for no reason but helps prevent a conflict when multiple people are working on the same repository. One challenge we ran into was the merge conflict. Our first attempt at creating a merge conflict didn't actually produce one, because the second branch was created after the first change had already been merged into main. We solved it by branching an older commit so that both branches diverged from the same starting point. 

## The Merge Conflict and How We Resolved It
Two branches each modified line 2 of this README with different text. After the
first branch was merged into main, the second branch's pull request showed a
conflict, since both had changed the same line from a shared earlier version.
We resolved it using GitHub's "Resolve conflicts" tool: we removed the `<<<<<<<`,
`=======`, and `>>>>>>>` conflict markers, kept the version of the line we wanted,
and committed the merge directly from the pull request.
