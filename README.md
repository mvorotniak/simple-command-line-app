Simple Command Line App
-------------------------
This is a simple command line app for testing different command line requests.
The `javac` program generates instructions in a special format
that the java command can run called bytecode. Then java
launches the Java Virtual Machine (JVM) before running the
code. The JVM knows how to run bytecode on the actual
machine it is on.

### Just Compile and Execute
The filename must match the class name, including case, and
have a `.java` extension.

Compile ("javac" = java + compile). After the command line request is processed you'll see a new Main.class file is created.
`
javac src\com\mvoro\developer\Main.java
`

Execute ("cp" means classpath). When the execution finishes a message is printed in the screen.
`
java -cp src com.mvoro.developer.Main
`

### Passing parameters to the Java program
Compile
`
javac src\com\mvoro\developer\Main.java
`

Execute. As a result both words "Hello" and "World" are printed.
`
java -cp src com.mvoro.developer.Main Hello World
`

### Running the program in one line
You need Java 11 to run the program in one line.
This feature is called launching _single-file source-code_ programs. The name cleverly tells you that it can be used only if your
program is one file.

Compile and Execute (notice that the `Main.class` file was not created)
`
java src\com\mvoro\developer\Main.java Hello World
`
