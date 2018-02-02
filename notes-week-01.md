# Week 01: Hand-on the Terminal

### 1. Open terminal on MAC
Terminal is a shell which receive/send input and output for command-line program.
* **command+space** to open spotlight
* search "terminal" to open terminal.
![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13ckagp5j20g701swel.jpg)

### 2. Shell commands
Following are some commands you can input in terminal.
##### 1. Directory: Where you are 
Please type often `pwd` and `ls` to make sure where you are. 
* `ls` means listing, showing the files in current folder.
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13e6cg8yj20fg01v0ss.jpg)

* `cd` means change directory, or change to a folder.
eg:
  `cd desktop` to go to "desktop".
  ![](https://ws1.sinaimg.cn/large/5b088c35gy1fo1c690shmj20eh015t8n.jpg)  
    
  `cd ~` or `cd `to return to home.
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13ghb9grj20es012747.jpg)
    
  `cd desktop/17444519` 
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13j4q9jkj20dr00wwee.jpg)
    
  `cd .` to go to current diretory. 
    
  `cd ..` to return back to the upper directory.
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13k20gw1j20ea00yglj.jpg)

* `pwd ` means print what directory, or show where you are.
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13l2gwb2j20ep01g0sp.jpg)

##### 2. Creat/delete/rename files and folders 
Space separates the arguments and commands. So be careful.You can `ls` to check the new file or folder.
*(Make sure it exists.)*

* `touch` means creat a file
* `rm` means delete a file
eg:
  At first, `ls` to see files in current folder.
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13qeisecj20e700t0so.jpg)
  
  `touch ex1.py` to creat a file called "ex1.py",then `ls`.
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13qx0ejmj20ek01y3yl.jpg)
  
  `rm ex1.py` to remove a file called "ex1.py". 


* `mkdir` means creat a folder
* `rmdir` means delete a folder
eg:
  `ls`to see files in current folder.
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13sjhu6hj20ed016mx4.jpg)
  
  `mkdir Big_data` to creat a new directory, or a folder.
    ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13sucn5ej20f601v3ym.jpg)
    
  `rmdir Big_data` to remove the directory.

* `mv` means rename
eg:
  `mv ex1.py exercise.py` to rename "ex1.py" as "exercise.py".
  `mv 123 456`to rename "123" as "456".

##### 3. Execute .py file
* `python exercise.py` to execute python scripts.

### 3. Edit Python file:
You can open .py by double clicking the file.
*(If it doesn't work, you can download some third party editors,such as **sublime**, **visual studio code**. You can edit .py file by these editors.)*

* `print ` is a python language, which means print, or show, in the terminal.
eg:
  `print "hello"` on sublime to print the string hello.
  ![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13ui71hqj20at03fjre.jpg)
  
  **command+S** to save the file as "ex1.py" on desktop.

  `python ex1.py`on terminal to execute the file.
![](https://ws1.sinaimg.cn/large/5b088c35ly1fo13vng40hj20f201vq2y.jpg)
