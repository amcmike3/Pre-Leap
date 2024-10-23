**Part 1 - GitHub Repository Setup**

**Creating a GitHub Repository**

In this section, we will utilize _GitHub_ as a platform to store, collaborate on, and share code. To maintain consistency in file structure and naming conventions, we request that you create a GitHub repository named 'PreLeap' for the PreLeap work. 

Tasks:

1. Create a GitHub repository named **PreLeap**, and initialize it with a _README.md_. There will be a green button on your home page of github where you can create a new repository and a checkbox to initialize it with a repository.

2. Copy the _Clone or Download_ link for the **PreLeap** repository.

3. Clone this repository into your home directory using the terminal:

   ```bash
   cd ~
   git clone https://github.com/YOUR_GITHUB_USERNAME/PreLeap.git
   ```

4. Navigate to the cloned working directory:

   ```bash
   cd ~/PreLeap/
   code .
   ```

   In the vs code editor, select the _README.md_ file and add the following text:

   ```
   ## PreLeap

   Hello World
   ```

   Save the change using _Ctrl-S_.

5. Push this change to GitHub:

   ```bash
   git status
   git add README.md
   git status
   git commit -m "initial commit hello world"
   git branch -M master
   git push origin master
   ```

6. Check your GitHub repository to view the changes.

**First Exercise**

1. Create a directory (folder) for lab exercises:

   ```bash
   cd ~/PreLeap/
   pwd
   mkdir Labs
   ls
   ```

2. Enter the Labs directory:

   ```bash
   cd Labs
   touch HelloWorld.java
   code .
   ```

3. Input the following starter code and save the program:

```java
public class HelloWorld {
    public static void main(String[] args) {
      System.out.println("Hello, World");
    }
}
```

4. Compile and run the code:

   ```bash
   javac HelloWorld.java
   ls
   java HelloWorld
   ```

5. Push your work to GitHub:

   ```bash
   git add HelloWorld.java
   git status
   git commit -m "finish HelloWorld"
   git push origin master
   ```

**Following this example, repeat these steps after each lab to run and push your program to your GitHub repository.**

**Setting up Your File Structure**

You will establish a local repository named _PreLeap_ under your HOME directory for this work and initialize it as a _Git_ repository. Your file structure should resemble the following as you proceed through the lab materials:

```
HOME
   PreLeap
   └── Labs
       ├── part1Lab1.java
       ├── part1Lab2.java
       ├── part1Lab3.java
       └── ...
```

[Up](README.md) | [Next](part2.md)