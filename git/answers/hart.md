# GIT

## QUESTIONS

- What is git? Why do we need it?
    - a version control system for software development (theoretically could be used to manage version changes in any developing collection of interrelated resources, e.g. a film script or a legal framework). its greatest strength is being able to track (and later integrate) parallel branches of work. it's needed because multiple authors working on a single codebase will mutate its code in often contradictory or mutually incompatible ways, requiring checkpoints where their changes can be compared, corrected, and integrated into a working whole. git manages this through branching, committing, and merging changes in bite-size chunks – which allows collaborators to see high-level digests along with granular line-by-line highlights of those changes.
- What are the top 10 commands? What do they do?
    1. clone (copies a whole repository of code from a url to local storage)
    2. pull (gets latest version of the original repository and updates the local version)
    3. branch (creates a new branch from the current 'commit' or save point)
    4. checkout (switches to a branch and logs it as the one to stage your changes in)
    5. add (stages a file as part of the next change record to be committed)
    6. commit (creates a local save point for current branch, and describes changes made)
    7. push (publishes the commits to the public record of the current branch)
    8. merge (merges the specified branch into the current one)
    9. diff (inspects the differences between various branches, staged/committed files, etc)
    10. status (summarizes the current branch, staged/committed files, untracked files, etc)
- How do you open a PR?
    - push all commits to the remote repo
    - go to the repo on github (can also be done from the CLI, but I prefer browser)
    - click "Compare & pull request" or the "Pull requests" tab > "New pull request"
    - pick the appropriate branch (e.g. the branch I just pushed and its origin)
    - fill out the form with an informative title and clear description of changes
    - submit

## RESOURCES

GIT Cheatsheet:
https://education.github.com/git-cheat-sheet-education.pdf
https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/