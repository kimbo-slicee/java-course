# What do I need to Work with java in my machine 💻?
To work with Java on your machine, you'll need to set up a development environment. Here are the key steps:
1. Install Java Development Kit (JDK):
> What Is JDK 📌: JDK is a software development kit that includes the necessary tools to develop and run Java applications. It contains the Java Runtime Environment (JRE), a compiler (JVM), and other tools.
> Download and Install:
Visit the Oracle JDK Downloads page or download an open-source version like OpenJDK.
Choose the version compatible with your OS (Windows, macOS, Linux).
Follow the instructions to install the JDK on your machine.
2. Set up Environment Variables (Optional but Recommended):
   On some systems, you may need to set up the (JAVA_HOME) environment variable to point to the directory where Java is installed.
> On Windows 💻:
Right-click on "My Computer" or "This PC" and choose "Properties."
Click on "Advanced system settings" and then "Environment Variables."
Add a new variable called JAVA_HOME and set its value to the installation path of the JDK.
Add %JAVA_HOME%\bin to your system's PATH variable.
3. Install an Integrated Development Environment (IDE):
   While you can write Java code using a simple text editor, using an IDE makes development easier and more efficient.
> Popular IDEs for Java:
IntelliJ IDEA: A powerful IDE with many features, including smart code completion, debugging, and integration with version control systems.
Eclipse: A widely used, open-source IDE that supports Java and many other languages.
NetBeans: Another open-source IDE that provides strong support for Java development.
4. Verify Installation:
   After installing the JDK, verify that it is correctly installed by opening a terminal/command prompt and running:
```
java -version

```
5. Optional Tools (for advanced development):
   Build Tools:
   **Maven or Gradle:**
>These are build automation tools that help you manage project dependencies and automate tasks such as compilation, testing, and deployment.

**Version Control:**
>Install Git to manage your source code using platforms like GitHub or GitLab.

**Database:**
>If your project involves working with databases, you may need MySQL, PostgreSQL, or SQLite along with JDBC (Java Database Connectivity) drivers.
# Write your Java Code without using IDE (JShell).
JShell is a tool introduced in Java 9 that provides an interactive Read-Eval-Print Loop (REPL) for Java. It allows you to execute Java code snippets, evaluate expressions, and explore Java APIs interactively without needing to write a full program, compile, or package code into a .java file.
**How to Start JShell:**
1. Install Java 9 or higher if you haven’t already.
2. Open your terminal (Command Prompt on Windows, Terminal on macOS/Linux).
3. Type jshell and press Enter.
4. You will enter an interactive JShell session, where you can start typing Java code.
   **Example of Using JShell:**
```shell
jshell> int a = 10;
a ==> 10

jshell> System.out.println(a * 2);
20

jshell> String greet(String name) {
   ...> return "Hello, " + name;
   ...> }
|  created method greet(String)

jshell> greet("Java");
$3 ==> "Hello, Java"
```
**JShell Commands:**
- /exit: Exits the JShell session.
- /list: Lists all the code snippets entered in the session.
- /vars: Lists all variables defined in the session.
- /methods: Lists all methods defined in the session.
- /help: Displays help information for using JShell.

