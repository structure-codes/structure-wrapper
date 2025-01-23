# Structure wrapper repository
The purpose of this repo is to make it easier to clone and manage all the components of the structure app

To clone the repo and all of the submodule repos at once:
```
git clone --recurse-submodules git@github.com:structure-codes/structure-wrapper.git
```

To fetch upstream changes for the submodules:
```
git submodule update --remote
```

To add a new submodule:
```
git submodule add <repo>
```

Learn more about submodules here:
https://git-scm.com/book/en/v2/Git-Tools-Submodules