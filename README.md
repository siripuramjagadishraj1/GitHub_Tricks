# GIT COMMANDS
### Create Repo
echo "# test" >> README.md <br/>
git init <br/>
git add README.md <br/>
git commit -m "first commit" <br/>
git remote add origin https://github.com/siripuramjagadishraj1/GitHub_Tricks.git <br/>
git push -u origin master <br/>

### Working with Repo
git clone https://github.com/siripuramjagadishraj1/GitHub_Tricks.git (Then edit files) <br/>
git status <br/>
git add editedFile.txt <br/>
git status <br/>
git commit -m "First edit" <br/>
git status <br/>
git push origin master <br/>
git push origin master:development //Creates development branch <br/>
git branch -a  //shows all branches <br/>
git checkout branchname //switch to branch name <br/>
git checkout -b newbranch //creates and swithches to new branchname <br/>

#### User name and Password handling <br/>
git config --global --unset credential.helper  //reset Credentials <br/>
git config --global user.name "enteruser name" <br/>
git config --global user.email  "enter mail" <br/>
git config --global github.user  "enter password" <br/>
git config --global credential.helper wincred <br/>
