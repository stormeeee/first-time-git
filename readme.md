# First Time git setup

```bash
sudo apt install git -y
sudo apt install gh -y

git config --global user.name <>
git config --global user.email <>
git config --list
gh auto login
```

# To create a repository from cmd and push refs from cmd
1. Initialise the code folder as a git repository
    ```bash
    git init
    ```
2. Add all the files ready to be pushed
    ```bash
    git add .
    ```
3. Commit the files 
    ```bash
    git commit -m ""
    ```
4. Now create a remote repository in your github account using command line
    ```bash
    gh repo create <repo name> --public/private --confirm
    ```
5. Now add remote origins to you local code folder
    ```bash
    git remote add origin https://github.com/username/repo-name
    ```
6. Now push the changes to github
    ```bash
    git push -u origin main
    ```
7. To check from the cmd itself if the changes are pushed or not!
    ```bash
    gh repo view username/repo
    ```
    or else visit on web
    
    
    
    
    
    
    
    
    
