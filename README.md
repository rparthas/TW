# TW Bootcamp Projects

This repository contains a collection of Java projects developed as part of the TW Bootcamp.

## Projects

### Tic-Tac-Toe

A simple command-line based Tic-Tac-Toe game.

**To Build and Run:**

This project uses Maven. To build and run the application, navigate to the `tictactoe` directory and run the following commands:

```bash
mvn clean install
mvn exec:java -Dexec.mainClass="com.tw.tictactoe.App"
```

### TWBootcamp Exercises

This project contains a collection of smaller Java exercises.

**Sub-projects:**

*   **cashier:** A simulation of a cashier system.
*   **milk:** A simulation of a milk delivery system.
*   **PlayerGame:** A game involving players with different strategies.

**To Compile and Run:**

This project is a standard Eclipse project. To compile and run the files, you can import it into Eclipse or use the command line.

To compile all files from the `TWBootcamp` directory:

```bash
javac -d bin $(find src -name "*.java")
```

To run a specific application, for example the cashier application:

```bash
java -cp bin com.tw.cashier.Application
```
