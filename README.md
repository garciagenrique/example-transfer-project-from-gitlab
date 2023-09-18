# transfer-to-github-example

This repository shows the steps to transfer a project from GitLab to Github.

1. Got to github.com
    * Create an accont in case you don't have one.
2. Create a **PUBLIC**  empty project in your github profile.
    * No need to add anything; nor `REAMDE.md`, neither `license` or `.gitignore` files
    * The name of the repository doesn't need to be the same. You can always keep the same of course.
    * **EXAMPLE**: Created empty new project: https://github.com/garciagenrique/example-transfer-project-from-gitlab
3. Open a terminal, add the github repository as a remote repo and push things there.
    * `git clone `
    * `git remote add github git@github.com:garciagenrique/example-transfer-project-from-gitlab.git`
    * `git push --mirror github`
    