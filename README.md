# transfer-to-github-example

This repository shows the steps to transfer a project from GitLab to Github.

1. Got to `github.com`
    * Create an accont in case you don't have one.
2. Create a **PUBLIC** and empty project in your github profile.
   - No need to add anything; nor `REAMDE.md`, neither `license` or `.gitignore` files
   - The name of the repository doesn't need to be the same. You can always keep the same of course.
   - **EXAMPLE**: Created empty new project: https://github.com/garciagenrique/example-transfer-project-from-gitlab
   - If you prefer, you can push the project to an organisation instead of your personal profile

3. Open a terminal, add the github repository as a remote repo and push the repository there.

Please adapt this snippet with your user and project name
```bash
> git clone git@gitlab.in2p3.fr:escape2020/virtual-environment/transfer-to-github-example.git
> cd transfer-to-github-example
> git remote add github git@github.com:garciagenrique/example-transfer-project-from-gitlab.git
> git push --mirror github
```
     
