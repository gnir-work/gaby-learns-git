## Command words
git - A tool for managing code across several instances and many developers
git repo - A single git project
git hub - a cloud for hosting your git repo

## Commands
git clone - clone a remote repo locally
git status - show current repo status
git add - move a file from changed_files to staged_to_commit.
git commit -m <message> - Wrap all off the staged_to_commit files to a single commit.
git diff - Show the current diff from the last commit or staged_to_commit if present
git log - Show the history of commits - a list of the commit id, author, date and commit message.
git show <commit id> - Show the changes of a specific commit

## Git stages
untracked - files that git doesn't know.
changed_files - files that changed and git knows.
staged_to_commit - files that changed and were added via `git add`
commmit - The act of saving act of the staged changes to one commit.
