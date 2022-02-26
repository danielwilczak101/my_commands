# my_commands
This is a file that I use when programming. Its nothing more then a bunch of commands that i update. I tend to forget them so i have a text file with them in it.


### Jupyter Notebook
```bash
jupyter notebook list  // Running notebooks in the background 
jupyter notebook stop <port> // Close the notebook based on the port
jupyter notebook --ip 0.0.0.0 --port 8080 & // Runn as back process & port it to local machines localhost.
```


### Github ssh key authentication
```
ssh-keygen -t rsa  // generate ssh key
cat /home/<pc-name>/.ssh/<filename> // show the key so you can add to github
```

### Installing my git bash style.
```Bash
sudo apt update;
sudo apt install git; 
git config --global user.name "Daniel Wilczak";              
git config --global user.email "danielwilczak101@gmail.com"; 
git clone <URL from github> 
git status 
git pull
```

### If i ever want to me a local git repository.
https://bit.ly/3uhuljr


### Python Virtual Env
```
python -m venv env  // Generate virtual env
env/bin/activate // Start the virtual env
pip3 freeze > requirements.txt // Save installed packages
deactivate // Deactivate

pip3 install -r requirements.txt // Installing requirments
```

### Angular
```
ng generate component components/button // create button inside of components
```

### FastAPI
```
py -m uvicorn main:app --reload // run localhost
```

### PyPI Package commands
```
python setup.py bdist_wheel sdist   // Build package for publishing
twine upload dist/*                 // Upload package to PyPI

pip3 install --upgrade <package_name>

python setup.py bdist_wheel         // If you change the setup.py
pip install -e .                    // To install the package locally
```

### Terminal color and python alias.

```bash
sudo nano ~/.zshrc
```
Then add:

```bash
alias python=python3
alias py=python3

NEWLINE=$'\n'
PROMPT="%(!.%F{red}.%F{white})%n%F{cyan}@%m %F{yellow}%d%F{reset}:"
```

### C
```

gcc -o <filename> <filename.c> // compile
./<filename>                   // run
```
### Django
```
sudo /opt/bitnami/ctlscript.sh restart apache  // restart apache
```
### Mongodb
```
db             // Tells you what databases there are
use <database> // Switch into that database
show dbs       // list the databases available

db.my_collection.InsertOne( { x: 1 } ); 
// db refers to the current database 
// and myCollection is the name of the collection

Shell Methods - https://docs.mongodb.com/manual/reference/method/
```


### Github
```
git lfs track "*.<FILE TYPE>" // To add fat boy files above 30mb to github.
```

### Git
```
git init        // Initialize local repository
git add <file>  // add File(s) to index
git status      //check status if working tree
git commit      // Commit changes in index
git push        // Push to repository
git pull        // Pull latest from remote repository 
git clone       // Clone Repository into a new directory
git config --global user.name username
git config --global user.email email
```

### PI
```
Sudo apt-get update          // update pi
sudo apt install git-all.    // Get all 
```


### Terminal commands

```
touch <Filename.txt> // Create file
cd move directory    // move directory
ls                   // Show directory
mkdir <foldername>   // make a folder
pwd                  // See working directory
mv                   // move file
cat                  // view a file
.quit                // Exit python interpretor
tree                 // See a tree of the current directory
```
### JupterNotebook commands
```
jupyter notebook   // To run the system for it.
```

### Sqlite commands
```
sqlite3 FILENAME.db // connect to the database
.tables             // Shows all tables in database
.header on          // turn header on
.mode column        // show table columns
.quit               // ends the sqlite3 interpreter  

SELECT * FROM data; // Run sql command in the shell
```

### Vim commands
```
i     // Insert
esc   // Get out of insert
:wq!   // save and exit
:1,$d  // Select all and delete
```
### Nano
```
Ctrl + 0 // Save file
Crtl + x // Exit file
https://wiki.gentoo.org/wiki/Nano/Basics_Guide // More info
```










