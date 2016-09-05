# boilerplate-gitignore

1. Clone the repo somewhere: `[path]/boilerplate-gitignore`
2. Add the following to your .bashrc file:
```shell
BOILERPLATE_GITIGNORE_PATH=[path]/boilerplate-gitignore/
if [ -f $BOILERPLATE_GITIGNORE_PATH/add_alias ]; then
    . $BOILERPLATE_GITIGNORE_PATH/add_alias
fi
```
and replace `[path]` with the where you cloned the repo.

3. Now resource your bashrc:
```
$ source ~/.bashrc
```


### To use

From the git repo you wish to add the `.gitignore` simply execute the command:
```
$ add-gitignore
```
A `.gitignore` file will be copied into the working directory.
