# Getting Started - Alice Scenario
## Step 1 Creates a new project and hosts it on GitHub
### Create folder for your project
```
luthfir97@MLuthfirRY50:~$ mkdir rhymes 
luthfir97@MLuthfirRY50:~$ cd rhymes
```

### Make an empty Git repo
```
luthfir97@MLuthfirRY50:~/rhymes$ git init 
```

### Make some readme.txt 4 a first commit (Optional)
```
luthfir97@MLuthfirRY50:~/rhymes$ touch README.txt
luthfir97@MLuthfirRY50:~/rhymes$ git add *
luthfir97@MLuthfirRY50:~/rhymes$ git commit -m "First Commit"
```

### Add some random explanation about the project to the README file.
```
luthfir97@MLuthfirRY50:~/rhymes$ echo 'HUEHUEHUEHUEHU.' >> README.txt
```

### Commit the repo update
```
luthfir97@MLuthfirRY50:~/rhymes$ git add *
luthfir97@MLuthfirRY50:~/rhymes$ git commit -m "First Commit"
```

### Review uncommitted changes. Then commit them.
```
luthfir97@MLuthfirRY50:~/rhymes$ git status
luthfir97@MLuthfirRY50:~/rhymes$ git diff
luthfir97@MLuthfirRY50:~/rhymes$ git add README.txt
luthfir97@MLuthfirRY50:~/rhymes$ git commit -m 'Added project overview to README.txt'
```

### Download Alice favorite rhymes.
```
luthfir97@MLuthfirRY50:~/rhymes$ wget https://github.com/bryanhirsch/rhymes/blob/master/all-around-the-mulberry-bush.txt
luthfir97@MLuthfirRY50:~/rhymes$ wget https://github.com/bryanhirsch/rhymes/blob/master/jack-and-jill.txt
luthfir97@MLuthfirRY50:~/rhymes$ wget https://github.com/bryanhirsch/rhymes/blob/master/old-mother-hubbard.txt
luthfir97@MLuthfirRY50:~/rhymes$ wget https://github.com/bryanhirsch/rhymes/blob/master/twinkle-twinkle.txt
luthfir97@MLuthfirRY50:~/rhymes$ wget https://github.com/bryanhirsch/rhymes/blob/master/hokey-pokey.txt
``` 

### Final Task
The Last task have been downloaded, but no commited. you can see this with
```
luthfir97@MLuthfirRY50:~/rhymes$ git status
```
Alice add all the rhyme at one by using

```
luthfir97@MLuthfirRY50:~/rhymes$ git add *
luthfir97@MLuthfirRY50:~/rhymes$ git commit "Add All Song"
```

### Now, lets make the repo up in Github
```
luthfir97@MLuthfirRY50:~/rhymes$ git remote add origin https://github.com/MLuthfirR/rhyme.git
luthfir97@MLuthfirRY50:~/rhymes$ git push -u origin master
```
