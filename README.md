# How to keep up to date a forked repo

#### Clone the repo first
```git
  $ git clone <url>
```

#### Check the remote origin
```git
  $ git remote -v
```


#### Add a new upstream 
- upstream mean where you get the update from
```git
  $ git remote add upstream <upstream link>
```


#### Check the new upstream 
```git
  $ git remote -v
```


#### For update origin with changes that happened in upstream
- or pull down all the remote changes from upstream
- they are not merge with our local changes
```git
  $ git fetch upstream
```


#### For merge with local file
```git
  $ git merge upstream/dev
```
