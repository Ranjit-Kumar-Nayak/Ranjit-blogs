---
title: "🐧 Exploring the Linux World: An Introduction to Linux Part -3"
seoDescription: "📄 cat: To view and concatenate files.
🔄 tac: Reverse the order of lines in a file.
🖋️ touch: Create empty files or update timestamps.
✍️ vi and vim:"
datePublished: Sun Nov 05 2023 03:12:30 GMT+0000 (Coordinated Universal Time)
cuid: clokwe2za000009leawj75wfx
slug: exploring-the-linux-world-an-introduction-to-linux-part-3
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1699153706646/426550aa-73a8-47b7-80c6-252824df5e7c.webp
tags: linux, linux-for-beginners, 90daysofdevops, trainwithshubham, devopswithranjit

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699095786745/6a89303b-0465-472b-9395-216d58f4c01e.webp align="center")

Commands and text editors for file creation and text manipulation in the Linux world! 🔧📄👩‍💻

* `touch`✨
    

* `cat` 📜
    
* `vi/vim` 🔧
    
* `nano` 👩‍💻
    

## cat😺

The 🐱 cat 🐱 is one of the most universal commands! 🌎 All it does is copy the standard input to the standard output. 📥➡️📤😺

If you want to see the file content, here's the command for a file named "ranjit" 📂

```plaintext
cat ranjit
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699088055469/300dcd8c-41b2-44f2-a7bb-1f73ba138dd1.png align="center")

📄 If you want to create the file and add the data to it, you can use the `cat` command in combination with the `>` operator to redirect the output to a file.

you can save the file by <mark>ctrl +D.</mark>

```plaintext
cat > ranjit
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699092091836/5f2c533f-9418-41a7-ab5e-2bd74813be0e.png align="center")

📂 Copy the files:

📄 You can use the `cat` command to copy the content from "ranjit" and save it in "copy.txt":

```plaintext
cat ranjit > copy.txt
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699092230414/e80b572f-0343-4e61-93a4-3b5d42a5238a.png align="center")

🔗 Concatenate two files:  
This command will concatenate the contents of "file1" and "file2" and save them in "allContent.txt"📄🔗📄

`echo` "this is file1"&gt;file1 - it write the line 👉this is file1👈 in file1

```plaintext
cat file1 file2 >> allContent.txt
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699092458194/11bc7355-deaa-464e-bd1a-4df3174277ee.png align="center")

To append to the content of the file named "Ranjit" without removing the existing text, you can use this command: (📝🔗 Append your text to "ranjit"!)

you can simply save this by <mark>CTRL+D</mark>

```plaintext
cat >>ranjit
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699092780448/c53e8bba-a600-4a37-8ae2-bf81cd671e7b.png align="center")

## touch👉✨

* it will create one or multiple empty files
    
* change and modify the time stamp
    

📄 Create a single empty file:

```plaintext
touch file1
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699093052037/8aa51a85-1348-43f9-b26c-879ac1242baa.png align="center")

create multiple empty files 📄: This command will create five empty files named "file1" "file2" "file3" "file4" and "file5"

```plaintext
touch file1 file2 file3 file4 file5
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699093147356/80d208cb-611d-42da-9567-57a1e6155633.png align="center")

You can have some fun with file creation and timestamp modification using the `touch` and `stat`

```plaintext
stat file4
```

`-m` - &gt; This is used for the modification time of the `file4`

`-a` -&gt; this is a change the access time of the file

```plaintext
touch -m file4
```

```plaintext
touch -a file4
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699094347030/4fabd662-a14b-4909-8faf-260a7f531931.png align="center")

📝 To open a file in the Vim or Vi text editor, use the following command:vi editor create a **newFile** with editor.

Let's explore the powerful features of the Vi 🖋️ or Vim 📝 text editor.

* To exit and save changes:
    
    * Press `Esc` to ensure you're in normal mode.
        
    * Type:`wq` and press `Enter`. 💾
        
* To exit without saving changes:
    
    * Press `Esc` to ensure you're in normal mode.
        
    * Type:`q` and press `Enter`. ❌
        
* To save changes without quitting:
    
    * Press `Esc` to ensure you're in normal mode.
        
    * Type:`w` and press `Enter`. 💾
        
* To force quit without saving changes:
    
    * Press `Esc` to ensure you're in normal mode.
        
    * Type:`q!` and press `Enter`. 🚫
        

vi editor some shortcut

* * `i` - Insert mode:
        
        * Press `i` enter insert mode and start typing. 📝
            
    * `o` - Insert on the next line:
        
        * Press `o` to open a new line below the current line and start typing. ➡️📝
            
    * `a` - Insert after the cursor:
        
        * Press `a` to insert text after the cursor position. ✏️
            
    * `r` - Replace:
        
        * Press `r` to replace the character under the cursor with the next character you type. 🔄
            
    * `d` - Delete:
        
        * Press `d` followed by another `d` to delete the word under the cursor. 🗑️🗑️
            
    * `u` - Undo:
        
        * Press `u` to undo the most recent change. ↩️
            
    * `x` - Remove one character:
        
        * Press `x` to delete the character under the cursor. ❌
            

```plaintext
vi newFile
```

```plaintext
nano newFile
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1699094516512/10001f01-63d6-4e8a-82c8-ba92499a7b05.png align="center")

<mark>Join me on my journey of tech exploration and knowledge sharing.</mark>

***<mark>Happy Learning 😊:)</mark>***

👍 Like 🔄 Share

Here is My blogs 👉👉 [**Blogs❤**](https://ranjitkumarnayak.hashnode.dev/)

[**Follow Me ❤**](https://hashnode.com/@RanjitKumarNayak)& Subscribe My Newsletter for More 📧👍---

%[https://hashnode.com/@RanjitKumarNayak]