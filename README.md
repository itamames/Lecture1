
# Lecture 1: Welcome to COP 3530!

My name is Dr. Ilmar Tamames, and I will be your instructor for the course COP 3530: Data Structures. This is a course designed as an undergraduate-level course that covers a study of fundamental data structures and their efficient use in solving problems.

For this course, we will use several tools. The programming language is JAVA, and you can use the IDE of your choice. I recommend using Visual Studio Code since it can switch to almost any language. As programmers, you should not tie yourself to a language but more to learning concepts and solutions. Additionally, you will need to use GitHub. You do not need to start with a deep understanding of it, but as we progress along the course, you will become proficient in it.

The classes will be in Markdown instead of PowerPoint and you can reference the examples directly in the GitHub repository for the lecture. As an alternative, I will include them as PDFs in Canvas, along with the code examples.

The class consists of 6 modules, each one with an assignment due in 2 weeks and a 50-minute Online Quiz at the end of it. The is no Midterm or Final exam. Each quiz is worth 10% of the final grade and each assignment will be 2%. There is one 
introductory assignment for 2% and a group project (up to 3 members) for 20%. Participation accounts for 6%, and it includes participating in forums and classes, answering emails, communicating with me for questions, and overall politeness.


For the first introductory task, you need to reply to the topic in the discussion board for introducing yourself. Additionally, you have to accept assignment 0 with the GitHub repository for this module and pull request a change to the README.md file. This is due Friday, January 13, 2023. The first real assignment, due Wednesday, January 25, 2023, will cover the first 4 Lectures. The first Quiz will be Friday, January 27, 2023, and will cover the same material as the assignment. I will post the answers to the assignment on Wednesday, January 25, 2023, to give you time to prepare for the first Quiz.

Best of luck!

Ilmar Tamames

# What is Git and GitHub

https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

## Overview
In this course, we will be submitting ALL of our homeworks on [Github classroom](https://classroom.github.com/). Github classroom will allow you to easily acquire starter code, art assets, and other things we want you to have for each assignment, and will make saving your work and submitting your work trivial. Github classroom will also make our group projects easier to manage. If you have never used Github before, don’t worry. This page goes over the absolute bare essentials. The overall process is:

* You will create a normal account on [Github](https://github.com). if you do not already have one.
* You will link your Github account to your student roster name on our [Github classroom](https://classroom.github.com/).
* You will checkout the starter code for an assignment.
* You will commit and push your work to your repository to submit it.

## Step 1: Make a Github Account (if you don’t have one)
If you do not yet have a Github account, you can easily make one at [Github.com](https://github.com). It might be easiest to use your FIU email address and use the account for school work, but you can use any email address you’d like.

## Step 2: Go to our Github Classroom and link account
Go to our Github classroom link. For Spring 2023 that is this classroom [here](https://github.com). Once there, you should see a list of names of students in the course. Find your name and select it. Follow any additional instructions to link your personal Github account to the our course.

## Step 3: Checkout an Assignment!
For each assignment, there will be a Github assignment invite link. For example, if you checkout Homework 1, you’ll see a link at the top of the assignment. By clicking on that link, you should be able to get the starter code for that assignment and setup a repository.

## Step 4: Commit and Push your Work for Grading!
Once you have a repository, you can use [GitHub Desktop](https://github.com), Visual Code itself or git commands (on your console or similar) to go through the typical git repository cycle.



### Git Console Commands
 To clone your repo onto your machine, you’ll do something like this:

```
git clone <path to repository>
```

Or, for a specific example:

```
git clone https://github.com/markfloryan/gamedesign/
```

will clone the course repository.

Once you have the repository on your machine you can do some work, add files, code, test, etc. Every once in a while you should commit and push changes. To commit, do:

```
git add .
```
Adds new files that you've added to your project. Don't need this every time.
```
git commit . 
```
Commit changes locally, will need to enter a message to report changes.

Once you’ve done enough work, you should periodically push those changes to the server. The most simple way:

```
git push
```

Every time you push changes to your repository, the graders and TAs will be able to see all of the commits and messages and changes. You can push as many times as you want before the assignment deadline. You can even push after the deadline too. The grader can see the state of the repository at the moment the deadline passed, so feel free to keep working.

These are just the basics of Github. The internet contains many more detailed resources for this.

# Getting Started with Java in VS Code

>Adapted from https://github.com/microsoft/vscode-docs/blob/main/docs/java/java-tutorial.md
https://code.visualstudio.com/docs/java/java-tutorial

This tutorial shows you how to write and run Hello World program in Java with Visual Studio Code. It also covers a few advanced features, which you can explore by reading other documents in this section.

For an overview of the features available for Java in VS Code, see [Java Language Overview](https://github.com/microsoft/vscode-docs/blob/main/docs/languages/java.md).

If you run into any issues when following this tutorial, you can contact us by entering an [issue](https://github.com/microsoft/vscode-java-pack/issues).

## Setting up VS Code for Java development

### Coding Pack for Java

To help you set up quickly, you can install the **Coding Pack for Java**, which includes VS Code, the Java Development Kit (JDK), and essential Java extensions. The Coding Pack can be used as a clean installation, or to update or repair an existing development environment.

<a class="install-extension-btn" onclick="pushCodingPackEvent('java', 'win')" href="https://aka.ms/vscode-java-installer-win">Install the Coding Pack for Java - Windows</a>

<a class="install-extension-btn" onclick="pushCodingPackEvent('java', 'mac')" href="https://aka.ms/vscode-java-installer-mac">Install the Coding Pack for Java - macOS</a><br>

> **Note**: The Coding Pack for Java is only available for Windows and macOS. For other operating systems, you will need to manually install a JDK, VS Code, and Java extensions.

### Installing extensions

If you are an existing VS Code user, you can also add Java support by installing the [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack), which includes these extensions:

* [Language Support for Java™ by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
* [Debugger for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)
* [Test Runner for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test)
* [Maven for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)
* [Project Manager for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-dependency)
* [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

<a class="install-extension-btn" href="vscode:extension/vscjava.vscode-java-pack">Install the Extension Pack for Java</a>

The [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) provides a Quick Start guide and tips for code editing and debugging. It also has a FAQ that answers some frequently asked questions. Use the command **Java: Tips for Beginners** from the Command Palette (`kb(workbench.action.showCommands)`) to launch the guide.

![Java Getting Started](https://code.visualstudio.com/assets/docs/java/java-tutorial/getting-started.png)

You can also install extensions separately. The **Extensions Guide** is provided to help you. You can launch the guide with the **Java: Extensions Guide** command.

For this tutorial, the only required extensions are:

* [Language Support for Java™ by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
* [Debugger for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)

## Installing and setting up a Java Development Kit (JDK)

To use Java within Visual Studio Code, you need to install a Java Development Kit (JDK) on your local environment. JDK is a software development environment used for developing Java applications.

### Supported Java versions

The [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) supports Java version 1.5 or above.

> **Note**: To configure JDKs for your projects, see [Configure Runtime for Projects](https://github.com/microsoft/vscode-docs/blob/main/docs/java/java-project.md#configure-runtime-for-projects). To enable Java preview features, see [How can I use VS Code with new Java versions](https://github.com/microsoft/vscode-docs/blob/main/docs/java/java-faq.md#how-can-i-use-visual-studio-code-with-new-java-versions).

### Installing a Java Development Kit (JDK)

If you have never installed a JDK before and need to install one, we recommend you to choose from one of these sources:

* [Microsoft Build of OpenJDK](https://www.microsoft.com/openjdk)
* [Oracle Java SE](https://www.oracle.com/java/technologies/javase-downloads.html)


## Creating a source code file

Create a folder for your Java program and open the folder with VS Code. Then in VS Code, create a new file and save it with the name `Hello.java`. When you open that file, the Java Language Server automatically starts loading, and you should see a language status item with a loading icon on the right side of the Status Bar showing the language status is busy. After it finishes loading, you can hover on the language status item and find the loading process has been finished successfully. You can also choose to pin the status item in the status bar.

<video autoplay loop muted playsinline controls>
  <source src="https://code.visualstudio.com/docs/java/java-tutorial/JavaHelloWorld.Standalone.mp4" type="video/mp4">
</video>

>**Note**: If you open a Java file in VS Code without opening its folder, the Java Language Server might not work properly.

VS Code will also try to figure out the correct package for the new type and fill the new file from a template. See [Create new file](/docs/java/java-editing.md#create-new-file).

You can also create a Java project using the **Java: Create Java Project** command. Bring up the **Command Palette**  (`kb(workbench.action.showCommands)`) and then type `java` to search for this command. After selecting the command, you will be prompted for the location and name of the project. You can also choose your build tool from this command.

<video autoplay loop muted playsinline controls>
  <source src="https://code.visualstudio.com/docs/java/java-tutorial/JavaHelloWorld.Project.mp4" type="video/mp4">
</video>

Visual Studio Code also supports more complex Java projects — see [Project Management](https://code.visualstudio.com/docs/java/java-project).

## Editing source code

You can use code snippets to scaffold your classes and methods. VS Code also provides IntelliSense for code completion, and various refactor methods.

<video autoplay loop muted playsinline controls>
  <source src="https://code.visualstudio.com/docs/java/java-tutorial/edit-code.mp4" type="video/mp4">
</video>

To learn more about editing Java, see [Java Editing](https://code.visualstudio.com/docs/java/java-editing).

## Running and debugging your program

To run and debug Java code, set a breakpoint, then either press `kb(workbench.action.debug.start)` on your keyboard or use the **Run** > **Start Debugging** menu item. You can also use the **Run|Debug** CodeLens option in the editor. After the code compiles, you can see all your variables and threads in the **Run and Debug** view.

<video autoplay loop muted playsinline controls>
  <source src="https://code.visualstudio.com/docs/java/java-tutorial/run-debug.mp4" type="video/mp4">
</video>


For more information, see [Java Debugging](https://code.visualstudio.com/docs/java/java-debugging).

