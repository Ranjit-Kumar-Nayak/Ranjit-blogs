---
title: "Unlocking the Power of Linux: A Beginner's Guide 🐧Part -4"
seoTitle: "ls touch head tail vi vim cat linux"
seoDescription: "devops linux basics"
datePublished: Mon Nov 06 2023 14:15:11 GMT+0000 (Coordinated Universal Time)
cuid: clomzi5if000009kwb283a2vy
slug: unlocking-the-power-of-linux-a-beginners-guide-part-4
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1699280000473/2274aa0c-ebc9-493c-a7c0-073bbb36cbd1.jpeg
tags: linux, devops, 90daysofdevops, trainwithshubham, devopswithranjit

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699280074243/ec5aede7-8bc6-4bc1-9985-9d198e0a9806.jpeg align="center")

Introduce you to some essential Linux commands: `tail`, `head`, `mkdir`, `cd`, and `ls`, and explain how to use them effectively. 🤓

**1\.** `tail` **- Peek into the End of Files 📃**

* The `tail` command is your go-to tool for viewing the end of a file.
    
* Use it like this: `tail [options] filename`.
    
    Example:
    
    ```plaintext
    bashCopy codetail -n 10 mytext.txt
    ```
    
* For example, to display the last 10 lines of a file named "mytext.txt," use `tail -n 10 mytext.txt`.
    
* You can also use the `-f` option to follow a file as it grows, which is handy for log files. Just run `tail -f mylog.log`, and it will continuously update the output as new data is appended. 📜👁️
    

**2\.** `head` **- Explore the Beginning of Files 📄**

* Much like `tail`, `head` allows you to examine a file, but this time at the beginning.
    
* The basic syntax is `head [options] filename`.
    
    Example:
    
    ```plaintext
    bashCopy codehead -n 5 important.txt
    ```
    
* To see the first 5 lines of a file named "important.txt," use `head -n 5 important.txt`.
    
* `head` is particularly useful when you want to get a quick glimpse of the structure or content of a file without reading it entirely. 📜🔍
    

**3\.** `mkdir` **- Create New Directories 📁**

* `mkdir` stands for "make directory" and does exactly that.
    
    Example:
    
    ```plaintext
    bashCopy codemkdir my_documents
    ```
    
* To create a new directory, simply run `mkdir directory_name`.
    
* You can also create nested directories by specifying the path, like `mkdir -p my_folder/subfolder/another_subfolder`. 📁🏞️
    

**4\.** `cd` **- Change Your Current Directory 🚶‍♀️**

* The `cd` command lets you navigate between directories.
    
    Example:
    
    ```plaintext
    bashCopy codecd directory_name
    ```
    
* To change to a specific directory, type `cd directory_name`.
    
* If you need to go back to the previous directory, you can use `cd ..`.
    
* Typing `cd` without any arguments will take you to your home directory. 🚪🌍
    

**5\.** `ls` **- List Contents of a Directory 📂**

* `ls` helps you see what's inside a directory.
    
    Example:
    
    ```plaintext
    bashCopy codels -l
    ```
    
* A simple `ls` command will list the files and directories in your current location.
    
* You can add options like `-l` for a detailed list or `-a` to show hidden files (those starting with a dot).
    
* For example, to list all files in the current directory with detailed information, use `ls -l`. 📂📜
    

**6\.** `pwd` **- Show Your Current Directory 📌**

* Knowing your current directory is crucial when working in Linux. The `pwd` command does just that.
    
    Example:
    
    ```plaintext
    bashCopy codepwd
    ```
    
* When you run `pwd`, it will display the full path of your current directory. This is handy when you need to keep track of your location within the file system. 🗺️
    

**7\.** `touch` **- Create Empty Files 📝**

* Sometimes, you need to create an empty file, and that's where `touch` comes in.
    
    Example:
    
    ```plaintext
    bashCopy codetouch my_file.txt
    ```
    
* To create an empty file, use `touch filename`. This is especially useful for creating placeholders for future content. 📝
    

**8\.** `rm` **- Remove Files and Directories 🗑️**

* When it's time to clean up your system, the `rm` command is your friend.
    
    Example:
    
    ```plaintext
    bashCopy coderm file_to_remove.txt
    ```
    
* Be cautious with this command, as it permanently deletes files and directories. To remove a file, simply use `rm filename`. To remove a directory and its contents, use `rm -r directory_name`. 🗑️
    

**9\.** `cp` **- Copy Files and Directories 📦**

* Need to duplicate a file or directory? `cp` is the answer.
    
    Example:
    
    ```plaintext
    bashCopy codecp file_to_copy.txt destination_directory/
    ```
    
* To copy a file, use `cp source_file destination`. To copy a directory and its contents, use `cp -r source_directory destination`. 📦
    

**10\.** `mv` **- Move or Rename Files and Directories 🔄**

* The `mv` command lets you both move and rename files and directories.
    
    Example:
    
    ```plaintext
    bashCopy codemv old_name.txt new_name.txt
    ```
    
* To rename a file, use `mv old_name new_name`. To move a file or directory to a new location, use `mv source destination`. 🔄
    

**11\.** `grep` **- Search Text Patterns 🧐**

* The `grep` command is your go-to tool for searching text patterns within files.
    
    Example:
    
    ```plaintext
    bashCopy codegrep "search_term" file_to_search.txt
    ```
    

<mark>Join me on my journey of tech exploration and knowledge sharing.</mark>

***<mark>Happy Learning 😊:)</mark>***

👍 Like 🔄 Share

Here is My blogs 👉👉 [**Blogs❤**](https://ranjitkumarnayak.hashnode.dev/)

[**Follow Me ❤**](https://hashnode.com/@RanjitKumarNayak)& Subscribe My Newsletter for More 📧👍---