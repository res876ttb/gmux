# gmux

Manage git repos.

# Usage

Use command `gmux help` for more messages, `gmux help <subcmd>` for help messages for sub command.
1. `gmux session` to create a session.
2. `gmux add <path_to_git_repo>` to add a git repo into current session.
3. `gmux set repo [--all, --pull, --checkout]` to set whether `repo` is used.
4. `gmux session <session name>` to switch session.
5. `gmux delete <session name>` to delete a session.
6. `gmux set session old_name new_name` to rename a session.
7. `gmux ls` to list all sessions.
8. `gmux ls -a` to list all sessions and all the repos.
9. `gmux checkout` to checkout all repos to a certain branch. Note that `git stash` will automatically used if any of the repos are not clean.
10. `gmux status` to show the status of all repos in the current session.
