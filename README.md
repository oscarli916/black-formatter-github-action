# Black formatter with Github Action

Format Python code with Black formatter and make a commit using Github Action Bot

## Setup Repository Permission

To allow Github Action to do a write operation on your repo, you have to enable Workflow permissions

This setting can be found in a repository's settings under `Actions > General > Workflow permissions.`

## Using Github Action Bot for commit messages

Set user.name: `git config --global user.name 'github-actions[bot]'`

Set user.email: `git config --global user.email '<id>+github-actions[bot]@users.noreply.github.com'` where you can find the id in https://api.github.com/users/github-actions%5Bbot%5D
