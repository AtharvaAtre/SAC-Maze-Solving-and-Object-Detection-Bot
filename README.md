# Wall-E_v2.2-beta

*Development Repository for the self-balancing-line-following bot workshop, implemented with ESP32*

## Guidelines

### General

1) Strict deadlines will be followed, since the tasks in general are not complicated. Failure to do so will result in elimination from the project after warnings.
2) The ones who will structure and compile the code will have the responsibility of making it easy-to-read and debug for the ones who will test it.
3) Try to maintain error logs in a file or screenshots for every stage of development and any genuine errors.

### Git

**1. Branches & Workflow**

After the project is tracked (after `git init`) and the initial commit had been made, create the following branches.

    1. `master`
    2. `testing`
    3. `development`

* All commits must be initially made to the `development` branch. Once a feature or a fix is committed **then and then only** will it move the `testing` branch. Once the code has been tested properly it can be merged with the `master` branch.

* Since multiple people will be working in a repository, this structure will be further broken down. From the last stable point of `development` create branches as follows `memeber-name/feature-name` or `member-name/fixes-issue`. For example, `vedant/udp-logger` or `lukesh/fixed-load-prohibited`. 

* Once you have finished your implementation, merge it into `development` and follow the workflow mentioned in the above paragraph. Also, each member will work only on his/her respective branch.

**2. GitIgnore**
* The .gitignore file tells Git which files or folders to ignore in a project.
* Basic information on what is gitignore and how to use it can be found [here](https://www.freecodecamp.org/news/gitignore-what-is-it-and-how-to-add-to-repo/)
* [GitIgnore Templates](https://github.com/github/gitignore)

**3. Files Not to Track**
* Track (or Push) only the files that are necessary to build/run the code.
* Examples include intermediary build files like `.o`\, output files eg `binary files`, `py.swp`, `py.swo`, etc. and hidden folders generated by text editors and IDE's like `.vscode`.

**4. Commit Messages**
* Commit messages must be short(*80-100 characters*) and mention what was done in this change. Avoid committing messages such as **Fixed Crash** and **Refactor Code**.
* Refer to this [blog post](https://chris.beams.io/posts/git-commit/) for more information as it explains most of the guidelines.


