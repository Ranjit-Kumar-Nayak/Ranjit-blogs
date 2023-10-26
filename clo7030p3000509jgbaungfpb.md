---
title: "🚀 Mastering Linux: Kernel, Shell, and Scripting Dive 🌧"
seoDescription: "What is a Kernel
What is a Shell?
What is Linux Shell Scripting?"
datePublished: Thu Oct 26 2023 09:47:06 GMT+0000 (Coordinated Universal Time)
cuid: clo7030p3000509jgbaungfpb
slug: mastering-linux-kernel-shell-and-scripting-dive
tags: linux, devops, 90daysofdevops, trainwithshubham, devopswithranjit

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1698313380449/ac1a9a3c-5390-4282-8748-39da240210e8.png align="center")

### **🌐 What is a Kernel?**

💡 At the heart of every Linux system lies the kernel. It serves as the bridge between the 🖥️ hardware and 💾 software, managing system resources and providing the 💥 bash for software to run. It handles tasks like 🧠 memory management, 🔄 process scheduling, 🌐 device communication, and more. 🚀

### **🐚 What is a Shell?**

Shell is a command-line interface (CLI) that takes your input and communicates with the kernel to execute your commands. various types of shells are available for Linux, such as Bash, and Zsh.

```plaintext
ls -lrth 
```

when you run `ls -lrth` command on your CLI (shell) at that time it with communicate with the kernel it display the output.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1698313401792/7495abff-bc3e-4ec8-8a4c-23b1090d734c.png align="center")

### **📜 What is Linux Shell Scripting for DevOps?**

It is a powerful way to automate multiple tasks and create customized workflows using the shell. It involves writing a bunch of commands in a script file 📜, which can be executed all at once 🚀. Shell scripting is the key to streamlining your tasks and boosting productivity! 💪🐧

Example -:)

```plaintext
#!/bin/bash
echo "I will complete #90DaysOfDevOps challenge"
```

#! /bin/bash - &gt; It is known as the 'shebang' or 'hashbang'! 🎯 It's a best practice to include it in your script file. 🚀

echo "I will complete #90DaysOfDevOps challenge " ➡️ it will display: `I will complete #90DaysOfDevOps challenge`" 😊

Q: Write a Shell Script to take user input, input from arguments and print the variables.

```plaintext
#/bin/bash
echo "Enter Your Name -:"
read name
echo "enter my name $name"
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1698312973478/2c97e6e0-7ec2-4c82-9f8d-afbb9214c326.png align="center")

Q: Write an Example of If else in Shell Scripting by comparing 2 numbers.

```plaintext
  #!/bin/bash
  first=10
  second=20
  if [ $first -gt $second ];
  then
          echo "then $first is Greater than $second"
  else
          echo "then $second is greater than $first"
  fi

```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1698313193609/574c1fa9-4464-4559-a130-f5210510583d.png align="center")

  
***<mark>Happy Learning 😊:)</mark>***

👍 Like 🔄 Share

follow Me for more Amazing content -: [**Ranjit**](https://hashnode.com/@RanjitKumarNayak)