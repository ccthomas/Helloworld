# Helloworld
Just another repository

## About Me
My name is Christopher Thomas
and a student at OKstate!

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

Reset to the directory to commit specified. If no commit is listed, it will got to most recent commit.
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
