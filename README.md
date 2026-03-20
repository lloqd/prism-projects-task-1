# prism-projects-task-1
Task 1: Git and Markdown for the Projects domain at PRISM
***
# What is *Git*?
*Git* is a distributed version control system (VCS) designed to track changes in source code, allowing one to branch off the main repository to test new features, to revert back to previous states if something breaks, and to cleanly manage contributions between different collaborators on the same project.

While *Git* runs locally, there are multiple hosting services for *Git* repositories available, the most popular being GitHub, GitLab, etc.

## How to *push* code to GitHub?
As mentioned previously, GitHub is a hosting platform for *Git* repositories, which is analogous to cloud storage for one's personal files, and similarly, we also need to upload our source code to our repositories hosted online, the process of which is called *pushing code*.
To put it simply, there are three steps:
1) **Staging**: `git add ./example_file` (This tells *Git* which files in the working directory are to be saved to the repo)
2) **Committing**: `git commit -m "Example commit message"` (Next, we take a "snapshot" of these files in their current state and attach a commit message explaining our changes for whoever needs to see it)
3) **Pushing**: `git push` (Finally, the snapshot is uploaded to the repository hosted on GitHub)
***
# What is *Markdown*?
*Markdown* is a way of formatting plain text using some special symbols or "tags", allowing one to easily format one's text just by typing them in between. Thus, it is a markup language and is widely used for writing documentation (like this *README*), and can parse directly into HTML.


For example: 
- to render an italicized word, like *this*, it's as simple as encasing the word in `asterisks (*)` or `underscores (_)`
- to make headings, like the ones above, a `hashtag (#)` is used as a prefix
- and to make lists like this one, we can use `dashes (-)` for bulleted lists
