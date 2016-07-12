git hooks

pre-commit:
 - does not let a commit to be made to master
 - does not let a commit go ahead if there is a syntax error in \*.rb (make sure you dont have a branch/head-commit containing .rb in it!)

pre-push:
 - does not let allow a push to master
 - does not let allow a push from master

usage:
cp <hook_filename> <destination_repo_path>/.git/hooks/

