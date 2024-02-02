## Some Github Features Hiding

###  OCTOCAT

- [www.myoctocat.com](myoctocat)

    This allows you to design your own octocat. Octocat is the official mascot.
    The character is a hybrid of an octopus and a cat that symbolizes github's 
    friendly and welcoming nature. I just designed my octocat and added as my 
    alternative github account's avatar.

### FORK AND CODESPACE

#### Fork

    To fork means to retrieve a copy of a repository from another author and 
    possess all the key information and features that repository has.

#### Github.dev 
    
    After forking, press __period__ (__.__) and this will open github.dev.
    
    
    **Github.dev** is an IDE that has does not have any compute attached to it
    and makes it really easy to start working with files. It opens an amazing 
    text editor looking like VS Code

#### Codespaces

    Click on Code tab in the repository, select Codespace.

    A Codespace is an instant cloud developer environment where we can run, test,
    debug, push, without the machine setup locally.



### TOPICS TO BE COVERED

#### Cloning
    Cloning can be done in different ways namely HTTPS, SSH, GithubCLI

##### HTTPS

    ```sh
    git clone <git url>
    ```

#### Commits

    For a new machine that has never made a commit, it needs to be set up 
    with the following command:

    ```
    git config --global core.editor vim
    ```

    When we want to commit code, we write git commit which will open up the 
    commit to edit message in the editor of choice.
    
    ```sh
    git commit
    ```


#### Log

    git log will show the recent commits to the git tree

#### Push

    When we want to push a repo to our remote origin

    ```
    git push
    ```
#### Branching

#### Staching

#### Merging

#### Reset
    
    Reset allows you to move staged changes to be unstaged. This is useful when
    you want to revert all files not to be committed.
