# Project Planning Test

I like the automatability of GitHub Projects and want to see if I can easily automate the flow I have in mind

# Proposed Flow

* We don't really care about epics, we can just group stories by labels instead
* Stories are GitHub Issues and describe high level goals, not directly worked on
* Milestones represent a sprint
* Tasks are PRs and linked back to stories (issues)
* How do I create a PR and a branch from an issue

# Todo

- [x] Mark tasks without a time and prioritization as invalid
- [x] Keep invalid tasks in the To Do column of the sprint board
- [x] Make a branch and draft PR for users when stories get moved to In progress -> https://octokit.github.io/rest.js/v17#git-create-ref
- [x] Open a draft PR on first commit to issue branch
- [x] If a task gets added to a milestone, also add it to the sprint board
- [ ] Create sprint milestone on a schedule
- [ ] Close sprint milestones on a schedule
- [ ] Archive all cards when their associated milestone is closed if they are in the `Done` column
- [ ] Move unclosed issues in milestone (sprint) to next milestone (sprint)
- [ ] Terraform for boards and labels
