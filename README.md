# front-end-tech
Here i put all front-end related technology code and my practice stuff

# Some Important git tip

or create a new repository on the command line

echo "# front-end-tech" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/rajkhare1/front-end-tech.git
git push -u origin master


…or push an existing repository from the command line

git remote add origin https://github.com/rajkhare1/front-end-tech.git
git push -u origin master

—————
git —version - for check git on your local
git clone url.git  - copy your code
git status - show the status
git diff filename
git add filename - ready for stage
git commit -m “commiit message” - for commit to local
git push origin master - for push changes to github website


Cool git command run your project:
git log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'

git lg instead of git log

Here's the free code snippet, and what your .gitconfig file would look like when you add it to your global git config
https://codingforeverybody.com/snippets/git-lg


