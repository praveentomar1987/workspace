# neurolab-mongo-python

![image](https://user-images.githubusercontent.com/57321948/196933065-4b16c235-f3b9-4391-9cfe-4affcec87c35.png)

### Step 1 - Install the requirements

```bash
pip install -r requirements.txt
```

### Step 2 - Run main.py file

```bash
python main.py
```

### Git Version
```bash
git --version
```


To download your dataset

```
wget https://raw.githubusercontent.com/avnyadav/sensor-fault-detection/main/aps_failure_training_set1.csv
```

This is changes made in neuro lab


Git commands

If you are starting a project and you want to use git in your project
```
git init
```
Note: This is going to initalize git in your source code.


OR

You can clone exiting github repo
```
git clone <github_url>
```
Note: Clone/ Downlaod github  repo in your system


Add your changes made in file to git stagging are
```
git add file_name
```
or
```
git add .
```
Note: You can given file_name to add specific file or use "." to add everything to staging are


Create commits
```
git commit -m "message"
```

```
git push origin main
```
Note: origin--> contains url to your github repo
main--> is your branch name 

To push your changes forcefully.
```
git push origin main -f
```


To pull  changes from github repo
```
git pull origin main
```
Note: origin--> contains url to your github repo
main--> is your branch name


To remove remote origin
```
git remote remove origin
```

To check the version of remote git
```
git remote -v
```

To add the new url (git)
```
git remote add origin <give your url>
```

To chech the logs (changes with date and time)
```
git log
```


To sign-in in git thru vscode

<Want to sign in, Copy code and paste it>


For soft reset of git origin main means previous code also will be there
```
git reset -–soft 6afd
```

To check the status 
```
git status
```

To change the author of git
```
Git config –global user.email <your_git_register_emil>
```
```
Git config –global user.name <user_name>
```