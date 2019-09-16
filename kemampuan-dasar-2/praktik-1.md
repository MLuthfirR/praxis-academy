# Getting Started - Alice Scenario

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
luthfir97@MLuthfirRY50:~/rhymes$ wget https://www.acquia.com/sites/default/files/blog/all-around-the-mulberry-bush.txt
luthfir97@MLuthfirRY50:~/rhymes$ wget https://www.acquia.com/sites/default/files/blog/jack-and-jill.txt
luthfir97@MLuthfirRY50:~/rhymes$ wget https://www.acquia.com/sites/default/files/blog/old-mother-hubbard.txt
luthfir97@MLuthfirRY50:~/rhymes$ wget https://www.acquia.com/sites/default/files/blog/twinkle-twinkle.txt
luthfir97@MLuthfirRY50:~/rhymes$ wget https://www.acquia.com/sites/default/files/blog/hokey-pokey.txt
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
luthfir97@MLuthfirRY50:~/rhymes$ git remote add origin [Your Repo Link]
luthfir97@MLuthfirRY50:~/rhymes$ git push origin master
```
