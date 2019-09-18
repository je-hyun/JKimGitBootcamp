# JKimGitBootcamp
Git and Github exercises compiled and presented by Je Hyun Kim for CUS1151.

## Setting up
### Downloading
* Mac - http://git-scm.com/download/mac
* Windows - http://msysgit.github.io/
* Linux - http://git-scm.com/book/en/Getting-Started-Installing-Git

Check if git is installed correctly. Open your terminal and type the following command
```
$ git --version
```

### Setting up for github
First, create a github account at https://github.com if you don't have an account already.

In your terminal, copy and paste each of these commands and replace the information inside quotes. 
```
$ git config --global user.name "Your name here"
$ git config --global user.email "your_email@example.com"
```
* (Optional more info https://kbroman.org/github_tutorial/pages/first_time.html)

## Main presentation
https://rogerdudler.github.io/git-guide/

## Exercise
### Exercise 1 (Basics).
1. Create a github repository called hello-world on http://github.com <br />
![step1](https://help.github.com/assets/images/help/repository/repo-create.png) <br />
![step2](https://help.github.com/assets/images/help/repository/create-repository-name.png) <br />
![step3](https://help.github.com/assets/images/help/repository/create-repository-init-readme.png) <br />
2. Clone the github repository to your computer.
```
$ git clone "URL_TO_THE_REPOSITORY" #Copy the repository locally
$ cd hello-world #Move directories to hello world
```
Then, create a text file called "myFile.txt" in that location (using any text or code editor) with some text in it (for example, Hello World!).
```
$ git status #View the state of the repo
$ git add myFile.txt #Stage a file
$ git commit -m "Commenting my first commit!"
$ git push origin master
```

### Exercise 2 (Collaborating).

## Adding other collaborators on github
https://stackoverflow.com/questions/7920320/adding-a-collaborator-to-my-free-github-account
