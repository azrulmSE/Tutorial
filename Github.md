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
Additional information:

[https://help.github.com/categories/managing-remotes/]https://help.github.com/categories/managing-remotes/

