# GIT CheatSheet

## setup
1. set a name that is identifiable for credit when receivew history

   ```
   git config --global user.name "[firstname]"
   ```

2. set and email , associated with each history maker

   ``` 
   git config --global user.email "[valid email]"
   ```
 
Configuring user information used across all local repositories

## setup and init

1. initialize an existing directory and git repository
    
    ``` 
    git init
    ```
2. download an entire git repository into local machine
    ```
    git clone [repository url]
    ```

## stage and snapshot

1. show modified files in working directory 
   ```
   git status
   ```

2. add files to next commit 
    ```
    git add [files] 
    ```
3. unstage all files while retaining the changes in working directory
    ```
    git reset [file]
    ```
4. diff of what is changed but not staged
    ```
    git diff
    ```
5. commit your staged content as a new commit   snapshot 
    ```
    git commit -m "commit message"
    ```

## Branch and merger 

1. list your branches
    ```
    git branch
    ```
2. create a new branch at the current commit
    ```
    git branch [branch-name]
    ```
3. switch to another branch and check it out into your working directory
    ```
    git checkout [branch name]
    ```
4. merge the specified branch’s history into the current one
    ```
    git merge [branch]
    ```
5. show all commits in the current branch’s history
    ```
    git log
    ```