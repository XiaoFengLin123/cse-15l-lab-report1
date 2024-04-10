**Lab Report 1** 

**Examples of `cd`**

An example of using the command with no arguments
![Image](cd example 1.jpg)

The absolute path to the working directory before the command was run: `/c/Users/capta/lecture1`
When `cd` is used without arguments, the current working directory is changed to the home directory. which, in my case, it went to `/c/Users/capta`, which is my home directory
Having no arguments means entering the `cd` command without additional information. This performs the default operation of changing the directory to the user's home directory. 
There is no error in this case since if `cd` is not provided with any arguments, the working directory will be changed to the user's home directory. 

An example of using the command with a path to a directory as an argument.
![Image](cd example 2.jpg)

The absolute path to the working directory was right before the command was run: `/c/Users/capta`
When we use the command `cd` with a path to lecture1 as an argument, it changes the current working directory to `/c/Users/capta/lecture1`. The output of this command is that I am in `/c/Users/capta/lecture1`, which is also a working directory.  `cd` changes the working directory to the path that is specified which was `lecture1`. Since lecture1 is a working directory and the path `/c/Users/capta/lecture1` exists, it changes it to `/c/Users/capta/lecture1`. 
The directory exists, so I didn't get an error. However, if the directory doesn't exist or the path is incorrect, I will get an error and cannot change the working directory.  

An example of using the command with a path to a file as an argument.
![Image](example 3.jpg)

The absolute path to the working directory was right before the command was run: `/c/Users/capta/lecture1`
When we use the command `cd` with a path to a file as an argument, in this case Hello.java, we get an error that says `bash: cd: Hello.java is not a directory.` 
This means that `cd` cannot be used with a path to a file as its argument; you can use the directory part of the file's path to change the working directory to where the file is located. The working directory is still `/c/Users/capta/lecture1`. The  `cd` command requires a directory as an argument, not a file. If you want to navigate to a file, you need to change it to the directory that contains that file but not the file itself. 

**Examples of `ls`**

An example of using the command with no arguments

![Image](ls example 1.jpg)

The absolute path to the working directory was right before the command was run: `/c/Users/capta/lecture1`
When we use the command `ls` without any arguments, it displays the files and directories in the current working directory. When you use `ls` without any arguments, you are simply viewing the current location within the filesystem, which is the directory I am currently in (`/c/Users/capta/lecture1`). The output doesn't give an error as it just lists the contents of my current working directory, and since `/c/Users/capita/lecture1` is a working directory, it didn't cause an error. 

Share an example of using the command with a path to a directory as an argument.
![Image](ls example 2.jpg)

The absolute path to the working directory was right before the command was run: `/c/Users/capta/lecture1`
We use the command `ls /c/Users/capta/lecture1/messages` or `ls lecture1`, it listed the contents of a specified directory, which in this case was `/c/Users/capta/lecture1/messages`. We don't need to be in that directory to list the contents, but the command will allow us to see what files and directories are within that working file directory. This output doesn't give an error unless the provided directory is not a directory. 


Share an example of using the command with a path to a file as an argument.
![Image](ls example 3.jpg)

The absolute path to the working directory was right before the command was run: `/c/Users/capta/lecture1`
When we use the command  `ls Hello.java`, it gives us back Hello.java. This is because when we `ls` a file, we just confirm if that file exists and spit out the path that contains that file if the file exists. If that file doesn't exist, it will say that the file `ls: cannot access 'filename': No such file or directory.` In this example, since we are already in the working directory that contains Hello.java, we will just get back the file name, which is Hello.java. 

**Examples of `cat`**

An example of using the command with no arguments.
![image](https://github.com/XiaoFengLin123/cse-15l-lab-report1/assets/146484956/918bb65e-e17a-4e88-9e5b-6f5b9f7785b4)

The absolute path to the working directory was right before the command was run: `/c/Users/capta/lecture1`
When we use `cat` without any argument, it just creates a new space character in the terminal when I try to enter and execute the command. It's not doing anything and keeps prompting me to enter an argument. This is because `cat` is supposed to be used to concatenate files and output the results. This is not an error and is purposeful. Since we didn't provide two files, it will keep prompting us until we give it a file. 

An example of using the command with a path to a directory as an argument.
![image](https://github.com/XiaoFengLin123/cse-15l-lab-report1/assets/146484956/fe3ee934-a35e-49fe-a7fb-c58bc5e247ea)

The absolute path to the working directory was right before the command was run: `/c/Users/capta`
When we try to use `cat` and a path to a directory as an argument, in this case, lectre1, we get an error that says `lecture1: Is a directory`. This is an error because Cat only works with files and prints the contents. If we try to use a directory it will cause an error since it only accepts files. 

An example of using the command with a path to a file as an argument.
![image](https://github.com/XiaoFengLin123/cse-15l-lab-report1/assets/146484956/07245916-2c78-458b-9d88-1c6b9f27d946)


The absolute path to the working directory was right before the command was run: `/c/Users/capta/lecture1`

When we use `cat Hello.java`, it prints the contents of the file in Hello.java. It spit out the code within the Java file and printed it to the terminal. This is because `cat` is often used to read and then display the content of the file if that file is within the current working directory. This is not an error because  `cat` is suppose to display all of the contents to the terminal for you to read. 


