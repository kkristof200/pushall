# pushall

## Description
pushes all github repos from a certain directory

## Install
~~~~shell
wget https://raw.githubusercontent.com/kkristof200/pushall/master/pushall -O /usr/local/bin/pushall && chmod u+x /usr/local/bin/pushall
# or
curl https://raw.githubusercontent.com/kkristof200/pushall/master/pushall > /usr/local/bin/pushall && chmod u+x /usr/local/bin/pushall
~~~~

## Usage
~~~~shell
pushall [path_to_folder_where_the_repo_folders_are]
# path defaults to ~/github
~~~~

## Dependency
[push](https://raw.githubusercontent.com/kkristof200/push/master/push)
