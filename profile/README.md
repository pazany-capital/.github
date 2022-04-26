# For developers

### General policy

- Please follow appropriate conventions, be it a language convention or REST API convention. Ask if you don't know or understand something. Don't spend too much time being stuck
- Please cover your code with tests. Unit and *integrational(if it's appropriate)*

### Process of committing:

1. Create a new branch(`git checkout -b <branch-name>`) that explain what feature are you developing. The convention for branch names is words separated with dashes(`-`) e.g. `new-ema-strategy`
2. Write your changes(**don't forget to add tests!**)
3. Push your changes;
  If you're not using IDE's built in VCS, here's a guide for terminal:
  ```bash
  git add . # stage your changes
  git commit -m 'Add new strategy' # make sure the commit message is descriptive
  git push origin <branch-name> # push your changes to the newly created branch
  ```
4. After previous step, the changes will be pushed to the new branch and the link will appear(unless the PR already exists) in your terminal, offering to create a pull request. Follow that link
5. Wait for CI to pass
6. Ask for a review from engineering team
7. If a reviewer asks for a change - go back to step 2
8. Merge

### Repositories

If you're creating a repository, let's discuss the name :) A bad beginning makes a bad ending.
