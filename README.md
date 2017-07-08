# Helloworld
Just another repository

## About Me
My name is Christopher Thomas. I am a undergraduate at Oklahoma State University pursuing a Bachelor of Science in Computer Science with expected Graduation date of May 2018.

### Accounts
[Facebook](https://www.facebook.com/CCThomas94)<br>
> Account is private. Must send Friend Request to view my Profile

[GitHub](https://github.com/CCThomas)<br>
[LinkedIn](https://www.linkedin.com/in/christopher-c-thomas/)<br>

### Work History
#### Harvard-Smithsonian Center for Astrophysics
Job Title: Software Engineer, Fellow<br>
Date: Summer 2016
###### Smithsonian Astrophysical Observatory
* Took an old program that manages the database for the MicroObservatory’s remote controlled telescopes, and reproduced it in JavaScript.
* Developed a JavaScript tool using D3.js to take in a text file of Exoplanet data and visualize the data.
###### High Energy Astrophysics
* Started the conversion process for NASA’s Chandra X-Ray Observatory Dark Image Calibration software from IDL to Python.

#### Cerner Corporation
Job Title: Software Intern<br>
Date: Summer 2017
###### Configuration Management
* Implemented a new feature to the Bedrock Framework.
* Modified several of the Configuration Management Wizards to fix various issues.

## Text Art to Spice up Code
[Pokémon](TextArt/Pokémon.txt)<br/>
[Portal](TextArt/Portal.txt)<br/>
[Star Wars](TextArt/StarWars.txt)<br/>

## How to use Git
Initialize a Github Repo
```
git init
```

Add remote branch, allows you to push your changes to GitHub
> Click "Clone or Download" to get the git@github address

```
git remote add origin <url_to_github_repo>
EX: git remote add origin git@github.com:ChristopherThomas94/hello-world.git
```

Add Changes
> Use "git add *" to add everything in that directory (This will not update deleted files)

> Only use "*" when everything you are committing should have the same message. Otherwise add and commit each file individually

> Use "git add -u" to update all changes (This includes deleted files)

```
git add <path_to_file>
Ex: git add HelloWorld.java
```

Commit Changes
```
git commit -m "Commit Message"
EX: git commit -m "Added HelloWorld java file to Repo"
```

Reset to the directory to commit specified. If no commit is listed, it will go to most recent commit.
```
git reset --hard <commit>
EX: git reset --hard
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
