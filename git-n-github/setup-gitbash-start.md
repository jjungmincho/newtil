# How to setup your git bash (& Terminal) when you first start

1. Set up User name
```
git config --global user.name "your_name"
```

2. Set up User email
```
git config --global user.email "your_email"
```

3. Confirm the info
```
git config --list
```
Check your user name and your user email in this part.

## Go to Visual Studio Code
1. Search "Terminal" in Visual Studio Code
(Make sure you logged in your Github via Visual Studio Code before)

2. Initiate (just for the first project when you link)
```
git init
```

3. Add the file
```
git add .
```
. means all

4. Check the status
```
git status
```

5. Create a history
```
git commit -m "write your message here"
```

6. Link my local project to Github repo
```
git remote add origin [Copy the link from SSH under Code in Github repo. eg. https://github.com/yourprojectname/yourfilename.md]
```

7. Check if it worked
```
git remote -v
```

8. upload to Github
```
git push origin master
```
Important! **master 자리에는 branch이름이 들어가면 됨 branch이름이 main라하면 git push origin main 이라고 써야함**


## Resources
[코딩알려주는 누나❤](https://hackmd.io/@oW_dDxdsRoSpl0M64Tfg2g/ByfwpNJ-K)
