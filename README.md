# hello-world
Just another repository

## About Me
My name is Christopher Thomas
and a student at OKstate!

## How to run Code
Compiling java files
> class_files: Location for Class files to be save

> java_files/*.java: Location of java files to be compiled
```
javac -d class_files java_files/*.java
```

Running class files
> class_files: Location of class file to run

> ProgramManager: Class file to run
```
java -cp class_files ProgramManager
```

## How to use Git
Initialize a Github Repo
```
git init
```

Add remote branch, allows you to push your changes to GitHub
```
git remote add origin <url_to_github_repo>
EX: git remote add origin git@github.com:ChristopherThomas94/hello-world.git
```
Add Changes
```
git add <file_to_add>
EX: git add HelloWorld.java
```
Commit Changes
```
git commit -m "Commit Message"
EX: gti commit -m "Added HelloWorld java file to Repo"
```
Pull from Branch, helps avoid merge conflicts
```
git pull origin <branch-name>
EX: git pull origin master
```
Finally Push to Branch
```
git push origin <branch-name>
EX: git push origin master
```

## Formatting README
You can have plain text

* Or some bullets
  * Maybe Some nested bullets
  
> Also what ever this is

> If you do not put a space between ">"
> It will put them on the same line!
