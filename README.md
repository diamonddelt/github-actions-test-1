# Sample Github Actions Workflow

This simple GH Actions workflow does the following:

1. Installs an NPM module called `bats` on an Ubuntu Linux runner
1. Once installed, the workflow runs `bats -v` to check if it successfully installed