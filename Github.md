# Github Common Tutorial

- Download from any github source

``` 
git clone http://<url>.<sources>.git
```
Example:
```
git clone https://github.com/azrulmSE/Tutorial.git
```

- Disable upload for file

``` git reset -- main/dontcheckmein.txt ```

- Disable upload for folder

``` 
git reset -- node_modules/* 
```
- Upload git

``` 
git add . 
git commit -m 'upload to git' 
git push origin
```
- Remove origin
```
git remote remove origin
```
- Check origin
```
git remote
```
- Configuring a remote for a fork
```
git remote -v
git remote add upstream https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git
git remote -v
```
- Syncing a fork
```
git fetch upstream
git checkout master
git merge upstream/master
```

Additional information:

[Managing Remotes](https://help.github.com/categories/managing-remotes/)

[Create new github repo from command line](https://coderwall.com/p/mnwcog/create-new-github-repo-from-command-line)

