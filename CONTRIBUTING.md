# How to Contribute

I'd love to accept your patches and contributions to this project. There are just a few small guidelines you need to follow. Please read the following content before contributing. Thanks for your cooperation.

---
## About Pull Requests

1. Fork this repository and clone the repository you forked.
    ```bash
    # Clone your fork of the repo into the current directory
    git clone https://github.com/<YOUR_GITHUB_ID>/onos-practice
    # Navigate to the newly cloned directory
    cd <REPO_NAME>
    ```
2. Create new branch named `develop` and switch to this branch
    ```bash
    # Create a new branch named develop
    $ git branch develop
    # Switch to branch named develop
    $ git checkout develop
    ```
3. Assign the original repository to a remote called `upstream` and update
    ```bash
    # Assign the original repo to a remote called "upstream"
    $ git remote add upstream https://github.com/yungshenglu/onos-practice
    # Update to remote repository
    $ git remote update
    ```
4. Pull the latest version from our repository and merge to your branch
    ```bash
    # Pull the latest version from our repository
    $ git fetch upstream master
    # Merge our latest version to your branch
    $ git rebase upstream/master
    ```

---
## Contributor

ONOS code is hosted and maintained using [Gerrit](https://gerrit.onosproject.org/). Code on [GitHub](https://github.com/opennetworkinglab/onos/tree/master) is only a mirror. The ONOS project does **NOT** accepte code through pull request on GitHub. To contribute to ONOS, please refer to [Sample Gerrrit Workflow](https://wiki.onosproject.org/display/ONOS/Sample+Gerrit+Workflow). It should includes most of things you'll need to get your contribution started!

* [David Lu](https://github.com/yungshenglu)

---
## License

ONOS (Open Network Operating System) is published under Apache License 2.0