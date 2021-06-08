# IntelliJ Idea

* **Ctrl + Q** --- Документация
* **Shift + Ctrl + I** --- Реализация метода на котором установлен курсор
* **Ctrl + P** --- Информация о параметрах, необходимых для конкретного метода
* **Alt + Ctrl + F7** --- Показать места использования
* **Ctrl + P** --- Сведения о параметрах метода
* **F4** --- Переход в реализацию класса
* **Ctrl + Alt + L** --- Формат текста
* **Shift + Alt + Pup/Pdown** --- Поднять или опустить строку


# Git commands

* **git help command** --- man page for git commands
* **git show 8569daf (coomit hash)** --- shows commit if not specified shows the last commit
* **git status** --- shows untracked files
* **git branch** --- shows at which branch you are currently working
* **git diff master..feature** --- how what changes was made on feature compared to master
* **git checkout -b branch_name** --- creates new branch
* **git checkout branch-name** --- change between bracnhes
* **git add .** --- move all files in current dir to the stage
* **git add --all** --- move all files in current dir to the stage
* **git add -p yourfile.html** --- allow you to CHOOSE what changes you want to commit in this file. (example -> if you added 2 lines of code git will offer you to commit changes line by line. You can choose to save (commit) first added line but not second. Very convinient feature!.) 
* **git rm --cached filename** --- remove file from stage area
* **git rm --cached -r directory** --- remove all files and in dir from stage area
* **git commit -m** --- commit changes from staging with a message
* **git commit -a** --- commit without git add for ***TRACKED*** files
* **git remote -v** --- shows which github repos are connected with ur local repo 
* **git remote add origin https://github.com/Dzentsetsu/Tips.git** --- creates a handle in your local repo with alias ORIGIN to this "https://github.com/Dzentsetsu/Tips.git" repo (now you can fetch from it and push to it)
* **git remote remove alias** --- removes a handle to github repo (this is used when for example you have 2 repos where you commit ur local files to and now you do not want to use one of them anymore,so you can delete a handle to it)
* **git push -u origin my_branch** --- Type this if it is the first time that you push that branch in just created repo.

# Linux terminal 

* **Ctrl+L** --- clear's terminal instead of typing command "clear"
* **apt-cache pkgnames anyname | less** --- list every package with anyname in the beginning of the package name
* **uname -a** --- determine the processor architecture, the system hostname and the version of the kernel
* **lsmod** --- shows which loadable kernel modules are currently loaded
* **tree** --- tree is a recursive directory listing program that produces a depth-indented listing of files
* **>** --- output redirection. Redirect output from left side command to right side ex. (ls > fileList.txt)
* **|** --- put result of one command  as input to another
* **grep** --- print lines that match patterns


# JS

Array methods
* **Array.push()** --- method adds one or more elements to the *end* of an array and ***returns the new length of the array***
* **Array.unshift()** ---  method adds one or more elements to the beginning of an array and ***returns the new length of the array***
* **Array.pop()** --- method removes the last element from an array and ***returns that element***
* **Array.shift()** --- method removes first element from an array and ***returns that removed element***
* **Array.splice()** ---  method changes the contents of an array by removing or replacing existing elements and/or adding new elements

# VScode

Extremely usefull
* **Ctrl+Shift+P** --- wraps selected text in specified container (e.x **.container** will give you div with a class=container)
* https://docs.emmet.io/cheat-sheet/ --- Emmet cheatsheet - **SUPER USEFULL!!!!**:astonished:
